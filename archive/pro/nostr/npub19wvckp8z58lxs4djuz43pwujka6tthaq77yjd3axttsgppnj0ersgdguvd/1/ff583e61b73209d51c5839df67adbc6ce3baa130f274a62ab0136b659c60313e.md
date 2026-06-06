6/5/2026 - Minor release today - v1.6.8.1

- fixed archive reconciliation issue where events detected in the Continuum archive were not always being marked as archived in the local database
- centralized application database access by moving inline SQL into db_utils and vault_db
- reduced route/service database coupling to simplify future schema updates and migration support