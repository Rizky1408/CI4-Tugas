<strong>Disini saya menggunakan fitur migration yang ada dalam codeigniter untuk konfigurasi dengan database</strong>


## Installation & updates

cloning gihtub ke dalam folder htdoc
```
git clone https://github.com/Rizky1408/CI4-Tugas
```

copy ```env``` ke ```.env``` untuk konfigurasi <br>
jalankan ```php spark db:create``` untuk membuat database <br>
jalankan ``` php spark migrate``` untuk menjalankan migrasi database <br>
jalankan ```php spark db:seed users``` untuk mengisi tabel database users
jalankan ```php spark key:generate``` untuk mengekripsi password yang sudah di isi melalui spark users diatas
jalankan ```php spark serve``` untuk menjalankan server dan buka browser ```htttp://localhost:8080``` <br>

## demo
<img src="https://github.com/Rizky1408/CI4-Tugas/blob/main/ss1.png">
<img src="https://github.com/Rizky1408/CI4-Tugas/blob/main/ss2.png">
<img src="https://github.com/Rizky1408/CI4-Tugas/blob/main/ss3.png">

