# KKS Kereső - Telepítési útmutató

## GitHub Pages telepítés (ajánlott)

### 1. Repository feltöltése

1. Menj a GitHub-ra és hozz létre egy új repository-t (pl. `kks-search`)
2. Töltsd fel **MINDEN fájlt a repository gyökerébe** (ne mappába!):
   - index.html
   - manifest.json
   - service-worker.js
   - huha_hatter.jpg
   - icon-192.png
   - icon-512.png
   - README.md
   - .github/workflows/static.yml

### 2. GitHub Pages bekapcsolás

1. Menj a repository **Settings** → **Pages** oldalára
2. **Source**: válaszd ki a **GitHub Actions** opciót
3. A workflow automatikusan lefut és deploy-olja az oldalt

### 3. Az app URL-je

Az app elérhető lesz a következő címen:
```
https://[felhasználónév].github.io/[repository-név]/
```

Például: `https://hererakos.github.io/kks-search/`

## iPhone-ra telepítés

### 1. Cache törlés (fontos!)

Safari → Beállítások → Safari → **Töröld az előzményeket és weboldal adatokat**

### 2. Főképernyőre helyezés

1. Nyisd meg az app URL-jét Safari-ban
2. Nyomd meg a **Megosztás** gombot (⬆️)
3. Görgess le és válaszd: **Hozzáadás a kezdőképernyőhöz**
4. Nyomd meg a **Hozzáadás** gombot

### 3. App indítása

- Most már a főképernyőről indítható lesz
- Offline is működik!
- Jelszó: **2344**

## Hibakeresés

### Fehér oldal vagy 404 hiba

1. **Ellenőrizd**: Minden fájl a repository gyökerében van (ne mappában!)
2. **GitHub Actions**: Menj az Actions fülre és nézd meg hogy sikerült-e a deploy
3. **Cache törlés**: Töröld a böngésző cache-ét
4. **Várj 2-3 percet**: A GitHub Pages deploy-nak néha időbe telik

### Service Worker nem működik

1. Töröld a régi app-ot a főképernyőről
2. Töröld a Safari cache-t
3. Töltsd újra az oldalt
4. Telepítsd újra

## Támogatás

Ha továbbra is problémád van, ellenőrizd hogy:
- ✅ Minden fájl a repository gyökerében van
- ✅ A GitHub Actions workflow lefutott sikeresen
- ✅ A böngésző cache törölve van
- ✅ Várj legalább 2-3 percet a deploy után
