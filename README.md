### Build Instructions

1. Install [XAMPP](https://www.apachefriends.org/).
2. Move the project folder to:
3. Start **Apache** and **MySQL** from the XAMPP Control Panel.
4. Open `http://localhost/phpmyadmin`, create a database (e.g. `aol_kel3`), and import `database_kel3.sql`.
5. Edit `koneksi.php` with:
```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "aol_kel3";
Run the website with: 
http://localhost/aol-se-kel3/
