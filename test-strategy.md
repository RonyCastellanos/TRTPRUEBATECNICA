PLAN DE ATAQUE 
1.	Se realizaron pruebas de caja blanca para revisar la estructura de del código se realizaron los siguientes tipos de pruebas: 

-	Pruebas de flujo de control, estas para verificar la estructura del código y el flujo del mismo durante su ejecución.

-	Pruebas de cambios básicos, esta para verificar que cada sentencia del código se ejecute mínimo una vez.

2.	Se realizaron las pruebas de caja negra para validar la funcionabilidad del programa según lo establecido en los requerimientos del programa, se realizaron los siguientes tipos de pruebas: 

-	Pruebas de Humo, esto para validar que el    sistema cumpla con el funcionamiento básico según lo solicitado en el requerimiento 

-	Pruebas funcionales, esta para verificar que el programa funcionara según lo indicado en los requerimientos
 
-	
LISTADO DE ERRORES ENCONTRADOS Y SOLUCIONES 
1.	 En la línea 46 const ATTEMPS = 5; estaba definido en 5 y no en 10 esto ocasionaba que fueran únicamente 5 inténtenos solución fue definirlo de la siguiente manera ATTEMPS = 10;

2.	En la línea 44 let randomNumber = Math.random() * 10; el calculo se realizaba de esa manera lo que ocasiobana que solo se tomaran números del 1 al 10 y no del 1 al 100 la solución fue definirlo de la siguiente manera let randomNumber = Math.random() * 100; 


3.	En la línea 49 const lowOrHi = document.querySelector('.low0rHi'); se tenía un error de sintaxis se  solución fue definirlo de la siguiente manera const lowOrHi = document.querySelector('.lowOrHi');

4.	En la función function setGameOver() { en la línea 95 resetButton.addeventListener('click', resetGame); tenían un problema de sintaxis, se  solución fue definirlo de la siguiente manera resetButton.addEventListener('click', resetGame);


5.	Se encontró el error que cuando se adivinaba el numero el mensaje se mostraba en color rojo, se solucionó cambiándola por el color correspondiente 

6.	Cuando el numero era menor o mayor el mensaje se mostraba en color rojo y no en negro como se indica en el requerimiento: se solucionó cambiándola por el color correspondiente. 

7.	También se encontró el error que cuando a pesar que no se colocara el numero correcto el programa siempre indicaba que se ganaba y por ende no aparecía la opción perdiste en color rojo, se soluciono Se encontró que el condicional para definir el ganador y la derrota estaban al revés se modificó la misma. 


8.	Se encontró que cuando se ingresa un numero que no sea entero lo cuenta como un intento algo que es indistinto a lo solicitado en el requerimiento, se solucionó agregando una alerta para identificar si se está enviando un carácter que no sea entero, se validó todos aquellos números que no sean enteros y no son tomados dentro de los intentos validando que solamente sean enteros.
 
