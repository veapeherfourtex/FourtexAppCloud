
FOURTEX Installer Package
-------------------------

📦 Contenido:
- FOURTEX.app — Aplicación Mac con lanzador incorporado
- FourtexApp/  — Proyecto con base de datos y sistema Streamlit

🧩 ¿Cómo usarlo en tu Mac?

1. Abre Terminal y navega a esta carpeta:
   cd ~/Desktop/FourtexInstaller

2. Genera el ícono .icns desde el iconset (una sola vez):
   iconutil -c icns fourtex.iconset

3. Copia el archivo fourtex.icns generado en:
   Applications/FOURTEX.app/Contents/Resources/

4. Dale permiso al lanzador:
   chmod +x Applications/FOURTEX.app/Contents/MacOS/launch_fourtex.sh

5. (Opcional) Crea un instalador .pkg:
   pkgbuild --root Applications --install-location /Applications --identifier com.fourtex.app --version 1.0 FOURTEX.pkg

🖱️ También puedes ejecutar directamente:
   - Haz doble clic en FOURTEX.app
   - O ejecuta Launch_FourtexApp.command si lo necesitas

👤 Autor: Pedro H. Velandia
🔖 Proyecto: Sistema de Mantenimiento FOURTEX
