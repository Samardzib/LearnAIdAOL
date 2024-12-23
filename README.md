# LearnAid

![Lernaid LOGO](https://github.com/user-attachments/assets/e5ea8c07-a703-4e2e-a7be-fe7313410259)

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#learnaid">LearnAid</a>
    </li>
    <li>
      <a href="#anggota-tim">Anggota Tim</a>
    </li>
    <li>
      <a href="#target-sdgs">Target SDGs</a>
    </li>
    <li>
      <a href="#link-website">Link Website</a>
    </li>
    <li>
      <a href="#struktur-erd-database">Struktur ERD Database</a>
    </li>
    <li>
      <a href="#halaman-website">Halaman Website</a>
      <ul>
        <li><a href="#1-halaman-login">1. Halaman Login</a></li>
        <li><a href="#2-halaman-register">2. Halaman Register</a></li>
        <li><a href="#3-halaman-forgot-password">3. Halaman Forgot Password</a></li>
        <li><a href="#4-halaman-homepage">4. Halaman Homepage</a></li>
      </ul>
    </li>
    <li>
      <a href="#dibangun-dengan">Dibangun Dengan</a>
    </li>
    <li>
      <a href="#memulai">Memulai</a>
      <ul>
        <li><a href="#prasyarat">Prasyarat</a></li>
        <li><a href="#instalasi">Instalasi</a></li>
      </ul>
    </li>
    <li>
      <a href="#ucapan-terima-kasih">Ucapan Terima Kasih</a>
    </li>
  </ol>
</details>

LearnAid adalah platform web inovatif yang dirancang untuk membantu pelajar meningkatkan produktivitas mereka melalui fitur-fitur canggih seperti sistem login, daftar tugas dengan kemampuan CRUD, dan timer Pomodoro untuk manajemen waktu yang efektif. Dengan LearnAid, pelajar dapat mengelola waktu dan tugas mereka dengan lebih baik, sehingga meningkatkan efisiensi belajar.

---

## Anggota Tim

| Nama                | Peran & Kontribusi            |
|---------------------|-------------------------------|
| Sean Kenneth Tommy Keleyan         | Pemimpin Proyek, Login & CRUD|
| Syafiq Ammar Muhadzdzib    | UI/UX Desainer, Desain Homepage (frontend) |
| Ferry Jaya Dinata   | Pengembang Backend, Logika Timer |
| Reinaldy Zulfananda Arkaan    | Penulis Konten, Dokumentasi, alert notification  |

---

## Target SDGs

**Tujuan 4: Pendidikan Berkualitas**  
LearnAid berkomitmen untuk mendukung pelajar dalam mencapai pendidikan berkualitas dengan menyediakan alat bantu yang meningkatkan produktivitas dan efisiensi belajar. Dengan fitur-fitur yang terintegrasi, pelajar dapat lebih fokus dan terorganisir dalam proses belajar mereka.

---

## Link Website
[Demo LearnAid](https://learnaid.xyz/login)

---

## Struktur ERD Database

![WhatsApp Image 2024-12-23 at 22 56 12_80bf0c7d](https://github.com/user-attachments/assets/1990e0b8-0e07-427d-8f84-2b62bb45a299)

---

## LOGO

![Lernaid LOGO](https://github.com/user-attachments/assets/ceed91c1-b4ad-4407-8e5c-892c789288f8)

---

## Halaman Website

### 1. Halaman Login
**Tampilan:**
- Formulir sederhana dengan dua input: satu untuk email dan satu untuk password.
- Tombol "Login" yang jelas dan mencolok.
- Tautan untuk mengarahkan pengguna ke halaman "Forgot Password" dan "Register" jika mereka belum memiliki akun.

**Fungsi:**
- Memungkinkan pengguna untuk masuk ke akun mereka.
- Validasi input untuk memastikan bahwa username/email dan password yang dimasukkan benar.
- Mengarahkan pengguna ke homepage setelah login berhasil.

### 2. Halaman Register
**Tampilan:**
- Formulir pendaftaran dengan input untuk nama, email address, password dan konfirmasi password.
- Tombol "Register" yang jelas.
- Tautan untuk kembali ke halaman login bagi pengguna yang sudah memiliki akun.

**Fungsi:**
- Memungkinkan pengguna untuk membuat akun baru.
- Validasi input untuk memastikan bahwa semua field diisi dan email dalam format yang benar.
- Mengarahkan pengguna ke halaman login setelah pendaftaran berhasil.

### 3. Halaman Forgot Password
**Tampilan:**
- Formulir dengan input untuk email yang terdaftar.
- Tombol "Reset Password" yang jelas.
- Tautan untuk kembali ke halaman login.

**Fungsi:**
- Memungkinkan pengguna untuk memasukkan email mereka untuk menerima instruksi reset password.
- Validasi input untuk memastikan bahwa email yang dimasukkan terdaftar.
- Mengirimkan email dengan tautan untuk mereset password jika email valid.

### 4. Halaman Homepage
**Tampilan:**
- Header dengan logo dan navigasi ke halaman lain (Logout).
- Bagian utama yang menampilkan fitur utama LearnAid, termasuk Pomodoro Timer dan To-Do List.
- Informasi tambahan tentang teknik Pomodoro dan manfaatnya.
- Testimoni pengguna yang memberikan kepercayaan kepada pengunjung baru.
- Serta informasi tentang tim yang bekerja di projek ini

**Fungsi:**
- Menyediakan informasi publik tentang LearnAid dan fitur-fitur yang ditawarkan.
- Menyediakan akses cepat ke fitur Pomodoro Timer dan To-Do List.
- Mengedukasi pengguna tentang teknik Pomodoro dan manfaatnya.

---

## Tampilan Fitur
**1. Register**

![WhatsApp Image 2024-12-23 at 22 18 20_c80e3371](https://github.com/user-attachments/assets/b5e3a435-e7b4-4064-aec4-c3935c6fdd93)

**2. Login**

![WhatsApp Image 2024-12-23 at 22 18 21_dd734874](https://github.com/user-attachments/assets/e508b826-928f-48d1-bfb3-0e3e6eea60d0)

**3. Timer**

![WhatsApp Image 2024-12-23 at 22 20 35_d8a2c7a0](https://github.com/user-attachments/assets/8ace2662-34b1-454a-af5f-7c6aaeb4c6ca)

**4. Todolist(CRUD)**

![WhatsApp Image 2024-12-23 at 22 20 53_e2913c83](https://github.com/user-attachments/assets/f6826ef6-bf80-4f6f-b56e-644e579578ab)

**5. What is LernAid & Fun fact about pomodoro**

![WhatsApp Image 2024-12-23 at 22 23 06_9c369c77](https://github.com/user-attachments/assets/416f124c-7b9c-4b29-b68e-ab66959df9be)

**6. Why Pomodoro Method is  Effective? & Testimonials**

![WhatsApp Image 2024-12-23 at 22 23 05_cdfc886c](https://github.com/user-attachments/assets/f4421ea6-6537-4491-bcab-0d60d9dab119)

**7. Meet the Teams**

![WhatsApp Image 2024-12-23 at 22 23 05_ce4d505a](https://github.com/user-attachments/assets/19c7d0ba-1b25-4d3a-a0a9-d4082a8af572)

---

## Dibangun Dengan
- **Frontend**: Bootstrap, JavaScript
- **Backend**: Laravel
- **Database**: MySQL

---

## Memulai

### Prasyarat
- Composer
- PHP >= 8.0
- MySQL

### Instalasi
1. Clone repositori:
   ```sh
   git clone https://github.com/username-anda/learnaid.git
   ```
2. Instal dependensi:
   ```sh
   composer install
   ```
3. Konfigurasi lingkungan:
   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
4. Migrasi database:
   ```sh
   php artisan migrate
   ```
5. Jalankan aplikasi:
   ```sh
   php artisan serve
   ```

---

## Ucapan Terima Kasih
- **Terima Kasih Khusus**: Kepada mentor dan kontributor atas masukan berharga mereka.
- **Sumber Daya yang Digunakan**:
  - [Dokumentasi Laravel](https://laravel.com/docs)
  - [Framework Bootstrap](https://getbootstrap.com)

---

<p align="right">(<a href="#readme-top">kembali ke atas</a>)</p>
