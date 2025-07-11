# EcoTasks 🌱

**EcoTasks** adalah aplikasi frontend berbasis **Blazor WebAssembly** yang dibuat untuk membantu mengelola dan menampilkan data tugas (task management) secara interaktif. Proyek ini ditujukan sebagai latihan dan pengembangan skill frontend menggunakan teknologi .NET.

---

## 🔧 Tech Stack

- **Blazor WebAssembly (.NET 8)**
- **C#** untuk komponen dan logika aplikasi
- **HTML & CSS** untuk struktur dan tampilan
- **Bootstrap 5** untuk styling dasar
- **HttpClient** untuk pengambilan data dari file JSON atau API

---

## 📁 Fitur Utama

- 📋 Menampilkan daftar tugas dari `tasks.json`
- 🌤️ Halaman prediksi cuaca dari `weather.json`
- 🧭 Navigasi antar halaman dengan `NavMenu`
- 🔥 Dukungan **Hot Reload** saat development
- 🎨 Styling dapat disesuaikan melalui `wwwroot/css/app.css`

---

## 🚀 Cara Menjalankan

> Pastikan kamu sudah menginstal .NET SDK minimal versi 6 atau 8.

Langkah-langkah menjalankan aplikasi:

```bash
# Clone repositori
git clone https://github.com/rafliadipratama/EcoTasks.git
cd EcoTasks

# Restore dependensi dan jalankan server dengan hot reload
dotnet watch run

# Buka browser dan akses:
http://localhost:5000
````

---

## 🗂 Struktur Folder

```text
EcoTasks/
│
├── Pages/                     # Halaman Razor utama
│   ├── Index.razor
│   ├── Counter.razor
│   └── FetchData.razor
│
├── Shared/                    # Komponen bersama & layout
│   ├── NavMenu.razor
│   └── MainLayout.razor
│
├── wwwroot/                   # Aset statis (CSS, gambar, JSON)
│   ├── css/
│   ├── favicon.png
│   ├── index.html
│   └── sample-data/
│       ├── tasks.json
│       └── weather.json
│
├── App.razor                  # Root komponen aplikasi
├── Program.cs                 # Entry point aplikasi
└── EcoTasks.csproj            # File proyek Blazor
```

---

## 🧠 Rencana Pengembangan (Opsional)

* Integrasi dengan API eksternal
* Tambah/menghapus tugas secara dinamis
* Sistem login sederhana
* Tema terang dan gelap

---

## 🖼️ Screenshot

Tambahkan screenshot jika tersedia. Contoh:

![Screenshot EcoTasks](screenshot.png)

---

## 👨‍💻 Kontribusi

Kontribusi sangat terbuka! Jika kamu ingin menambahkan fitur atau memperbaiki bug:

1. Fork repo ini
2. Buat branch baru (`feature/fitur-baru`)
3. Commit perubahan
4. Push ke branch kamu
5. Buka Pull Request

---

## 👤 Author

Made with ❤️ by **Rafli Adipratama**

* GitHub: [@rafliadipratama](https://github.com/rafliadipratama)
* LinkedIn: [linkedin.com/in/rafliadipratama](https://linkedin.com/in/rafliadipratama)

---

## 📜 Lisensi

Proyek ini dilisensikan di bawah lisensi MIT – silakan gunakan, modifikasi, dan distribusikan dengan bebas.

Terima kasih telah mengunjungi proyek ini!
