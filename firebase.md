# Hacer deploy de una app web en Firebase

- Crear un proyecto en firebase console
- Abrir un cmd
- Instalar por primera vez las herramientas de firebase
`npm install -g firebase-tools`

- Loguearse
`firebase login`

- En la carpeta en la que se encuentre el proyecto o archivos a hacer deploy, abrir un cmd
- Ejecutar
`firebase init`
- El comando anterior generará archivos de configuración, y tambien una carpeta "public", es necesario mover ahí los archivos que se quieran publicar.
- Una vez que se hayan movido todos los archivos a la carpeta public, es necesario ejecutar el comando:
`firebase deploy`