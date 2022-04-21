<p align="center">
<img align="center" src="http://ForTheBadge.com/images/badges/built-with-love.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/uses-html.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/makes-people-smile.svg"> <img align="center" src="http://ForTheBadge.com/images/badges/built-by-developers.svg">
</p>

# ⏲️ Jam Sholat Masjid Al - Muttaqin

<p>Aplikasi ini menggunakan algoritma perhitungan sholat dari perhitungan Jam Kementerian Agama Indonesia. Aplikasi ini dibuat untuk mengoptimalkan waktu sholat dari sebuah masjid. Aplikasi ini dibuat dengan menggunakan bahasa pemrograman PHP dan menggunakan library PHP yang dibutuhkan untuk menghitung waktu sholat. Aplikasi ini dibuat dengan menggunakan framework Codeigniter.</p>

<img src="" height="300px" width="600px">
<img src="" height="300px" width="600px">
<img src="" height="300px" width="600px">
<img src="" height="300px" width="600px">
<br>

## 👦🏽 Siapa pembuat aplikasi ini?

| Profile        |  Keterangan                      |
|----------------|----------------------------------|
| Nama           | Bagus Budi Satoto                |
| Jurusan        | S1 - Informatika                 |
| Kampus         | Universitas Amikom Yogyakarta    |


## 🧑🏽‍💻 Profile 
<div>
      <p><i class="fas fa-envelope-open-text"></i><a href="mailto:" target="_blank"> Mail : bagusbudi1308@gmail.com</a></p>            
      <p><i class="fab fa-github"></i> <a href="https://github.com/bagussatoto"> Github : Bagus Budi Satoto</a></p>  
      <p><i class="fab fa-facebook"></i> <a href="https://www.facebook.com/bagussatoto1"> Facebook : Bagus Budi Satoto</a></p>
      <p><i class="fab fa-instagram"></i> <a href="https://www.instagram.com/bagus_satoto1"> Instagram : Bagus Budi Satoto</a></p>    
      <p><i class="fab fa-linkedin"></i> <a href="https://www.linkedin.com/in/bagussatoto/"> Linkedin : Bagus Budi Satoto</a></p>
</div>

## 🖥️ Fitur Aplikasi Jam Digital

- Halaman awal dashboard <br><br>

A. Dashboard 
- Menampilkan informasi tentang waktu sholat yang akan datang <br><br>
- Menampilkan motivasi untuk sholat <br><br>

B. Setting 
- Pengaturan dasar 
  <il>- Tentang Masjid<il>
  <il>- Pengeturan Slide Show<il >
  <il>- Layout Aplikasi<il>
  <il>- Kunci Layar Aplikasi<il>

- Notifikasi 
  <il>Informasi Tambahan Ketika Adzan dan Iqomah<il>
  <il>Informasi Waktu Sholat Jum'at<il>
  <il>Informasi Waktu Syuruk<il>

- Pengaturan Teks Berjalan 

- Slide 1 & Slide 2

- Upload Gambar

- Informasi Tentang Aplikasi 
  <il>Profil Pembuat<il>
  <il>Tentang Hak Cipta<il>
  <il>Tentang Aplikasi<il>
  <il>Contributor<il>
  <il>Version<il>

## 📚 Cara menggunakan aplikasi ini

<ul>
      <li>1. Install Apache https://pimylifeup.com/raspberry-pi-apache</li>
      <li>2. Ubah permission</li>
      <ul>
        <li>sudo usermod -a -G www-data pi ----> [pi adalah nama user yang dipakai untuk login]</li>
        <li>sudo chown -R -f www-data:www-data /var/www/html</li>
      </ul>
      <li>3. Install PHP</li>
      <ul>
        <li>sudo apt install php7.3 php7.3-mbstring php7.3-mysql php7.3-curl php7.3-gd php7.3-zip -y</li>
      </ul>
      <li>4. Install MySQL https://pimylifeup.com/raspberry-pi-mysql</li>
      <ul>
        <li>sudo apt install mariadb-server</li>
        <li>sudo apt-install php-mysql</li>
      </ul>
      <li>5. Buat database</li>
      <ul>
        <li>sudo mysql -u root</li>
        <li>create database masjid;</li>
        <li>quit</li>
      </ul>      
      <li>6. Download dan extract folder imasjid.</li>
        <ul>
          <li>sudo cp -R imasjid /var/www/html</li>
          <li>sudo chown pi /var/www/html/imasjid</li>
          <li>sudo chmod -R 767 /var/www/html/imasjid</li>
        </ul>
      </li>
      <li>7. Restore database from file</li>
        <ul>
          <li>sudo mysql -u root masjid < masjid.sql  --> saya jalankan perintah ini dari folder /var/www/html/imasjid</li>
        </ul>
      </li>
      <li>8. Grant user ke database masjid</li>
        <ul>
          <li>grant all on masjid.* to monitor@localhost identified by 'monitor';</li>
          <li>flush privileges;</li>
        </ul>
      </li>
    </ul>


## ⛔  Alat Yang Digunakan Untuk Membuat Web :

-   WAMP
-   Visual Studio Code
-   Git
-   Cloud (Github)
-   PHP 7.4.9
-   MYSQL 8.0.13
-   Codeigniter 3.1.10
-   Bootstrap 4.3.1
-   Font Awesome 5.13.1
-   Jquery 3.3.1
-   Sweet Alert 2
-   Font Awesome 5.13.1

## ‼️ Tentang Hak Cipta
<p>Aplikasi ini bebas dipakai/dikembangkan oleh siapa saja semata-mata hanya untuk kepentingan masjid. Dilarang memperjualbelikan aplikasi ini dengan alasan   apapun.</p>
<p>Mohon tetap mencantumkan nama saya ◎ <i class="fab fa-github"></i> <a href="https://github.com/bagussatoto"> Bagus Budi Satoto</a></p> jika ada modifikasi di aplikasi ini.</p>
<p>Jika ke depannya aplikasi ini dipakai di suatu masjid, mohon informasikan ke saya nama masjid, alamat, beserta tampilan akhirnya. Ini hanya sebagai tracking agar saya tahu berapa banyak masjid yg menggunakan aplikasi ini.</p>

## 📌 Request Fitur Baru dan Pelaporan Bug

Anda dapat meminta fitur baru maupun melaporkan bug melalui menu **issues** yang sudah disediakan oleh GitHub (lihat menu di atas), posting issues baru dan kita akan berdiskusi disana.

## 🛒 Berkontribusi

Siapapun dapat berkontribusi pada proyek ini mulai dari pemrograman, pembuakan buku manual, sampai dengan mengenalkan produk ini kepada Mahasiswa 
Untuk belajar agar mengurangi kesenjangan pendidikan teknologi dengan cara membuat postingan issue di repository ini.

