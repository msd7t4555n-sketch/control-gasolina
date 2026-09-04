# 🚗 Control de Gasolina

Aplicación web progresiva (PWA) para registrar recargas de combustible y controlar el rendimiento de uno o varios vehículos.

## ✨ Funciones

- Registro de recargas de gasolina
- Cálculo automático de distancia recorrida
- Rendimiento en km/L
- Costo total de cada recarga
- Costo por kilómetro
- Dashboard con gráficas
- Historial de recargas
- Varios vehículos
- Alertas de disminución de rendimiento
- Exportación CSV compatible con Excel
- Respaldo y restauración de datos
- Funcionamiento como PWA

## 🌐 Publicar en GitHub Pages

### Opción recomendada: desde la web de GitHub

1. Crea una cuenta en GitHub si todavía no tienes una.
2. Haz clic en **New repository**.
3. Ponle un nombre, por ejemplo:

   `control-gasolina`

4. Selecciona **Public**.
5. Crea el repositorio.
6. Sube TODOS los archivos de esta carpeta al repositorio.
7. En GitHub entra a:

   **Settings → Pages**

8. En **Build and deployment** selecciona:

   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**

9. Pulsa **Save**.
10. Espera unos minutos.

GitHub mostrará una dirección similar a:

`https://TU-USUARIO.github.io/control-gasolina/`

## 📱 Instalar en iPhone

1. Abre la dirección de la aplicación con **Safari**.
2. Toca el botón **Compartir**.
3. Desplázate y selecciona **Añadir a pantalla de inicio**.
4. Pulsa **Añadir**.
5. La aplicación aparecerá como un icono en tu iPhone.

## 💾 Importante sobre tus datos

Los datos se guardan localmente en el dispositivo.

Se recomienda utilizar periódicamente la opción:

**Historial → Respaldo**

para guardar una copia de seguridad.

## 📂 Archivos principales

- `index.html` → Aplicación
- `manifest.webmanifest` → Configuración PWA
- `sw.js` → Funcionamiento sin conexión
- `icons/` → Iconos de la aplicación
- `.nojekyll` → Compatibilidad con GitHub Pages
