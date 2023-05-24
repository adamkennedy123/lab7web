LANGKAH-LANGKAH MENGGUNAKAN CODEIGNETER

DOWNLOAD CODEIGNETER

EKSTRAK FILE CODEIGNETER DAN SIMPAN DI XAMPP/HTDOCS

RENAME CODEIGNETER SESUKA MASING-MASING DISINI SAYA RENAME MENJADI ci4

BUKA XAMPP DAN JALANKAN APACHE

![Screenshot (13)](https://github.com/adamkennedy123/lab7web/assets/92745982/d94d109d-d969-4b71-9e96-b95a6ff2f2ca)


KLIK CONFIG DI APACHE DAN KLIK PHP(php.ini)

![Screenshot (14)](https://github.com/adamkennedy123/lab7web/assets/92745982/bf7fc336-1bc4-4c45-a2d4-175adaf93e7d)


TEKAN CRTL+F SECARA BERSAMAAN DAN TULIS INTL

![Screenshot (15)](https://github.com/adamkennedy123/lab7web/assets/92745982/3d62f0c1-026a-45fe-8390-f698841db061)

HAPUS TITIK KOMA PADA extension=intl JIKA SUDAH DI HAPUS TEKAN CTRL+S UNTUK SAVE

![Screenshot (16)](https://github.com/adamkennedy123/lab7web/assets/92745982/692e30a8-dc76-4232-b9f4-78e4dec8c6a0)


BUKA FOLDER BUKA xampp/htdocs/ci4 CARI env DAN UBAH MENJADI .env

SETELAH ITU BUKA VSCODE DAN BUKA FILE .env

GANTI #CI_ENVIRONMENT = PRODUCTION MENJADI SEPERTI DI BAWAH INI

![Screenshot (18)](https://github.com/adamkennedy123/lab7web/assets/92745982/20f830bb-8742-4b63-8a40-531abf2deff7)

SETELAH UDAH DIUBAH MAKA PENCET FILE app/config/routes.php

GANTI $routes-setautoroute (false) menjadi (true) SEPERTI DI BAWAH INI

![Screenshot (5)](https://github.com/adamkennedy123/lab7web/assets/92745982/31a1aeaa-7cb8-4d6b-8609-c80d7c632e53)

DAN KETIK SEPERTI DIBAWAH INI

![Screenshot (19)](https://github.com/adamkennedy123/lab7web/assets/92745982/51008f1e-5847-49ec-accc-a9104944e5a0)

BUKA KEMBALI XAMPP DAN KLIK SHELL 

UBAH DIRECTORY MASING MASING

SETELAH SELESAI DIUBAH MAKA COPY KODINGAN DIBAWAH INI

````
php spark
````
MAKA MENGHASILKAN OUTPUT DIBAWAH INI

![Screenshot (7)](https://github.com/adamkennedy123/lab7web/assets/92745982/5413299c-02c4-4daa-9e08-23e2241471bd)

UNTUK MENJALANKAN HASIL KODINGAN KITA MAKA COPY KODINGAN DIBAWAH INI

````
php spark serve
````
MAKA MENGHASILKAN OUTPUT DIBAWAH INI

LALU COPY HTTPS://LOCALHOST:8080 DAN PASTE KE BROWSER

![Screenshot (9)](https://github.com/adamkennedy123/lab7web/assets/92745982/7485aebd-aaf6-44db-9546-f579822f93a0)

LALU MENGHASILKAN SEPERTI DIBAWAH INI

![Screenshot (3)](https://github.com/adamkennedy123/lab7web/assets/92745982/99021ac9-6d98-4070-9ebf-6c38045bcd73)


#UNTUK KODINGAN BISA LIAT DI FILE DIBAWAH INI

app/Views/template

app/Views/about.php

#UNTUK TAMPILAN BISA LIAT DI FILE DIBAWAH INI

public/style.css
