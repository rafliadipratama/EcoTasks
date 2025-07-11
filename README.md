# 🌱 EcoTasks

**EcoTasks** adalah aplikasi frontend berbasis **Blazor WebAssembly** yang dirancang untuk mengelola dan menampilkan data tugas (task management) secara interaktif. Proyek ini merupakan latihan pengembangan skill frontend menggunakan teknologi modern dari .NET.

---

## 🔧 Tech Stack

- ⚙️ **Blazor WebAssembly (.NET 8)**
- 🧠 **C#** untuk logika aplikasi dan komponen Razor
- 🧱 **HTML & CSS** untuk struktur & tampilan
- 🎨 **Bootstrap 5** untuk styling responsif
- 🌐 **HttpClient** untuk fetch data dari file JSON atau API

---

## 📁 Fitur Utama

- ✅ Menampilkan daftar tugas dari `tasks.json`
- ☁️ Menampilkan data cuaca dari `weather.json`
- 🧭 Navigasi antar halaman via komponen `NavMenu`
- ♻️ **Hot Reload** saat development (`dotnet watch run`)
- 🎨 Styling mudah dikustomisasi melalui `wwwroot/css/app.css`

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
Buka browser dan akses: http://localhost:5000

🗂 Struktur Folder
plaintext
Copy
Edit
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
🧠 Rencana Pengembangan (Opsional)
🔗 Integrasi dengan API eksternal

➕ Tambah/hapus tugas secara dinamis

🔐 Sistem login sederhana

🌗 Tema terang dan gelap (dark mode)

🖼️ Screenshot
Tambahkan screenshot dari aplikasi kamu di bawah ini jika tersedia:


👨‍💻 Kontribusi
Kontribusi sangat terbuka! Untuk berkontribusi:

Fork repositori ini

Buat branch baru (feature/nama-fitur)

Commit perubahan kamu

Push ke GitHub dan buka Pull Request

👤 Author
Made with ❤️ by Rafli Adipratama

GitHub: @rafliadipratama

LinkedIn: linkedin.com/in/rafliadipratama

📜 Lisensi
Proyek ini dilisensikan di bawah lisensi MIT – silakan gunakan, ubah, dan bagikan proyek ini secara bebas.

Terima kasih telah mengunjungi proyek ini! 🙏

yaml
Copy
Edit

---

Jika kamu ingin menambahkan badge (seperti license, last commit, stars, atau tech stack), tinggal beri tahu, dan saya bisa bantu generate-nya juga.
