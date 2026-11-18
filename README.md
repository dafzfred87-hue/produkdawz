# 👑 DaWz Store Official — Website v2

Website toko digital futuristic dengan animasi canvas particles, efek glitch, scan line, dan order langsung ke Telegram.

---

## 🚀 Deploy ke Vercel

### Step 1 — Push ke GitHub

```bash
cd /storage/emulated/0/Download/produkdawz

git config --global --add safe.directory $(pwd)
git config --global user.email "dafzfred87@gmail.com"
git config --global user.name "dafzfred"

git init
git add .
git commit -m "init dawz store v2"
git branch -M main
git remote add origin https://dafzfred87-hue:TOKEN@github.com/dafzfred87-hue/produkdawz.git
git push -u origin main --force
```

### Step 2 — Deploy di Vercel

1. Buka vercel.com → New Project → Import `produkdawz`
2. Framework Preset: **Other**
3. Klik **Deploy** — selesai ✅

Tidak perlu env variables. Static HTML murni.

---

## ✏️ Yang Perlu Diedit

Buka `public/index.html`, cari dan ganti:

| Yang dicari | Ganti dengan |
|---|---|
| `6281234567890` | Nomor WA lo (tanpa +) |
| `@Dafzfred` | Username TG lo |
| `DaWzStore9` | Channel testi lo |

---

## 🏃 Jalankan Lokal

```bash
cd /storage/emulated/0/Download/produkdawz/public
python -m http.server 8080
```

Buka: `http://localhost:8080`

---

© 2026 DaWz Store Official
