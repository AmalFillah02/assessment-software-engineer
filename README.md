# Assessment Test - Software Engineer
Ahsanul Amal Fillah

## 📁 Daftar Proyek

### A. Next.js CRUD (App Router + DaisyUI)
- 📂 Folder: `nextjs-crud-posts`
- ✅ Fitur:
  - App Router
  - CRUD Posts (Create, Read, Update, Delete)
  - DaisyUI untuk komponen
- 🔗 Repository
[Github](https://github.com/AmalFillah02/nextjs-crud-daisyui-host)

# Cara Run
- Masuk ke direktori nextjs-crud-daisyui-host (ex: /c/Projectku/assessment-software-engineer/nextjs-crud-daisyui-host)
  ```bash
  cd /c/Projectku/assessment-software-engineer/nextjs-crud-daisuui-host
- Jalankan perintah jika sudah berhasil masuk ke direktori nextjs-crud-daisyui-host
  ```bash
  npm run dev

---

### B. Laravel CRUD API
- 📂 Folder: `laravel-crud-api`
- ✅ Fitur:
  - Migrasi tabel `posts`
  - Seeder dummy posts
  - Endpoint: GET, POST, PUT, DELETE
  - Pagination
- 🔗 Repository
[Github](https://github.com/AmalFillah02/laravel-crud-api)

# Cara Run (hidupkan local Server XAMPP)
- Masuk ke direktori nextjs-crud-daisyui-host (ex: /c/Projectku/assessment-software-engineer/laravel-crud-api)
  ```bash
  cd /c/Projectku/assessment-software-engineer/laravel-crud-api
- Jalankan perintah jika sudah berhasil masuk ke direktori laravel-crud-api
  ```bash
   composer install
- Copy file .env lalu koneksikan ke database lokal:
   ```bash
   cp .env.example .env
- generate key:
   ```bash
   php artisan key:generate
- migrasi database:
   ```bash
   php artisan migrate
- Jalankan server:
   ```bash
   php artisan serve

## 📂 Konfigurasi

Edit file .env:
- Generate key
  ```bash
  APP_NAME=Laravel
  APP_ENV=local
  APP_KEY=base64:xxxxxxxxx
  APP_DEBUG=true
  APP_URL=http://localhost

- Jika menggunakan mysql:
   ```bash
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=nama-database
   DB_USERNAME=root
   DB_PASSWORD=

# Jalankan di 127.0.0.1:xxxx/posts

---

### C. Django Auth & CRUD User
- 📂 Folder: `django-auth-crud`
- ✅ Fitur:
  - Sign Up, Sign In, Sign Out
  - CRUD User (protected by Auth)
- 🔗 Repository
[Github](https://github.com/AmalFillah02/django-auth-crud)

# Cara Run
- Masuk ke direktori django-auth-crud (ex: /c/Projectku/assessment-software-engineer/django-auth-crud)
  ```bash
  cd /c/Projectku/assessment-software-engineer/djangi-auth-crud
- Jalankan perintah jika sudah berhasil masuk ke direktori django-auth-crud
  ```bash
  python manage.py runserver
