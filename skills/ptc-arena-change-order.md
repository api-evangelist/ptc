---
name: arena-change-order
description: Open an Arena change, attach affected items and read it back through the Arena REST API.
api: Arena PLM REST API
generated: 2026-10-20
method: generated
source: openapi/ptc-arena-openapi.yml
operations:
- login
- getChanges
- createChange
- createChangeItemAssociation
- getChangeItemAssociations
- getChange
- logout
---
1. `login` and keep the `arena_session_id` token.
2. `getChanges` to find any open change for the same items, otherwise `createChange`.
3. `createChangeItemAssociation` for each affected item, then `getChangeItemAssociations` to verify.
4. `getChange` to read status; `logout`. Errors use the `{status, errors[{code,message}]}` envelope (errors/ptc-error-codes.yml).
