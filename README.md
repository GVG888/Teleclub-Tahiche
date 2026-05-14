# Teleclub Tahiche

Sitio web para el restaurante Teleclub Tahiche en Lanzarote.

## Estructura del proyecto

- `index.html` - Página principal
- `carta.html` - Menú/Carta del restaurante
- `photos/` - Fotografías del restaurante
- `uploads/` - Imágenes adicionales
- `tweaks-panel.jsx` - Componente React para personalización

## Desarrollo local

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:3000`

## Deploy en Vercel

### Opción 1: Conectar directamente desde GitHub

1. Sube este repositorio a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Importa el repositorio
4. Vercel detectará automáticamente que es un sitio estático
5. ¡Hecho! Tu sitio estará en vivo

### Opción 2: Deploy desde la CLI de Vercel

```bash
npm install -g vercel
vercel
```

## Notas

- Este es un sitio HTML estático
- Las imágenes se sirven desde las carpetas `photos/` y `uploads/`
- El archivo `tweaks-panel.jsx` es un componente React que puede integrase si lo necesitas
