# 09 — Documentos, Firma e Información (Knowledge)

- **Documentos**: repositorio, edición hojas, dividir PDFs, etiquetas/flujo.
- **Firma electrónica**: campos (firma/nombre/fecha), envío y registro.
- **Información (Knowledge)**: wiki tipo Notion, permisos y publicación.

## Documentos

El propósito del módulo **Documentos** es eliminar el uso de archivos dispersos en correos o carpetas locales y centralizar toda la información documental de la empresa en un entorno seguro, ordenado y accesible.

![Documentos](../assets/img/09-documentos_firma_info/Documentos.png)

### Repositorio

El módulo Documentos de Odoo funciona como un espacio digital donde se centraliza toda la documentación generada en la empresa. Su integración con otros módulos permite que los archivos creados en tareas, proyectos, ventas o recursos humanos se almacenen automáticamente en este entorno.

Los documentos pueden organizarse en carpetas temáticas, lo que facilita la clasificación por área, cliente o tipo de contenido.

![Repositorio](../assets/img/09-documentos_firma_info/Repositorio.png)

Además, cada archivo puede etiquetarse con marcadores personalizados, que no solo ayudan a filtrar y buscar, sino que también pueden activar acciones automáticas. Por ejemplo, una etiqueta puede indicar que el documento debe enviarse al departamento contable o que requiere validación antes de ser compartido.

También es posible asignar un responsable o vincular el documento a un contacto específico, lo que permite mantener el control sobre quién debe revisarlo o actuar sobre él.

![Asignacion](../assets/img/09-documentos_firma_info/Asignacion.png)

Este sistema convierte el módulo en una herramienta clave para mantener la trazabilidad documental, reducir el uso de papel y mejorar la colaboración entre equipos.

### Edición hojas

Odoo permite trabajar directamente con sus propias hojas de cálculo integradas, sin necesidad de descargar ni abrir archivos en aplicaciones externas.

* Al subir un archivo Excel, se puede abrir y editar desde el navegador usando las Hojas de cálculo de Odoo.
* Esta funcionalidad es ideal para trabajo colaborativo, ya que permite ver quién ha modificado qué, mantener el historial de cambios y evitar conflictos de versiones.
* Las hojas pueden vincularse a tareas, proyectos o documentos específicos, facilitando el análisis de datos en contexto.

![Subir hoja de calculo](../assets/img/09-documentos_firma_info/Subir_hoja.png)

![Abrir hoja de calculo de Odoo](../assets/img/09-documentos_firma_info/Abrir_hoja_odoo.png)

![Hoja de calculo de Odoo](../assets/img/09-documentos_firma_info/Hoja_Odoo.png)

### Dividir PDFs

El módulo incluye una herramienta práctica para dividir archivos PDF directamente desde la interfaz.

* Al seleccionar un documento PDF, Odoo muestra todas sus páginas en miniatura.
* El usuario puede elegir qué páginas conservar, separar o eliminar.
* Se pueden generar varios documentos nuevos a partir de uno solo, lo que facilita la gestión de contratos, facturas o informes extensos.

  Añadimos el PDF de prueba y hacemos clic sobre el documento.
  ![Añadimos el pdf](../assets/img/09-documentos_firma_info/Pdf.png)

  En la parte superior derecha, accedemos al menú "Acciones" donde aparece la opción "Dividir PDF".

  ![DividirPDF](../assets/img/09-documentos_firma_info/Dividir_PDF.png)

  Tras seleccionar las páginas que queremos conservar o dividir, Odoo crea nuevos documentos independientes directamente desde el PDF original.

  ![Le damos a "Dividir"](../assets/img/09-documentos_firma_info/Dividir.png)

## Firma electrónica

El módulo Firma de Odoo permite gestionar la validación digital de documentos de forma rápida, segura y sin necesidad de impresión ni escaneo. Está integrado con el módulo Documentos, lo que facilita el envío, seguimiento y archivo de contratos, autorizaciones o formularios.

![Firma electronica](../assets/img/09-documentos_firma_info/Firma_electronica.png)

### Campos (firma/nombre/fecha)

Al preparar un documento para firma electrónica en Odoo, es posible insertar **campos dinámicos** que indican al firmante dónde debe completar la información requerida. Estos campos se añaden mediante una interfaz de arrastrar y soltar, lo que facilita su colocación precisa sobre el documento.

![Contrato de ejemplo](../assets/img/09-documentos_firma_info/Ejemplo_contrato.png)

Arrastramos "Firma", "Nombre" y "Fecha" en los lugares correspondientes.

![Contrato](../assets/img/09-documentos_firma_info/Contrato.png)

Le damos a "Firmar ahora"

![Firmar ahora](../assets/img/09-documentos_firma_info/Firmar_ahora.png)

Cuando le hacemos click a nombre y fecha se rellenan los datos automaticamente y seleccionamos donde hemos dejado la firma antes y si queremos podemos modificarla.

![Firma completada](../assets/img/09-documentos_firma_info/Firma_completada.png)

![Validar y enviar documento](../assets/img/09-documentos_firma_info/Validar_y_enviar.png)

### Envío y registro

Una vez firmado el documento podemos descargar el documento.

![Documento firmado](../assets/img/09-documentos_firma_info/Documento_firmado.png)

El módulo de "Documentos" nos ayuda a tener un control de los documentos firmados.

![Contrato firmado](../assets/img/09-documentos_firma_info/Contrato_firmado.png)

## Información (Knowledge)

El módulo Información (también conocido como Knowledge) es una aplicación de productividad que permite a los usuarios crear, organizar y compartir contenido relevante dentro de la organización. Su propósito principal es construir una base de conocimiento interna, accesible y estructurada.

![Información](../assets/img/09-documentos_firma_info/Informacion.png)

### Wiki tipo Notion

Una wiki tipo Notion dentro de Odoo se puede construir usando el módulo Información (Knowledge), que está diseñado precisamente para crear una base de conocimiento colaborativa, muy similar a lo que ofrece Notion.

![Información Notion](../assets/img/09-documentos_firma_info/Informacion_notion.png)


* Sirve para documentar todo lo que ocurre en la empresa, desde procesos hasta ideas, políticas, manuales, y más.
* Puedes crear artículos con texto enriquecido, imágenes, enlaces, listas, y referencias cruzadas a otros módulos de Odoo.

* Es ideal para centralizar el conocimiento de la empresa y evitar que se pierda cuando alguien se va.
* Puedes organizar los artículos por categorías, asignar etiquetas, y controlar quién puede ver o editar cada contenido.
* Es útil para formar nuevos empleados, compartir procedimientos internos, y mejorar la colaboración entre equipos.

![Espacio trabajo](../assets/img/09-documentos_firma_info/Espacio_trabajo.png)

![Le damos a los 3 puntos](../assets/img/09-documentos_firma_info/Espacio_trabajo2.png)

![Portada e indice](../assets/img/09-documentos_firma_info/Portada_indice.png)

### Permisos y publicación

Para compartir, pulsa el boton "Compartir", habilita el "Articulo compartido a la web" y podrás ver que también puedes dar acceso general y añadir personas con accesos espeficicos.

![Permisos y publicación](../assets/img/09-documentos_firma_info/Permisos_y_publicacion.png)
