npm install @popperjs/core
npm install bootstrap
npm install -save-dev parcel sass
**Y ya está instalado**
1. Añadimos la carpeta "src"
    1.1 Añadimos "index.html"
        1.1.1 Linkeamos el ".scss"
        1.1.2 Linkeamos el "index.js": script src="./index.js" type="module"
    1.2. Añadimos "index.js"
        1.2.1 import * as bootstrap from 'bootstrap';
2. Añadimos la carpeta "scss"
    2.1. Añadimos "style.scss
3. Añadimos ".sassrc"
    3.1. {"includePaths":["node_modules"]}
4. Añadir "start": "parcel ./index.html", dentro de scrip
5. En la consola "npm start"
6. Dentro de "style.scss"
    6.1. @import "../node_modules/bootstrap/scss/functions";
    6.2. @import "../node_modules/bootstrap/scss/variables";
    6.3. @import "../node_modules/bootstrap/scss/mixins";