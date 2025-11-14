# 04 — PostgreSQL en Linux

1. Instala PostgreSQL desde repos:

   ```bash
   sudo apt -y install postgresql
   ```

   ![Instalar PostgreSQL](../assets/img/04-postgresql_linux/paso01_install_postgresql.png)
2. Verifica el servicio:

   ```bash
   sudo systemctl status postgresql
   ```

   ![Estado PostgreSQL](../assets/img/04-postgresql_linux/paso02_estado_postgresql.png)
3. Cambia contraseña del usuario `postgres`.

   ![Cambiar contraseña](../assets/img/04-postgresql_linux/paso03_contraseña_cambiada.png)

> Resultado esperado: PostgreSQL instalado y activo.
