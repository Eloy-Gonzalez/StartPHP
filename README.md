# StartPHP
Framework MVC PDO PHP para desarrollo de Aplicaciones web

# Changelog 
Versión 1.0 23/10/2016
* Rediseño del árbol de archivos
* Implementación de Multiples Frameworks CSS (Bootstrap, Materialize)
- Se eliminaron varias clases entre ellas Form, Session, Cookie
* La aplicacion a usar se seleccionará desde el archivo index.php

Varsión 2.0 11/04/2017
* Rediseño del árbol de archivos
+ Añadida interfaz abstracta para el manejo de multiples bases de datos (Mysql, PostgreSQL, SQLite)
- Eliminación de métodos one y many de la clase model.php (Ver Versión 1.0)
* Mejora en el cacheo de archivos disminuyendo el uso de memoria dinamica
+ Añadida Seguridad y encriptación en rutas del framework 
+ Añadido soporte para navegación Movil (Responsive).

20/04/2017
+ Añadidos templates starter para los frameworks CSS integrados (Bootstrap y Materialize).

22/04/2017
+ Añadido soporte para el uso del framework JQuery

23/04/2017
+ Actualizado el api JQuery a su versión 3.2.1

02/05/2017
* Modificada Configuración de parametros de conexión a Base de datos, Ahora se podrá configurar desde el archivo base Index.php

06/05/2017
* Se modificó la configuración de parametros de conexión la base de datos ahora se definirá desde el Index.php sin pasar como parametro al método constructor del framework, logrando optimizar el código base.
- Se Eliminó la clase Executor, Ahora se realizaran las consultas (Querys) desde la clase Database.
+ Agregado mecanismo de captura de excepciones evitando mostrar errores fatales que destruyan el flujo de datos en PHP.
+ Agregado método SimpleQuery Para consultas directas a base de datos.
+ Agregado métodos PreparedQuery, PreparedSelect para consultas preparadas hacia el motor de base de datos logrando bindear parametros para evitar inyecciones SQL. (Fase Experimental).
+ Añadida mejor seguridad en el flujo de datos.
+ Añadida nueva fuente "Font-Awesome" para darle más contenido a los proyectos

09/05/2017
+ Sistema ajax vinculada con las acciones del framework 

11/05/2017
+ Actualizada versión Framework CSS Bootstrap

17/05/2017
* Modificada la configuración de parametros de conexión a la base de datos, ahora se incluira un archivo Config.ini en cada aplicación donde se definiran dichos parametros DB_HOST, DB_USER, DB_PASS, DB_NAME, si estos no son definidos, el framework dará una advertencia.

19/05/2017
* Optimizado el core del framework reduciendo así el código base mejorando la carga del mismo junto con las aplicaciones.
