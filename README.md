# Catatan Belanja

Aplikasi **Catatan Belanja** adalah aplikasi web sederhana berbasis [Laravel](https://laravel.com/) untuk mencatat daftar belanja harian Anda.

## Fitur

- Menambah, mengedit, dan menghapus catatan belanja
- Menandai item belanja sebagai sudah dibeli
- Tampilan sederhana dan mudah digunakan

## Instalasi

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/devtest611/catatan-belanja.git
   cd catatan-belanja
   ```

2. **Install dependencies:**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Copy file environment dan generate key:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Atur konfigurasi database di file `.env` sesuai kebutuhan.**

5. **Jalankan migrasi database:**
   ```bash
   php artisan migrate
   ```

6. **Jalankan aplikasi:**
   ```bash
   php artisan serve
   ```

Akses aplikasi di [http://localhost:8000](http://localhost:8000).

## Kontribusi

Kontribusi sangat terbuka! Silakan buat pull request atau buka issue jika menemukan bug atau ingin menambah fitur.

## Lisensi

Proyek ini menggunakan lisensi [MIT](https://opensource.org/licenses/MIT).

---

> Dibuat dengan ❤️ menggunakan Laravel.