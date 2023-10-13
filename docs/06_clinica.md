# Medidas de importancia clínica.

En este capítulo se resolverán problemas relativos a:

- Diferencias entre Proporción, Tasa, Razón, odds.
- Medidas de asociación en tablas 2x2. Riesgo Relativo. Riesgo Absolutos. Odds-Ratio.
- Indicadores estadísticos básicos para evaluar el desempeño de un procedimiento diagnóstico: Sensibilidad y Especificidad. Probabilidades pre y post prueba.

## Pregunta test

¿Cómo se denomina la medida de epidemiología que indica la probabilidad de que una enfermedad se desarrolle en un grupo de individuos expuesto a un factor de riesgo comparada con la del grupo no expuesto?

a) Incidencia acumulada 
b) Densidad de incidencia 
c) Fracción atribuible
d) Prevalencia
e) Riesgo relativo

<button onclick="f1()">Respuesta correcta</button>
<p id="1"></p>
<script>
function f1() {
  document.getElementById("1").innerHTML = "e";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Riesgo_relativo)

## Pregunta test

En un estudio de casos y controles si se constata asociación estadística mediante la chi- cuadrado clásica ¿Cómo mediremos la magnitud de la asociación?

a) Riesgo relativo
b) Riesgo atribuible
c) Fracción de riesgo atribuible
d) Odds ratio
e) Densidad de incidencia

<button onclick="f2()">Respuesta correcta</button>
<p id="2"></p>
<script>
function f2() {
  document.getElementById("2").innerHTML = "d";
}
</script>

[Explicación](https://www.elsevier.es/es-revista-educacion-medica-71-articulo-el-odds-ratio-su-interpretacion-S1575181317300360)

## Pregunta test

A la capacidad de una prueba diagnóstica para identificar correctamente a los que no padecen la enfermedad se le denomina:

a) Sensibilidad
b) Especificidad
c) Valor predictivo positivo
d) Valor predictivo negativo
e) Razón de probabilidad

<button onclick="f3()">Respuesta correcta</button>
<p id="3"></p>
<script>
function f3() {
  document.getElementById("3").innerHTML = "b";
}
</script>

[Explicacion](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Problema

Si una prueba diagnóstica tiene una sensibilidad  del 75% y una especificidad del 85%, calcule la razón de probabilidad positiva.

### Solución

La razón de probabilidad positiva, también conocido como *cociente de probabilidad positivo* (CPP) o *likelihood ratio* (LR), nos indica cuánto más probable es tener un positivo en la prueba en un enfermo que en un sano. El uso del LR constituye una herramienta de gran utilidad para la toma de decisiones clínicas frente a la solicitud de algún test diagnóstico, porque son valores inherentes a éste e independientes de la prevalencia de la enfermedad. 

Matemáticamente, sería el resultado del cociente:

$\frac{positivos ~ en ~ enfermos}{positivos ~ en ~ sanos}$

Sabemos que:

- la proporción de positivos en los enfermos es la Sensibilidad
- la proporción de los positivos en sanos son los Falsos Positivos que serían aquellos sanos que no dan negativo o, lo que es lo mismo, $1 -$ Especificidad.

Entonces, en nuestro problema:

$CPP= \frac{S}{1-E}= \frac{0.75}{1-0.85}=\frac{0.75}{0.15}=5$

Así, **la razón de probabilidad positiva es 5** lo que indica que en esta prueba diagnóstica, un enfermo tiene 5 veces más posibilidades de dar positivo que un sano.

[Explicación](https://www.elsevier.es/es-revista-revista-argentina-radiologia-383-articulo-likelihood-ratio-razon-verosimilitud-definicion-S0048761916301910)

## Pregunta test

La proporción de enfermos que han dado un resultado negativo en la prueba diagnóstica dividido entre la proporción de sanos que también han dado negativo en dicha prueba se denomina:

a) Razón de probabilidad positiva
b) Valor predictivo negativo
c) Valor predictivo positivo
d) Razón de probabilidad negativa
e) Especificidad

<button onclick="f5()">Respuesta correcta</button>
<p id="5"></p>
<script>
function f5() {
  document.getElementById("5").innerHTML = "d";
}
</script>

[Explicación](https://www.redalyc.org/journal/3555/355568264003/html/)

## Pregunta test

Si al aplicar una prueba diagnóstica se observa un 10% de falsos positivos cuál de las siguientes afirmaciones es cierta:

a) La sensibilidad es el 90%
b) La especificidad es el 90%
c) El valor predictivo positivo es el 90%
d) El cociente de probabilidad positivo es del 90%
e) La sensibilidad es el 10%

<button onclick="f6()">Respuesta correcta</button>
<p id="6"></p>
<script>
function f6() {
  document.getElementById("6").innerHTML = "b";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Problema

Si la probabilidad de tener la enfermedad $A$ es del 5%, la de tener la enfermedad $B$ es del 10% y la de tener al menos una de las dos es del 13%, ¿cúal es la probabilidad de tener las dos?

### Solución

Éste es un típico problema de Probabilidad con sucesos de Bachillerato que se resuelve muy fácilmente recordando la opraciones con sucesos y los Diagramas de Venn:

- $A$ = tener la enfermedad $A$ $P(A)=0.05$
- $B$ = tener la enfermedad $B$ $P(B)=0.10$
- $A \cap B$ = tener las dos enfermedades
- $A \cup B$ = tener, al menos, una de las dos enfermedades $P(A \cup B) = 0.13$

Con un diagrama de Venn:

<img src="img/7_1.png" width="577" />

Así, $P(A \cup B)=P(A)+P(B)-P(A \cap B) \Rightarrow 0.13=0.05 + 0.10 - P(A \cap B)$

de donde

$P(A \cap B)=0.02$

Entonces, **la probabilidad de tener las dos enfermedades es del 2%**.

## Pregunta test

En una prueba diagnóstica es importante determinar:

a) La sensibilidad
b) La especificidad
c) El valor predictivo positivo 
d) Todas son ciertas

<button onclick="f7()">Respuesta correcta</button>
<p id="7"></p>
<script>
function f7() {
  document.getElementById("7").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

Si una prueba diagnóstica se aplica a un grupo de población en el que la prevalencia de la enfermedad es superior a la de la población general aumentará su:

a) Sensibilidad
b) Especificidad
c) Valor predictivo positivo
d) Razón de probabilidad positivo
e) Sensibilidad y especificidad

<button onclick="f8()">Respuesta correcta</button>
<p id="8"></p>
<script>
function f8() {
  document.getElementById("8").innerHTML = "c";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Problema

Si una prueba diagnóstica que tiene una sensibilidad del 90% y una especificidad también del 90% se aplica a una población de 200 individuos con una prevalencia de enfermedad del 50% ¿Cuál será el valor predictivo positivo?

### Solución

Tenemos que recordar que 

$VPP=\frac{Verdaderos ~ positivos}{Total ~ positivos}=\frac{Verdaderos ~ positivos}{Verdaderos ~ positivos ~ + ~ Falsos ~ positivos}$

Vamos a hacer una tabla con los datos del problema. Sabemos que:

|   | Enfermo | Sano |   |
|:-:|:-:|:-:|:-:|
| Positivo (+) |   |   |   |
| Negativo (-) |   |   |   |
|   | 100 | 100 | 200 |

ya que se aplica a una población de 200 individuos con una prevalencia de enfermedad del 50% . Ahora:

- la Sensibilidad es la proporción de enfermos que son diagnosticados como positivos (proporción de verdaderos positivos) por lo que:

$0.90 = \hat{P}(+/E) = \frac{verdaderos ~ positivos}{100}$ de donde el numero de verdaderos positivos es 90.

- la Especificidad es la proporción de sanos diagnosticados como negativos (proporción de verdaderos negativos) por lo que:

$0.90 = \hat{P}(-/S) = \frac{verdaderos ~ negativos}{100}$ de donde el numero de verdaderos negativos es 90.

En la tabla:

|   | Enfermo | Sano |   |
|:-:|:-:|:-:|:-:|
| Positivo (+) |  90 |   |   |
| Negativo (-) |   |  90 |   |
|   | 100 | 100 | 200 |

Terminando de cumplimentar los datos que faltan, tenemos:

|   | Enfermo | Sano |   |
|:-:|:-:|:-:|:-:|
| Positivo (+) |  90 |  10 | 100  |
| Negativo (-) |  10 |  90 |  100 |
|   | 100 | 100 | 200 |

Nos piden el VPP:

$VPP=\frac{Verdaderos ~ positivos}{Total ~ positivos})\frac{90}{100}=0.90$

por lo que **el VPP de la prueba es del 90%**.

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

Cierto tests diagnóstico acierta sobre el 100% de los individuos enfermos y el 50% de los sanos. Cierta persona pasa el test con resultado negativo. Entonces:

a)	Esta sana.
b)	Esta enferma.
c)	Existe una probabilidad del 50% de que esté sana.
d)	Existe una probabilidad del 75% de que esté sana.
e)	Existe una probabilidad del 75% de que esté enferma.

<button onclick="f8_1()">Respuesta correcta</button>
<p id="8_1"></p>
<script>
function f8_1() {
  document.getElementById("8_1").innerHTML = "a";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

Si aplicamos una prueba de laboratorio para el diagnóstico de una determinada enfermedad que es 2 veces más frecuente en hombres que en mujeres ¿Cuál de los siguientes parámetros será más elevado en la población femenina que en la masculina?

a) La prevalencia de la enfermedad
b) La sensibilidad de la prueba
c) La especificidad de la prueba
d) El valor predictivo positivo de la prueba
e) El valor predictivo negativo de la prueba

<button onclick="f10()">Respuesta correcta</button>
<p id="10"></p>
<script>
function f10() {
  document.getElementById("10").innerHTML = "a";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

¿Cómo se calcula la sensibilidad de un test diagnóstico?

a)	Contabilizando el número de tests positivos en una muestra aleatoria de individuos.
b)	Contabilizando el número de tests negativos en una muestra aleatoria de individuos.
c)	Contabilizando el número de tests positivos en una muestra aleatoria de enfermos.
d)	Contabilizando el número de tests negativos en una muestra aleatoria de sanos.
e)	Ninguna de las anteriores es cierta.

<button onclick="f10_1()">Respuesta correcta</button>
<p id="10_1"></p>
<script>
function f10_1() {
  document.getElementById("10_1").innerHTML = "c";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

¿Cuál es la proporción de enfermos sobre el total?

a) La prevalencia
b) La incidencia
c) El total de positivos para el test
d) El valor predictivo
e) El total de las personas estudiadas

<button onclick="f11()">Respuesta correcta</button>
<p id="11"></p>
<script>
function f11() {
  document.getElementById("11").innerHTML = "a";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

Cierto test diagnóstico acierta sobre el 100% de los individuos sanos y el 0% de los individuos enfermos. Elegida una persona al azar:

a)	Hay una probabilidad del 50% de que esté enferma.
b)	Hay una probabilidad del 0% de que esté enferma.
c)	Hay una probabilidad del 100% de que esté enferma.
d)	El test será negativo.
e) Ninguna de las anteriores es cierta.

<button onclick="f11_1()">Respuesta correcta</button>
<p id="11_1"></p>
<script>
function f11_1() {
  document.getElementById("11_1").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

El parámetro que mide la fuerza de asociación entre la exposición y la enfermedad se denomina:

a) Factor de riesgo
b) Riesgo atribuible
c) Factor protector
d) Riesgo relativo

<button onclick="f12()">Respuesta correcta</button>
<p id="12"></p>
<script>
function f12() {
  document.getElementById("12").innerHTML = "d";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Riesgo_relativo)

## Pregunta test

En una población, hay tantos hombres como mujeres, el 20% son varones y fumadores y el 20% de las mujeres fuman. Entonces:

a)	Fuman tantos hombres como mujeres.
b)	Por cada mujer fumadora hay dos hombres fumadores.
c)	Por cada hombre fumador hay dos mujeres fumadoras.
d)	Hay un 40% de fumadores en la población.
e)	Nada de lo anterior es cierto.

<button onclick="f12_1()">Respuesta correcta</button>
<p id="12_1"></p>
<script>
function f12_1() {
  document.getElementById("12_1").innerHTML = "b";
}
</script>

**Explicación**

Con los datos del problema, tenemos:

|   | Hombre | Mujer |   |
|:-:|:-:|:-:|:-:|
| Fuma (+) |  20 | 10  |   |
| No fuma (-) |  |  |  |
|   | 50 | 50 | 100|

(El 20% de las mujeres fuman, el 20% del 50% es 10)

## Pregunta test

Para conocer el exceso de riesgo en los individuos expuestos comparando con los no expuestos utilizaremos:

a) Riesgo relativo
b) Diferencia de incidencias
c) Odds ratio
d) Incidencia acumulada
e) Riesgo atribuible

<button onclick="f13()">Respuesta correcta</button>
<p id="13"></p>
<script>
function f13() {
  document.getElementById("13").innerHTML = "e";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Riesgo_atribuible)

## Pregunta test

Para estudiar la efectividad de un test diagnóstico ante una enfermedad se toma un grupo de 200 personas enfermas y 200 que no la padecen, y se observan los resultados. ¿Qué podemos estimar directamente de ellos?

a)	La sensibilidad y especificidad del test.
b)	La incidencia de la enfermedad en la población.
c)	El índice predictivo de verdaderos positivos.
d)	Son correctas (a) y (c).
e)	Todo lo anterior.

<button onclick="f13_1()">Respuesta correcta</button>
<p id="13_1"></p>
<script>
function f13_1() {
  document.getElementById("13_1").innerHTML = "a";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

¿Cuál de las siguientes medidas utilizaría para cuantificar el imparto potencial de un programa preventivo en la población?

a) Riesgo relativo
b) Odds ratio
c) Razón de prevalencia
d) Disminución de la prevalencia
e) Riesgo atribuible

<button onclick="f14()">Respuesta correcta</button>
<p id="14"></p>
<script>
function f14() {
  document.getElementById("14").innerHTML = "e";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Riesgo_atribuible)

## Pregunta test

El porcentaje de individuos fumadores o con bronquitis se puede interpretar como una probabilidad:

a)	De un suceso intersección
b)	Condicionada.
c)	De un suceso unión.
d)	A posteriori.
e)	De un suceso complementario.

<button onclick="f14_1()">Respuesta correcta</button>
<p id="14_1"></p>
<script>
function f14_1() {
  document.getElementById("14_1").innerHTML = "c";
}
</script>

[Explicación](https://www.um.es/documents/4874468/11785083/tema-4.pdf/6d391656-5f98-49e4-b8b7-1d8d38767b7e)

## Pregunta test

El porcentaje de individuos con bronquitis entre los fumadores se puede interpretar como una probabilidad:

a) De un suceso intersección
b) Condicionada.
c) De un suceso unión.
d) A posteriori.
e) De un suceso complementario.

<button onclick="f14_2()">Respuesta correcta</button>
<p id="14_2"></p>
<script>
function f14_2() {
  document.getElementById("14_2").innerHTML = "b";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Probabilidad_condicionada)

## Pregunta test

El porcentaje de individuos con bronquitis que además son fumadores se puede interpretar como una probabilidad:

a)	De un suceso intersección
b)	Condicionada.
c)	De un suceso unión.
d)	A posteriori.
e)	De un suceso complementario.

<button onclick="f14_3()">Respuesta correcta</button>
<p id="14_3"></p>
<script>
function f14_3() {
  document.getElementById("14_3").innerHTML = "a";
}
</script>

[Explicación](https://www.um.es/documents/4874468/11785083/tema-4.pdf/6d391656-5f98-49e4-b8b7-1d8d38767b7e)

## Problema

El 12% de los individuos de una población padece osteoporosis. EL 25% de ellos lo sabe. ¿Qué tasa de individuos tiene osteoporosis y lo desconoce?

### Solución

Si el 25% de los que tienen osteoporosis lo sabe, el 75% de los que tienen osteoporosis lo desconoce. Por lo tanto, la tasa de individuos que tiene osteoporosis y lo desconoce será el 75% del 12%, es decir, $0.75 \cdot 0.12 = 0.09$. Entonces, **la tasa de individuos que tiene osteoporosis y lo desconoce es del 9%**.

## Pregunta test

¿Cómo se denomina la proporción de enfermos que presentan un resultado positivo de un método diagnostico?

a) Valor predictivo positivo del método
b) Valor predictivo negativo del método
c) Especificidad del método
d) Razón de probabilidad positiva
e) Ninguna de las anteriores

<button onclick="f15()">Respuesta correcta</button>
<p id="15"></p>
<script>
function f15() {
  document.getElementById("15").innerHTML = "e";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

Una prueba con alta sensibilidad:

a) Presenta pocos falsos negativos
b) Presenta pocos falsos positivos
c) Tiene una p < 0’05
d) Necesariamente tiene una especificidad alta 
e) Presenta muchos falsos positivos

<button onclick="f16()">Respuesta correcta</button>
<p id="16"></p>
<script>
function f16() {
  document.getElementById("16").innerHTML = "a";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

La probabilidad de que un individuo tomado aleatoriamente en una serie de sujetos de estudio tenga un resultado negativo en las pruebas diagnosticas si realmente no tiene la enfermedad se denomina:

a) Sensibilidad
b) Especificidad
c) Proporción de falsos negativos
d) Proporción de falsos positivos
e) Valor predictivo negativo

<button onclick="f17()">Respuesta correcta</button>
<p id="17"></p>
<script>
function f17() {
  document.getElementById("17").innerHTML = "c";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Problema

La osteoporosis afecta 4 veces más a mujeres que a hombres. El 8% de las mujeres padece osteoporosis en una población donde hay tantos hombres como mujeres. ¿Cuál es la prevalencia de la osteoporosis en la población?

### Solución

Hagamos una tabla con los datos:

|   | Hombres | Mujeres |   |
|:-:|:-:|:-:|:-:|
| Osteoporosis (+) | 1  | 4  |   |
| No Osteoporosis (-) |   |   |   |
|   | 50 | 50 | 100 |

ya que el 50% son mujeres y el 8% padece osteoporosis ($0.08 \cdot 0.50 = 0.04$) y los hombres que padecen de osteoporosis son la cuarta parte que las mujeres.

Si completamos la tabla:

|   | Hombres | Mujeres |   |
|:-:|:-:|:-:|:-:|
| Osteoporosis (+) | 1  | 4  | 5  |
| No Osteoporosis (-) | 49  | 46  | 95  |
|   | 50 | 50 | 100 |

por lo que **la prevalencia de la osteoporosis en la población es del 5%**

## Pregunta test

Para conocer los índices (valores) predictivos en un test diagnóstico para una enfermedad que tiene un 1% de afectados en la población, será necesario conocer:

a)	Sensibilidad y verdaderos positivos
b)	Prevalencia.
c)	Verdaderos positivos y prevalencia.
d)	Especificidad y verdaderos negativos
e)	Falsos positivos y verdaderos positivos.

<button onclick="f18()">Respuesta correcta</button>
<p id="18"></p>
<script>
function f18() {
  document.getElementById("18").innerHTML = "e";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Valores_predictivos)

## Pregunta test

Elija la afirmación correcta relativa a pruebas diagnósticas:

a)	La sensibilidad se obtiene usando la noción subjetiva de probabilidad.
b)	El índice predictivo positivo se obtiene directamente de la noción frecuentista de probabilidad.
c)	La tasa de verdaderos positivos se obtiene directamente de la noción frecuentista de probabilidad.
d)	La prevalencia de la enfermedad se obtiene a partir del teorema de Bayes.
e)	nada de lo anterior es cierto.

<button onclick="f19()">Respuesta correcta</button>
<p id="19"></p>
<script>
function f19() {
  document.getElementById("19").innerHTML = "c";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Pregunta test

El 2% de la población padece diabetes. Si de ellos, el 30% no está diagnósticado, esta cantidad puede entenderse como una probabilidad...

a)	De un suceso intersección
b)	Condicionada.
c)	De un suceso unión.
d)	A posteriori.
e)	De un suceso complementario.

<button onclick="f20()">Respuesta correcta</button>
<p id="20"></p>
<script>
function f20() {
  document.getElementById("20").innerHTML = "b";
}
</script>

[Explicación](https://es.wikipedia.org/wiki/Probabilidad_condicionada)

## Problema

En una población, el 5% son enfermos diagnosticados de una enfermedad, la cual padece el 10% de la población. Calcular la probabilidad de estar diagnósticado para un individuo enfermo.

### Solución

Éste es un problema de probabilidad condicionada. [Recordamos](https://es.wikipedia.org/wiki/Probabilidad_condicionada):

$P(A/B)=\frac{P(A \cap B)}{P(B)}$

En nuestro caso:

- $E$ = estar enfermo $P(E)=0.10$
- $D$ = estar diagnosticado
- $E \cap D$ = estar enfermo y diagnosticado $P(E \cap D) = 0.05$

Se pide calcular la probabilidad de estar diagnósticado para un individuo enfermo, es decir, $P(D/E)$. Entonces:

$P(D/E)=\frac{P(D \cap E)}{P(E)}= \frac{0.05}{0.10}=0.50$

Así, **la probabilidad de estar diagnósticado para un individuo enfermo es del 50%**.

## Pregunta test

Una prueba diagnóstica de cierta enfermedad, tiene una tasa de aciertos del 90% tanto sobre enfermos como sanos. La incidencia de la enfermedad en la población es del 50%. Si se pasa el test a una persona y sale positivo, la probabilidad de que realmente esté enferma es:

a)	45%
b)	50%
c)	75%
d)	90%
e)	100%

<button onclick="f21()">Respuesta correcta</button>
<p id="21"></p>
<script>
function f21() {
  document.getElementById("21").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

## Problema

Una enfermedad tiene una incidencia del 50% en la población. Un test para detectarla posee una tasa de verdaderos positivos del 80%, y de falsos positivos del 20%. Si un individuo resulta ser positivo, calcular la probabilidad de que esté enfermo.

### Solución

En este caso, vamos a hacer una tabla de contingencia con los datos para 200 individuos:

|   | Enfermo (E) | Sano (S) |   |
|:-:|:-:|:-:|:-:|
| Positivo (+) | 80  | 20  |   |
| Negativo (-) |   |   |   |
|   | 100 | 100 | 200 |

Si completamos la tabla:

|   | Enfermo (E) | Sano (S) |   |
|:-:|:-:|:-:|:-:|
| Positivo (+) | 80  | 20  | 100  |
| Negativo (-) |  20 | 80  | 100  |
|   | 100 | 100 | 200 |

Se pide que, si un individuo resulta ser positivo, calcular la probabilidad de que esté enfermo, es decir $P(E/+)= \frac{80}{100}=0.80$. 

Entonces **Si un individuo resulta ser positivo, la probabilidad de que esté enfermo es del 80%**.

## Pregunta test

En una población el 30% son hombres de los cuales son deportistas el 20%, frente al 25% de las mujeres. Escogida una persona al azar es deportista. La probabilidad de que sea mujer es (aproximadamente):

a)	$0,235$
b)	$0,60$
c)	$0,74$
d)	$0,25$
e)	No puede calcularse con esos datos.

<button onclick="f22()">Respuesta correcta</button>
<p id="22"></p>
<script>
function f22() {
  document.getElementById("22").innerHTML = "c";
}
</script>

