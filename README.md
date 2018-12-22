# express_eslint
Proyecto base node.js para arrancar el desarrollo de un API con Node.js. Implementa express para la construcción del API, ESLint para mantener el código legible y nodemon para refrescar los cambios en tiempo real mientras de desarrollan las funcionalidades del API.

## ¿Cómo se usa?

### Obtener el proyecto
+ 1 Clonar o descargar el proyecto
> $ git clone https://github.com/proartmateur/express_eslint.git

+ 2 Quitar ruta remota y agregar la propia
> $ git remote rm destination & git remote add \<tu repositorio\>

### Personalizar el proyecto
+ Edita los campos dentro del archivo package.json
<code>
  "name": "nombre_del_proyecto",
  "version": "0.0.1",
  "description": "",
  "author": "Tu Nombre",
</code>

### Instalar el los módulos del proyecto
Ejecuta:
<code> $ npm install </code>

### Ejecutar el proyecto
Hay dos maneras de ejecutar el proyecto:
+ **Modo desarrollador**
Permite refrescar en tiempo real el API para ver los cambios en caliente. 
<code>$ npm run dev </code>
> *Esto se logra gracias al uso de nodemon como dependencia de desarrollo*

+ **Modo Producción**
Ejecuta el proyecto para producción, en caso de realizar cambios, no se verán refrescados hasta que se detenga y se vuelva a ejecutar. 
<code>$ npm start </code>
