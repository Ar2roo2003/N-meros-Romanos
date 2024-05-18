José Arturo Reyes Roa – 1116842

Read me – Números enteros a romanos

Requerimientos
1.	Debe tener una función que reciba un numero entero “n” para luego transformarlo a su equivalente en números romanos, por partes, es decir por nivel de unidad para ser más específico, milésima, centena, decena, unidad).
2.	Debe pedirle al usuario el número con el que desea trabajar.
3.	Debe de poder manejar errores a modo de que el programa pueda seguir corriendo sin interrupción.
4.	Debe usar un número valido para llamar la función que transforma a romano. 
5.	Debe devolver el número introducido seguido por su equivalente en romano.
Criterios de Aceptación 
1.1	La función es capaz de convertir exitosamente el numero a romano.
1.2	La función es dinámica siendo capaz de ser llamada múltiples veces con diferentes tipos de datos y devolver el valor correcto, aun así.

2.1 El código muestra por consola el mensaje "Introduzca el valor numérico a usar (entre 3999 y 1): ".
2.2 El código permite al usuario introducir una entrada mediante el teclado.

3.1 Si el código recibe un valor no numérico este deberá de ser capaz de permitirle al usuario volver a intentar.
3.2 Si el código recibe un valor numérico por encima o por debajo del aceptado, este deberá de ser capaz de permitirle al usuario volver a intentar.
3.3 Cuando reciba un valor invalido deberá mostrar por consola el mensaje de error, "El dato que usted ha introducido no es válido, vuelva a intentar.".

4.1 Suponiendo que se recibió un valor numérico válido el código trabajara con el mismo y conseguirá todas las variables que requiera, en este caso la milésima, centena, decena y unidad.
4.2 Se llama la función múltiples veces para que trabaje con cada nivel del número inicial.
4.3 Aunque el número conseguido en un nivel especifico corresponda a un 0, el cual es un numero no existente para los romanos, debe ser capaz de manejarlo.

5.1 Deberá mostrar en la consola los resultados obtenidos mediante el siguiente mensaje, "El numero {numero} en romano es igual a {romano}."; siendo los datos que están dentro de las llaves ( {} ), el numero que introdujo el usuario, y el equivalente del número introducido en romano, respectivamente.
 
Casos de Prueba
En respuesta a los criterios de aceptación No. 1.1 y No. 1.2.
-	Se introduce el número 3999, se mostrará por pantalla, "El número 3999 en romano es igual a MMMCMXCIX.".
-	Se introduce el número 1, se mostrará por pantalla, "El número 1 en romano es igual a I.".
-	Se introduce el número 108, se mostrará por pantalla, "El número 108 en romano es igual a CVIII.".

En respuesta a los criterios de aceptación No. 2.1 y No. 2.2.
-	El usuario ejecuta el archivo “Números enteros a romanos.sln”, para luego correr el código con el depurador de local de Windows, y apenas inicie el programa, se mostrará el mensaje esperado "Introduzca el valor numérico a usar (entre 3999 y 1): ", y el programa esperara a que el usuario introduzca el número que desee, para luego presionar la tecla Enter.

En respuesta a los criterios de aceptación No. 3.1, No. 3.2 y No. 3.3.
-	Se introduce el número 0, se mostrará por pantalla, "El dato que usted ha introducido no es válido, vuelva a intentar.", y permitirá al usuario volver a introducir el número.
-	Se introduce el número 4000, se mostrará por pantalla, "El dato que usted ha introducido no es válido, vuelva a intentar.", y permitirá al usuario volver a introducir el número.
-	Se introduce el dato toif, se mostrará por pantalla, "El dato que usted ha introducido no es válido, vuelva a intentar.", y permitirá al usuario volver a introducir el número.
-	Se introduce el dato t4, se mostrará por pantalla, "El dato que usted ha introducido no es válido, vuelva a intentar.", y permitirá al usuario volver a introducir el número.

En respuesta a los criterios de aceptación No. 4.1, No. 4.2 y No. 4.3.
-	Se introduce el número 1000, se mostrará por pantalla, "El número 108 en romano es igual a M.".
-	Se introduce el número 100, se mostrará por pantalla, "El número 108 en romano es igual a C.".
-	Se introduce el número 10, se mostrará por pantalla, "El número 108 en romano es igual a X.".
-	Se introduce el número 1, se mostrará por pantalla, "El número 108 en romano es igual a I.".

En respuesta a los criterios de aceptación No. 5.1.
-	Después de introducir un numero válido cualquiera, en este caso 24, mostrará el mensaje esperado "El número 24 en romano es igual a XXIV.".

