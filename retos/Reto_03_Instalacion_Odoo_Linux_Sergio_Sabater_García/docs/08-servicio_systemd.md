# 08 — Servicio systemd (`odoo.service`)

1. Crea el servicio en `/etc/systemd/system/odoo.service`:
   ```ini
   [Unit]
   Description=Odoo Service
   After=network.target postgresql.service

   [Service]
   Type=simple
   User=odoo
   Group=odoo
   ExecStart=/opt/odoo/venv/bin/python /opt/odoo/odoo-src/odoo-bin -c /etc/odoo/odoo.conf
   Restart=on-failure

   [Install]
   WantedBy=multi-user.target
   ```
   ![Hacer nano](../assets/img/08-servicio_systemd/paso01_nano.png)
   ![Añadir servicios](../assets/img/08-servicio_systemd/paso02_añadir_servicio.png)

2. Recarga y arranca:
   ```bash
   sudo systemctl daemon-reload
   sudo systemctl enable --now odoo
   sudo systemctl status odoo
   ```

![Recarga y arranca](../assets/img/08-servicio_systemd/paso03_recarga_y_arranca.png)

> Resultado esperado: servicio `odoo` activo y habilitado.
