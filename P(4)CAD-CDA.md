# Entradas Analógicas
![Esta es una imagen de ejemplo](http://robots-argentina.com.ar/didactica/wp-content/uploads/PINOUT-ANALOGICO.png)

>Las tarjetas de arduino **generalmente cuentan con
6 entradas analógicas (A0 – A5)**.

Estas entradas funcionan como convertidores
Analógico a Digital (ADCs) de 10 bits

El voltaje de referencia de las entradas analógicas se 
puede ajustar mediante el pin Vin y el jumper Vin.
El jumper Vin es utilizado para configurar un voltaje 
de referencia de 5V

 ## `analogRead()`.

 Esta función es utilizada para leer un valor analógico de alguna de las terminales de entrada A0 a A5. 
 
 Este valor es representado por
 10 bits, arrojando valores enteros (int) entre 0 y 1023.


 Esta función tarda cerca de 100 microsegundos para leer una
 entrada analógica, por lo que el máximo número de lecturas es de
 10,000 por segundo.


 Sintaxis:  
 `analogRead()`.

 Donde pin es el número de la terminal analógica a leer (A0 – A5)

 