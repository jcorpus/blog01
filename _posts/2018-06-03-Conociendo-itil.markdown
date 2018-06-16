---
layout:     post
title:      "Conociendo ITIL"
subtitle:   "ITIL v3."
date:       2018-06-02 10:16:00
author:     "jcorpus"
header-img: "img/itil/ITIL%20-%20procesos..jpg"
---

<h3 class="section-heading">1. Fundamentos de ITIL</h3>
<h3>&nbsp;&nbsp; 1.1 ITIL en sus inicios</h3>
<p style="text-align:justify;">ITIL (Information Technology Infraestructure Library o Biblioteca de Infraestructura de Tecnologías de la Información) es un compendio de publicaciones, o librería, que describen de manera sistemática un conjunto de “buenas prácticas” para la gestión de los servicios de Tecnología Informática (en adelante TI). Las organizaciones cada vez dependen más de la las herramientas informáticas para llevar a cabo su trabajo diario. Este trabajo además está gestionado y controlado a través de otros sistemas informáticos, pudiendo estar éstos a su vez dentro de una red controlada por otros sistemas y así sucesivamente. Por tanto la complejidad de estos procesos hizo crecer la demanda y necesidad de las entidades (públicas o privadas) de disponer de un modelo que les permitiera gestionar su infraestructura TI más fácilmente y que pudieran dar soporte a los objetivos de negocio.</p>
<p style="text-align:justify;">ITIL nació en la década de 1980, a través de la Agencia Central de Telecomunicaciones y Computación del Gobierno Británico (Central Computer and Telecommunications Agency - CCTA), que ideó y desarrolló una guía para que las oficinas del sector público británico fueran más eficientes en su trabajo y por tanto se redujeron los costes derivados de los recursos TI. Sin embargo esta guía demostró ser útil para cualquier organización, pudiendo adaptarse según sus circunstancias y necesidades. De hecho resultó ser tan útil que actualmente ITIL recoge la gestión de los servicios TI como uno de sus apartados, habiéndose ampliado el conjunto de “buenas prácticas” a gestión de la seguridad de la información, gestión de niveles de servicio, perspectiva de negocio, gestión de activos software y gestión de aplicaciones. 
En la actualidad ITIL pertenece al Oficina de Comercio Británico (Office of Government Commerce - OGC), pero puede ser utilizado para su aplicación libremente.
</p>
<h3>&nbsp;&nbsp; 1.2 Librería</h3>
<p style="text-align:justify;">
ITIL no comenzó a ser utilizada de manera común hasta aproximadamente 1990; desde esa fecha el crecimiento de la librería se situó en aproximadamente 30 publicaciones que hacían de su utilización un proceso complejo. Se hizo necesaria por tanto una revisión que agrupa los libros según conjuntos estructurados en los procesos que estuvieran más íntimamente relacionados, enmarcando la gran cantidad de publicaciones existente en ocho volúmenes, denominándose desde entonces como ITIL v2. 
La última versión vio la luz en 2007, denominada como ITIL v3. En esta versión se ha realizado un refresco (refreshment en palabras de la OGC), agrupando los elementos principales de ITIL en 5 volúmenes, que pueden encontrarse en la actualidad con los siguientes títulos (en inglés original).
</p>

<ol>
<li>ITIL v3 Service Strategy (SS)</li>
<li>ITIL v3 Service Design (SD)</li>
<li>ITIL v3 Service Operation (SO)</li>
<li>ITIL v3 Continual Service Improvement(CST) </li>
<li>ITIL v3 Service Transition (ST)</li>
</ol>
<h3>&nbsp;&nbsp; 1.3 Características de ITIL</h3>
<p style="text-align:justify;">La causa de que ITIL se haya convertido desde 1990 en un modelo de referencia y haya experimentado una expansión tan grande con respecto a otros modelos como CMM/CMMI y posteriormente COBIT se fundamenta en dos motivos:</p>
<ul>
<li>En las características esenciales de esta librería.</li>
<li>Actualmente demuestra ser compatible con respecto a la introducción de normas internacionales y otros modelos de gestión paralelos en la Organización.</li>
</ul>
<p>Las características se pueden resumir en las siguientes<p/>

<h5>&nbsp;1. NO DESARROLLADA CON DERECHOS DE PROPIEDAD </h5>
<p>
<ul>
<li>Se trata de un modelo de aplicación basado en mejores prácticas independientemente de proveedores asociados a su aplicación. </li>
<li>Las mejores prácticas están basadas en procesos puestos en marcha y recopilados en estos volúmenes, no tienen derechos de uso por prácticas personales o empresariales únicas.
</li>
</ul>
</p>
<h5>&nbsp;2. DE DOMINIO PÚBLICO</h5>
<p>
<ul>
<li>Transición de conocimiento libre.</li>
<li>Es de libre utilización. Cualquiera, independientemente de las características de la entidad puede
ponerlo en práctica, incluso únicamente las partes que le apliquen.</li>
</ul>
</p>
<h5>&nbsp;3. COMPENDIO DE MEJORES PRÁCTICAS</h5>
<p>
<ul>
  <li>Se puede aplicar y obtener beneficios adaptando el modelo a las características de cada necesidad, creciendo constantemente porque se retroalimenta de nuevas mejores prácticas. </li>
  <li>Estas mejores prácticas son el resultado de los resultados obtenidos por el trabajo diario de expertos y profesionales del mundo de las TI desde hace casi tres décadas.</li>
</ul>
</p>
<h5>&nbsp;4. ESTÁNDAR INTERNACIONAL </h5>
<p>
<ul>
  <li>Trata de establecer, al igual que se realizó en otras ciencias, una estandarización en los conceptos, lenguaje, estructura y formas de trabajo de las organizaciones en todo el mundo con respecto a las TI.</li>
  <li>Está desarrollado y responde a la estructura común del lenguaje y su terminología, así como los documentos que se utilizan actualmente en el mundo empresarial (servicios, procesos, estrategia, objetivos, responsabilidades, recursos, etc.).</li>
</ul>
</p>
<h5>Ciclo de Vida de ITIL</h5>
<p align="center">
<img width="400px"  src="{{ site.baseurl }}/img/itil/flujo%20de%20funcionamiento%20itil.png" alt="Post Sample Image">
</p>
<small text-align:center;>Flujo de funcionamiento de ITIL</small>
<br>
<p>
<ul>
  <li><strong>Estrategia del servicio:</strong> Propone tratar la gestión del servicio como un activo que genera valor para la organización</li>
  <li><strong>Diseño del servicio:</strong> Propone desarrollar servicios a los requisitos de la organización y/o modificar o mejorar los servicios existentes y prevenir ante desastres</li>
  <li><strong>Transición del servicio:</strong> Propone una base de datos para gestionar los servicios, asegurar la operación del servicio, realizar un plan de pruebas para la puesta en funcionamiento de los nuevos servicios o modificaciones de los ya existentes y planes de rollback.</li>
  <li><strong>Operación del Servicio:</strong> Propone monitoreo permanente de los servicios y propone una base de datos de conocimiento donde se debe registrar incidentes, problemas y peticiones de los accesos a los servicios.</li>
<li><strong>Y mejora continua del servicio:</strong> Propone una revisión total de todos los componentes del ciclo de vida de un servicio, incluyendo los procesos de la Organización con el fin de actualizar o retirar servicios que no estén dando valor agregado a los clientes.</li>
</ul>
</p>
<h5>Las certificaciones ITIL v3</h5>
<p style="text-align:justify">El modelo de aplicación de mejores prácticas ITIL tiene, como cualquier otro modelo o norma internacional de gestión, un comité rector que actualiza, verifica, mejora la librería, evalúa nuevas mejores prácticas y además certifica qué personas pueden asesorar a las organizaciones en cuestiones de ITIL.
Las certificaciones han variado en las distintas versiones de ITIL, siendo en la actualidad cuatro las que pueden
obtenerse, según el nivel de profundización en la materia:</p>
<ol>
  <li>ITIL Fundation Level.</li>
  <li>TTIL Intermediate Level - Service Lifecycle & Service Compability Streams.</li>
  <li>ITIL Expert Level.</li>
  <li>ITIL Master.</li>
 </ol>
<ol>
  <li>Foundation Level – Nivel Fundamentos: este nivel trata de introducir al alumno en el conocimiento y
comprensión para ofrecer una buena base en conceptos clave, terminología y procesos de ITIL.</li>
  <li>Intermediate Level – Nivel Intermedio: existen tres niveles o módulos de aprendizaje en este nivel.
i. Módulos del Ciclo de Vida: basados en los cinco libros de ITIL v3.
ii. Módulos de Capacidad: que desarrollan los siguientes apartados: Portafolio de Servicio y
Gestión de Relaciones; Diseño y Optimización del Servicio; Entrega, Monitorización y
Control del Servicio; Operación y Soporte del Servicio.
iii. Gestión a través del Ciclo de Vida: en el que se reúnen los dos módulos anteriores para
llegar a comprender cómo relacionar todo el conocimiento.</li>
  <li>Expert Level – Nivel Experto: una vez obtenidos los niveles anteriores, incluidos los tres módulos del Nivel
Intermedio, se pasa a tener la certificación en Experto ITIL, sin necesidad de realizar ninguna prueba.</li>
  <li>ITIL Master – Nivel Avanzado: nivel más alto al que se puede aspirar en la actualidad. Se espera que en este
nivel estén los consultores ITIL.</li>
</ol>
<p style="text-align:justify;">Para acceder a estos niveles es necesario realizar exámenes en Institutos Oficiales Acreditados por APM Group a través del ITIL Qualifications Board. En la actualidad se ha establecido un sistema de créditos por el que se puede navegar por la siguiente figura para obtener la cantidad de créditos necesarios que se piden para disponer de la certificación en los niveles anteriormente descritos, además de poder optar a los nuevos certificados v3 a través de cursos puente desde v2, o asimilación de créditos por certificaciones superiores a la Foundation v2.</p>

<h3 class="section-heading">2. COBIT 5 y sus Principios</h3>
<p>COBIT 5 es un marco de trabajo y no una metodología. Permite comprender el gobierno y la gestión de las tecnologías de información (TI) de una organización, así como evaluar el estado en que se encuentran las TI en la empresa. </p>
COBIT(Control Objectives for Information and related Technology, Objetivos de control para la información y tecnologías relacionadas).
<h6>El marco de trabajo de COBIT5</h6>
<p style="text-align:justify;">Dicho en pocas palabras, COBIT 5 ayuda a las Organizaciones a crear un valor óptimo a partir de la TI, al mantener un equilibrio entre la realización de beneficios y la optimización de los niveles de riesgo y utilización de los recursos.
</p>
<p style="text-align:justify;">COBIT 5 permite que las tecnologías de la información y relacionadas se gobiernen y administren de una manera holística a nivel de toda la Organización, incluyendo el alcance completo de todas las áreas de responsabilidad funcionales y de negocios, considerando los intereses relacionados con la TI de las partes interesadas internas y externas.
</p>
<p style="text-align:justify;">Los principios y habilitadores de COBIT 5 son genéricos y útiles para las Organizaciones de cualquier tamaño, bien sean comerciales, sin fines de lucro o en el sector público.
</p>
<p>Los principios de COBIT 5</p>
<p align="center">
<img width="400px"  src="{{ site.baseurl }}/img/itil/principios-de-cobit.PNG" alt="Post Sample Image">
</p>
<small text-align:center;>Principios de COBIT 5 . © 2012 ISACA</small>



