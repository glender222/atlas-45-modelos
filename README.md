# Atlas de 45 Modelos

Atlas en español de 45 modelos estadísticos y de aprendizaje automático. Cada ficha reúne su propósito, fundamentos matemáticos, supuestos, limitaciones, referencias, implementaciones en R y Python y recursos visuales. Incluye búsqueda y filtros de interactividad, visualizaciones 3D y disponibilidad de recursos.

[Abrir el sitio](https://atlas-45-modelos.vercel.app)

## Desarrollo

Requiere Node.js 22.12 o superior.

```sh
npm ci
npm run dev
```

## Compilación

```sh
npm run build
npm run preview
```

Proyecto web con HTML, CSS, JavaScript y Vite. El archivo original `atlas-45-modelos.html` se convirtió en `index.html`, que conserva el contenido y las interacciones del atlas. Edita ese archivo para actualizar las fichas o el diseño. La compilación genera `dist/`.

## Publicación

Vercel: preset **Vite**, comando `npm run build`, salida `dist`. No necesita variables de entorno ni un servidor de aplicaciones.

Para publicar cambios manualmente desde la raíz del proyecto: `npx vercel --prod`. La integración automática con GitHub requiere autorizar este repositorio en la aplicación de Vercel.
