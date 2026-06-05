# Turnos Manager — Deploy en GitHub Pages

## Pasos para subir (5 minutos)

### 1. Crear repositorio en GitHub
- Entrá a github.com
- Click en "New repository"
- Nombre: `turnos-manager`
- Visibilidad: **Public** (necesario para GitHub Pages gratis)
- Click "Create repository"

### 2. Subir los archivos
Desde la página del repositorio vacío:
- Click "uploading an existing file"
- Arrastrá los 4 archivos: `index.html`, `manifest.json`, `sw.js`, `icon-192.svg`
- Click "Commit changes"

### 3. Activar GitHub Pages
- Ir a Settings → Pages
- Source: "Deploy from a branch"
- Branch: `main` / `(root)`
- Click Save

### 4. Tu URL
En 1-2 minutos tu app queda en:
`https://TU_USUARIO.github.io/turnos-manager`

### 5. Instalar en el celu
- Abrí la URL desde **Chrome en Android**
- Aparecer un banner "Agregar a pantalla de inicio" → tocalo
- En **iPhone**: Safari → botón compartir → "Añadir a pantalla de inicio"

---

## Funcionalidades

- **Turnos del día**: ver, agregar, editar y eliminar crew
- **Mi turno**: configurá tu horario y activá el filtro "Solo mi turno"
- **Timeline**: visualización gráfica de todos los turnos del día
- **Importar**: subí una foto/captura del Orquest Decide y la IA extrae los turnos
- **Offline**: funciona sin internet después de la primera carga
- **Guardado local**: los datos se guardan en el dispositivo

## Notas
- La función de importar con IA requiere conexión a internet
- Los datos se guardan solo en el dispositivo (localStorage)
- Para compartir con otros managers en el futuro, se puede agregar sincronización con Google Sheets o Firebase
