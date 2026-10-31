# Hotiralar muzeyi

Ushbu loyiha Windows uchun Electron desktop ilova sifatida tayyorlandi. Ilova belgisi `logo/` papkasidagi siz yuborgan suratdan yaratildi.

## Windows uchun EXE yaratish

1. Kompyuterga Node.js (LTS) o‘rnating: https://nodejs.org/
2. Ushbu papkani oching va terminalda quyidagilarni bajaring:

```bash
npm install
npm run dist:win
```

3. Tayyor o‘rnatuvchi fayl `dist/` papkasida `Hotiralar muzeyi Setup 1.0.0.exe` nomi bilan hosil bo‘ladi.

## GitHub orqali avtomatik EXE

Loyihani GitHub repositoryga yuklang. `.github/workflows/build-windows.yml` workflow `main` yoki `master` branchga push qilinganda Windows EXE yaratadi va Actions artefakti sifatida saqlaydi.

## Ishga tushirish

```bash
npm install
npm start
```
