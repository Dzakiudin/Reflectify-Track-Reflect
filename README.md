# 🌿 Reflectify — Track & Reflect

[![Status](https://img.shields.io/badge/status-private-red?style=flat-square)]()
[![Made with](https://img.shields.io/badge/made%20with-Firebase-orange?style=flat-square\&logo=firebase)]()
[![Powered by](https://img.shields.io/badge/powered%20by-Gemini%20AI-blue?style=flat-square\&logo=google)]()
[![UI](https://img.shields.io/badge/UI-TailwindCSS-38B2AC?style=flat-square\&logo=tailwindcss\&logoColor=white)]()
[![License](https://img.shields.io/badge/license-private-lightgrey?style=flat-square)]()

---

Reflectify adalah aplikasi **refleksi diri dan pelacak pertumbuhan pribadi** yang dirancang untuk membantu pengguna mencatat aktivitas harian, menulis jurnal reflektif, serta melacak suasana hati dan fokus dengan dukungan **AI dan Firebase**.

Repositori ini dibuat **khusus sebagai dokumentasi pribadi** dan **tidak bersifat open source**.

---

## 🌐 Demo Langsung

👉 **Coba aplikasi di sini:** [https://reflectfy.netlify.app/](https://reflectfy.netlify.app/)

> Note: Beberapa fitur mungkin memerlukan login atau konfigurasi Firebase agar berfungsi penuh.

---

## 🚀 Fitur Utama

* **🔐 Sistem Autentikasi**

  * Login & register via Firebase Auth (Email/Password)
  * Setiap pengguna memiliki data yang terpisah

* **📆 Daily Tracker**

  * Catat aktivitas harian dengan mudah
  * Edit & hapus aktivitas kapan saja

* **📓 Insight Journal**

  * Tulis refleksi berdasarkan kategori (*Mindset*, *Emosi*, *Spiritual*, *Sosial*, *Skill*)
  * Disimpan otomatis dan ditampilkan berdasarkan waktu

* **📊 Growth Dashboard**

  * Visualisasi grafik hubungan *Mood vs Fokus* selama 7 hari terakhir
  * Menggunakan Chart.js

* **🤖 AI Companion**

  * Terintegrasi dengan Gemini API
  * Memberi tanggapan reflektif, logis, dan empatik

* **💡 Daily Prompt**

  * Menyediakan pertanyaan refleksi acak setiap hari

---

## 🧠 Teknologi yang Digunakan

| Lapisan     | Teknologi                                    |
| ----------- | -------------------------------------------- |
| Frontend    | HTML5, Tailwind CSS, JavaScript (ES Modules) |
| Database    | Firebase Firestore                           |
| Autentikasi | Firebase Auth                                |
| Visualisasi | Chart.js                                     |
| Ikon        | Heroicons / Ionicons                         |
| AI          | Gemini API                                   |

---

## 📂 Struktur Proyek

```
reflectify/
│
├── index.html          # File utama aplikasi
├── /src/               # Screenshot atau aset visual
└── README.md           # Dokumentasi proyek
```

---

## ⚙️ Cara Menjalankan

1. **Clone Repository**

   ```bash
   git clone https://github.com/USERNAME/reflectify.git
   cd reflectify
   ```

2. **Konfigurasi Firebase**

   * Buka `index.html`
   * Masukkan konfigurasi Firebase Anda:

     ```js
     const firebaseConfig = {
       apiKey: "YOUR_API_KEY",
       authDomain: "...",
       projectId: "...",
       ...
     };
     ```

3. **Tambahkan Gemini API Key**

   * Masih di `index.html`, ubah bagian:

     ```js
     const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY_HERE";
     ```

4. **Jalankan Aplikasi**

   * Buka `index.html` langsung di browser modern
   * Tidak membutuhkan server backend (semua via Firebase)

---

## 🖼️ Preview Antarmuka (UI)

| Halaman          | Tampilan                                                                                                                |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Login / Register | ![Auth Page Preview](https://github.com/Dzakiudin/Reflectify-Track-Reflect/blob/main/src/login%20register%20mobile.png) |
| Tracker Harian   | ![Tracker Preview](https://github.com/Dzakiudin/Reflectify-Track-Reflect/blob/main/src/tracker%20mobile.png)            |
| Insight Journal  | ![Journal Preview](https://github.com/Dzakiudin/Reflectify-Track-Reflect/blob/main/src/jurnal%20mobile.png)             |
| Growth Dashboard | ![Dashboard Preview](https://github.com/Dzakiudin/Reflectify-Track-Reflect/blob/main/src/growth%20mobile.png)           |
| AI Companion     | ![AI Chat Preview](https://github.com/Dzakiudin/Reflectify-Track-Reflect/blob/main/src/ai%20mobile.png)                 |

---

## 🔒 Lisensi & Penggunaan

> **⚠️ Catatan Penting**
>
> Proyek ini bersifat **pribadi (private)** dan **tidak diperbolehkan untuk disalin, disebarluaskan, atau dimodifikasi tanpa izin tertulis.**
>
> Hak cipta © 2025 **JakiJeki**
> Diperbolehkan hanya untuk dokumentasi, arsip, atau portofolio pribadi.
> **Bukan untuk publik atau penggunaan komersial.**

---

## 💬 Kredit

* Developer: **@JakiJeki**
* Website: [https://reflectfy.netlify.app](https://reflectfy.netlify.app)
* Teknologi pendukung: Firebase, Chart.js, Tailwind CSS, Gemini API
* Tujuan: Meningkatkan kesadaran diri dan kebiasaan refleksi harian

---

### 🪞 “Refleksi kecil hari ini, transformasi besar di masa depan.”

> *Reflect. Grow. Repeat.*
