# Fundamentos de la programación 1
## Ejercicio 2: Perímetro de un triángulo
Dada la longitud de los lados de varios triángulos debes calcular el perímetro de cada uno de ellos. 

![Triángulos](http://1.bp.blogspot.com/_N8OYdq6QuXk/TFkxE9duTFI/AAAAAAAAAKg/qzdO-CitSjw/s320/TRIANGLES+TYPES.jpg)
### Objetivo del problema
En este problema se practican las expresiones aritméticas, las instrucciones de asignación y de entrada/salida.
### Entrada
La entrada comienza con un entero que indica el número de casos de prueba que vendrán a continuación. Cada caso se escribe en una línea y consta de tres valores enteros positivos correspondientes a los tres lados del triángulo.
### Salida
Para cada caso de prueba se escribe en una línea el valor del perímetro del triángulo.
### Entrada de ejemplo
```C++
3
2 4 6
50 20 35
200 600 100
```
### Salida de ejemplo
```C++
12
105
900
``` 
### Plantilla de prueba
- Para trabajar con el JuezDOM, será común pasarle una serie de casos y para ello, necesitaremos bucles. 
- Un bucle es es una secuencia de instrucciones de código que se ejecuta varias veces. El bucle parará una vez se haya cumplido cierta condición.
- Dado que no hemos visto bucles en la parte de teoría todavía, se proporciona la siguiente plantilla desde la que partir para resolver el problema dado:

```C++
/*

Asignatura: Fundamentos de la Programación 1
Grupo: F

Nombre del primer alumno/a: [NOMBRE Y APELLIDOS]
Nombre del segundo alumno/a: [NOMBRE Y APELLIDOS]
Identificador de pareja en juez DOM: [ID AQUÍ]

Nombre de ejercicio: Ejercicio 2 - Perímetros

*/

#include <iostream>
using namespace std;

int main()
{
    int nCasos = 0;
    int i = 1;
    //Declara e inicializa las variables que necesites aquí 

    // Pedimos cantidad de casos
    cin >> nCasos;
    while (i <= nCasos) {
        // Incluye aquí el código necesario para resolver el problema
        
        
        //Actualizamos índice del bucle
        i++;
    }

    return 0;
}
``` 


### Código fuente
- Puedes testear tu código fuente en el JuezDOM tantas veces como quieras.
- Para obtener la máxima puntuación, el código fuente deberá seguir las buenas prácticas explicadas en clase: comentarios, indentación, etc.
- Para este ejercicio solamente es necesario trabajar con un fichero fuente. El fichero se llamará: FP1_ejercicio_02.cpp. No es necesario adjuntar el resto de ficheros generados por el compilador o por Visual Studio en la entrega.
- El fichero FP1_ejercicio_02.ccp deberá contener la siguiente cabecera (modificada con vuestros datos):

```C++
/*
Asignatura: Fundamentos de la Programación 1
Grupo: F

Nombre del primer alumno/a: [NOMBRE Y APELLIDOS]
Nombre del segundo alumno/a: [NOMBRE Y APELLIDOS]
Identificador de pareja en juez DOM: [ID AQUÍ]

Nombre de ejercicio: Ejercicio 2 - Perímetros
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
