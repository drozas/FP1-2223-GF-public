# Fundamentos de la programación 1
## Ejercicio 6: Juego de dados
![dados](https://cdn.iconscout.com/icon/premium/png-256-thumb/dice-266-799783.png)

A mis primos pequeños, Jorge y Ana, les gusta mucho jugar a los dados. Se sientan los dos en el suelo toda la tarde cada uno
con un dado. El juego consiste en tirar el dado y gana aquel que saca un número mayor.

Hoy les han regalado un par de dados más y han decidido que en lugar de tirar cada uno un dado van a tirar cada uno dos dados.
Ganará aquel cuyos dados sumen más. Como son tan pequeños pasan mucho tiempo pensando cuál de los dos ha ganado después
de tirar los dados. Decides ayudarles con un programa que dados los valores de los dados les diga quién es el ganador, pero para que vayan aprendiendo a sumar el programa les dirá también la suma de los dados de cada uno.

### Objetivo del problema
 - Practicar instrucciones condicionales sencillas. 

### Requisitos de implementación
 - Se utilizará un bucle *while* para tratar los casos (el número de partidas) e instrucciones condicionales para decidir el ganador.
 - Recuerda seguir las buenas prácticas con respecto al código que hemos visto en clase: indentación, uso razonable de comentarios, etc.


### Entrada
 - La entrada comienza con un entero que indica el número de casos de prueba que vendrán a continuación.
 - Cada caso consta de 4 valores enteros, los dos primeros indican los valores de los dados de Jorge y los dos siguientes los valores de los dados de Ana. 
 - No es necesario hacer un control de la entrada (asumimos que el usuario introducirá valores válidos similares a los de "Entrada de ejemplo").

### Salida
- Para cada caso de prueba se indica en una línea el nombre y la puntuación de cada uno, empezando por el que ha ganado. En caso de empate se indicará EMPATE seguido del valor de la suma.

### Entrada de ejemplo
```C++
3
3 2 6 1
5 4 5 2
2 2 2 2
```
### Salida de ejemplo
```C++
ANA 7 JORGE 5
JORGE 9 ANA 7
EMPATE 4
``` 
### Código fuente
- Puedes testear tu código fuente en el JuezDOM tantas veces como quieras.
- Para obtener la máxima puntuación, el código fuente deberá seguir las buenas prácticas explicadas en clase: comentarios, indentación, etc.
- Para este ejercicio solamente es necesario trabajar con un fichero fuente. El fichero se llamará: FP1_ejercicio_06.cpp. No es necesario adjuntar el resto de ficheros generados por el compilador o por Visual Studio.
- El fichero FP1_ejercicio_06.ccp deberá contener la siguiente cabecera (modificada con vuestros datos):

```C++
/*
Asignatura: Fundamentos de la Programación 1
Grupo: F

Nombre del primer alumno/a: [NOMBRE Y APELLIDOS]
Nombre del segundo alumno/a: [NOMBRE Y APELLIDOS]
Identificador de pareja en juez DOM: [ID AQUÍ]

Nombre de ejercicio: Ejercicio 6 - Juego de Dados
*/
``` 

### Formato de entrega
- El código fuente se entregará a través del campus virtual.
- Las entregas se agruparán junto a otros ejercicios, siguiendo las indicaciones del profesor/a.
- Solamente es necesario que realice la entrega uno de los estudiantes de la pareja.
- La entrega se realizará en el campus virtual antes de la fecha final fijada por el profesor/a.
- Se adjuntará en el campus virtual otro documento explicando las pautas de dicha entrega.
- El código que será evaluado es el que se entrega en el campus virtual, no en el JuezDOM. Recuerda, además, que aunque tu código fuente pase la batería de pruebas del juez, dichas pruebas no son exhaustivas. Durante la corrección manual del código pueden detectarse errores que el juez no identificó.

### Autores/as
- Creado por Isabel Pita.
- Modificado por David Rozas.
