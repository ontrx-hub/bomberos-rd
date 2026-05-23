# 🚒 Bomberos RD — Mapa Interactivo

Mapa interactivo de los Cuerpos de Bomberos de la República Dominicana.

## 🌐 Ver en vivo
Una vez publicado en GitHub Pages, estará disponible en:
`https://TU-USUARIO.github.io/bomberos-rd/`

## 🚀 Cómo publicar en GitHub Pages

1. Crea un repositorio en GitHub (ej: `bomberos-rd`)
2. Sube este archivo `index.html` a la rama `main`
3. Ve a **Settings → Pages**
4. En **Source**, selecciona `Deploy from a branch`
5. Elige `main` y carpeta `/ (root)`
6. Guarda — en 1-2 minutos estará en línea ✅

## ✨ Funcionalidades

- 🗺️ Mapa interactivo con OpenStreetMap (sin costo)
- 🚒 Marcadores de cuerpos de bomberos con info detallada
- 🔴 Sombreado de zona de cobertura al seleccionar estación
- 💧 Marcadores de cisternas voluntarias
- ✏️ Modo edición para agregar estaciones y cisternas
- 📱 Responsive (computadoras y smartphones)
- 🎨 Interfaz roja institucional

## 📝 Actualizar datos

Los datos de estaciones están en el archivo `index.html`, en el array `stations`.
Cada estación tiene:
- `name`: Nombre
- `address`: Dirección
- `chief`: Intendente/Jefe
- `phone`: Teléfono
- `lat/lng`: Coordenadas GPS
- `units`: Unidades de combate
- `coverage`: Polígono de zona de cobertura
- `photo`: URL de foto (opcional)

## 🗺️ Mapa base
Usa OpenStreetMap — completamente gratuito, sin API key necesario.
