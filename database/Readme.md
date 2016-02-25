Skema database
==============

Dalam direktori ini telah disediakan skema database untuk aplikasi ini.
Cukup jalankan perintah berikut ini untuk memasukkan skema ke database.

    php artisan migrate

Dan telah disediakan pula satu data login default dengan info *username* dan *password*.
Bisa dilihat pada file `seeds/TblKepegawaianTableSeeder.php`.

Kredensial login default adalah username = `admin` dan password adalah `password` juga.

Eksekusikan perintah berikut ini untuk meng-query data ke dalam database.

    php artisan db:seed
