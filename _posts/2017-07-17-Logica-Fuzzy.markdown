---
layout:     post
title:      "Intenigencia Artificial Lógica Fuzzy "
subtitle:   "Lógica Fuzzy."
date:       2017-07-17 15:50:00
author:     "jcorpus"
header-img: "img/prolog-sql/inteligencia_artificial_p.jpg"
---

<h2 class="section-heading">Inteligencia Artificial Logica Fuzzy</h2>
<p style="text-align:justify;">La lógica Booleana es conocida como la más precisa de todas las ciencias y disciplina teóricas. La mayoría de las ciencias modernas
y matemáticas se basan en sus principios. La lógica boleana tiene la desventaja de no poder reproducir los patrones del pensamiento humano.
</p>
<p style="text-align:justify;">Es así como a mediados de los años sesenta, el profesor Lotfi Zadeth de la universidad de California en Berkeley, pretendiendo suplir esta deficiencia de la
lógica tradicional, crea la que hoy se denomina como lógica Fuzzy.
Como disciplina teórica matemática, la lógica fuzzy está diseñada para reaccionar a cambios continuos de la variable a ser controlada y se
diferencia con la lógica Booleana por no estar restringida a dos únicos valores de 0 y 1. En su lugar permite valores parciales y multivalores
de verdad. Se puede afirmar, tal como lo demostró Bart Kosko, que la lógica Booleana es un caso especial de la lógica Fuzzy.
</p>
<p>El lenguaje del mundo real usano en control fuzzy permite a los programadores incorporar la lógica ambigua de los humanos dentro de la computadora. El uso de modelos lingüísticos en lugar de modelos matemáticos mejora grandemente la transparencia del sistema y facilita las potenciales modificaciones. Intenta controlar procesos, capturando el conocimiento que los especialistas poseen de su experiencia real, sin tener que modelar el sistema. </p>

<img style="  display: block;margin-left: auto;margin-right: auto " src="{{ site.baseurl }}/img/prolog-sql/logica-fuzzy.gif" alt="imagen fuzzy">


<h2>Tipos de Incerteza</h2>
<p>Muchas disciplinas matemáticas tratan con la descripcion de incerteza, tales como la teoria de la probabilidad, la teoria de
la información y la teoría del conjunto fuzzy. Es más conveniente clasificarlos por el tipo de incerteza que tratan.</p>
<h3>Incerteza Estocástica</h3>
<p>Trata con la incerteza hacia la ocurrencia de un cierto evento. El siguiente es un ejemplo de este caso.</p>
<p style="font-weight:bold">La probabilidad de dar en el blanco es 0.8</p>
<p>El evento en sí mismo, dar en el blanco, está bien definido. La incerteza surge como consecuencia de que sí el blanco será o no alcanzado. Esta incerteza es cuantificado por un grado de probabilidad. En el caso que se analiza, la probabilidad </p>
<h3>Ahora veremos un ejemplo con el programa xfuzzy</h3>
<p>La abuela María prepara sus deliciosas galletas caseras de forma artesanal desde hace más de 40 años. El toque
secreto de la receta consiste en hornearlas cuidadosamente hasta que toman su característico color dorado. Durante este
delicado proceso la abuela María observa periódicamente las galletas y ajusta la temperatura del horno de forma
adecuada:<p/>
<p>
a. Si las galletas están un poco crudas, entonces la temperatura del horno debe ser media.
b. Si las galletas están medio hechas, entonces la temperatura del horno debe ser alta.
c. Si las galletas están doraditas, entonces la temperatura del horno debe ser baja. </p>
<p>Tras diversas entrevistas con la abuela se han podido establecer los siguientes conjuntos difusos sobre un índice
cromático especial (0 = galleta cruda; 10 = galleta chamuscada) y la temperatura del horno:</p>

Indice | valores 
--- | --- 
*un poco crudas* | *(0/0, 0.5/1, 1/3, 1/4, 0.5/6, 0/7)*
*medio hechas* | (0/3, 1/5, 1/6, 0/8) 
*doraditas* | (0/5, 1/7, 1/8, 0/9) 



