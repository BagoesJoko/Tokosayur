<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Installation (English)
1. If you want to use ressend for email authentication, edit .env and paste it in the RESEND_KEY section. if you use gmail smtp, open mail.php in config then edit 'default' to env('MAIL_MAILER', 'log')

2. After you migrate the database, then register your account, then edit your account role to 1 in the database, to get admin page access.

3. For payment gateway simulation, you can create a <a href="https://midtrans.com" title="text">Midtrans</a> account to get an API key, then edit the Midtrans server key and Midtrans client key.

- cd TokoSayur
- php artisan migration
- php artisan serve
- npm run dev

This web application is still not perfect, please forgive me if there are any shortcomings.

## INSTALASI (Indonesia)

1. Jika Anda ingin menggunakan resend untuk autentikasi email, edit .env dan tempel di bagian RESEND_KEY. Jika Anda menggunakan gmail smtp, buka mail.php di config lalu edit 'default' menjadi env('MAIL_MAILER', 'log') 

2. Setelah Anda melakukan migrasi database, lalu daftarkan akun Anda, lalu edit role akun Anda menjadi 1 di database, untuk mendapatkan akses halaman admin.

3. Untuk simulasi payment gateway, Anda dapat membuat akun <a href="https://midtrans.com" title="text">Midtrans</a> untuk mendapatkan kunci API, lalu edit kunci server Midtrans dan kunci klien Midtrans.

- cd TokoSayur
- php artisan migration
- php artisan serve
- npm run dev

Aplikasi web ini masih belum sempurna, mohon maaf jika ada kekurangan.

## PREVIEW 
<a href="https://tokosayur.69dev.id">Toko Sayur</a>
