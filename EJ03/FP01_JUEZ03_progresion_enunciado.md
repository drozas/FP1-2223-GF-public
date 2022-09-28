# Fundamentos de la programación 1
## Ejercicio 3: Progresión aritmética
![Progresiones](https://is4-ssl.mzstatic.com/image/thumb/Purple114/v4/23/b5/79/23b579b0-a21e-3a3c-50e4-beb91dce604d/source/256x256bb.jpg)

Una progresión aritmética es una sucesión de números tales que la diferencia de dos términos sucesivos cualesquiera de la secuencia es una constante.
Dada una progresión aritmética cuyos términos consecutivos se diferencian en una unidad, se pide calcular la suma de todos los términos de la progresión. Concretamente, el programa aplicará la siguiente fórmula:
```C++
res = (n2 - n1 + 1) * (n1 + n2) / 2;
```
### Objetivo del problema
En este problema se practican las expresiones aritméticas, las instrucciones de asignación y entrada/salida y el bucle while para tratar los casos de prueba. 
### Entrada
La entrada comienza con un entero que indica el número de casos de prueba que vendrán a continuación. Cada caso consta de dos valores enteros, n1 y n2 que indican el primer y el último término de la progresión.
Se garantiza (no es necesario controlarlo) que 0 <= n1 <= n2 <= 100.000.
### Salida
Para cada caso de prueba se indica en una línea el valor de la suma de la progresión dada.
### Entrada de ejemplo
```C++
3 
1 5
4 12
5 5
```
### Salida de ejemplo
```C++
15
72
5
``` 
### Código fuente
- Puedes testear tu código fuente en el JuezDOM tantas veces como quieras.
- Para obtener la máxima puntuación, el código fuente deberá seguir las buenas prácticas explicadas en clase: comentarios, indentación, etc.
- Para este ejercicio solamente es necesario trabajar con un fichero fuente. El fichero se llamará: FP1_ejercicio_03.cpp. No es necesario adjuntar el resto de ficheros generados por el compilador o por Visual Studio.
- El fichero FP1_ejercicio_03.ccp deberá contener la siguiente cabecera (modificada con vuestros datos):

```C++
/*
Asignatura: Fundamentos de la Programación 1
Grupo: F

Nombre del primer alumno/a: [NOMBRE Y APELLIDOS]
Nombre del segundo alumno/a: [NOMBRE Y APELLIDOS]
Identificador de pareja en juez DOM: [ID AQUÍ]

Nombre de ejercicio: Ejercicio 3 - Progresión Aritmética
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
