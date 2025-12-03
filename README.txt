INSTRUCCIONES - Invitación Elegante A (GitHub Pages)

Archivos:
 - index.html          -> portada (público)
 - confirmar.html      -> formulario para invitados (guarda en local o envía a Apps Script)
 - admin-secreto-8734.html -> panel admin (contraseña: pabloAdmin2025)

Pasos para desplegar en GitHub Pages:
1) Crear repo público (por ejemplo 'invitaciones')
2) Subir los 3 archivos a la raíz
3) En Settings -> Pages -> Source: Branch 'main' (root)
4) Esperar ~1 min; el sitio queda en https://TU-USUARIO.github.io/invitaciones/

Apps Script (opcional):
- Si querés guardar centralizado, desplegá el Apps Script y pegá la URL en CONFING.APP_SCRIPT_ENDPOINT de confirmar.html

Generación PDF:
- El admin usa jsPDF + html2canvas para generar 3 PDFs desde los registros guardados en localStorage:
  - Listado de asistencias (completo)
  - Restricciones alimentarias
  - Sugerencias musicales

Contraseña admin por defecto: pabloAdmin2025
