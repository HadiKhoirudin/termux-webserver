Setup instalasi Web Server Android dengan menggunakan aplikasi Termux yang meliputi paket instalasi PHP, Apache2, MariaDB /MySQL, Composer, PHPMyAdmin, dan mc File Explorer.

Oleh Hadi Khoirudin, S.Kom.

## A. Cara Instalasinya : 
1. Silahkan buka aplikasi Termux, lalu kemudian jalankan perintah ini :

```
pkg install git -y && cd ~/ && git clone https://github.com/HadiKhoirudin/termux-webserver.git && cd ~/termux-webserver && chmod +x setup && bash setup && cd ~/
```

2. Setelah Termux membuka browser secara otomatis, maka silahkan coba login ke http://localhost:8080/phpmyadmin dengan user : root dan passwordnya dikosongkan saja.

3. Jika dapat masuk ke dalam tampilan database MySQL maka proses instalasi sudah selesai.

## B. Cara Menjalankannya : 
1. Silahkan buka aplikasi Termux, lalu kemudian jalankan perintah ini :

```
webserver
```

2. Untuk mengedit file silahkan jalankan perintah berikut ini :

```
cd ~/ && mc
```
3. Untuk menggunakan perintah composer silahkan jalankan perintah composer. Misalnya : 

```
composer create-project --prefer-dist laravel/laravel projectlaravel

```

## Selesai
