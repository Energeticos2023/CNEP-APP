# Registro CNEP — aplicación para GitHub Pages

Aplicación PWA de captación y registro de la Comunidad Nacional de Electricistas del Perú.

## Publicar en GitHub Pages

1. Cree un repositorio nuevo, por ejemplo: `cnep-registro`.
2. Suba **todos los archivos y la carpeta `assets`** de este paquete.
3. En GitHub abra **Settings → Pages**.
4. En **Build and deployment**, seleccione **Deploy from a branch**.
5. Seleccione la rama **main**, carpeta **/(root)** y pulse **Save**.
6. GitHub mostrará el enlace público en unos minutos.

## Instalar en Android

Abra el enlace en Chrome y pulse **Instalar app**. Si no aparece, abra el menú ⋮ y seleccione **Agregar a pantalla principal**.

## Instalar en iPhone

Abra el enlace en Safari, pulse **Compartir**, elija **Agregar a inicio** y confirme con **Agregar**.

## Datos configurados

- WhatsApp receptor: 934 608 162
- Correo: tecnicos.electricistas.del.peru@gmail.com

El formulario guarda las solicitudes directamente en Supabase como pendientes. No se necesita enviar un mensaje por WhatsApp. Coordinación valida desde https://energeticos2023.github.io/cneperu/admin.html.

La membresía aceptada se refleja automáticamente en el directorio de CNEP si el solicitante autorizó publicar su perfil. Se utiliza la misma base que la web principal.

Publicar también membership.css, registration.js y app.js. No colocar claves privadas ni enlaces de activación en este repositorio.
