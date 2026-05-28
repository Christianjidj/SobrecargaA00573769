# SobrecargaA00573769
Los ejercicios de clase.


ejemplo1

<img width="1239" height="728" alt="image" src="https://github.com/user-attachments/assets/1b7c9cba-1b2c-445e-bb85-1053138ed1bb" />

¿Qué clase se define? Punto
¿Qué operador se sobrecarga? +
¿Cuántos operandos utiliza? 1 o 2
¿Qué tipo de dato devuelve? punto
¿El operador modifica el objeto actual o crea uno nuevo? Crea uno nuevo.
¿La sobrecarga hace que el código sea más claro? En casos simples, como este, si.
¿Qué error común ayuda a evitar este ejemplo? Sumar tipos que no se pueden sumar normalmente.


ejemplo2

<img width="871" height="663" alt="image" src="https://github.com/user-attachments/assets/b65b30fd-809b-4783-adce-4688f70af72c" />

¿Qué clase se define? Libro
¿Qué operador se sobrecarga? ==
¿Cuántos operandos utiliza? 1 o 2
¿Qué tipo de dato devuelve? bool
¿El operador modifica el objeto actual o crea uno nuevo? Ninguna de las dos.
¿La sobrecarga hace que el código sea más claro? En casos simples, como este, si.
¿Qué error común ayuda a evitar este ejemplo? Comparar tipos que no se pueden comparar normalmente.



ejemplo3

<img width="943" height="608" alt="image" src="https://github.com/user-attachments/assets/778cb13c-5e7b-4764-bdfc-3cfb17503cd2" />

¿Qué clase se define? Persona
¿Qué operador se sobrecarga? <<
¿Cuántos operandos utiliza? 1
¿Qué tipo de dato devuelve? ostream&
¿El operador modifica el objeto actual o crea uno nuevo? Ninguna de las dos.
¿La sobrecarga hace que el código sea más claro? Si tienes claro que quieres extraer del objeto si.
¿Qué error común ayuda a evitar este ejemplo? Intentar imprimir un objeto sin una funcion de salida o sin haber hecho esta sobrecarga.


ejemplo4

<img width="933" height="690" alt="image" src="https://github.com/user-attachments/assets/d84d5f58-197c-46db-b701-c5f0b0ebff3a" />


¿Qué clase se define? Contador
¿Qué operador se sobrecarga? ++
¿Cuántos operandos utiliza? 1
¿Qué tipo de dato devuelve? Contador
¿El operador modifica el objeto actual o crea uno nuevo? Las dos, crea temp (objeto contador) y actualiza su propio atributo valor;
¿La sobrecarga hace que el código sea más claro? No mucho, lo mas util que hace es una copia de si mismo cada que se usa el operador.
¿Qué error común ayuda a evitar este ejemplo? Perder el valor del objeto antes de ser incrementado.


ejemplo5


<img width="1238" height="597" alt="image" src="https://github.com/user-attachments/assets/bf2e3e2a-d330-46a8-a951-37459530ec3d" />

¿Qué clase se define? Cadena
¿Qué operador se sobrecarga? =
¿Cuántos operandos utiliza? 1
¿Qué tipo de dato devuelve? Cadena&
¿El operador modifica el objeto actual o crea uno nuevo? Se modifica a si mismo.
¿La sobrecarga hace que el código sea más claro? Si, simplifica un proceso muy largo en un solo operador.
¿Qué error común ayuda a evitar este ejemplo? Si nomas usaramos el = sin la sobrecarga el texto de los dos objetos no es lo que seria igual, sino todo el objeto.



ejemplo6


<img width="1024" height="635" alt="image" src="https://github.com/user-attachments/assets/8e1d6ef3-b421-4115-a46d-67d7c9e72162" />

¿Qué clase se define? Temperatura
¿Qué operador se sobrecarga? double()
¿Cuántos operandos utiliza? ninguno
¿Qué tipo de dato devuelve? Double
¿El operador modifica el objeto actual o crea uno nuevo? Crea una copia del valor celsius de tu objeto en una variable tipo double.
¿La sobrecarga hace que el código sea más claro? Si, simplifica una converción de tipos.
¿Qué error común ayuda a evitar este ejemplo? Querer obtener un numero de un objeto con valores numericos a una variable de tipo numerico (int,double).
