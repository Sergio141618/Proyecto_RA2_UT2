# 06 — Instalación de Odoo

## Paquete oficial (repositorio Odoo)

 Información basada en la [documentación oficial de Odoo 19](https://www.odoo.com/documentation/19.0/es/administration/on_premise/packages.html#repository).


1. Añade repositorio/clave y luego instala `odoo`:

   ```bash
   wget -q -O - https://nightly.odoo.com/odoo.key | sudo gpg --dearmor -o /usr/share/keyrings/odoo-archive-keyring.gpg
   ```

   ```bash
   echo 'deb [signed-by=/usr/share/keyrings/odoo-archive-keyring.gpg] https://nightly.odoo.com/19.0/nightly/deb/ ./' | sudo tee /etc/apt/sources.list.d/odoo.list
   ```

   ```bash
   sudo apt-get update && sudo apt-get install odoo
   ```


   ![Instalando Odoo](../assets/img/06-instalacion_de_odoo/paso01_instalando_odoo.png)
   ![Odoo instalado](../assets/img/06-instalacion_de_odoo/paso02_odoo_instalado.png)

> Resultado esperado: binarios/código de Odoo instalados.
