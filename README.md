PARCEL_Ejercicio

Práctica módulo 3 Parcel

Se ha realizado lo siguiente:
Implementar una aplicación simple que: Páginas y scripts en: src/index.js y src/index.html para mostrar los logos, páginas

-Tenga el bundling montado con pacerl.

  - Configuracion en package.json
    -Muestre unlogo (si queréis el de lemoncode).

  - Logos en content -> logos_1 y logos_2 de lemoncode
  - abrir src/index.html
-Este montada con typescript.  
-Tenga el texto de hola mundo estilado con SASS

  -  src/mystyles.scss
  
  Para ejecutar:
npm run start

Como esta puesto en packaje.json -> start, abre la web directamente con el holamundo con sass y la imagen
"start": "rimraf dist && parcel ./src/index.html --open",
