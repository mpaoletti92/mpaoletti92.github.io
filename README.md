# mpaoletti.github.io

Sitio web científico personal de **Mercedes E. Paoletti** — Universidad de Extremadura, grupo HyperComp. Construido a partir del CVN de FECYT.

> Imagen hiperespectral · Deep learning · HPC para observación de la Tierra.

## 🚀 Publicar en GitHub Pages

### Opción A — sitio personal (recomendada): `TU_USUARIO.github.io`

1. Crea un repositorio **público** con el nombre exacto **`TU_USUARIO.github.io`** (por ejemplo `mpaoletti.github.io`).
2. Sube el contenido de esta carpeta (`index.html` en la raíz).
3. En **Settings → Pages**, asegúrate de que:
   - *Source* = **Deploy from a branch**
   - *Branch* = **main** / carpeta **/ (root)**
4. En 1–2 minutos tu web estará en **`https://TU_USUARIO.github.io`**.

### Opción B — como proyecto: `TU_USUARIO.github.io/nombre-repo`

1. Crea un repo público con cualquier nombre (p. ej. `web-cientifica`).
2. Sube `index.html` a la rama `main`.
3. En **Settings → Pages**, *Branch* = **main** / **/ (root)**.
4. Disponible en **`https://TU_USUARIO.github.io/web-cientifica`**.

## 🛠️ Subida rápida con Git

```bash
git init
git add .
git commit -m "Initial commit: web científica"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_USUARIO.github.io.git
git push -u origin main
```

O bien arrastra los archivos desde github.com → *Add file* → *Upload files*.

## 🌐 Dominio propio (opcional)

Si tienes un dominio (p. ej. `mercedespaoletti.com`):

1. Crea un archivo `CNAME` en la raíz con el dominio.
2. En tu proveedor DNS añade un registro *CNAME* `www → TU_USUARIO.github.io` y registros *A* apuntando a las IPs de GitHub Pages.
3. En **Settings → Pages → Custom domain**, escribe el dominio y activa *Enforce HTTPS*.

## 📝 Actualizar la web

Edita `index.html` y haz commit. GitHub Pages se reconstruye automáticamente.

## 🧱 Estructura

```
.
├── index.html     # Web completa (HTML + CSS + JS inline, autónoma)
└── README.md
```

Todo está en un único archivo, sin dependencias ni pasos de build. Las tipografías se cargan desde Google Fonts vía CDN.

## 🪪 Créditos

Construido a partir del CVN (FECYT) de Mercedes E. Paoletti.
ORCID: [0000-0003-1030-3729](https://orcid.org/0000-0003-1030-3729)
