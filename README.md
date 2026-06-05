# Portal de Descargas Corporativas

Portal web estático para acceso directo a las descargas oficiales de aplicaciones aprobadas por el departamento IT.

## Características

- 44 aplicaciones en 7 categorías
- Búsqueda en tiempo real
- Filtro por categoría
- Badge "Recomendado" para apps prioritarias
- Versión y plataforma por app
- Dark mode automático
- Sin dependencias externas (salvo Google Fonts)

## Uso

Abrir `index.html` directamente en el navegador, o publicar vía GitHub Pages.

## GitHub Pages

1. Ve a **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `root`
4. Guardar — disponible en `https://<usuario>.github.io/<repo>/`

## Estructura

```
index.html   ← portal completo (single-file)
README.md
```

## Mantenimiento

Todas las apps están definidas en el array `apps` dentro del `<script>` de `index.html`. Cada entrada tiene:

```js
{ name, desc, icon, bg, tag, platform, version, rec, url }
```

- `rec: true` activa el badge "★ Recomendado"
- `version` se muestra en la tarjeta (actualizar manualmente)
