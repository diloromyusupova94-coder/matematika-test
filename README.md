# 🧮 MathStar — Matematika O'yini

Bolalar uchun interaktiv matematika testi. **Offline** ishlaydi (PWA).

## 📁 Fayllar
```
index.html     ← Asosiy ilova (barcha kod shu yerda)
sw.js          ← Service Worker (offline ishlash uchun)
manifest.json  ← PWA manifest (telefonga o'rnatish uchun)
```

## 🚀 GitHub Pages'ga Deploy (BEPUL, LIMITSIZ)

### 1-qadam: GitHub repo yaratish
1. [github.com](https://github.com) ga kiring
2. **New repository** bosing
3. Nom bering: `mathstar` (yoki xohlagan nom)
4. **Public** qiling
5. **Create repository** bosing

### 2-qadam: Fayllarni yuklash
```bash
# Lokal kompyuterda (Git o'rnatilgan bo'lsa):
git init
git add .
git commit -m "MathStar ilova"
git branch -M main
git remote add origin https://github.com/USERNAME/mathstar.git
git push -u origin main
```

**Yoki GitHub saytida:**
1. Repo ichida **Add file → Upload files** bosing
2. `index.html`, `sw.js`, `manifest.json` fayllarini yuklang
3. **Commit changes** bosing

### 3-qadam: GitHub Pages yoqish
1. Repo **Settings** ga kiring
2. Chap menuda **Pages** ni toping
3. **Source**: `Deploy from a branch`
4. **Branch**: `main` → `/ (root)` → **Save**
5. 2-3 daqiqa kuting

### ✅ Natija
Ilovangiz: `https://USERNAME.github.io/mathstar/`

---

## 📱 Telefongan o'rnatish (PWA)
1. Brauzerda ilova saytiga kiring
2. **"Bosh ekranga qo'shish"** bosing
3. Endi offline ham ishlaydi! 🎉

---

## 🆚 Platform taqqoslash

| Platform | Narx | Cheklov | Tavsiya |
|----------|------|---------|---------|
| **GitHub Pages** | Bepul | Faqat statik | ⭐ ENG YAXSHI |
| Netlify | Bepul | 100GB/oy bandwidth | ✅ Yaxshi |
| Vercel | Bepul | Hech qanday cheklov | ✅ Yaxshi |
| Railway | $5/oy | Backend kerak | ❌ Ortiqcha |
| Firebase Hosting | Bepul | 10GB/oy | ✅ Yaxshi |

**Tavsiya: GitHub Pages** — statik sayt uchun eng yaxshi, bepul, limitsiz, doimiy ishlaydigan platforma.

---

## 🎮 Ilova xususiyatlari
- ✅ 5 daraja, har birida 100 bosqich
- ✅ Har bosqichda 20 ta savol, 4 variant
- ✅ 15/20 ball o'tish talabi
- ✅ Yulduz tizimi (1-3 yulduz)
- ✅ Streak tizimi 🔥
- ✅ Xatolar tahlili
- ✅ Medallar
- ✅ Statistika sahifasi
- ✅ Ovozli feedback
- ✅ Offline ishlaydi (PWA)
- ✅ Telefongi o'rnatiladi
- ✅ LocalStorage (progress saqlanadi)
