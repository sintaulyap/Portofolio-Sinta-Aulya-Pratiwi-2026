# Portfolio — Sinta Aulya Pratiwi

Website portofolio pribadi (Finance, Accounting & Tax Specialist), dibuat dengan HTML, CSS, dan vanilla JavaScript murni (tanpa framework, tanpa build step).

## Struktur

```
.
├── index.html   # seluruh halaman (markup, style, script jadi satu file)
└── README.md
```

## Cara publish ke GitHub Pages

1. **Buat repository baru** di GitHub, misal `sinta-portfolio`.
2. **Upload file ini** ke repo (lewat web GitHub "Add file → Upload files", atau lewat git di terminal):
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: portfolio site"
   git branch -M main
   git remote add origin https://github.com/USERNAME/sinta-portfolio.git
   git push -u origin main
   ```
3. Di repo, buka **Settings → Pages**.
4. Pada **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit, situs akan aktif di:
   ```
   https://USERNAME.github.io/sinta-portfolio/
   ```

## Catatan

- File `index.html` sudah lengkap (HTML + CSS + JS dalam satu file), jadi tidak perlu proses build apa pun — cukup upload dan aktifkan GitHub Pages.
- Beberapa sertifikat dimuat lewat pratinjau Google Drive (`drive.google.com/file/d/.../preview`). Pastikan file di Drive tersebut sudah diset **"Anyone with the link can view"**, kalau tidak pratinjau tidak akan muncul di GitHub Pages.
- Kalau nanti mau pakai custom domain, tinggal tambahkan file `CNAME` berisi domain kamu di root repo, lalu atur DNS-nya sesuai instruksi GitHub Pages.
