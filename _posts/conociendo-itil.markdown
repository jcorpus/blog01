---
layout:     post
title:      "Conociendo ITIL"
subtitle:   "ITIL v3."
date:       2018-06-02 10:16:00
author:     "jcorpus"
header-img: "img/prolog-sql/prolog-page.png"
---

<h2 class="section-heading">1. Fundamentos de ITIL</h2>
<h2>&nbsp;&nbsp; 1.1 ITIL en sus inicios</h2>
<p style="text-align:justify;">ITIL (Information Technology Infraestructure Library o Biblioteca de Infraestructura de Tecnologías de la Información) 
es un compendio de publicaciones, o librería, que describen de manera sistemática un conjunto de “buenas prácticas” para 
la gestión de los servicios de Tecnología Informática (en adelante TI). Las organizaciones cada vez dependen más de la las
herramientas informáticas para llevar a cabo su trabajo diario. Este trabajo además está gestionado y controlado a través 
de otros sistemas informáticos, pudiendo estar éstos a su vez dentro de una red controlada por otros sistemas y así sucesivamente. 
Por tanto la complejidad de estos procesos hizo crecer la demanda y necesidad de las entidades (públicas o privadas) de disponer
de un modelo que les permitiera gestionar su infraestructura TI más fácilmente y que pudieran dar soporte a los objetivos de negocio.</p>
<p>ITIL nació en la década de 1980, a través de la Agencia Central de Telecomunicaciones y Computación del Gobierno Británico (Central Computer and Telecommunications Agency - CCTA), que ideó y desarrolló una guía para que las oficinas del sector público británico fueran más eficientes en su trabajo y por tanto se redujeron los costes derivados de los recursos TI. Sin embargo esta guía demostró ser útil para cualquier organización, pudiendo adaptarse según sus circunstancias y necesidades. De hecho resultó ser tan útil que actualmente ITIL recoge la gestión de los servicios TI como uno de sus apartados, habiéndose ampliado el conjunto de “buenas prácticas” a gestión de la seguridad de la información, gestión de niveles de servicio, perspectiva de negocio, gestión de activos software y gestión de aplicaciones. 
En la actualidad ITIL pertenece al Oficina de Comercio Británico (Office of Government Commerce - OGC), pero puede ser utilizado para su aplicación libremente.
</p>
<p style="text-aligh:justify;">ITIL nació en la década de 1980, a través de la Agencia Central de Telecomunicaciones y Computación del Gobierno Británico (Central Computer and Telecommunications Agency - CCTA), que ideó y desarrolló una guía para que las oficinas del sector público británico fueran más eficientes en su trabajo y por tanto se redujeron los costes derivados de los recursos TI. Sin embargo esta guía demostró ser útil para cualquier organización, pudiendo adaptarse según sus circunstancias y necesidades. De hecho resultó ser tan útil que actualmente ITIL recoge la gestión de los servicios TI como uno de sus apartados, habiéndose ampliado el conjunto de “buenas prácticas” a gestión de la seguridad de la información, gestión de niveles de servicio, perspectiva de negocio, gestión de activos software y gestión de aplicaciones. 
En la actualidad ITIL pertenece al Oficina de Comercio Británico (Office of Government Commerce - OGC), pero puede ser utilizado para su aplicación libremente.
</p>
<h2>&nbsp;&nbsp; 1.2 Librería</h2>
<p style="text-align:justify;">
ITIL no comenzó a ser utilizada de manera común hasta aproximadamente 1990; desde esa fecha el crecimiento de la librería se situó en aproximadamente 30 publicaciones que hacían de su utilización un proceso complejo. Se hizo necesaria por tanto una revisión que agrupa los libros según conjuntos estructurados en los procesos que estuvieran más íntimamente relacionados, enmarcando la gran cantidad de publicaciones existente en ocho volúmenes, denominándose desde entonces como ITIL v2. 
La última versión vio la luz en 2007, denominada como ITIL v3. En esta versión se ha realizado un refresco (refreshment en palabras de la OGC), agrupando los elementos principales de ITIL en 5 volúmenes, que pueden encontrarse en la actualidad con los siguientes títulos (en inglés original).
</p>

<ol>
<li><>
</ol>

<p style="text-align:justify;">Conectaremos Prolog con SQLServer en la plataforma windows. Empezaremos creando la base de datos en sql server, con el nombre "hospital" y con una tabla llamada resumen </p>
<h4>Creamos la tabla resumen con los siguientes campos.</h4>
<img src="{{ site.baseurl }}/img/prolog-sql/tabla.PNG" alt="Post Sample Image">
<br>
<h4>Llenamos la tabla con los siguientes datos.</h4>

<img src="{{ site.baseurl }}/img/prolog-sql/resumen.PNG" alt="datos de la tabla">
<br>
<h2>Ahora crearemos un nuevo origen de Datos llamado "NuevaConexion".</h2>
<h4>Nos dirigimos a herramientas administrativas, luego a origen de datos ODBC</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/herramientas administrativas.PNG" alt="Post Sample Image">
 <h4>Agregamos uno nuevo</h4>
  <img src="{{ site.baseurl }}/img/prolog-sql/nuevo origen de datos.PNG" alt="Post Sample Image">
  <h4>Seleccionamos SQL native client</h4>
  <img src="{{ site.baseurl }}/img/prolog-sql/seleccionamos sql native.PNG" alt="Post Sample Image">

 <br>
 <h4>Conexión establecida.</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/conexion establecida.PNG" alt="Post Sample Image">
 
 <h2 class="section-heading">Ahora comenzaremos con Prolog</h2>
 <p>Para este tutorial trabajaré con SwiProlog, la instalación es sencilla, puedes descargarlo desde <a href="http://www.swi-prolog.org/Download.html"  target="_blank">Aquí</a></p>
 <p>Comenzaremos escribiendo el siguiente codigo prolog, y el nombre de la conexión que creamos para este tutorial "NuevaConexion", en usuario lo dejamos en root y password en blanco en mi caso.</p>
 <p>Seleccionamos la cantidad de la tabla resumen.</p>

 <p>Compilamos y ejecutamos el predicado sistema.</p>
 <img src="{{ site.baseurl }}/img/prolog-sql/resultado1.PNG" alt="Post Sample Image">
 
 
 <h4>Ahora realizarenos el mismo ejercicio usando el modo gráfico de Prolog.</h4>

<p>Compilamos y llamamos al predicado sistema, seleccionamos los sintomas y la probabilidad bayesiana de tener la enfermedad, con el siguiente resultado.</p>
<img src="{{ site.baseurl }}/img/prolog-sql/resultado2.PNG" alt="Post Sample Image">
<p>El codigo fuente de prolog lo puedes descargar desde <a href="https://github.com/jcorpus/USP/tree/master/USP9/Inteligencia_artificial/prolog">Aquí</a><p>
