
# Sistem Informasi Sekolah

Sistem informasi sekolah berbasis laravel 11 dengan template dashboard
[Stisla](https://getstisla.com/)
## Authors

- [Pascal Adnan](https://www.github.com/lacsapadnan)


## Fitur


- CRUD Mata Pelajaran
- CRUD Guru
- CRUD Kelas
- CRUD User
- CRUD Materi
- CRUD Tugas & Jawaban
- CRUD Jadwal Sekolah


## Screenshots

<img width="938" height="440" alt="image" src="https://github.com/user-attachments/assets/e98d2684-420b-4d85-b575-057a57ab296d" />

<img width="953" height="447" alt="image" src="https://github.com/user-attachments/assets/95a7d86f-5b01-41ec-b457-291133a06f76" />

<img width="955" height="439" alt="image" src="https://github.com/user-attachments/assets/67205e36-5b81-436d-9e91-c538ea748c45" />



## Instalasi

clone project atau download

```bash
  git clone https://github.com/DemisonWonda/sis.git
  cd Sistem-Informasi-Sekolah
  npm install
  composer install
  cp .env.example .env
```

Buka `.env` dan atur database anda
```bash
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=
```

Install website
```bash
  php artisan key:generate
  php artisan migrate --seed
```

Jalankan website
```bash
  php artisan serve
```
## Default akun untuk testing

Admin
```bash
  email : admin@mail.com
  password : admin123
```

Guru
```bash
  email : budi@mail.com
  password : budi123

  email : gunawan@mail.com
  password : gunawan123
```

Siswa
```bash
  email : kevin@mail.com
  password : kevin123

  email : siska@mail.com
  password : siska123
```
## Update Selanjutnya

(Free Version)
- Fitur Pengumuman Sekolah ✅
- Role Orang tua (Lihat pengumpulan tugas) ✅
- Pengaturan ✅

(Premium Version)
- Premium Template Metronic ✅
- Fitur Absensi ✅
- Fitur Kuis atau Ujian ✅
- Fitur Tabungan Siswa ✅
- Fitur Pembayaran Sekolah ✅
- Payment Gateway (Midtrans, Xendit, Tripay, dll) ✅(Currently Xendit Integrated)
- Role Orangtua (Lihat absensi, nilai) ✅
- Fitur e-rapot ✅
- Fitur nilai tugas ✅


## DEMO PREMIUM

https://sekolah.karsagroup.id

Admin
```bash
  email : admin@gmail.com
  password : password123
```

## PEMBELIAN

~~Promo 10/10 Orang Pertama **500rb**~~
Promo 15/20 Kloter Berikutnya **750rb**

Hubungi 
- https://wa.me/6282244793613
- http://instagram.com/lacsapadnan



