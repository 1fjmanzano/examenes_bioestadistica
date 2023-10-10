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

## Pregunta test

Si una prueba diagnóstica tiene una sensibilidad de del 75% y una especificad del 85% la razón de probabilidad positiva es:

a) 5
b) 10 
c) 2 
d) 8 
e) 15

<button onclick="f4()">Respuesta correcta</button>
<p id="4"></p>
<script>
function f4() {
  document.getElementById("4").innerHTML = "a";
}
</script>

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
dl cociente de probabilidad positivo es del 90%
e) La sensibilidad es el 10%

<button onclick="f6()">Respuesta correcta</button>
<p id="6"></p>
<script>
function f6() {
  document.getElementById("6").innerHTML = "b";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/relaci%C3%B3n-entre-variables-cualitativas.html#diagno%CC%81stico-cli%CC%81nico)

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

## Pregunta test

Si una prueba diagnóstica que tiene una sensibilidad del 90% y una especificidad también del 90% se aplica a una población de 200 individuos con una prevalencia de enfermedad del 50% ¿Cuál será el valor predictivo positivo?

a) 90%
b) 80% 
c) 70% 
d) 60% 
e) 50%

<button onclick="f9()">Respuesta correcta</button>
<p id="9"></p>
<script>
function f9() {
  document.getElementById("9").innerHTML = "a";
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

¿Cuál es la proporción de enfermeros sobre el total?
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

[Explicación](https://es.wikipedia.org/wiki/Valores_predictivos#:~:text=Los%20valores%20predictivos%20(positivo%20y,resultado%20de%20la%20prueba%20diagnóstica.)




