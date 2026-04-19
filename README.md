# Lemoncode Mod8 Cloud — Despliegue manual

Despliegue manual en GitHub Pages del portfolio que vive en
https://github.com/SergioSuarezGil/Portfolio.

## URL de la app desplegada

https://sergiosuarezgil.github.io/Lemoncode_Mod8_Cloud_Manual/

## Cómo se despliega

Desde un clon local del repo `Portfolio`:

```bash
BASE_PATH=/Lemoncode_Mod8_Cloud_Manual/ npm run build
npx gh-pages -d dist --dotfiles \
  --repo https://github.com/SergioSuarezGil/Lemoncode_Mod8_Cloud_Manual.git
```
