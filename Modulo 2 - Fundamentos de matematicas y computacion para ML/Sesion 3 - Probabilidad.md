# Probabilidad

## Experimento aleatorio

Un experimento aleatorio es un proceso que produce un resultado no predecible, es decir, no se puede predecir con certeza el resultado de un experimento aleatorio. Por ejemplo, lanzar un dado, lanzar una moneda, el resultado de un partido de futbol, el resultado de un examen, etc.

## Espacio muestral

El espacio muestral de un experimento aleatorio es el conjunto de todos los posibles resultados del experimento. Por ejemplo, el espacio muestral de lanzar un dado es {1, 2, 3, 4, 5, 6}, y el espacio muestral de lanzar una moneda es {cara, sello}.

## Evento

Un evento es un subconjunto del espacio muestral, es decir, es un conjunto de posibles resultados del experimento. Por ejemplo, el evento de obtener un numero par al lanzar un dado es {2, 4, 6}, y el evento de obtener cara al lanzar una moneda es {cara}.

## Ley DeMorgan

La ley DeMorgan establece que la negacion de la union de dos conjuntos es igual a la interseccion de las negaciones de los conjuntos, y la negacion de la interseccion de dos conjuntos es igual a la union de las negaciones de los conjuntos.

La ley DeMorgan se puede expresar de la siguiente manera:

- La negacion de la union de dos conjuntos A y B es igual a la interseccion de las negaciones de los conjuntos A y B:

  - ¬(A ∪ B) = ¬A ∩ ¬B

- La negacion de la interseccion de dos conjuntos A y B es igual a la union de las negaciones de los conjuntos A y B:

  - ¬(A ∩ B) = ¬A ∪ ¬B

## Formula de Laplace

La formula de Laplace se utiliza para calcular la probabilidad de un evento, y se define como el cociente entre el numero de casos favorables y el numero de casos posibles.

La formula de Laplace se puede expresar de la siguiente manera:

- La probabilidad de un evento A es igual al cociente entre el numero de casos favorables y el numero de casos posibles:

  - P(A) = n(A) / n(S)

Donde:

- P(A) es la probabilidad del evento A.
- n(A) es el numero de casos favorables del evento A.
- n(S) es el numero de casos posibles del espacio muestral.

## Probabilidad condicional

La probabilidad condicional de un evento A dado un evento B es el cociente entre la probabilidad de la interseccion de los eventos A y B, y la probabilidad del evento B.

La probabilidad condicional se puede expresar de la siguiente manera:

- La probabilidad del evento A dado el evento B es igual al cociente entre la probabilidad de la interseccion de los eventos A y B, y la probabilidad del evento B:

  - P(A|B) = P(A ∩ B) / P(B)

Donde:

- P(A|B) es la probabilidad del evento A dado el evento B.
- P(A ∩ B) es la probabilidad de la interseccion de los eventos A y B.
- P(B) es la probabilidad del evento B.

## Independencia de eventos

Dos eventos A y B son independientes si la probabilidad de la interseccion de los eventos A y B es igual al producto de las probabilidades de los eventos A y B.

La independencia de eventos se puede expresar de la siguiente manera:

- Dos eventos A y B son independientes si la probabilidad de la interseccion de los eventos A y B es igual al producto de las probabilidades de los eventos A y B:

  - P(A ∩ B) = P(A) * P(B)

Donde:

- P(A ∩ B) es la probabilidad de la interseccion de los eventos A y B.
- P(A) es la probabilidad del evento A.
- P(B) es la probabilidad del evento B.

## Teorema de Bayes

El teorema de Bayes se utiliza para calcular la probabilidad de un evento A dado un evento B, y se define como el cociente entre la probabilidad del evento B dado el evento A, y la probabilidad del evento B.

El teorema de Bayes se puede expresar de la siguiente manera:

- La probabilidad del evento A dado el evento B es igual al cociente entre la probabilidad del evento B dado el evento A, y la probabilidad del evento B:

  - P(A|B) = P(B|A) * P(A) / P(B)

Donde:

- P(A|B) es la probabilidad del evento A dado el evento B.
- P(B|A) es la probabilidad del evento B dado el evento A.
- P(A) es la probabilidad del evento A.
- P(B) es la probabilidad del evento B.

## Clasificador naive bayes

El clasificador naive bayes es un modelo de clasificacion que se basa en el teorema de Bayes para calcular la probabilidad de que un dato pertenezca a una clase, y se define como el producto de las probabilidades condicionales de los atributos del dato dado la clase.

El clasificador naive bayes se puede expresar de la siguiente manera:

- La probabilidad de que un dato x pertenezca a una clase c es igual al producto de las probabilidades condicionales de los atributos del dato x dado la clase c:

  - P(c|x) = P(x1|c) *P(x2|c)* ... *P(xn|c)* P(c)

Donde:

- P(c|x) es la probabilidad de que el dato x pertenezca a la clase c.
- P(x1|c) es la probabilidad condicional del atributo x1 dado la clase c.
- P(x2|c) es la probabilidad condicional del atributo x2 dado la clase c.
- P(xn|c) es la probabilidad condicional del atributo xn dado la clase c.
- P(c) es la probabilidad de la clase c.

## Mediciones de tendencia central asimetrica y variabilidad

Las mediciones de tendencia central asimetrica y variabilidad se utilizan para describir la distribucion de los datos, y se definen como la media, la mediana, la moda, la varianza, la desviacion estandar, y el coeficiente de variacion.

Las mediciones de tendencia central asimetrica y variabilidad se pueden expresar de la siguiente manera:

- La media es el promedio de los datos.

- La mediana es el valor que divide a los datos en dos partes iguales.

- La moda es el valor que aparece con mayor frecuencia en los datos.

- La varianza es la media de los cuadrados de las diferencias entre los datos y la media.

- La desviacion estandar es la raiz cuadrada de la varianza.

- El coeficiente de variacion es la desviacion estandar dividida por la media.

## Distribucion normal

La distribucion normal es una distribucion de probabilidad que se utiliza para modelar la distribucion de los datos, y se define por su media y su desviacion estandar.

## Varianza y desviacion estandar

La varianza y la desviacion estandar son mediciones de variabilidad que se utilizan para describir la distribucion de los datos, y se definen como la media de los cuadrados de las diferencias entre los datos y la media, y la raiz cuadrada de la varianza, respectivamente.

## Estadistica inferencial

La estadistica inferencial es una rama de la estadistica que se utiliza para hacer inferencias acerca de una poblacion a partir de una muestra, y se define por su media y su desviacion estandar.

## Skewness y kurtosis

La skewness y la kurtosis son mediciones de asimetria y apuntamiento que se utilizan para describir la distribucion de los datos, y se definen como la tercera y la cuarta potencia de las diferencias entre los datos y la media, respectivamente.

## Prueba de hipotesis

La prueba de hipotesis es un procedimiento que se utiliza para hacer inferencias acerca de una poblacion a partir de una muestra, y se define por su media y su desviacion estandar.

## Tipos de hipotesis

Los tipos de hipotesis son la hipotesis nula y la hipotesis alternativa, y se definen como la hipotesis de que no hay diferencia entre dos grupos, y la hipotesis de que hay diferencia entre dos grupos, respectivamente.

### Hipotesis nula

La hipotesis nula es la hipotesis de que no hay diferencia entre dos grupos.

### Hipotesis alternativa

La hipotesis alternativa es la hipotesis de que hay diferencia entre dos grupos.

## Referencias

Event Space
<https://www.youtube.com/watch?v=4wV9xGJXFjg&t=388s>

Conditional Probability
<https://www.youtube.com/watch?v=ibINrxJLvlM>

Bayes
<https://www.youtube.com/watch?v=XQoLVl31ZfQ&t=257s>

<https://www.analyticsvidhya.com/blog/2017/03/conditional-probability-bayes>
-theorem/
<https://rohanmandrekar.netlify.app/post/sentiment-analysis/>
