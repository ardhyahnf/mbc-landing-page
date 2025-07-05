# MBC Laboratory Website

Website resmi MBC Laboratory – Pusat Riset Teknologi yang berfokus pada Cybersecurity, Big Data, GIS, dan Game Technology.

**📁 Struktur Proyek**

├── index.html       ← Halaman utama website
├── design.css       ← File CSS untuk styling 
├── script.js        ← Script interaktif
├── mbclab.png       ← Logo lab


**💻 Cara Menjalankan Secara Lokal**

1. Pastikan semua file (`index.html`, `design.css`, `script.js`, `mbclab.png`) berada dalam satu folder.
2. Buka `index.html` dengan browser (klik dua kali atau gunakan `Live Server` di VS Code).

**🚀 Deployment**

Website ini di-deploy menggunakan [Netlify](https://www.netlify.com/).

Langkah Deployment:
1. Buka [Netlify Dashboard](https://app.netlify.com/).
2. Klik "Add new site" > "Import an existing project".
3. Hubungkan ke repository GitHub kamu yang berisi file website.
4. Pilih branch (misal: `main`) dan klik Deploy Site.
5. Setelah berhasil, kamu akan mendapatkan URL publik seperti `https://mbcwebsite.netlify.app/`.

**🔒 SSL & Backend**

- SSL: Netlify secara otomatis memberikan HTTPS/SSL gratis untuk setiap domain.
- Backend: Tidak digunakan. Semua halaman bersifat statis.
