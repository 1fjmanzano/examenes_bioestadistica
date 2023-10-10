# Análisis Inferencial. Aplicaciones.

En este capítulo se resolverán problemas relativos a:

- Objetivos del estudio, hipótesis de trabajo e hipótesis estadísticas
- Importancia de las distribuciones de probabilidad en el trabajo práctico
- Estimación puntual y por intervalo
- Verificación de las hipótesis de trabajo: contraste de hipótesis

## Pregunta test

En relación a las técnicas de inferencia estadística, elija la afirmación correcta:

a)	La media poblacional es una estimación puntual.
b)	La media muestral es un parámetro.
c)	Sólo se rechaza una hipótesis nula si esta es falsa.
d)	Un intervalo de confianza es una estimación confidencial de un parámetro.
e)	Todo lo anterior es falso

<button onclick="f1()">Respuesta correcta</button>
<p id="1"></p>
<script>
function f1() {
  document.getElementById("1").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/estimacio%CC%81n-de-para%CC%81metros.-intervalos-de-confianza.html)

## Pregunta test

Una estimación confidencial para un nivel de confianza fijado, da por respuesta:

a)	Una aproximación de la media.
b)	Una aproximación de una proporción.
c)	Una probabilidad.
d)	Un intervalo.
e)	Un nivel de significación.

<button onclick="f2()">Respuesta correcta</button>
<p id="2"></p>
<script>
function f2() {
  document.getElementById("2").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/estimacio%CC%81n-de-para%CC%81metros.-intervalos-de-confianza.html)

## Pregunta test

El perímetro torácico en un grupo de militares presenta distribución gaussiana con 95 cm de media y 5 cm de desviación típica. Elegimos a una muestra de 100 indivíduos y calculamos la media de la misma. Elija la afirmación correcta:

a)	La media de la muestra valdrá 95 cm.
b)	La media de la muestra sería un valor comprendido entre 90 y 100 cm con confianza del 68%.
c)	La media de la muestra será un valor comprendido entre 95 y 100 cm con confianza del 95%.
d)	La media de la muestra será un valor comprendido entre 94 y 96 cm con confianza del 95%.
e)	Todo lo anterior es falso.

<button onclick="f3()">Respuesta correcta</button>
<p id="3"></p>
<script>
function f3() {
  document.getElementById("3").innerHTML = "d";
}
</script>

**Explicación** 

Consideramos la variable aleatoria

$X$ = perímetro torácico en un grupo de militares $X \equiv N(95, 5)$

El intervalo de confianza para la media muestral $\overline{x}$ al 95% será:

$\mu \pm z_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}}$

Para una confianza del 95%, $z_{\alpha/2} = 1.96$ ([ver vídeo](https://youtu.be/wWeogWp_bO8)) de donde:

$\mu \pm z_{\alpha/2} \cdot \frac{\sigma}{\sqrt{n}}= 95 = 95 \pm 1.95 \cdot \frac{5}{\sqrt{100}}= (94.02002,95.97998) \approx (94, 96)$

Se puede comprobar el resultado utilizando el applet [Probability Distributios: Statistical Inference for $\mu$](https://homepage.divms.uiowa.edu/~mbognar/applets/mu.raw.html) introduciendo los valores $n=100$, $\overline{x}=95$ y $\sigma = 5$ con $95$ % de CI (confidence Interval) y activando la opción *Show equations*.

## Pregunta test

El consumo diario de Calorías se distribuye en una población de forma normal, con media 2500 y desviación típica 100. Si elijo una muestra de tamaño 100, entre qué valores espero encontrar su media (con una probabilidad del 95% de acertar):

a)	Entre 2400 y 2600.
b)	Entre 2300 y 2700.
c)	Entre 2490 y 2510.
d)	Entre 2480 y 2520.
e)	Entre 2498 y 2502.

<button onclick="f4()">Respuesta correcta</button>
<p id="4"></p>
<script>
function f4() {
  document.getElementById("4").innerHTML = "d";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/)

## Pregunta test

En una muestra aleatoria de 100 individuos se obtiene una media muestral de 50, la desviación típica es 20. Elija la afirmación correcta:

a)	El 68% de los individuos de la muestra tiene sus valores comprendidos entre 48 y 52.
b)	El 95% de los individuos de la muestra tiene sus valores comprendidos entre 46 y 54.
c)	Hay una probabilidad del 68% de que la media de la población esté comprendida entre 30 y 70.
d)	Hay una probabilidad del 95% de que la media de la población esté entre 46 y 54.
e)	Todo lo anterior es falso.

<button onclick="f5()">Respuesta correcta</button>
<p id="5"></p>
<script>
function f5() {
  document.getElementById("5").innerHTML = "d";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/)

## Pregunta test

Una muestra aleatoria de 64 pacientes refleja que el presión arterial diastólica media es 150 (DT 16), con distribución aproximadamente normal. Elija la afirmación correcta.

a)	La media de la población está con confianza del 95% entre 134 y 166
b)	La media de la población está con confianza del 68% entre 142 y 158
c)	La media de la población está con confianza del 95% entre 148 y 152
d)	La media de la población está con confianza del 95% entre 146 y 154
e)	El error típico es de 1 punto.

<button onclick="f6()">Respuesta correcta</button>
<p id="6"></p>
<script>
function f6() {
  document.getElementById("6").innerHTML = "d";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/)

## Pregunta test

Qúe propiedad o propiedades caracterizan a una distribución normal tipificada frente a una distribución normal cualquiera:

a)	El área bajo su función de densidad es igual a 1.
b)	Su media es 1 y su desviación típica es 0.
c)	Su rango de valores oscila entre 0 y 3.
d)	Su media es 0 y su desviación típica es 1.
e)	Son ciertas (c) y (d)

<button onclick="f7()">Respuesta correcta</button>
<p id="7"></p>
<script>
function f7() {
  document.getElementById("7").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/distribuciones-de-probabilidad.html#distribucio%CC%81n-z)


## Pregunta test

En una población, el peso tiene media 60 kg y desviación típica 6 Kg. La altura tiene de media 170 cm y desviación 6 cm. Cierto individuo tiene un peso de 70 Kg y altura 180 cm.

a)	La altura tiene un valor más extremo que el peso.
b)	El peso es menos extremo que la altura.
c)	Peso y altura son valores igualmente extremos.
d)	El peso es más extremo que la altura.
e)	La altura es menos extrema que el peso.

<button onclick="f8()">Respuesta correcta</button>
<p id="8"></p>
<script>
function f8() {
  document.getElementById("8").innerHTML = "c";
}
</script>

**Explicación**

En este caso debemos comparar valores en 2 variables normales (o gaussianas):

- Peso $\equiv N(60, 6)$ para un valor de 70 kg.
- Altura $\equiv N(170, 6)$ para un valor de 180 cm.

Podemos hacerlo con una tabla ([ver vídeo](https://youtu.be/xCBUdpIUx18)) o usando Excel@ o una app específica. ([ver vídeo](https://youtu.be/rxkPlU1Ud7c)).

Utilizando la aplicación [Probability Distributions: Normal Distribution](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html), obtenemos la probabilidad de pesar menos de 70 kg:

<img src="img/3_1.png" width="748" />

y la probabilidad de medir menos de 180 cm:

<img src="img/3_1.png" width="748" />

En ambos casos, la probabilidad es $0.95221$

## Pregunta test

El nivel medio de glucemia en una población tiene un comportamiento gausiano con media 150mg/dl, y un coeficiente de variación del 10%. Entre qué valores se situa el 95% de los individuos de la población.

a)	Entre 140 y 160.
b)	Entre 130 y 170.
c)	Entre 120 y 180.
d)	Entre 110 y 190.
e)	Entre 100 y 200.

<button onclick="f9()">Respuesta correcta</button>
<p id="9"></p>
<script>
function f9() {
  document.getElementById("9").innerHTML = "c";
}
</script>

**Explicación**

En este caso, nos dan el coeficiente de variación, $CV=\frac{\sigma}{\overline{x}}$. Entonces:

$0.10 = \frac{\sigma}{150} \Rightarrow \sigma = 15$

Así la variable $X$ = nivel medio de glucemia $\equiv N(150, 15)$.

En una distribución normal, el 95% de los datos están en el intervalo $\mu \pm 2  \sigma= 150 \pm 30 = (120,180)$

## Pregunta test

La concentración de calcio se comporta en los mamíferos como una distribución normal de media 10 y desviación típica 2. ¿Con qué frecuencia se encuentran mamíferos con una concentración superior a 14?

a)	95%
b)	68%
c)	50%
d)	5%
e)	2,5%

<button onclick="f10()">Respuesta correcta</button>
<p id="10"></p>
<script>
function f10() {
  document.getElementById("10").innerHTML = "e";
}
</script>

**Explicación**

Con [Probability Distributions: Normal Distribution](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html) tenemos:

<img src="img/3_3.png" width="748" />

## Pregunta test

El IMC se distribuye en una población de forma normal. El 95% central de los individuos tiene un IMC comprendido entre 20 y 24. Entonces:

a)	La media es 22.
b)	La desviación típica es 1.
c)	La curtosis es cero.
d)	Todas las anteriores son correctas.
e)	Sólo dos de las anteriores son correctas.

<button onclick="f11()">Respuesta correcta</button>
<p id="11"></p>
<script>
function f11() {
  document.getElementById("11").innerHTML = "d";
}
</script>

[Explicación](https://1fjmanzano.github.io/bioestadistica/distribuciones-de-probabilidad.html#distribucio%CC%81n-normal)

## Problema

El tiempo que los empleados de una oficina tardan en completar una tarea específica sigue una distribución normal con una media de 45 minutos y una desviación típica de 5 minutos. ¿Cuál es el tiempo que separa aproximadamente al 16% más rápido de los empleados del resto?

### Explicación

Este es un problema de distribución normal inversa [Ver vídeo](https://youtu.be/BqGHUqC4cdQ). 

Si utilizamos la aplicación [Probability Distributios: Normal Distribution](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html) no tenemos más que introducir los valores $\mu = 45$, $\sigma = 5$ y $P(X > x)= 0.16$ para obtener un valor de $x = 49.97229 \ approx 50$.

Entonces, **l tiempo que separa aproximadamente al 16% más rápido de los empleados del resto es de 50 minutos**.

## Pregunta test

Los ingresos de un grupo de personas siguen una distribución normal con una media de 50,000 € y una desviación típica de 10,000 €. ¿Cuál es el rango aproximado de ingresos que abarca al 95% de las personas en este grupo?

a	Entre 30,000€ y 70,000€
b	Entre 20,000€ y 80,000€
c	Entre 40,000€ y 60,000€
d	Entre 10,000€ y 90,000€
e	Entre 50,000€ y 100,000€

<button onclick="f12()">Respuesta correcta</button>
<p id="12"></p>
<script>
function f12() {
  document.getElementById("12").innerHTML = "a";
}
</script>

[Explicación](https://youtu.be/TjZvZVxItLc)

## Pregunta test

La cantidad de tiempo que los estudiantes tardan en completar un examen sigue una distribución normal con una media de 120 minutos y una desviación típica de 20 minutos. ¿Qué porcentaje de estudiantes termina el examen en menos de 100 minutos?

a)	2.5%
b)	5%
c)	16%
d)	34%
e)	50%

<button onclick="f13()">Respuesta correcta</button>
<p id="13"></p>
<script>
function f13() {
  document.getElementById("13").innerHTML = "c";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html)

## Pregunta test

La duración de las llamadas en un centro de atención al cliente sigue una distribución normal con una media de 8 minutos y una desviación típica de 2 minutos. ¿Cuál es el tiempo que separa aproximadamente al 2.5% de las llamadas más cortas del resto?

a)	2 minutos
b)	4 minutos
c)	6 minutos
d)	10 minutos
e)	12 minutos

<button onclick="f14()">Respuesta correcta</button>
<p id="14"></p>
<script>
function f14() {
  document.getElementById("14").innerHTML = "b";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html)

## Pregunta test

En una población de estudiantes, las calificaciones en matemáticas tienen una media de 75 y una desviación típica de 10, mientras que las calificaciones en ciencias tienen una media de 80 y una desviación típica de 5. Un estudiante obtiene una calificación de 90 en matemáticas y 85 en ciencias. ¿Cuál de las siguientes afirmaciones es correcta?

a)	La calificación de matemáticas es más extrema que la de ciencias.
b)	La calificación de ciencias es más extrema que la de matemáticas.
c)	Las calificaciones de matemáticas y ciencias son igualmente extremas.
d)	La calificación de matemáticas es menos extrema que la de ciencias.
e)	No se pueden comparar ambas calificaciones.

<button onclick="f15()">Respuesta correcta</button>
<p id="15"></p>
<script>
function f15() {
  document.getElementById("15").innerHTML = "a";
}
</script>

[Explicación](https://homepage.divms.uiowa.edu/~mbognar/applets/normal.html)
