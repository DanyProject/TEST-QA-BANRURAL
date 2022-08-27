1. El botón "Ingresar el número aleatorio" no responde
Descripción: Al presionar el botón no se realiza ninguna acción.
Solución: para poder solucionarlo se verifico en el código que no se estaba llamando a la función que ejecuta las acciones, por lo que,
se agrego la llamada a la función.

2. Los colores de los mensajes no corresponden.
Descripción: Al felicitar muesrtra el mensaje en rojo; Al perder muestra el mensaje en negro; Al ser incorrecto muestra el mensaje en verde.
Solución: a nivel de código se verifico el color de las alertas y se coloco el correcto para cada una.

4. no valida que sean 10 intentos.
Descripción: al quinto intento detiene el juego.
solución: se cambio el número de intentos en el código a 10.

5. no valida si el número ingresado excede los 100 o es menor a 0

6. no valida que se ingresan letras
Descripción: El campo en el que se ingresan los datos permite letras y caracteres.
Solución: se creo una función para solo permitir el ingreso de números enteros.

7. El número random generado se muestra en decimales, cuando debería ser un entero
Descripción: Al revisar la consola, se pudo notar que los números random mostrados eran decimales.
Solución: se agrego una función para que al generar un número random, solo desliegue valores enteros.

8. Los mensajes que muestra por las acciones no son correctos.
Descripción: Si el número es igual al random indica que perdiste; Si se llega al límite de intentos indica el mensaje de felicitación.
Solución: Se corrigieron los mensajes del código para que correspondan con sus acciones.

9. El botón comienza un nuevo juego no funciona
Descripción: Al terminar el juego despliega el botón para comenzar de nuevo, sin embargo, al presionarlo no realiza ninguna acción.
Solución: Se modifico el código, de modo que se pueda identificar el boton agregado para posterior identificarlo y realizar el remove y reinicio de las variables.

10.  Los mensajes que validan si un número es mayor o menor se encuentran invertidos
Descripción: al ingresar un número menor que el random muestra un mensaje indicando que es mayor y al ingresar un número mayor al random muestra un mensaje indicando que es menor.
solución: Invertir el mnesaje mostrado a nivel de código.