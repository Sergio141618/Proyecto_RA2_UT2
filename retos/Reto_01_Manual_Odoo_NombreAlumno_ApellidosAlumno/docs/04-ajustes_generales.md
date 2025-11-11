# 04 — Ajustes generales

Una vez instalada la base de datos, haremos los ajustes generales que permiten adaptar la instancia de Odoo a las necesidades del proyecto, mejorar la experiencia de usuario y reforzar la seguridad del entorno.

A continuación se detallan los principales aspectos que conviene revisar tras la instalación:

- Activar notificaciones y (opcional) PWA.
- Perfil: modo oscuro, datos, 2FA, firma email, notificaciones en Odoo.
- Usuarios y compañías.
- Idiomas y diseño de documentos.
- Emails de resumen: periodicidad y destinatarios.

## Pasos

### 1. Activar notificaciones y PWA

Estando en el panel principal de Odoo, en la zona superior derecha, observarás un icono de mensajes (representado por un bocadillo de diálogo). Al hacer clic sobre él, se desplegarán varios mensajes informativos, entre los que se incluyen:

* La opción para habilitar las notificaciones del navegador, que permiten recibir alertas en tiempo real sobre tareas, mensajes o eventos.

  ![Activar notificaciones](../assets/img/04-ajustes_generales/Activar_noti.png)
* La opción para instalar Odoo como aplicación de escritorio (PWA), lo que permite acceder al sistema como si fuera una app nativa, con icono propio y sin barra de navegación. Esta opción es opcional.

  ![Instalar PWA](../assets/img/04-ajustes_generales/PWA.png)

### 2. Perfil

**Modo oscuro**

Estando en el panel principal de Odoo , dirígete a la esquina superior derecha, donde aparece una letra "A". Al hacer clic sobre ella, se desplegará un menú con varias opciones. Selecciona “My Preferences” para acceder a la configuración personal del perfil.

![Darle a My Preferences](../assets/img/04-ajustes_generales/Mis_preferencias.png)

Desde esta sección podrás poner el modo oscuro y no olvides darle a "Update Preferences".

![Poner el modo oscuro](../assets/img/04-ajustes_generales/Modo_oscuro.png)

**Datos**

Dentro del apartado “My Preferences”, es recomendable revisar y actualizar los datos personales del usuario para garantizar que la información del sistema esté correctamente asociada a cada cuenta, incluyendo campos como nombre, correo electrónico, idioma y zona horaria. Pudiendo añadir teléfono de trabajo, móvil de trabajo, dirrección privada, teléfono privado, correo electrónico privado y contacto de emergencia en la pestaña "Private".

![Darle a My Preferences](../assets/img/04-ajustes_generales/Mis_preferencias.png)

![Los datos en la sección de preferencias](../assets/img/04-ajustes_generales/Preferencias_datos.png)

![Sección private](../assets/img/04-ajustes_generales/Private.png)

**2FA**

Para activar la autenticación en dos pasos (2FA) en Odoo, primero accede al panel principal y dirígete a la esquina superior derecha, donde aparece la letra “A”. Haz clic sobre ella y selecciona la opción “My Preferences”.

![Darle a My Preferences](../assets/img/04-ajustes_generales/Mis_preferencias.png)

Dentro de esta sección, selecciona el apartado “Seguridad”. Allí verás la opción “Autenticación de dos factores” (2FA), que puedes activar para reforzar la seguridad de tu cuenta.

![Autentificación en dos pasos](../assets/img/04-ajustes_generales/Autentificación_dos_pasos.png)

Tras darle a "Habilitar la A2F" te pedira la contraseña

![Contraseña para la autentificación](../assets/img/04-ajustes_generales/Contraseña.png)

Luego de poner la contraseña se mostrará un código QR que deberás escanear con una aplicación de autenticación. Una vez escaneado, introduce el código temporal generado por la app en el campo correspondiente y se activará la autenticación en dos pasos.

![Codigo de autentificación](../assets/img/04-ajustes_generales/Codigo.png)

Desde ese momento, cada vez que inicies sesión en Odoo se te pedirá el código de verificación, lo que añade una capa extra de protección frente a accesos no autorizados.

**Firma email**

Dentro del apartado “My Preferences”, Odoo permite personalizar la firma de correo electrónico que se incluirá automáticamente al final de los mensajes enviados desde el sistema.

![Firma del correo electronico](../assets/img/04-ajustes_generales/Firma_correo.png)

**Notificaciones en Odoo**

Dentro de “My Preferences”, puedes configurar cómo recibir las notificaciones internas, eligiendo entre gestionarlas directamente dentro de Odoo o recibirlas por correo electrónico, según tu preferencia de trabajo.

![Notificaciones por Odoo](../assets/img/04-ajustes_generales/Notificación_odoo.png)

### 3. Usuarios y compañías

Desde el menú principal, accede al módulo “Ajustes” y arriba a la izquierda dirígete a las secciones “Ususarios y Compañías” para gestionar el acceso y la estructura organizativa del sistema.

![Ir a ajustes generales](../assets/img/04-ajustes_generales/Ajustes_generales.png)

![Sección de usuarios y compañias](../assets/img/04-ajustes_generales/Usuarios_y_compañías.png)

**Compañías**

Odoo permite gestionar múltiples compañías dentro de una misma. Se añade una nueva compañía dandole a "Compañías". Luego estarás en la ventana de "Compañías", donde podrás añadir nuevas compañías y completa los datos fiscales, logotipo y configuración básica de la entidad.

![Sección compañias](../assets/img/04-ajustes_generales/Compañias.png)

![Nueva compañia](../assets/img/04-ajustes_generales/Nueva_compañía.png)

![Añadir compañia](../assets/img/04-ajustes_generales/Añadir_compañia.png)

**Usuarios**

Odoo permite gestionar múltiples usuarios con distintos roles y permisos. Se añade un nuevo usuario dándole a “Usuarios”. Luego estarás en la ventana de “Usuarios”, donde podrás crear nuevos usuarios y completar su nombre, correo electrónico, compañía asignada y nivel de acceso.

![Sección usuarios](../assets/img/04-ajustes_generales/Usuarios.png)

![Nuevo usuario](../assets/img/04-ajustes_generales/Nuevo_usuario.png)

![Añadir usuario](../assets/img/04-ajustes_generales/Añadir_usuario.png)

### 4. Idiomas y diseño de documentos

**Idiomas**

Odoo permite trabajar con diferentes idiomas en la interfaz; para añadir uno nuevo, ve a Ajustes , accede al apartado “Idiomas” y pulsa “Añadir idiomas” para instalar el idioma deseado en el sistema.

![Ir a ajustes generales](../assets/img/04-ajustes_generales/Ajustes_generales.png)

![Idiomas](../assets/img/04-ajustes_generales/Idiomas.png)

![Elegir idiomas](../assets/img/04-ajustes_generales/Elegir_idioma.png)

Idioma instalado

![Instalar idioma](../assets/img/04-ajustes_generales/Instalar_idioma.png)

Cuando se ha agregado el nuevo idioma, el usuario puede cambiarlo en su perfil.

![Cambiar idioma](../assets/img/04-ajustes_generales/Cambiar_idioma.png)

**Diseño de documentos**

Odoo permite personalizar el diseño de documentos como presupuestos y facturas; para hacerlo, ve a Ajustes, accede al apartado “Diseño de documentos” y selecciona la plantilla que mejor se adapte a tu empresa.

![Ir a ajustes generales](../assets/img/04-ajustes_generales/Ajustes_generales.png)

![Diseño de documentación](../assets/img/04-ajustes_generales/Diseño_documentación.png)

![Configuración de documentación](../assets/img/04-ajustes_generales/Configuración_de_documentación.png)

### 5. Emails de resumen

Odoo permite configurar el envío de emails de resumen con información relevante. Para activarlos, ve a Ajustes, accede al apartado “Emails de resumen” y define la periodicidad, el contenido y los destinatarios según tus necesidades.

![Ir a ajustes generales](../assets/img/04-ajustes_generales/Ajustes_generales.png)

![Correo electronico](../assets/img/04-ajustes_generales/Correo_electronico.png)

![Ajustes correo electronico](../assets/img/04-ajustes_generales/Ajustes_correo.png)

**1. Personalización de la Periodicidad (Frecuencia de Envío)**

Puedes decidir con qué frecuencia deseas recibir el resumen; por defecto, Odoo lo envía diariamente, pero puedes modificar la periodicidad y configurarlo como semanal o mensual según tus necesidades.

![Periocidad correo](../assets/img/04-ajustes_generales/Periocidad_correo.png)

**2. Configuración de destinatarios del correo**

Odoo permite gestionar quién recibe los correos de resumen; además del usuario principal, puedes configurar destinatarios adicionales para que otras personas también reciban estos informes automáticamente.

![Configuracion destinatarios](../assets/img/04-ajustes_generales/Configuracion_destinatarios.png)
