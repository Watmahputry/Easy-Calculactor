# Easy-Calculactor

# EasyCalculator - Aplikasi Mobile Kalkulator

## Deskripsi Project
EasyCalculator adalah aplikasi kalkulator sederhana berbasis Android, dibuat untuk menghitung operasi matematika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian.
Aplikasi ini juga menyimpan riwayat perhitungan ke database lokal (SQLite) dan memungkinkan pengguna untuk melihat dan menghapus riwayat tersebut.

## Fitur Utama
- Kalkulator untuk operasi dasar.
- Riwayat perhitungan disimpan secara otomatis.
- Menghapus riwayat perhitungan satu per satu.
- Desain antarmuka sederhana dan mudah digunakan.

## Storyboard UI/UX DEVELOPER
 ## 📱 Kalkulator Android - Modern & Sederhana

Aplikasi kalkulator modern dengan desain bersih dan antarmuka yang intuitif. Dilengkapi fitur histori perhitungan dan dukungan input ekspresi matematika lengkap.

---

### 🧭 **Storyboard Pengguna**

#### 1. **Buka Aplikasi**

* Pengguna membuka aplikasi dan langsung diarahkan ke tampilan utama kalkulator.
* Tampilan menampilkan layar hasil (`result`) dan layar ekspresi (`solution`) di atas.

#### 2. **Melakukan Perhitungan**

* Pengguna mengetik ekspresi seperti `12 + (3 * 5)` dengan mengetuk tombol-tombol angka dan operator.
* Input ditampilkan secara real-time pada layar ekspresi.

#### 3. **Melihat Hasil**

* Saat menekan tombol `=`, hasil perhitungan ditampilkan besar di bagian bawah layar ekspresi.

#### 4. **Riwayat Perhitungan**

* Semua perhitungan sebelumnya muncul dalam **RecyclerView** di bagian atas.
* Pengguna bisa menggulir untuk melihat riwayat sebelumnya.

#### 5. **Menghapus Riwayat**

* Pengguna bisa mengetuk tombol **"Clear History"** di samping label "History".
* Riwayat akan langsung terhapus untuk menjaga privasi dan kebersihan tampilan.

---

### ✨ **Fitur Utama**

* ✅ Antarmuka intuitif dan bersih (Material Design).
* ✅ Dukungan operator dasar dan tanda kurung.
* ✅ Tombol ekspresif berbentuk bulat (FAB Style).
* ✅ Tampilan hasil dan ekspresi yang terpisah untuk visibilitas.
* ✅ Riwayat perhitungan yang bisa dihapus.

---

### 📸 **Tangkapan Layar**

> *(Tambahkan screenshot jika tersedia, misalnya: `screenshots/home.png`, `screenshots/history.png`)*

---

### 🧱 **Struktur UI (XML Layout)**

* **`RelativeLayout`** utama untuk fleksibilitas posisi elemen.
* **`RecyclerView`** di atas sebagai histori.
* **`TextView`** untuk ekspresi dan hasil perhitungan.
* **`LinearLayout`** bertumpuk untuk barisan tombol kalkulator.
* **MaterialButton** digunakan untuk gaya tombol modern.

---

### 🚀 Teknologi

* Bahasa: Java
* UI: XML + Material Components
* Komponen: `RecyclerView`, `MaterialButton`, `TextView`, `RelativeLayout`

---

### 📦 Instalasi Lokal (Opsional)

```bash
git clone https://github.com/username/kalkulator-android.git
cd kalkulator-android
```

> Buka di Android Studio dan jalankan di emulator atau perangkat nyata.

---

### 💡 Catatan UX

* Gunakan `android:maxHeight` untuk membatasi tinggi RecyclerView agar tidak menutupi UI utama.
* Posisikan tombol penting seperti `C` dan `AC` dengan warna berbeda untuk mencegah kesalahan pengguna.
* Pastikan animasi sederhana (misalnya fade in/out pada history) untuk pengalaman yang mulus.

---

### 📬 Kontribusi

Terbuka untuk pull request dan saran desain!

---



[ Calculator Screen ]
+-------------------------------+
|    Expression (5+7×2)          |
|    Result (19)                 |
|-------------------------------|
| 7 | 8 | 9 | ÷                 |
| 4 | 5 | 6 | ×                 |
| 1 | 2 | 3 | -                 |
| 0 | . | = | +                 |
|        [History Icon]         |
+-------------------------------+

[ History Screen ]
+--------------------------------+
| 5+7×2 = 19         [Delete]    |
| 9-2 = 7            [Delete]    |
| 8÷4 = 2            [Delete]    |
+--------------------------------+

## Teknologi yang Digunakan
- Java (Android Studio)
- SQLite Database
- RecyclerView
- Material Design Components

## Pembagian Tugas (Untuk 4 Orang)

| Nama | Tugas |
|------|-------|
| Watmah | UI/UX Design (Membuat tampilan kalkulator dan history) |
| Wahyu Wulan Oktavia | Pembuatan Kalkulasi dan Logika Event pada tombol |
| Miranda Oktavia Siagian | Pembuatan Database Helper dan CRUD SQLite untuk Riwayat |
| Niken Ayu Ristiani | Integrasi RecyclerView + Tombol Delete di Riwayat |



## Link Repository
> [Link Github kamu di sini]

## Link Trello Board (SCRUM Management)
> https://wulanoktaviawahyu-1745597155870.atlassian.net/jira/software/projects/SCRUM/boards/1?atlOrigin=eyJpIjoiYmZmM2VhZjFlZjFjNDhlZGJiNDVkN2I4ZTdlMDEzYjkiLCJwIjoiaiJ9]
