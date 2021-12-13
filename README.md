# Readme para la ejecución del código de la API ActividadCowsay.js

# Recordar tener instalado nodejs y docker en su equipo.

Descargar el código de la carpeta ActividadMasterCowsay.

Abrir el IDE de preferencia o la terminal.

Ejecutar el archivo con el comando nodejs

# Ejemplo: nodejs <nombrearchivo.js>

Dockerizar:

Una vez ejecutado el archivo .js, 

usar los siguiente comandos para la dockerización:

docker build . -t <nombreusuario>/node-web-app

docker run -p 49160:8080 -d <nombreusuario>/node-web-app






