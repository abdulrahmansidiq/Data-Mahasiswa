## 📌 Data Mahasiswa - CRUD Dasar Codeigniter 3 & Bootstrap 5

Proyek ini adalah aplikasi sederhana dengan sistem crud untuk manajemen data mahasiswa yang dibangun menggunakan CodeIgniter 3 sebagai framework backend dan Bootstrap 5 untuk tampilan antarmuka (frontend).

### System Requirements

- PHP 7.2.5 or newer is recommended
- MySQL 5.7
- Codeigniter 3.1.xx
- Bootstrap 5.x.x

### Installation

1. Download atau clone repository ini
2. Buat database baru dengan nama `db_mahasiswa`
3. Import file `db_mahasiswa.sql` yang ada di folder `assets` ke database `db_mahasiswa`
4. Buka file `application/config/database.php` dan ubah konfigurasi sesuai dengan database yang telah dibuat.

Konfigurasi database seperti berikut:

```php
'hostname' => 'localhost',
'username' => 'root',
'password' => '',
'database' => 'db_mahasiswa',
'dbdriver' => 'mysqli',
```

5. Buka browser dan ketikkan alamat [Localhost](https://localhost/data-mahasiswa)

### Reference & Credits

- [Codeigniter](https://codeigniter.com/)
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
- [DataTables](https://datatables.net/)
