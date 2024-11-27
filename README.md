# API-Investigation
Integrantes :
Carlos Romero Cordero
Steven Montero Nájera

Este documento contiene la explicación de la creación de la Api propia enfocada en el registro de estudiante.
Para la creación de este proyecto de investigación primero se creo una carpeta local en el disco C para poder luego se ejecutada en el Visual Studio Code,
para esto se apertura la carpeta y crea un documento llamado app con extensión JS, en el cual se va a digitar el código que nos permite crear nuestra api
Seguido de esto abrimos la terminal del VS code y se digita el comando npm -v, esto con el fin de poder verificar que tenemos instalado npm.
Continuamos digitando el comando npm install express, esto nos crea dos documentos tipo JSON, nos dirigimos al documento creado y llamada app.js para poder
hacer uso de la extensión express, esto lo hacemos por medio de una variable constante, adicional a esto se creo una variable mas llamada app que va a 
permitir la llamada y uso de el JSON que va a contener la información de los estudiantes, el JSON  que se creo con el contenido de estudiantes tiene 6
registros, esto para efectos de la muestra de su funcionamiento y parte de la investigación.
Dicho Json contiene un id , nombre de estudiante y rol, seguido a esto se procede con la creación de los endpoints que van a contener la información y ruta
respectiva de nuestra api.
Endpoint por medio del método Get el cual nos permite fijar el home de la api y el uso del contenido del json que contiene la información de la api.
Endpoint por medio del método POST el cual nos permite crear un nuevo usuario , esto siguiendo el formato correspondiente del json, y nos da respuesta a ello.
Endpoint por medio del método Delete el cual nos permite eliminar el registro que se desea por medio de un index, en este caso se utiliza el índice que es el 
numero que identifica a cada uno de los estudiantes.
Es importante recalcar que se debe de asignar un puerto que es donde la api va a publicar la información contenida, en nuestro caso utilizamos una variable
llamada port que contiene el puerto numero 3000 que por el cual levantamos nuestra api, esto se le asigna a la variable app con el método listen.

Las pruebas de que esta api esta funcionando se deben realizar ejecutando desde la terminal de Visual Studio Code el comando node app.js, esto en nuestro caso 
ya que el documento tiene ese nombre (app.js)
La consola nos confirma que el servidor esta hosteado, ya que envía un mensaje que indica que esta escuchando.
Podemos hacer uso de la api y realizar pruebas de dos maneras, una por medio del browser ejecutando la ruta del local host, seguido por la correcta ruta asignada
en cada uno de los endpoints y que cumplen su respectiva funcionalidad.
En nuestro caso utilizamos la segunda manera de realizar pruebas que es por medio de la aplicación llamada postman, en ella se creo una colección para poder hacer
uso de los 3 métodos (GET, POST , DELETE).
Se realizan varias pruebas y se logra demostrar que todo esta funcional.

Esta creación de API se logra gracias a la investigación realizada en la documentación js y en el paso a paso de Manz.Dev adjuntamos la pagina de apoyo:
https://lenguajejs.com/nodejs/servidores/crear-api/
Igualmente nos apoyamos del canal de You Tube llamad Codelia, adjuntamos también el video visto https://www.youtube.com/watch?v=AWcm56_eNZg
Es importante recalcar que la guía dada en la clase que el profesor impartió también nos fue de mucha ayuda para guiarnos en exactamente que se quería con la inves_
tigación

Sin mas damos por concluido este documento con una breve explicación del como se realizo la API , quedando satisfechos por lo aprendido y quedando mucho mas interesados
en continuar aprendiendo, ya que nos permitió conocer que se puede crear una api a gusto y necesidad, sin depender que información ya creada, es decir podemos adaptar
nuestras necesidades para poder crear aplicaciones a gusto y mas personalizadas.
