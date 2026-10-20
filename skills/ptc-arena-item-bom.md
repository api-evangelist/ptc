---
name: arena-item-bom
description: Create an Arena PLM item and build its bill of materials through the Arena REST API.
api: Arena PLM REST API
generated: 2026-10-20
method: generated
source: openapi/ptc-arena-openapi.yml
operations:
- login
- getItems
- createItem
- getItem
- getBom
- createBomLine
- logout
---
1. `login` with a machine user's credentials; send the returned token as the `arena_session_id` header. Logging in again as the same user cancels the first session.
2. `getItems` to check the item number is free (a duplicate number returns 409), then `createItem`.
3. `getItem` to read the new item's GUID and attributes.
4. `createBomLine` for each child, then `getBom` to confirm the structure.
5. `logout` when done. A 429 means the 24-hour request limit is reached (rate-limits/ptc-rate-limits.yml). No idempotency key exists, so do not blindly retry creates.
