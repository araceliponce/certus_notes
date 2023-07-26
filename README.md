# certus_notes

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
