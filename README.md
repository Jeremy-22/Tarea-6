# Funciones, Modelos personalizados y Ecuaciones Diferenciales


Diseñar una capa en keras que transforme imágenes a color en escala degrises.
<br>
Al diseñar esta capa no tuve problema, aunque no la realize como se hizo en clase, pude obtener buenos resultados.
<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Tarea-6/blob/main/RGBaBN.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>

 ---

 Entrena una red neuronal para que reproduzca las siguientes funciones en el  intervalo  de  [-1,1].   Graficar  la  solución  de  la  red  en  conjunto  con  la gráfica de la función.
<br>
 (a)  $$3 sin(\pi x)$$
<br>
 (b) $$1 + 2x+ 4x^{3}$$
<br>
<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Tarea-6/blob/main/Funciones.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>
Con respecto a este ejercicio no tuve problema alguno, sin embargo, hice varias pruebas y la mejor es la que presento. Cuando termine de realizar todos los ejercicios vi que teniamos que tomar captura de todos los intentos, por esto mismo en lo que resta del reporte no habra evidencia de todos los intentos realizados.

---

Diseñar una capa entrenable que represente un polinomio grado 3: $$ f(x) =a0+a1x+a2x2+a3x3$$.  Los parámetros entrenables son los coeficientes $$ a0,a1,a2,a3$$. Posteriormente, entrenarla para ajustarla a la función $$ f(x) =cos(2x)$$ en el intervalo [-1,1].

<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Tarea-6/blob/main/CapyFu.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>

Al entrenar esta red, la grafica de la función de costo me dio una recta, sin embargo, al aumentar el numero de de capas y de neuronas obtuve un mejor resultado, con respecto al esperado.
<br>
<center>
<p align="center">
  <img src="fc.png" />
</p>
</center>
<br>

---

Entrenar una red neuronal que de la soluci ́on de las siguientes ecuaciones diferenciales en el intervalo [-5,5].  Graficar la solución numérica junto con la solución analítica.
<br>
(a) $$xy′+y=x2cosx$$ con $$y(0) = 0$$
<br>
(b) $$d2ydx2=−y$$ con $$y(0) = 1$$, $$y'(0) =−0.5$$
<br>
<center>
  <h4>Código de la red:</h4>
  <a href="https://github.com/Jeremy-22/Tarea-6/blob/main/SolED.ipynb" target="_blank">
    <img width="20%" src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</center>
<br>
Para este caso, tuve un problema al copilar pero no se a que se debió, sin embargo al copiar todo y pegarlo en otro archivo ya funciono, por otra parte, tuve que hacer varios intentos para llegar a la solucion esperada, tuve que hacer algo similar a lo anterior, aumentar el numero de capas, empezando con 20 neuronas, fui aumentando hasta llegar a las 150 y apatir de ahí fui disminuyendo hasta que llegue a la ultima capa de una neurona, con esto puedo obtener un buen resultado. A continucaión muestro el primer resultado antes de aumentar neuronas.
<br>
<center>
<p align="center">
  <img src="gf.png" />
</p>
</center>
<br>

### Atribuciones

- Este repositorio cuenta con una  [GNU License](https://github.com/Jeremy-22/RN/blob/main/LICENSE).
