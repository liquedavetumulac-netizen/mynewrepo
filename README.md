# MPDC Land Property Records and Geotagging System

PHP + MySQL/XAMPP starter application for the MPDC office.

## Setup

1. Copy the `mpdc-system` folder to `C:\xampp\htdocs\`.
2. Start Apache and MySQL in XAMPP.
3. Open phpMyAdmin.
4. Import `database/schema_complete.sql` into the `mpdc_system` database.
5. Verify `db.php` uses:
   - host: localhost
   - user: root
   - password: empty (default XAMPP)
   - database: mpdc_system
6. Put `create_admin.php` in the project root and open it once:
   `http://localhost/mpdc-system/create_admin.php`
7. Log in at:
   `http://localhost/mpdc-system/`
8. Delete `create_admin.php` after creating the account.

## Mapping

Leaflet + OpenStreetMap are used for visualization. GPS coordinates are not automatically treated as legal survey boundaries. Verified boundary markers can be connected as a polygon.

## Security

For production use, configure secure credentials, HTTPS, protected upload directories, CSRF tokens, and proper server permissions.
"# mynewrepo" 
