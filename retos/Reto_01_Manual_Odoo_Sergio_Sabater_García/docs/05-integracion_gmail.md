# 05 — Integración con Gmail (OAuth GCP + Add-on)

## Requisitos

- Cuenta Google Cloud (GCP).

## Pasos resumidos

### 1. Activar plugin de correo en Odoo e instalar Odoo Inbox Add-on en Gmail.

* Primero nos vamos a los ajustes generales, al apartado de integraciones.![Ir a ajustes generañes](../assets/img/05-integracion_gmail/Ajustes_generales_correo.png)
* Activamos la opción Plugin de correo y guardamos los cambios.
  ![Ir a integraciones](../assets/img/05-integracion_gmail/Activar_plugin.png)

  ![Activacion de plugin](../assets/img/05-integracion_gmail/Plugin_activado.png)
* En Gmail, hacemos clic en el botón de más (+) para buscar el complemento.
  ![Ir a Gmail](../assets/img/05-integracion_gmail/Gmail.png)
* Instalamos Odoo Inbox Add-on y concedemos los permisos..

  ![Instalar Inbox Addin a Gmail](../assets/img/05-integracion_gmail/Instalar_Odoo_Inbox_Addin.png)

  ![Iniciar seion Gmail](../assets/img/05-integracion_gmail/Iniciar_sesion_con_correo.png)![Dar permisos](../assets/img/05-integracion_gmail/Conceder_permisos.png)![Instalado correctamente](../assets/img/05-integracion_gmail/Instalado_correctamente.png)

  ![Instalacion completada](../assets/img/05-integracion_gmail/Instalacion_completada.png)

  ![Ejemplo](../assets/img/05-integracion_gmail/Ejemplo.png)

### 2. En Google Cloud Console: habilitar Gmail API, crear OAuth Client (Web), configurar redirect URI de Odoo.

**Acceso a OAuth en Odoo.**

* Primero activamos la autenticación OAuth y guardamos.
  ![Autenticacion](../assets/img/05-integracion_gmail/Autenticacion_OAuth.png)
* Ahora le damos a proveedores OAuth y le daremos a GoogleOAuth2.

  ![Proveedores](../assets/img/05-integracion_gmail/Proveedores.png)![Google OAuth](../assets/img/05-integracion_gmail/Google_OAuth.png)

  ![OAuth](../assets/img/05-integracion_gmail/OAuth.png)

**Creación del Proyecto en Google console cloud.**

* Buscamos por el navegador "Google console" y le daremos donde pone Google Cloud console.

  ![Google Cloud Console](../assets/img/05-integracion_gmail/Google_cloud.png)
* Accedemos a Google Cloud Console y creamos un nuevo proyecto.![Proyecto en Google Cloud Console](../assets/img/05-integracion_gmail/Nuevo_proyecto.png)

  ![Proyecto en Google Cloud Console](../assets/img/05-integracion_gmail/Proyecto_nuevo.png)

  ![Odoo-test creado](../assets/img/05-integracion_gmail/Odoo-test_creado.png)

**Habilitación de API.**

* Busca,os en el buscador del proyecto "gmail" y le damos a gmail API, que es la API que queremos habilitar.

  ![Gmail API](../assets/img/05-integracion_gmail/Gmail_API.png)

  ![Habilitar API](../assets/img/05-integracion_gmail/Habilitar_API.png)

**Creación de Credenciales.**

* Seleccionamos "Crear credenciales" y después "datos del usuario" y a siguiente y rellenamos los datos que nos piden y continuamos.![Crear credenciales](../assets/img/05-integracion_gmail/Crear_credenciales.png)

  ![Datos usuarios](../assets/img/05-integracion_gmail/Datos_usuarios.png)

  ![Datos piden](../assets/img/05-integracion_gmail/Datos_piden.png)
* Ahora le damos permisos que queremos concederle a Odoo como leer, redactar y enviar correos a tu nombre. Le damos a actualizar y guardamos y continuamos.![Permisos de correos](../assets/img/05-integracion_gmail/Permisos.png)
* Le añadimos el tipo de aplicación, nosotros le pondremos "Aplicación Web" y como nombre "odoo.email" y añadiremos la URL de redireccionamiento autorizada y le damos a crear.

  ![Credenciales creadas](../assets/img/05-integracion_gmail/Credenciales_creadas.png)

### 3. Copiar Client ID/Secret a Odoo (Gmail server settings) y Guardar.

**Copiamos el Client ID y el Client Secret generados en GCP.**

* Nos vamos a credenciales y dentro pulsamos nuestra cuenta.

![Credenciales](../assets/img/05-integracion_gmail/Credenciales.png)

* Dentro estará nuestro ID del cliente y el secreto del cliente.

  ![ID del cliente y el secreto del cliente](../assets/img/05-integracion_gmail/IDs.png)
* Copiamos nuestro ID de cliente, nos vamos a Odoo, lo pegamos, le damos a permitido y guardamos.

  ![Clave ID Odoo](../assets/img/05-integracion_gmail/Clave_ID_Odoo.png)
* Nos vamos a ajuste, al apartado de correos electronicos y activamos "Utilizar servidores de correo electrónico personalizados", ponemos el ID del cliente y el secreto del cliente y lo guardamos.

  ![Servidor gmail](../assets/img/05-integracion_gmail/Servidor_gmail.png)

### 4. Probar desde Gmail: crear contacto/oportunidad desde el add-on.

* Cuando estás en Gmail y abres un correo electrónico, puedes añadir directamente un contacto, una oportunidad o consultar la información de la empresa desde la barra lateral del complemento Odoo Inbox Add-on.

![Contacto email](../assets/img/05-integracion_gmail/Contacto_email.png)

![Crear oportunidad](../assets/img/05-integracion_gmail/Crear_oportunidad.png)

![Informacion de la empresa](../assets/img/05-integracion_gmail/Informacion_empresa.png)
