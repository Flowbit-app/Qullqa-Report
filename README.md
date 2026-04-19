<div align="center">

<img src="assets/img/upc-logo.png" alt="UPC Logo" width="150"/>

# Universidad Peruana de Ciencias Aplicadas

## Facultad de Ingeniería

## Programa Académico de Ingeniería de Software

**Ciclo:** 2026-10

**Curso:** Aplicaciones Web

**NRC:** 17953

**Docente del curso:** Alex Humberto Sánchez Ponce


# Informe de Trabajo Final

**Nombre de la Startup:** Flowbit

**Nombre del producto:** Qullqa


## Integrantes

<p align="center">
u202416272 - Asmat Alminco, Martin Alejandro<br>
u202414802 - Contreras Torres, Arturo Valentino<br>
u2024113169 - Güere Calero, Fernando Julio<br>
u20231h067 - Huaman Oscco, Aldo Jesus<br>
u202018427 - Ramos Fuentes Rivera, Adriana Nicole<br>

</p>


*Abril, 2026*

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| | | | |

---

# Project Report Collaboration Insights

---

# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|---------------------|---------------------|--------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Güere Calero, Fernando Julio <br>**AV1** <br> <br> Huaman Oscco, Aldo Jesus <br>**AV1** <br> <br> Ramos Fuentes Rivera, Adriana Nicole <br>**AV1** <br> | |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | Asmat Alminco, Martin Alejandro <br>**AV1** <br> <br> Contreras Torres, Arturo Valentino <br>**AV1** <br> <br> Güere Calero, Fernando Julio <br>**AV1** <br> <br> Huaman Oscco, Aldo Jesus <br>**AV1** <br> <br> Ramos Fuentes Rivera, Adriana Nicole <br>**AV1** <br> | |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Somos **Flowbit**, una startup tecnológica creada por estudiantes de la carrera Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC). Nuestra startup está enfocada en el desarrollo de soluciones digitales innovadoras orientadas a optimizar la gestión de negocios tradicionales mediante el uso de software inteligente y tecnologías emergentes. La empresa busca transformar procesos manuales e ineficientes en sistemas automatizados que permitan mejorar la toma de decisiones, reducir pérdidas y aumentar la productividad.

Nuestro producto principal es **Qullqa**, una solución diseñada para la gestión de bodegas y farmacias, integrando funcionalidades como control de inventario, reportes de ventas, alertas inteligentes y, como valor diferencial, el uso de dispositivos IoT para el seguimiento de entregas.

La misión de Flowhot es brindar soluciones tecnológicas accesibles e innovadoras que permitan a pequeños y medianos negocios optimizar sus procesos, mejorar su rentabilidad y tomar decisiones basadas en datos reales.

Nuestra visión es consolidarnos como una startup líder en el desarrollo de plataformas digitales para la gestión de negocios en Latinoamérica, destacando por la integración de tecnologías como IoT e inteligencia de datos, y contribuyendo a la transformación digital de sectores tradicionales como lo son las bodegas y farmacias.

Nuestros valores son:
- Innovación: Desarrollo constante de soluciones tecnológicas modernas y eficientes
- Compromiso: Enfoque en resolver problemas reales de nuestros clientes
- Accesibilidad: Crear herramientas fáciles y accesibles para negocios pequeños
- Responsabilidad: Garantizar confiabilidad en los datos y procesos
- Calidad: Priorizar la experiencia y necesidades del usuario

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/arturo-contreras.PNG" alt="Foto de Arturo Contreras" width="500"/>
    </td>
    <td><b>Nombre:</b> Arturo Valentino Contreras Torres</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414802</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Arturo Valentino Contreras Torres</b>, tengo 19 años y estudio la carrera de Ingeniería de Software en la UPC, actualmente estoy en el 5to ciclo. Me gusta aprender y aplicar tecnologías innovadoras para resolver problemas complejos y desarrollar soluciones eficientes. Me apasiona participar en concursos de programación en donde aprendo más sobre temas como programación competitiva, lenguajes como C++, Python, Java, frameworks como Flutter y habilidades como el trabajo en equipo.
      <br/><br/>
      Dentro del equipo, contribuyo en el desarrollo frontend y backend, asegurándome de aplicar principios de Domain Driven Design, patrones de diseño y buenas prácticas de desarrollo de software. Me considero una persona responsable, creativa y orientada al trabajo en equipo, con un enfoque en la mejora continua frente a nuevos desafíos.
    </td>
  </tr>
  <tr>
  </tr>

  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/aldo-jesus.png" alt="Foto de Aldo Huaman" width="500"/>
    </td>
    <td><b>Nombre:</b> Aldo Jesus Huaman Oscco</td>
  </tr>
  <tr>
    <td><b>Código:</b> u20231h067</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Aldo Jesus Huaman Oscco</b>, tengo 20 años y estudio la carrera de Ingeniería de Software en la UPC, estoy cursando el 5to ciclo de la carrera. Disfruto de resolver distintos tipos de problemas que impliquen logica para su resolucion. Tengo interes en desarrollar proyectos de interes social para el desarrollo de habilidades para mi portafolio profesional, manejo distintas tecnologias como lenguajes de programacion y de tipeado, conozco el desarrollo de fronted y backend. Disfruto de aplicar un manejo estructurado con el desarrollo de metodologias agiles en equipo. 
      <br/><br/>
      Dentro del equipo, contribuyo en fronted y backend con proyeccion a IOT, validare la aplicacion de principios DDD, y el seguimiento de patrones para la arquitectura asi como la implementacion de algoritmos que permitan la escalabilidad de nuestra base de datos en conjunto con el sistema.
    </td>
  </tr>
<tr>

</tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/Fernando-Guere.png" alt="Foto de Fernando Güere" width="500"/>
    </td>
    <td><b>Nombre:</b> Fernando Julio Güere Calero</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202413169</td>
  </tr>
  <tr>
    <td>
    <div align="Justify">
      <b>Descripción:</b><br/>
      Soy <b>Fernando Julio Güere Calero</b>, tengo 19 años y estudio la carrera de Ingeniería de Software en la UPC, estoy cursando el 5to ciclo de la carrera. Cuento con los conocimientos para programar en C++, Python y gestión de base de datos SQL. Además, tengo conocimiento para el desarrollo de páginas web usando HTML, CSS y JavaScript. Siempre estoy interesado en expandir mis conocimientos con otros lenguajes de programación para fortalecer mis competencias técnicas y enfrentar retos en la industria. 
      <br/><br/>
      Dentro del equipo, cumplo con las actividades de documentación y programación en un nivel intermedio. También quisiera destacar que soy responsable con las distintas tareas establecidas.
      </div>
    </td>
  </tr>

</table>

## 1.2. Solution Profile

Qullqa es una aplicación desarrollada por la startup Flowbit, orientada a optimizar la gestión de bodegas y farmacias independientes mediante herramientas digitales accesibles y eficientes. La plataforma permite a los usuarios controlar su inventario, registrar ventas, gestionar productos y obtener reportes que faciliten la toma de decisiones.

El sistema está diseñado para reemplazar métodos manuales o poco eficientes, integrando funcionalidades como alertas de bajo stock, notificaciones de productos por vencer y dashboards interactivos que brindan un visión clara del estado del negocio. De esta manera, Qullqa contribuye a reducir pérdidas económicas, mejorar la organización y aumentar la rentabilidad de los negocios.

Además, como valor diferencial, la solución tiene integración con dispositivos IoT que permiten el seguimiento de entregas hacia el almacén o bodega, brindando mayor seguridad y control de los productos.

Qullqa se presenta como una solución escalable, con distintos planes que se adaptan a las necesidades de cada negocio, desde funcionalidades básicas hasta herramientas más avanzadas de análisis y gestión.


### 1.2.1. Antecedentes y problemática

- **What:**
<br>
  <div>
    Nuestra propuesta de solución, Qullqa, se propone resolver las siguientes 3 problemáticas recurrentes en el comercio independiente:
  </div>
  <br>
  <div align="justify">
    Uno de los problemas más comunes que se enfrentan los dueños de bodegas y farmacias es la deficiencia en la gestión de inventarios y falta de rotación, los cuales, por ausencia de un sistema de gestión que les permita registrar información relevante acerca de sus productos, como la fecha de caducidad, número de lote, proveedor, cadena de frío, ubicación exacta (pasillo, estante, nivel), etc. En consecuencia, provoca que muchos establecimientos mantengan productos vencidos en sus almacenes, lo cual representa un riesgo significativo, ya que, de acuerdo con el Artículo 30 del Código de Protección y Defensa del Consumidor (2010), los consumidores tienen derecho a consumir alimentos inocuos. Los proveedores son responsables de la inocuidad de los alimentos que ofrecen en el mercado, de conformidad con la legislación sanitaria.
  </div>
  <br>
  <div align="justify">
    Por otro lado, el desconocimiento de la rentabilidad y finanzas generales, también representa un problema difícil de resolver para los dueños de bodegas y farmacias. Según la Cámara de Comercio de Lima (2025), la falta de liquidez continúa siendo un obstáculo determinante para las pequeñas y medianas empresas en el Perú. Cada año, más de 100 mil de estas unidades económicas dejan de funcionar, y cerca del 40% lo hace debido a la imposibilidad de sostener su flujo de caja. Además, al ser un negocio independiente donde el manejo de las finanzas puede llegar a ser desordenado e incompleto debido a la inexperiencia y falta de conocimiento por parte del dueño, es más común no saber el margen de ganancia real de los productos vendidos. Por consecuencia, al momento de realizar decisiones importantes, en muchos casos, terminan siendo decisiones erradas, reflejadas en los precios mal establecidos, problemas de flujo de caja, elecciones erróneas de productos a vender, etc.
  </div>
  <br>
  <div align="justify">
    Por último, otro problema es la logística enfocada en las entregas de los proveedores, ya que cuando un proveedor envía un pedido, los dueños no tienen visibilidad en tiempo real de dónde está el vehículo, cuándo llegará aproximadamente o si hubo demoras, como resultado, genera descoordinación, pérdida de tiempo y, en el caso de productos perecibles y medicamentos, riesgos de calidad. Además, es usual que los pedidos lleguen incompletos, con productos distintos a los solicitados o en mal estado por golpes o manipulación incorrecta durante el transporte, por lo que, sin un registro de evidencia fotográfica o de sensores, no se podría realizar el reclamo correspondiente al proveedor. Por consiguiente, brindar una solución eficiente a este problema, generaría una reducción en las pérdidas de productos.
  </div> <br>


- **Where:**
  <div align="justify">
   
  Se encuentra en bodegas y farmacias emprendedoras que se encuentren dentro del rango en ingresos y gestión de productos del NRUS como régimen tributario. Dichos emprendedores necesitan poder reducir brechas de tiempo y de accesibilidad en la gestión de sus productos por la poca calidad de software gratuitos y el precio de los mismos, sin posibilidad de ajustar sus necesidades a sus casos específicos. Dicho sector se encuentra entre los más solicitados por los emprendedores, ya que alínea las necesidades no genera costos exorbitantes por pertenecer a la misma. 
  
  También ocurre con trabajadores de las bodegas o farmacias, los cuales utilizan la infraestructura del negocio planteada previamente propuesta.

  </div>


- **When:**
  <div align="justify">
   
   Cuando un usuario que gestiona la bodega y farmacias se encuentra con propuesta de gestión de inventario robustas que sobrepasan su capacidad de inversión en las mismas, por lo que recurre a propuestas más económicas que no cumple con un buen estándar de optimización o directamente no las utiliza, lo que genera el uso de técnicas manuales.
   Luego, ocurre también con los trabajadores, aunque no sean mayoría. Según la SUNAT (2025), el NRUS permite como máximo en las bajas categorías unos 8.000 soles, por lo que en promedio para no sobrepasar costos, se tiene que considerar máximo 2 trabajadores. Ellos, se encargan en su mayoría de registrar los productos, para lo cual tienen que entender, de ser que un software se utilice, interfaces poco intuitivas y complejas debido a la poca inversión dedicada. Luego, de ser que no exista uno, se recurre a registros manuales, como tomar apuntas en una hoja o cuaderno, lo que da chance a más errores de registro. 

  </div>


- **Who:** <br/>
  <div align="justify">
    El problema afecta principalmente a dos perfiles de microempresarios en el sector de ventas minoristas:
  </div>
  <ul>
    <li>
      <div align="justify">
        El primer segmento objetivo son los bodegueros independientes. Este segmento está conformado por propietarios de bodegas o minimarkets que, por lo general, gestionan su negocio de forma manual o apoyándose en herramientas muy básicas. Estos emprendedores suelen manejar sus establecimientos de manera independiente o con el soporte de su familia, basando su administración diaria mayormente en métodos empíricos que resultan insuficientes para las demandas actuales del mercado.
      </div>
    </li>
    <br/>
    <li>
      <div align="justify">
        Como consecuencia de esta gestión tradicional, los bodegueros enfrentan desafíos críticos como el descontrol total de su stock, pérdidas económicas por productos vencidos y una falta de claridad sobre las ganancias reales obtenidas mes a mes. Ante esta situación, nuestro grupo busca una solución tecnológica que sea simple y accesible, permitiéndoles organizar mejor su negocio y optimizar su rentabilidad de manera intuitiva.
      </div>
    </li>
  </ul>

</div>

- **Why:** <br/>
  <div align="justify">
    La realidad del sector minorista en el Perú se caracteriza por una profunda brecha tecnológica y operativa que compromete la sostenibilidad de miles de microempresas. Según Romero (2024), de las más de 535,000 bodegas que operan a nivel nacional, apenas un 12 % había logrado adoptar herramientas digitales antes de la emergencia sanitaria, cifra que experimentó un retroceso debido a la inexistencia de soluciones adaptadas a la realidad técnica de estos negocios. Esta situación es crítica si se considera que el 70 % de estos establecimientos son gestionados bajo métodos estrictamente tradicionales y manuales, donde la administración diaria depende casi en su totalidad de la memoria del propietario o de registros informales en papel. Esta dependencia de sistemas no automatizados genera un entorno de ineficiencia operativa que no solo ralentiza la atención, sino que anula la capacidad de crecimiento y competitividad frente a las grandes cadenas de retail moderno.
  </div>
  <br/>
  <div align="justify">
    Este rezago digital tiene un impacto financiero directo y medible, especialmente en el manejo de inventarios críticos. De acuerdo con Mendoza y Anchiraico (2018), la ausencia de sistemas de gestión técnica en las boticas independientes es el detonante principal de los quiebres de stock y la baja rotación de productos, factores que merman severamente la rentabilidad anual del negocio. En este contexto, la falta de una trazabilidad precisa sobre las existencias no solo deriva en pérdidas económicas por mercadería vencida, sino que escala a un riesgo latente para la salud pública al no poder garantizar la integridad de los fármacos. Asimismo, Delgado y Lopez (2024) sostienen que una gestión deficiente incide negativamente en los márgenes de ganancia al generar costos ocultos por almacenamiento inadecuado y desperdicio de capital. Esta problemática se agrava por la incertidumbre constante en la cadena de suministro y la falta de monitoreo en tiempo real, manteniendo al pequeño empresario en un estado de vulnerabilidad financiera ante un mercado cada vez más automatizado.
  </div>
  <br/>

- **How:** <br/>
  <div align="justify">
  La ineficiencia operativa en bodegas y farmacias independientes se manifiesta a través de un flujo de trabajo fragmentado y empírico. Actualmente, la gestión de inventarios se ejecuta mediante registros manuales en cuadernos o hojas sueltas, lo que imposibilita una alerta temprana sobre fechas de vencimiento o niveles críticos de stock. Este proceso "analógico" provoca que el control dependa exclusivamente de la memoria del dueño, derivando en una fricción operativa constante.

  La problemática se agrava significativamente cuando el negocio cuenta con personal, ya que la ausencia de trazabilidad digital facilita conductas de riesgo. Al no existir un sistema de control que registre cada salida de producto o ingreso de dinero, el dueño pierde la capacidad de auditar las operaciones de sus empleados. Esto genera un entorno donde el personal puede manipular el stock, ocultar gastos o incurrir en "robos hormiga" sin ser detectados. Asimismo, se produce una confusión sistemática entre gastos personales y del negocio, donde la falta de una plataforma de auditoría impide supervisar efectivamente las transacciones de caja, permitiendo fugas de capital y una gestión de costos opaca.

  Por otro lado, la problemática logística ocurre por la opacidad en la comunicación con proveedores, interrumpiendo la atención al cliente para recibir pedidos sin una verificación técnica, y la gestión financiera se da por "bolsillo único", donde el flujo de caja personal se mezcla con el del negocio, impidiendo conocer el margen de ganancia real.
  </div>

- **How much:** <br/>
  <div align="justify">
  El impacto de esta problemática es crítico y medible tanto a nivel financiero como de mercado. A nivel macro, la falta de una gestión técnica contribuye a que el 40% de las microempresas en Perú cierren anualmente por insolvencia y mala administración de su liquidez (CCL, 2025). En el día a día, esta brecha tecnológica se traduce en pérdidas económicas directas que pueden representar entre el 10% y 15% del valor del inventario anual debido a productos vencidos o mermas logísticas.

  A esto se suma el impacto de la gestión negligente o malintencionada del personal: los costos ocultos por discrepancias de inventario, errores en el manejo de caja y la mezcla de gastos personales con los operativos, actúan como un factor silencioso que erosiona el margen de ganancia neto. Estas pérdidas, al no ser detectadas por un sistema de control centralizado, representan un "gasto fantasma" que acelera la insolvencia del establecimiento, impidiendo que el dueño tenga visibilidad real de cuánto dinero gana o pierde realmente.

  Desde la perspectiva del sector, el problema afecta a una escala masiva: el 88% de las más de 535,000 bodegas en el país operan en un estado de vulnerabilidad digital. Además, en el caso específico de las farmacias, el costo escala a un riesgo de salud pública, donde la falta de trazabilidad técnica pone en peligro la inocuidad de los medicamentos, exponiendo a los dueños a sanciones legales y multas que comprometen la continuidad de su patrimonio.
  </div>


### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem statement 1:** <br>
Nuestro producto fue diseñado para optimizar la gestión de productos e inventario para micro empresas o emprendedores las cuales no poseen una ERP, donde les ofrecemos distintos tipos de planes que se adapten a sus necesidades particulares y con ello, optimicen costos por ganancia y tiempo invertido en el registro de los productos.

Hemos observado que estos negocios no están logrando una gestión adecuada del inventario, debido al uso de métodos manuales o herramientas digitales poco accesibles, complejas o costosas, que no cumplen con los requerimientos mínimos o los sobrepasan.

Esto genera pérdidas económicas por productos vencidos, errores en el registro de stock y falta de visibilidad sobre el estado real del negocio, lo que afecta directamente su rentabilidad y sostenibilidad.

Por tanto, nos preguntamos: ¿Cómo podríamos simplificar y hacer más accesible la gestión de inventario para estos microempresarios, de modo que reduzcan errores operativos y mejoren el control de su stock, medido a través de la disminución de pérdidas?

**Problem statement 2:** <br>
El producto que creamos fue diseñado para ayudar a los pequeños emprendedores da un sector retail minorista para optimizar la gestión de su inventario.
Con ello, hemos observado que los dueños y trabajadores de farmacias y tiendas pasan demasiado tiempo registrando salidas y entradas de productos, debido a las herramientas que no son fáciles de usar o por procedimientos manuales. Esto causa retrasos en la atención al cliente, equivocaciones en las transacciones y poco rendimiento de eficiencia en las actividades diarias de la empresa.

Por tanto, nos preguntamos: ¿Qué estrategias podemos emplear para agilizar los procesos de gestión y administración de un inventario, con el objetivo de reducir el tiempo invertido y mejorar la efectividad de operaciones?

#### 1.2.2.2. Lean UX Assumptions
<div align="Justify">

- **1. ¿Quién es el usuario?** <br/>
  
    Los usuarios de Qullqa principalmente son propietarios de bodegas y minimarkets independientes que gestionan sus negocios de forma empírica y manual, representando un sector donde el 70% de los dueños superan los 41 años. También se incluyen dueños de farmacias y boticas pequeñas que requieren un control técnico más estricto para evitar riesgos sanitarios y operativos.
  

- **2. ¿Dónde encaja nuestro producto en su trabajo o vida?** <br/>
  
    Qullqa se integra en el núcleo de la operación diaria del negocio. En las bodegas, sustituye el cuaderno de notas o la memoria del dueño por un centro de control digital para registrar ventas y stock en tiempo real. En las farmacias, se convierte en la herramienta de seguridad que monitorea la vigencia de los medicamentos. Además, facilita la recepción de mercadería al conectar la gestión del almacén con dispositivos IoT que rastrean el estado de las entregas.
  

- **3. ¿Qué problema tiene nuestro producto y cómo se puede resolver?** <br/>
  <ul>
    <li> 
      <b>Resistencia al cambio digital:</b> Muchos bodegueros temen la complejidad técnica. <b>Solución:</b> Una interfaz extremadamente simplificada y un proceso de acompañamiento inicial que no requiera conocimientos avanzados.
    </li>

    <li>
      <b>Costo de implementación:</b> Las MYPES suelen tener presupuestos limitados. <b>Solución:</b> Un modelo de precios escalonado (freemium) donde las funciones básicas sean accesibles para negocios muy pequeños.
    </li>

    <li>
      <b>Precisión de los datos IoT:</b> Fallos en la conectividad podrían generar desconfianza. <b>Solución:</b> Implementar un sistema de caché local para que la app funcione sin internet y sincronice datos apenas recupere la conexión.
    </li>

  </ul>

- **4. ¿Cuándo y cómo es usado nuestro producto?** <br/>
  
    Es una herramienta de uso constante: desde la apertura del local para verificar el inventario, durante todo el día para registrar cada venta, y al momento de recibir pedidos de proveedores para validar el ingreso de stock mediante sensores IoT. También se consulta el cierre de caja para visualizar el dashboard de ganancias netas y reportes de desempeño.
  

- **5. ¿Qué características son importantes?** <br/>
  <ul>
    <li><b>Gestión Inteligente de Inventario:</b> Registro automatizado de entradas, salidas y alertas de bajo stock.</li>
    <li><b>Notificaciones de Vencimiento:</b> Alertas proactivas para evitar pérdidas por productos caducados.</li>
    <li><b>Módulo IoT de Seguimiento:</b> Monitoreo de seguridad para productos en tránsito hacia el negocio.</li>
    <li><b>Dashboards Financieros:</b> Visualización clara de ventas y rentabilidad real mes a mes.</li>
  </ul>
</div>

- **6. ¿Cómo debe verse nuestro producto y cómo comportarse?** <br/>
  <div align="justify">
    Debe ser limpio, rápido y de alto contraste, facilitando la lectura para usuarios mayores que operan en entornos de iluminación variable. El comportamiento debe ser predictivo; por ejemplo, sugerir la reposición de un producto antes de que se agote basándose en patrones de venta previos.
  </div>
  <br/>

- **Business Outcomes:** <br/>
  <ul>
    <li>
    Posicionamiento como la plataforma de gestión para MYPES líder en el mercado peruano.</li>
    <li>Generación de ingresos mediante planes premium para funciones avanzadas de análisis de datos e integración IoT.</li>
    <li>Reducción del 20% en las pérdidas por productos vencidos en los negocios afiliados.</li>
    <li>Alianzas estratégicas con proveedores mayoristas para integrar sus catálogos directamente en la app.</li>
  </ul>

- **User Outcomes:** <br/>
  <ul>
    <li><b>Claridad financiera:</b> El usuario conoce exactamente cuánto dinero gana y qué productos son los más rentables.</li>
    <li><b>Ahorro de tiempo:</b> Reducción del tiempo dedicado a inventarios manuales de horas a solo minutos.</li>
    <li><b>Seguridad:</b> Mayor confianza al recibir mercadería gracias al rastreo IoT.</li>
    <li><b>Reducción de riesgos:</b> Eliminación de multas o riesgos sanitarios por venta de productos vencidos en farmacias.</li>
  </ul>

- **Features:** <br/>
  <ul>
    <li><b>Dashboard de Inventario:</b> Panel visual con estados de stock (disponible, crítico, agotado).</li>
    <li><b>Sistema de Alertas:</b> Notificaciones push y correos sobre vencimientos próximos.</li>
    <li><b>Integración con Sensores IoT:</b> Conexión con hardware para el seguimiento de entregas en tiempo real.</div></li>
    <li><b>Registro de Ventas POS:</b> Interfaz táctil rápida para facturación y boleteo.</li>
    <li><b>Reportes de Rentabilidad:</b> Gráficos automáticos de ingresos vs. egresos mensuales.</li>
  </ul>
</div> 


#### 1.2.2.3. Lean UX Hypothesis Statements
<div align="justify">

**Hypothesis Statement 1** <br>
Creemos que simplificar y hacer más accesible la gestión de inventario mediante una plataforma intuitiva permitirá a los microempresarios reducir errores operativos y mejorar el control de su stock. Sabremos que esto es cierto cuando veamos que las pérdidas por productos vencidos se reducen en al menos un 50%, y la precisión del inventario aumenta hasta un 90% o más.

**Hypothesis Statement 2** <br>
Creemos que implementar herramientas que agilicen el registro de entradas y salidas de productos permitirá a los usuarios reducir el tiempo invertido en la gestión del inventario. Sabremos que esto es cierto cuando veamos que el tiempo promedio de registro de productos se reduce en al menos un 60%, y la eficiencia en la atención al cliente mejora en un 40%.

#### 1.2.2.4. Lean UX Canvas
<div>
  <img src="assets/img/artefacts/lean_ux_canvas(v2).png" alt="Foto Lean UX Canvas (V2)" width="1000"/>
</div>

## 1.3. Segmentos objetivo

- **Bodegueros independientes** <br>
Propietarios de bodegas o minimarkets que gestionan su negocio de forma manual o con herramientas básicas. Presentan problemas como descontrol del stock, pérdidas por productos vencidos y falta de claridad sobre sus ganancias mes a mes. Buscan una solución simple y accesible para organizar mejor su negocio

- **Farmacias independientes** <br>
Pequeñas farmacias que requieran un control más riguroso del inventario, especialmente en fechas de vencimiento y disponibilidad de medicamentos. Necesitan herramientas más confiables que les permitan reducir riesgos, evitar pérdidas y asegurar un mejor control operativo.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En esta sección se realiza la identificación y descripción de los principales competidores directos, los cuales ofrecen soluciones digitales enfocadas en la gestión de inventarios y operaciones comerciales, similares a la propuesta de valor de Qullqa.

- **Spry Sales** <br>
  Plataforma digital peruana enfocada en la gestión de ventas e inventario para pequeños y medianos negocios. Su propuesta se centra en simplificar el control de stock, registro de productos y seguimiento de ventas en tiempo real, permitiendo a los emprendedores tener una mejor visibilidad de su negocio. Ofrece funcionalidades como control de inventario, reportes básicos, gestión de clientes y ventas desde dispositivos móviles. Su principal fortaleza radica en su enfoque local y facilidad de uso; sin embargo, presenta limitaciones en cuanto a escalabilidad, automatización avanzada y personalización profunda de procesos, lo que puede restringir su adopción en negocios en crecimiento.

- **Zoho Inventory** <br>
  Solución global de gestión de inventario basada en la nube que permite a empresas gestionar pedidos, controlar stock, automatizar procesos y administrar múltiples canales de venta. Se integra con otras herramientas del ecosistema Zoho y plataformas externas como e-commerce y marketplaces, ofreciendo funcionalidades avanzadas como gestión de órdenes, seguimiento de envíos y reportes detallados. Su modelo de negocio se basa en suscripciones por niveles. Aunque es altamente robusto y escalable, su complejidad y costo pueden resultar poco accesibles para microempresarios o pequeños negocios que buscan soluciones más simples y económicas.

- **Odoo Inventory** <br>
  Parte del ecosistema ERP de Odoo, una plataforma modular que permite gestionar inventarios, logística, compras y ventas de manera integrada. Ofrece funcionalidades avanzadas como trazabilidad de productos, gestión de almacenes, automatización de reabastecimiento y control en tiempo real. Su principal ventaja es la integración con múltiples módulos empresariales (contabilidad, CRM, ventas, etc.), lo que permite una gestión completa del negocio. No obstante, su implementación puede ser compleja y requiere cierto nivel técnico o inversión en configuración, lo cual puede representar una barrera para microempresas o usuarios sin experiencia en sistemas ERP.

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="6" align="left">Competitive Analysis Landscape</th>
  </tr>

  <tr>
    <td><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5">
      Con el fin de identificar oportunidades de diferenciación, fortalezas clave y posibles debilidades. Esto permitirá definir una ventaja competitiva clara orientada a microempresarios y negocios pequeños que requieren soluciones accesibles, simples y eficientes.
    </td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th>Qullqa</th>
    <th>Spry Sales</th>
    <th>Zoho Inventory</th>
    <th>Odoo Inventory</th>
  </tr>

  <!-- PERFIL -->
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>Plataforma de gestión de inventario simple y accesible enfocada en microempresas (bodegas y farmacias).</td>
    <td>Sistema de ventas e inventario enfocado en pequeños negocios peruanos.</td>
    <td>Software global de inventario en la nube con múltiples integraciones.</td>
    <td>Módulo ERP completo para gestión empresarial integral.</td>
  </tr>

  <tr>
    <td><b>Ventaja competitiva</b></td>
    <td>Simplicidad, bajo costo y enfoque específico en microempresarios con problemas reales de inventario.</td>
    <td>Fácil uso y enfoque local adaptado a pequeños negocios.</td>
    <td>Alta automatización e integración con múltiples plataformas.</td>
    <td>Integración total con otros módulos empresariales (ERP).</td>
  </tr>

  <!-- PERFIL DE MARKETING -->
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>Bodegueros y farmacias independientes.</td>
    <td>Pequeños negocios y emprendedores locales.</td>
    <td>PYMES y empresas en crecimiento.</td>
    <td>Empresas medianas y grandes con procesos complejos.</td>
  </tr>

  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>Enfoque en educación digital, redes sociales y validación con usuarios reales.</td>
    <td>Marketing digital local y enfoque en emprendedores.</td>
    <td>Estrategia global, contenido educativo y ecosistema SaaS.</td>
    <td>Marketing basado en soluciones empresariales integradas.</td>
  </tr>

  <!-- PERFIL DE PRODUCTO  -->
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos & Servicios</b></td>
    <td>Gestión de inventario, alertas de vencimiento, control de stock, reportes simples.</td>
    <td>Control de ventas, inventario y clientes.</td>
    <td>Gestión de pedidos, inventario, envíos y reportes avanzados.</td>
    <td>Gestión de almacenes, trazabilidad, compras, ventas y más.</td>
  </tr>

  <tr>
    <td><b>Precios & Costos</b></td>
    <td>Modelos de suscripción y un plan gratuito siendo accesible para las microempresas.</td>
    <td>Suscripción accesible.</td>
    <td>Planes por suscripción (más costosos).</td>
    <td>Costos variables según módulos e implementación.</td>
  </tr>

  <tr>
    <td><b>Canales de distribución</b></td>
    <td>Web y móvil (enfocado en facilidad de acceso).</td>
    <td>Web y móvil.</td>
    <td>Web (cloud-based).</td>
    <td>Web (cloud y on-premise).</td>
  </tr>

  <!-- ANÁLISIS SWOT -->
  <tr>
    <td rowspan="4"><b>Análisis SWOT</b></td>
    <td><b>Fortalezas</b></td>
    <td>Enfoque específico en microempresas, facilidad de uso y bajo costo accesible.</td>
    <td>Adaptación al mercado local, interfaz simple.</td>
    <td>Alta integración con otras herramientas, funcionalidades avanzadas.</td>
    <td>Sistema ERP completo, alta personalización.</td>
  </tr>

  <tr>
    <td><b>Debilidades</b></td>
    <td>Menor reconocimiento de marca, funcionalidades limitadas en etapas iniciales.</td>
    <td>Limitada escalabilidad, pocas funcionalidades avanzadas.</td>
    <td>Complejidad para usuarios básicos, costos relativamente altos.</td>
    <td>Complejidad de implementación, requiere conocimientos técnicos.</td>
  </tr>

  <tr>
    <td><b>Oportunidades</b></td>
    <td>Alto número de negocios informales sin sistemas digitales, crecimiento de la digitalización en pequeños negocios.</td>
    <td>Crecimiento de emprendedores digitales.</td>
    <td>Expansión de negocios digitales globales.</td>
    <td>Empresas que buscan soluciones integrales.</td>
  </tr>

  <tr>
    <td><b>Amenazas</b></td>
    <td>Competidores consolidados con más recursos, resistencia al cambio tecnológico.</td>
    <td>Competidores más robustos.</td>
    <td>Soluciones más simples y económicas.</td>
    <td>Alternativas más simples para pequeños negocios.</td>
  </tr>

</table>

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se presenta el diseño de las entrevistas dirigidas a los segmentos objetivos, con el propósito de recolectar información relevante que permita comprender sus necesidades, comportamientos y problemáticas. Para ello, se han formulado preguntas principales y complementarias que guían la conversación, asegurando la obtención de datos tanto generales como específicos.

**Preguntas complementarias:**
- ¿Cuál es su edad?
- ¿En qué distrito reside actualmente?
- ¿Cuál es su estado civil?
- ¿A qué se dedica?
- ¿Qué fue lo que le inspiró a abrir su negocio?
- ¿Qué habilidades considera que son más sobresalientes en usted?
- ¿Qué canales usa para comunicarse con sus clientes?
- ¿Cuál es su objetivo como bodeguero/dueña de farmacia respecto a ventas y gestión de su  negocio?
- ¿Tiene alguna frustración respecto al manejo de su inventario?

**Preguntas principales** <br>
- Segmento Objetivo 1: (Bodegueros independientes)
  - ¿Cómo es su rutina desde que llega la primera mercadería del día hasta que cierra la reja de la bodega?
  - ¿Qué aplicaciones usa más en su día a día (WhatsApp para pedidos, Facebook, apps de bancos o alguna de delivery)?
  - ¿Cómo anota o registra los productos que le traen los proveedores? ¿Usa cuaderno, Excel o confía en su memoria?
  - ¿Qué hace usted cuando nota que un producto está por vencer y todavía tiene varias unidades en el estante?
  - ¿Cuál es el mayor problema que enfrenta actualmente al manejar su inventario?
  - ¿Ha tenido pérdidas por productos vencidos o falta de stock? ¿Cómo suele manejar esas situaciones?
  - ¿Cómo calcula sus ganancias diarias o mensuales? ¿Le resulta fácil o complicado? 
  - Si tuviera que contratar a un ayudante, ¿qué información del negocio le permitiría ver y qué cosas preferiría manejar solo usted?
  - Si existiera una aplicación que le ayude a controlar su inventario y ventas de manera sencilla, ¿la usaría? ¿por qué?
  - ¿Qué le podría generar dificultades al usar una aplicación para gestionar su negocio?

- Segmento Objetivo 2: (Farmacias independientes)
  - ¿Cómo es el proceso desde que un proveedor llega hasta que el producto está disponible para la venta?
  - ¿Qué herramientas o aplicaciones utilizas en tu día a día para gestionar la farmacia?
  - ¿Cómo registras los productos que ingresan a la farmacia?
  - ¿Cómo controlas las fechas de vencimiento de los medicamentos? Cuáles son sus métodos para prevenirlo? 
  - ¿Cuál es el mayor problema que enfrentas al manejar tu inventario?
  - ¿Has tenido pérdidas por vencimientos o falta de stock? ¿Cómo las manejas?
  - ¿Cómo haces el seguimiento de tus ventas o ganancias?
  - ¿Qué información le gustaría tener para decidir qué productos comprar más o dejar de vender?
  - ¿Qué tarea te quita más tiempo en el día y te gustaría automatizar?
  - Si existiera una aplicación que te ayude a controlar inventario, vencimientos y ventas, ¿la usarías? ¿Qué te preocuparía o dificultaría al usarla?
  - ¿Cómo categorizan los productos?


### 2.2.2. Registro de entrevistas

**PRIMER SEGMENTO OBJETIVO (BODEGUEROS INDEPENDIENTES)**

<u>Entrevista 1:</u>

Entrevistador: Fernando Julio Güere Calero

Datos del entrevistado

- **Nombre:** Raul
- **Apellidos:** Gimenez
- **Edad:** 61 años
- **Distrito:** Chaclacayo
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Raul_Segmento1.png" alt="Entrevista con Raul Gimenez" width="500"/>
  <br/><i>Evidencia de entrevista: Raul Gimenez</i>
</p>

**Resumen descriptivo:**
<div align="justify">
Es un emprendedor de tercera generación. Gestiona su inventario de forma manual con cuadernos y su principal frustración es la presión de la SUNAT y la municipalidad. Aunque usa Yape y aplicaciones de proveedores, teme que las apps de gestión "encadenen" sus datos. Busca un punto de venta (POS) sencillo que no restrinja el acceso a su información histórica.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413169_upc_edu_pe/IQCNzoA_BvcPRJP9Baxc_4mKAVFCGG13ZxRKSkL4itnHBLA?e=mPE13c&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


<u>Entrevista 2:</u>

Entrevistador: Fernando Julio Güere Calero

Datos del entrevistado

- **Nombre:** Jimmy
- **Apellidos:** Viera
- **Edad:** 28 años
- **Distrito:** Chaclacayo
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Jimmy_Segmento1.png" alt="Entrevista con Jimmy Viera" width="500"/>
  <br/><i>Evidencia de entrevista: Jimmy Viera</i>
</p>

**Resumen descriptivo:**
<div align="justify">
Estudiante que apoya en el negocio familiar. Confía principalmente en su memoria para el inventario, lo que resulta tedioso al trabajar con más personas. Utiliza aplicaciones de proveedores para pedidos pero critica la falta de flexibilidad en los horarios de entrega. Considera que una app de gestión le facilitaría mucho el control de stock y la comunicación.
</div>

***Enlace del video:*** [Ver grabación aquí](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202413169_upc_edu_pe/IQCeSnkB2TLFSYasRy9oINIGAd67FUgsN5274thKlHodem0?e=GaLWEi&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


<u>Entrevista 3:</u>

Entrevistador: Arturo Valentino Contreras Torres

Datos del entrevistado

- **Nombre:** Ruben
- **Apellidos:** De la Cruz
- **Edad:** 53 años
- **Distrito:** Comas
- **Timing:** 

<p align="center">
  <img src="assets/img/Entrevistas/Entrevista_Ruben_Segmento1.png" alt="Entrevista con Ruben de la Cruz" width="500"/>
  <br/><i>Evidencia de entrevista: Ruben de la Cruz</i>
</p>

**Resumen descriptivo:**

<div align="justify">
El señor Rubén, dueño de una bodega con dos años de funcionamiento, gestiona su negocio de manera manual. Registra la mercadería en un cuaderno mientras atiende a los clientes, y se comunica con proveedores mediante WhatsApp. El control de inventario lo realiza físicamente, revisando constantemente el almacén para evitar productos vencidos, ya que no todos los proveedores aceptan cambios. Aunque las pérdidas por vencimiento no son frecuentes, sí afectan sus ingresos. Además, lleva un control básico de sus ganancias, sin tener claridad total sobre su rentabilidad. Si bien le interesa la idea de usar un sistema digital, percibe estas herramientas como difíciles de aprender y costosas, lo que le genera desconfianza y limita su adopción.
</div>

***Enlace del video:*** 

<br>

**SEGUNDO SEGMENTO OBJETIVO (FARMACIAS INDEPENDIENTES)**

<u>Entrevista 1:</u>

Entrevistador: 

Datos del entrevistado

- **Nombre:** 
- **Apellidos:** 
- **Edad:** 
- **Distrito:** 
- **Timing:** 

<!-- Colocar screenshot de la entrevista -->

**Resumen descriptivo:**

<!-- Resumen entrevista -->

***Enlace del video:*** <!-- Link grupal de entrevistas -->


<u>Entrevista 2:</u>

Entrevistador: 

Datos del entrevistado

- **Nombre:** 
- **Apellidos:** 
- **Edad:** 
- **Distrito:** 
- **Timing:** 

<!-- Colocar screenshot de la entrevista -->

**Resumen descriptivo:**

<!-- Resumen entrevista -->

***Enlace del video:*** <!-- Link grupal de entrevistas -->


<u>Entrevista 3:</u>

Entrevistador: 

Datos del entrevistado

- **Nombre:** 
- **Apellidos:** 
- **Edad:** 
- **Distrito:** 
- **Timing:** 

<!-- Colocar screenshot de la entrevista -->

**Resumen descriptivo:**

<!-- Resumen entrevista -->

***Enlace del video:*** <!-- Link grupal de entrevistas -->


### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

## 2.4. Big Picture Event Storming

## 2.5. Ubiquitous Language

# Conclusiones
## Conclusiones y recomendaciones

## Video About-the-Team

# Bibliografía

Romero, P. (2024, 10 de enero). Retos para impulsar la expansión de las billeteras digitales en las bodegas peruanas. Conexión ESAN. Recuperado de https://www.esan.edu.pe/conexion-esan/retos-para-impulsar-la-expansion-de-las-billeteras-digitales-en-las-bodegas-peruanas

Delgado, R. S. B., & Lopez, H. Y. B., (2024). Modelo PDCA para incrementar el índice de rotación de inventario aplicando la clasificación ABC-SLP, Kanban y Conteo Cíclico en una pequeña empresa de comercio farmacéutico [Tesis de maestría, Universidad Peruana de Ciencias Aplicadas]. Repositorio Académico UPC. https://repositorioacademico.upc.edu.pe/handle/10757/682410

Mendoza, B. J. F., & Anchiraico, B. W. R., (2018). Determinación de patrones de ventas en boticas independientes para mejorar las ventas [Tesis de maestría, Universidad San Ignacio de Loyola]. Repositorio Académico USIL. https://hdl.handle.net/20.500.14005/8591

# Anexos
