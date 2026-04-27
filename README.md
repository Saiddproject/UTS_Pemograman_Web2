# UTS_Pemograman_Web2

# 🛡️ Lab Eksperimen Keamanan Web: SQLi & XSS
Proyek ini dibuat untuk memenuhi tugas **UTS Pemrograman Web**. Fokus utama proyek ini adalah melakukan eksperimen mandiri mengenai kerentanan web yang umum terjadi, yaitu **SQL Injection (SQLi)** dan **Cross-Site Scripting (XSS)** menggunakan PHP.
```
uts-pemrograman-web/
├── assets/
│   ├── css/
│   │   └── style.css       # File CSS mewah yang sudah dibuat
│   └── img/                # Simpan screenshot hasil eksperimen di sini
├── config/
│   └── database.php        # Konfigurasi database
├── sql-injection/
│   ├── index.php
│   ├── login-vulnerable.php
│   └── login-secure.php
├── xss/
│   ├── comment.php
│   ├── view-vulnerable.php
│   └── view-secure.php
├── db_setup.sql            # Script SQL untuk database
└── README.md               # Dokumentasi proyek (Wajib ada)
```
## 🚀 Fitur Lab
- **SQL Injection Lab**: Simulasi bypass login pada kode rentan vs proteksi menggunakan Prepared Statements.
- **XSS Lab**: Simulasi eksekusi skrip berbahaya pada kolom komentar vs proteksi menggunakan Output Encoding (`htmlspecialchars`).
- **Modern UI**: Antarmuka responsif dan mewah menggunakan CSS kustom.

## 🛠️ Teknologi yang Digunakan
- **Bahasa**: PHP 8.x
- **Database**: MariaDB / MySQL
- **Server**: Apache (XAMPP)
- **Styling**: Modern CSS with Inter Fonts

# 👤 Identitas
Nama: [Muhammad Said Abimanyu]

NIM: [312410145]
