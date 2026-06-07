# 💰 My Wallet

My Wallet adalah aplikasi manajemen keuangan sederhana berbasis HTML, Tailwind CSS, dan JavaScript yang membantu pengguna mengelola saldo, transaksi, serta target tabungan secara praktis.

## ✨ Fitur Utama

### 📊 Dashboard

* Menampilkan ringkasan kondisi keuangan.
* Menampilkan target tabungan aktif beserta progress.
* Menampilkan insight keuangan berdasarkan pemasukan dan pengeluaran.
* Menu navigasi cepat ke halaman Saldo dan Tabungan.

### 💵 Kelola Saldo

* Menambahkan transaksi pemasukan.
* Menambahkan transaksi pengeluaran.
* Menampilkan total saldo.
* Menampilkan total pemasukan.
* Menampilkan total pengeluaran.
* Riwayat transaksi lengkap.
* Hapus transaksi.
* Reset seluruh data transaksi.

### 🏦 Kelola Tabungan

* Membuat target tabungan baru.
* Menentukan nominal target.
* Menentukan deadline target.
* Progress tabungan otomatis.
* Setor tabungan langsung dari saldo.
* Validasi saldo sebelum setor.
* Riwayat setoran tabungan.
* Hapus target tabungan.

## 🛠️ Teknologi Yang Digunakan

* HTML5
* Tailwind CSS
* JavaScript (Vanilla JS)
* LocalStorage

## 📁 Struktur Folder

```text
My-Wallet/
│
├── dashboard.html
│
├── assets/
│   └── script.js
│
├── layouts/
│   ├── navbar.html
│   └── sidebar.html
│
└── pages/
    ├── saldo.html
    └── tabungan.html
```

## 🚀 Cara Menjalankan

1. Clone repository

```bash
git clone https://github.com/username/my-wallet.git
```

2. Buka project menggunakan Visual Studio Code.

3. Install extension **Live Server**.

4. Jalankan melalui Live Server.

```text
Klik kanan dashboard.html
→ Open with Live Server
```

## 💾 Penyimpanan Data

Aplikasi menggunakan LocalStorage sehingga data tetap tersimpan meskipun halaman direfresh atau browser ditutup.

Data yang disimpan:

### Transaksi

```javascript
wallet_transactions
```

### Target Tabungan

```javascript
wallet_savings
```

## 🔄 Alur Sistem

### Sistem Saldo

```text
Tambah Transaksi
        ↓
Simpan ke LocalStorage
        ↓
Hitung Saldo Otomatis
        ↓
Update Riwayat Transaksi
```

### Sistem Tabungan

```text
Buat Target
        ↓
Setor Tabungan
        ↓
Saldo Berkurang
        ↓
Tabungan Bertambah
        ↓
Progress Target Bertambah
        ↓
Riwayat Setoran Tersimpan
```

## 🎯 Tujuan Project

Project ini dibuat sebagai media pembelajaran untuk memahami:

* Manipulasi DOM JavaScript
* LocalStorage
* CRUD Data
* Pengelolaan State Sederhana
* Desain UI Modern dengan Tailwind CSS
* Responsive Web Design

## 📸 Preview

Tambahkan screenshot aplikasi pada bagian ini setelah project selesai dikembangkan.

## 👨‍💻 Developer

Muhammad Parhan Padilah

Project pembelajaran dan pengembangan keterampilan Front-End Web Development.
