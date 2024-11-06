# Introductions

Menghubungkan database accounts :
1. Jalankan Apache dan MySQL. Jika ada error phpcurl.dll saat menyalakan Apache, bisa diabaikan.
2. Buka phpmyadmin melalui laragon MySQL > phpmyadmin
3. Buat database akademik. Query ada di akademik.sql
4. Jalankan di terminal pada direktori proj_pbp :
```bash
php artisan migrate
```
```bash
php artisan db:seed --class=AccountSeeder
```
Setelah migrate, tabel akan masuk otomatis ke database akademik. Jika ada error, bisa diabaikan.
Setelah seeding, tabel akun akan terisi.  
5. Coba jalankan proj_pbp untuk melakukan login
