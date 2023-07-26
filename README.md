# certus_notes


---


existe angular.js y angular 2 (que usa typescript)


ver version:
ng -v
ng --version
ng version



ng new nombredeproyecto
ng generate (es mejor que crear manualmente, porque cada componente requiere varios archivos)


ng help


ng serve (el port es 4200)


ng test



tengo npm? npm --version
6.14.14


instalar angular cli:
npm install -g @angular/cli
(-g significa que se instala global, abrir vscode en modo administrador)



ng serve
if after, you get this error:
Error: This command is not available when running the Angular CLI outside a workspace.
:::::::::::::You should be positioned inside of directory where package.json is located.





---



  >>>>> angular tiene modulos, ejm: APP.MODULE.TS
  en proyectospequeños suele usarse soloun modulo


  (todo module tiene @NgModule({declarations,imports, exports, providers,bs}))



  >>>>> angular tiene componentes (template, metadatos,enlace de datos, directiva, pipes)


  ejm: footer,navbar,,,, VER APP.COMPONENT.TS


  ::: auto redirect to '/en' is bad for seo (?????)





---


ngfor


ng g m users
ng g c users/form
ng g c users/table



**importar FormsModule en el modulo contenedor de componente(s)

en printData(data) pregunta que tipo es (string,number,etc).
para poder poner printData(data:NgForm), importar ngForm con: import {NgForm} from '@angular/forms';




copiar en angular.json linea 27:

"styles": [
"node_modules/bootstrap/dist/css/bootstrap.min.css",
"src/styles.css"
],
"scripts": [
"node_modules/bootstrap/dist/js/bootstrap.min.js"
]
