# 🚀 Gyors telepítés - 3 lépés

## 1️⃣ GitHub Repository létrehozása

1. Menj a https://github.com/new oldalra
2. Repository név: `kks-search` (vagy bármi más)
3. Kattints a **Create repository** gombra

## 2️⃣ Fájlok feltöltése

1. A létrehozott repository oldalán kattints: **uploading an existing file**
2. Húzd be **MINDEN fájlt** egyszerre (ne a mappát, csak a fájlokat!):
   - ✅ index.html
   - ✅ manifest.json
   - ✅ service-worker.js
   - ✅ huha_hatter.jpg
   - ✅ icon-192.png
   - ✅ icon-512.png
   - ✅ README.md
   - ✅ TELEPITES.md

**FONTOS**: A `.github` mappát is fel kell tölteni! Ehhez:
- Vagy tölts fel mindent git parancssorból
- Vagy hozd létre a `.github/workflows/static.yml` fájlt manuálisan a GitHub webes felületén

## 3️⃣ GitHub Pages bekapcsolás

1. Repository → **Settings** → **Pages** (bal oldali menü)
2. **Source**: válaszd a **GitHub Actions** opciót
3. Várj 1-2 percet

✅ **Kész!** Az app elérhető: `https://[felhasználónév].github.io/kks-search/`

---

## 📱 iPhone-ra telepítés

1. Nyisd meg a fenti URL-t Safari-ban
2. Nyomd meg: ⬆️ (Megosztás) → **Hozzáadás a kezdőképernyőhöz**
3. Jelszó: **2344**

---

## 🆘 Ha nem működik

1. ✅ Ellenőrizd: Minden fájl a repository **gyökerében** van (ne mappában!)
2. ✅ GitHub → **Actions** fül → Nézd meg hogy sikeres-e a deploy
3. ✅ Várj 2-3 percet a deploy után
4. ✅ Töröld a böngésző cache-ét (Safari → Beállítások → Töröld előzményeket)
