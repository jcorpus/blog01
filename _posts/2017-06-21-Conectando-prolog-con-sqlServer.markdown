---
layout:     post
title:      "Conectando Prolog con Sql Server"
subtitle:   "Prolog con base de datos sql Server."
date:       2017-06-21 17:16:00
author:     "jcorpus"
header-img: "img/swiprolog.png"
---

<h2 class="section-heading">Conectando Prolog con Sql Server</h2>
<p style="text-align:justify;">En este post les enseñare a conectar Prolog con SQLServer en la plataforma windows. Primero empezaremos creando la base de datos en sql server, creamos la base de datos con el nombre "hostpital" y con una tabla resumen </p>

<img src="{{ site.baseurl }}/img/prolog-sql/tabla.PNG" alt="Post Sample Image">
<br>
<h4>Nos dirigimos a herramientas administrativas, luego a origen de datos ODBC</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/herramientas administrativas.PNG" alt="Post Sample Image">
 <h4>Nos dirigimos a herramientas administrativas, luego a origen de datos ODBC y agregamos uno nuevo</h4>
  <img src="{{ site.baseurl }}/img/prolog-sql/nuevo origen de datos.PNG" alt="Post Sample Image">
  <h4>Seleccionamos SQL native client</h4>
  <img src="{{ site.baseurl }}/img/prolog-sql/seleccionamos sql native.PNG" alt="Post Sample Image">
 <h4>Colocamos el nombre a nuestra conexion y en servidor colocamos un punto "."</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/colocamos el nombre a nuestra conexion y un servidor.PNG" alt="Post Sample Image">
 <h4>Seleccionamos autentificacion de Windows</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/autentificacion de windows.PNG" alt="Post Sample Image">
 <h4>Seleccionamos la base de datos creada</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/seleccionamos la base de datos creada.PNG" alt="Post Sample Image">
 <h4>Establecemos el idioma</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/establecemos el idioma.PNG" alt="Post Sample Image"> 
  <h4>Probamos el origen de datos y verificamos que la prueba se completo correctamente.</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/probamos el origen de datos.PNG" alt="Post Sample Image">
 <br>
 <h4>Conexión establecida.</h4>
 <img src="{{ site.baseurl }}/img/prolog-sql/conexion establecida.PNG" alt="Post Sample Image">
 
 <h2 class="section-heading">Ahora comenzaremos con Prolog</h2>
 <p>Para este tutorial trabajaré con SwiProlog, la instalación es sencilla, puedes descargarlo desde aquí <a href="http://www.swi-prolog.org/Download.html"  target="_blank"></a></p>
 <p></p>
 

