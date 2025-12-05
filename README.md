# Restore automotiverepair_backup.sql Backup in pgAdmin4 (Windows)

## Steps
1. Download `automotiverepair_backup.sql` from **Final Project/pg_dump**.
2. Open **pgAdmin4**.
3. In the left tree, right‑click **Databases** → **Create** → **Database…**.
4. Enter a name → click **Save**.
5. Right‑click the new database → **Restore…**.
6. In **Format**, select `Custom or tar`.
7. In **Filename**, browse to `automotiverepair_backup.sql` file.
8. Click **Restore**.

## Notes
- Select `.sql` files in the file explorer when browsing for backup to open.
- If collation/version mismatch errors occur, ensure a valid Template is selected under **Definition** tab.
- Tables and example queries can be found in Final Project documentation.
