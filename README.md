# Android-Prueba2doTrimestre
Para hacer las cosas más simples, nuestra aplicación va a tener completamente separados los conceptos de SQLite, Fragments y ListView.

 

La aplicación arranca mostrando tres botones: “Datos”, “Lista” y “Cambios”.  Cada uno de estos tres botones llama a una Activity diferente, independiente entre sí, que no están conectadas ni tienen relación.

 

La Activity “Datos” debe tener un EditText y un botón.  Al presionar el botón, agregar el texto ingresado a una base de datos (llamada como quieran), con una única tabla (llamada como quieran), y con un único campo (llamado como quieran), pero solamente si ese texto no estaba en la tabla previamente.   Si estaba, mostrar un cartel que indique que el dato está repetido y no será ingresado.  Si no estaba, agregarlo e informar que se agregó.  Validar que no se ingrese vacío.

 

La Activity “Lista” debe crear una lista inventada (harcodeada) con 10 elementos, conteniendo nombres de películas que le gustan a Leo Lob.   Estos nombres deben mostrarse en un ListView, cada una de cuyas celdas deberá mostrar el nombre de la película, y en un segundo renglón la cantidad de caracteres que tiene dicho nombre.

 

La Activity “Cambios” debe mostrar dos EditText y un botón en un fragment.  Al presionar el botón se debe reemplazar ese fragment por otro que muestre únicamente el texto más largo de los dos ingresados.
