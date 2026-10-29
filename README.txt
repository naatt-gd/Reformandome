# Reformándome — PWA personal

## Contenido
- `index.html`: aplicación completa.
- `manifest.json`: datos de instalación PWA.
- `sw.js`: caché offline.
- `icon-192.png` y `icon-512.png`: iconos.

## Cómo instalarla en iPhone (gratis)
Para instalar una PWA en iOS, los archivos deben servirse desde una dirección HTTPS. No basta con abrir el HTML desde Archivos.

### Opción gratuita: GitHub Pages
1. Entra en https://github.com desde Safari y crea una cuenta gratuita si no tienes.
2. Crea un repositorio nuevo. Para mantener el repositorio privado, revisa las opciones de Pages disponibles en tu cuenta; si Pages no está disponible en un repositorio privado, elige conscientemente si quieres publicar solo el código de esta app. Los registros personales no se envían al repositorio ni al servidor.
3. Sube los cinco archivos de esta carpeta a la raíz del repositorio.
4. En el repositorio abre **Settings → Pages**. En “Build and deployment”, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`, y guarda.
5. Espera a que GitHub Pages muestre la URL publicada (normalmente `https://TUUSUARIO.github.io/NOMBRE-REPO/`).
6. Abre esa URL en Safari en el iPhone y espera a que cargue completamente una vez con internet.
7. Pulsa **Compartir → Añadir a pantalla de inicio**. Si aparece la opción, activa “Abrir como app” y pulsa Añadir.
8. Abre Reformándome desde el icono de la pantalla de inicio. Vuelve a abrirla una vez con internet para que se almacenen los archivos offline.
9. En Ajustes de la app, exporta una copia de seguridad de vez en cuando y guárdala en Archivos/iCloud Drive.

## Privacidad y límites
- Misiones, ajustes y registros se guardan en `localStorage` del navegador del dispositivo.
- El alojamiento sirve los archivos de la app, pero no recibe los registros de hábitos.
- El código de la app alojada puede ser visible si usas un repositorio público.
- No borres datos de Safari ni elimines los datos del sitio sin exportar antes una copia.
- La copia JSON contiene tus registros: guárdala en un lugar privado.
- El uso offline requiere la primera carga online y que el navegador conserve la caché.
- Si cambias la fecha de inicio, las fechas del reto se recalculan; exporta una copia antes de hacer cambios importantes.

## Importante
Esta versión es un prototipo funcional personal, no una app médica ni financiera. Las misiones son generales y modificables; adapta el ejercicio a tus molestias y consulta con profesionales si tienes dolor o síntomas preocupantes.
