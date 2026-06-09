# Portal de Descargas Corporativas Pro

Portal HTML local para organizar enlaces oficiales de descarga de aplicaciones corporativas.

## Características

- Funciona abriendo `index.html` directamente.
- Catálogo base de aplicaciones.
- Añadir aplicaciones manualmente.
- Editar y borrar aplicaciones manuales.
- Favoritos.
- Categorías dinámicas.
- Búsqueda por nombre, descripción, categoría, plataforma, URL y notas.
- Importar/exportar JSON.
- Vista compacta.
- Modo claro/oscuro.
- Preparado como PWA con `manifest.json` y `sw.js`.
- Sin backend y sin envío de datos.

## Uso

1. Descarga el repositorio.
2. Abre `index.html` en el navegador.
3. Pulsa `+ Añadir app` para crear aplicaciones propias.
4. Usa `Exportar JSON` para guardar copia de seguridad.
5. Usa `Importar JSON` para restaurar o compartir catálogo.

## Nota sobre PWA

La instalación como PWA y el service worker funcionan mejor sirviendo la carpeta desde GitHub Pages, VS Code Live Server o cualquier servidor local. El portal principal funciona también abriendo el HTML directamente.

## Seguridad

Los datos manuales se guardan en `localStorage` del navegador. No contiene autenticación real ni control corporativo centralizado.
