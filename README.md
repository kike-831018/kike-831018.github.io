# Portafolio personal — Kike

Sitio estático con HTML, CSS y JavaScript, preparado para GitHub Pages.

## 1. Personaliza el contenido

Edita `index.html` y reemplaza:
- `Kike` / `kike.dev` por el nombre y marca que quieras mostrar.
- `tu.correo@ejemplo.com` por tu correo público de contacto.
- Los enlaces de GitHub y LinkedIn por tus perfiles reales.
- Descripciones, tecnologías y estados de los proyectos para que sean exactos.
- Los enlaces `#contacto` de Outfit y Triqui por sus repositorios públicos cuando existan.

No publiques contraseñas, tokens, claves API, direcciones personales ni datos privados.

## 2. Añade tus imágenes

Copia tus archivos a `assets/images/` usando estos nombres o actualiza las rutas en `index.html`:

| Archivo | Uso recomendado |
|---|---|
| `perfil.jpg` | Foto de presentación |
| `tourinvest.jpg` | Captura de TourInvest |
| `outfit.jpg` | Captura de Outfit |
| `triqui.jpg` | Captura de Triqui |
| `favicon.png` | Icono opcional del sitio |

Recomendación: foto vertical para `perfil.jpg`; capturas horizontales 16:9 para los proyectos. Optimiza las imágenes para que la página cargue rápido.

## 3. Prueba local

Abre `index.html` en el navegador. Para probar como sitio estático también puedes ejecutar, desde la raíz del proyecto:

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000`.

## 4. Publica con GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `kike-portfolio`.
2. Sube el contenido de esta carpeta a la raíz del repositorio: `index.html`, `css/`, `js/`, `assets/` y `README.md`.
3. En GitHub entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que termine el despliegue. GitHub mostrará la URL pública en la misma sección.

Si el repositorio se llama exactamente `USUARIO.github.io`, la URL será `https://USUARIO.github.io/`. Para otros nombres, normalmente será `https://USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Estructura

```text
portafolio-personal/
├── index.html
├── README.md
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── assets/
    └── images/
        ├── perfil.jpg
        ├── tourinvest.jpg
        ├── outfit.jpg
        └── triqui.jpg
```
