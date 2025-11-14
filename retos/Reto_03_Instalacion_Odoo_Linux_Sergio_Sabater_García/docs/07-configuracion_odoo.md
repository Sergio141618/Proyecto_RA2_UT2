# 07 — Configuración de Odoo (`/etc/odoo/odoo.conf`)

1. Crea/edita el archivo de configuración con:
   ```ini
   [options]
   db_host = False
   db_port = False
   db_user = odoo
   db_password = False
   addons_path = /opt/odoo/odoo-src/addons
   logfile = /var/log/odoo/odoo.log
   xmlrpc_port = 8069
   ```

   ![Configuracion de Odoo](../assets/img/07-configuracion_odoo/paso01_configuracion.png)
2. Crea carpetas y permisos si procede:
   ```bash
   sudo mkdir -p /var/log/odoo && sudo chown odoo:odoo /var/log/odoo
   ```
   ![Crear carpetas y permisos](../assets/img/07-configuracion_odoo/paso02_carpeta_y_permisos.png)

> Resultado esperado: configuración mínima funcional creada.
