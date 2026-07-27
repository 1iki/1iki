# Panduan Setup & Push ke Repositori GitHub @1iki

Repositori ini siap di-push ke repositori spesial GitHub Anda: `https://github.com/1iki/1iki`.

---

## Langkah 1: Push Repositori ke GitHub

Jalankan perintah berikut di terminal repositori lokal Anda (`c:\Code\AI CODER\BIO-GITHUB\PROFILE-SCANNER`):

```bash
git init
git add .
git commit -m "feat: setup cyber-terminal profile and jet heatmap for @1iki"
git branch -M main
git remote add origin https://github.com/1iki/1iki.git
git push -u origin main --force
```

---

## Langkah 2: Aktifkan Workflow Permissions di GitHub Actions

Agar animasi **Jet Heatmap** (`dist/github-jet.svg`) dapat ter-update otomatis setiap hari:

1. Buka repositori `1iki/1iki` di browser: `https://github.com/1iki/1iki`
2. Masuk ke **Settings** -> **Actions** -> **General**
3. Di bagian **Workflow permissions**, pilih **Read and write permissions**
4. Klik **Save**

---

## Langkah 3: Jalankan Workflow Pertama Kali (Opsional)

1. Buka tab **Actions** di repositori `1iki/1iki`
2. Pilih workflow **Update jet heatmap SVG** di sebelah kiri
3. Klik tombol **Run workflow** -> **Run workflow**
4. Workflow akan mengambil kalender kontribusi asli Anda dan memperbarui file `dist/github-jet.svg` secara otomatis!
