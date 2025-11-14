# 05 — Dependencias (Python, wkhtmltopdf, librerías)

1. Instala Python y paquetes de compilación:
   Ya esta instalado por defecto.

   ```bash
   sudo apt -y install python3 python3-pip python3-venv build-essential libxslt1-dev      libzip-dev libldap2-dev libsasl2-dev libjpeg-dev libpq-dev
   ```
2. Instala **wkhtmltopdf** compatible (para reportes PDF).

   ![Instalar wkhtmltopdf](../assets/img/05-dependencias/paso01_instalar_wkhtmltopdf.png)
3. Verifica versiones:

   ```bash
   python3 --version
   wkhtmltopdf --version
   ```

   ![Instalado Python](../assets/img/05-dependencias/paso02_python_instalado.png)

   ![Instalado wkhtmltopdfPytho](../assets/img/05-dependencias/paso03_wkhtmltopdfpytho_instalado.png)

> Resultado esperado: dependencias instaladas y comprobadas.
