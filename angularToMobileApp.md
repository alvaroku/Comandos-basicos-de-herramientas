# Angular To Mobile App

- Instalar capacitor core
`npm install @capacitor/core`

- Instalar capacitor cli- 
`npm install @capacitor/cli`

- Iniciar el capacitor
`npx cap init`

- Instalar el capacitor para ios
`npm install @capacitor/ios `

- instalar el capacitor para android
`npm install @capacitor/android`

## Ahora para generar la app 

- Compilar el proyecto de angular
`ng build`

- Agregar la app para ios
`npx cap add ios`

- Agregar la app para android
`npx cap add android`

- Para sincronizar la app con cada cambio del proyecto de angular se debe ejecutar el comando: `ng build` y luego: `npx cap sync`

- Abrir el proyecto de la app móvil generada para ios
`npx cap open ios`

- Abrir el proyecto de la app móvil generada para android
`npx cap open android`