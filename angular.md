# Comandos para Angular

Todo es por cmd
- Instalar por primera vez el cli de angular
`npm install -g @angular/cli`

En caso de que en el cmd no se pueda ejecutar comandos, se debe ejecutar los siguente:
`Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned`

- Crear un nuevo proyecto
`ng new my-first-project`
- Moverse a la ruta del proyecto
`cd my-first-project`

- Ejecutar app
`ng serve`

- Ejecutar app en un puerto definido
`ng serve --port=3500`

- Lanzar servidor y abrir el navegador por defecto automáticamente:
`ng serve --open`
`ng serve -o`

- Compilar para ambientes especificos
`ng build --configuration=[envName]`

- Crear modulos
`ng g module [folderName]/[moduleName]`
- Crear servicio
`ng generate service [folderName]/serviceName`

- Crearcomponentes
`ng generate component [folderName]/[componentName]`

- Instalar libreria para cookies
`npm install ngx-cookie-service --save`

- Compilar cuando la app estará en la raiz del host
`ng build`
- cuando no estará en la raiz del host
`ng build --base-href=/[folderName]/[folderName]/`

**Nota:**
en caso de error con node
abrir archivo npm y npm.cmd
cambiar `prefix -g` por `prefix --location=global`

- Agregar NgRx Store
`ng add @ngrx/store`

- Agregar Routing 
`ng generate module app-routing --flat --module=app`

- Agregar boostrap 
`npm install --save bootstrap`

- Agregar libreria de componentes NG Zorro
`ng add ng-zorro-antd`