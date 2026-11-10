# CotiERP — página de presentación

Página estática (HTML + CSS, sin servidor ni dependencias) que presenta CotiERP y tiene el botón **Descargar**, que apunta a las publicaciones del repositorio `joi-man/CotiERP-releases`:

- Descarga directa del instalador (siempre la última versión): `https://github.com/joi-man/CotiERP-releases/releases/latest/download/CotiERP-Setup.exe`
- Todas las versiones: `https://github.com/joi-man/CotiERP-releases/releases`

## Ver en su computadora

Abra `index.html` con el navegador (doble clic). No hace falta instalar nada.

## Publicar en Vercel

1. Subir este repositorio a GitHub (por ejemplo `joi-man/CotiERP-landing`).
2. En <https://vercel.com/new> elegir **Import Git Repository** y seleccionarlo.
3. *Framework Preset*: **Other**. Sin comando de compilación y con el directorio de salida vacío (la raíz). **Deploy**.
4. Cada cambio en la rama `main` se publica solo. Se puede asignar un dominio propio en *Settings ▸ Domains*.

(Con la CLI: `vercel --prod` desde esta carpeta.)

## Qué mantener al día

- El **estado** (sección «En qué estado está»): cuando se conecte SIFEN o se haga la prueba piloto, actualizar esa lista.
- Las **capturas** (`img/`): salen del recorrido visual del sistema (`tools/demo-tour.mjs` del repositorio principal); se guardan reducidas (JPEG, 1400 px de ancho).
- No agregar datos reales de ningún negocio: las capturas son del perfil de demostración.
