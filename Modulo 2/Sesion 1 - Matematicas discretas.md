# Matematicas discretas

## Introduccion a los conceptos de las matematicas discretas

Un conjunto es una coleccion de objetos, los objetos son llamados elementos del conjunto. Los conjuntos son una herramienta fundamental en las matematicas discretas.

Propiedades de los conjuntos:

- Un conjunto es una coleccion de objetos
- Los elementos de un conjunto son distintos
- Los elementos de un conjunto no tienen un orden
- Los elementos de un conjunto no se repiten

Ejemplo de un conjunto:

- El conjunto de los numeros naturales pares: {2, 4, 6, 8, 10, ...}
- El conjunto de los numeros naturales impares: {1, 3, 5, 7, 9, ...}
- El conjunto de los numeros naturales: {1, 2, 3, 4, 5, ...}
- El conjunto de los numeros enteros: {..., -3, -2, -1, 0, 1, 2, 3, ...}
- El conjunto de los numeros racionales: {1/2, 3/4, 5/6, 7/8, ...}
- El conjunto de los numeros reales: {1, 2, 3, 4, 5, ...}

## Algebra propocional

La logica proposicional es una rama de la logica matematica que estudia las proposiciones logicas, las cuales son oraciones que pueden ser verdaderas o falsas, pero no ambas a la vez.

Las proposiciones logicas son las unidades basicas de la logica proposicional, y se pueden combinar para formar proposiciones compuestas.

Las proposiciones logicas pueden ser:

- Simples: Son proposiciones que no se pueden descomponer en otras proposiciones mas simples.
- Compuestas: Son proposiciones que se forman a partir de
  - Una o mas proposiciones logicas
  - Uno o mas conectivos logicos

Los conectivos logicos son operadores que se utilizan para combinar proposiciones logicas y formar proposiciones compuestas.

Los conectivos logicos mas comunes son:

- Negacion
- Conjuncion
- Disyuncion
- Implicacion
- Doble implicacion

## Operadores de algebra proposicional

### Negacion

La negacion de una proposicion p se denota como ¬p, y se lee "no p". La negacion de una proposicion p es verdadera si p es falsa, y es falsa si p es verdadera.

### Conjuncion

La conjuncion de dos proposiciones p y q se denota como p ^ q, y se lee "p y q". La conjuncion de dos proposiciones p y q es verdadera si p y q son verdaderas, y es falsa en cualquier otro caso.

### Disyuncion

La disyuncion de dos proposiciones p y q se denota como p v q, y se lee "p o q". La disyuncion de dos proposiciones p y q es verdadera si p o q son verdaderas, y es falsa si p y q son falsas.

### Implicacion

La implicacion de dos proposiciones p y q se denota como p -> q, y se lee "si p entonces q". La implicacion de dos proposiciones p y q es falsa si p es verdadera y q es falsa, y es verdadera en cualquier otro caso.

### Doble implicacion

La doble implicacion de dos proposiciones p y q se denota como p <-> q, y se lee "p si y solo si q". La doble implicacion de dos proposiciones p y q es verdadera si p y q son verdaderas, o si p y q son falsas, y es falsa si p es verdadera y q es falsa, o si p es falsa y q es verdadera.

## Tablas de verdad

Una tabla de verdad es una tabla que muestra el valor de verdad de una proposicion compuesta para cada combinacion de valores de verdad de sus proposiciones componentes.

| p | q | ¬p | p ^ q | p v q | p -> q | p <-> q |
|---|---|----|------|------|-------|--------|
| V | V | F  | V    | V    | V     | V      |
| V | F | F  | F    | V    | F     | F      |
| F | V | V  | F    | V    | V     | F      |
| F | F | V  | F    | F    | V     | V      |

## Logica de predicados

La logica de predicados es una extension de la logica proposicional que permite cuantificar las proposiciones logicas.

Las proposiciones logicas cuantificadas son llamadas predicados, y pueden ser verdaderas o falsas dependiendo de los valores de sus variables libres.

Los predicados pueden ser:

- Simples: Son predicados que no se pueden descomponer en otros predicados mas simples.
- Compuestos: Son predicados que se forman a partir de
  - Un predicado
  - Uno o mas cuantificadores
  - Uno o mas variables libres

## Teoria combinacional

La teoria combinacional es una rama de las matematicas discretas que estudia los arreglos de objetos, y las operaciones que se pueden realizar sobre estos arreglos.

Los arreglos de objetos son llamados permutaciones, combinaciones y variaciones, y son fundamentales en la teoria combinacional.

Las permutaciones son arreglos de objetos en los que el orden de los objetos importa.

Las combinaciones son arreglos de objetos en los que el orden de los objetos no importa.

Las variaciones son arreglos de objetos en los que el orden de los objetos importa, pero se pueden repetir los objetos.

## Permutaciones

Una permutacion de n objetos es un arreglo de n objetos en el que el orden de los objetos importa.

El numero de permutaciones de n objetos es n!, que se lee "n factorial", y se define como el producto de los numeros naturales desde 1 hasta n.

n! = n *(n - 1)* (n - 2) *...* 3 *2* 1

ejemplo:

- 1! = 1
- 2! = 2 *1 = 2
- 3! = 3 *2* 1 = 6
- 4! = 4 *3* 2 * 1 = 24
- 5! = 5 *4* 3 *2* 1 = 120

## Combinaciones

Una combinacion de n objetos tomados de r en r es un arreglo de r objetos tomados de n objetos en el que el orden de los objetos no importa.

El numero de combinaciones de n objetos tomados de r en r es C(n, r), que se lee "n sobre r", y se define como el numero de permutaciones de n objetos tomados de r en r, dividido por el numero de permutaciones de r objetos.

C(n, r) = n! / (r! * (n - r)!)

ejemplo:

- C(4, 2) = 4! / (2! * (4 - 2)!) = 6
- C(5, 3) = 5! / (3! * (5 - 3)!) = 10
- C(6, 4) = 6! / (4! * (6 - 4)!) = 15
- C(7, 5) = 7! / (5! * (7 - 5)!) = 21
- C(8, 6) = 8! / (6! * (8 - 6)!) = 28

## Grafos

Un grafo es un conjunto de vertices y un conjunto de aristas, donde cada arista conecta dos vertices.

Los grafos son una herramienta fundamental en la teoria de grafos, y se utilizan para modelar relaciones entre objetos.

tipo de grafos:

- Grafos no dirigidos: Son grafos en los que las aristas no tienen direccion.
- Grafos dirigidos: Son grafos en los que las aristas tienen direccion.
- Grafos completos: Son grafos en los que todos los vertices estan conectados por aristas.
- Ciclos: Son grafos en los que se puede recorrer un camino cerrado de aristas.
- Matrices de adyacencia: Son matrices que se utilizan para representar grafos.

## Referencias

- Johnsonbaugh, R. (2005). Matemáticas Discretas (7ma ed.). Pearson
Educación de México

- White, R. T., & Tikayat Ray, A. (2021). Practical Discrete
Mathematics. Packt Publishing Ltd

- Halim, S. (2013). Competitive Programming 3.

- Gómez Fuentes, M. del C., & Cervantes Ojeda, J. (2014). Introducción
al análisis y al diseño de algoritmos. Universidad Autónoma
Metropolitana.
