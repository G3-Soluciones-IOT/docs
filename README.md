<p align="center">
  <strong>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</strong>
</p>

<p align="center">
  <img src="./assets/upc-logo.png" alt="UPC Logo" width="200"/>
</p>

<p align="center">
  Ingeniería de Software <br>
  2026-10 <br>
  1ASI0572 Desarrollo de Soluciones IOT <br>
  NRC: 17756 <br>  
  Profesor: David Carlos Vera Olivera <br><br>
  "Informe de Trabajo Final" <br>
  Startup:  - Producto: 
</p>

<br>

<p align="center"><strong>Relación de integrantes:</strong></p>

<table align="center">
  <thead>
    <tr>
      <th>Integrante</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Mathias Eduardo Bueno Perales</td>
      <td>U202313433</td>
    </tr>
    <tr>
      <td>Jhon Alexander Galvez Chambi</td>
      <td>U202323270</td>
    </tr>
    <tr>
      <td>Pablo Antonio Geronimo Quispe</td>
      <td>U202314304</td>
    </tr>
    <tr>
      <td>Ramiro Alexander Guzmán Chávez</td>
      <td>U202217062</td>
    </tr>
    <tr>
      <td>Omar Luquillas Asto</td>
      <td>U20211G641</td>
    </tr>
    <tr>
      <td>Fabrizio Alberto Paredes Santos</td>
      <td>U202310914</td>
    </tr>
    <tr>
      <td>Valentino Sandoval Paiva</td>
      <td>U20211A962</td>
    </tr>
  </tbody>
</table>

<br><br>

<p align="center">
  <strong>Abril, 2026</strong> <br>
  <strong>URL del proyecto:</strong>
  <a href="https://github.com/G3-Soluciones-IOT">
    https://github.com/G3-Soluciones-IOT
  </a>
</p>

---

## Registro de Versiones del Informe

| Versión | Fecha      | Autor                         | Descripción                                                                  |
|---------|------------|-------------------------------|------------------------------------------------------------------------------|
| AV1     | 05/04/2026 | Jhon Alexander Galvez Chambi  | Desarrollo de la carátula, tabla de contenidos y estructura general del informe. |
| AV1     | /04/2026   |                               |                                                                              |
| AV1     | /04/2025   |                               |                                                                              |
| AV1     | /04/2025   |                               |                                                                              |
| AV1     | /04/2025   |                               |                                                                              |

## Project Report Collaboration Insights

## Contenido

### Tabla de contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process.](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores.](#21-competidores)
    - [2.1.1. Análisis competitivo.](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores.](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas.](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas.](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas.](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
    - [2.3.1. User Personas.](#231-user-personas)
    - [2.3.2. User Task Matrix.](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
  - [2.4. Big Picture EventStorming.](#24-big-picture-eventstorming)
  - [2.5. Ubiquitous Language.](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories.](#31-user-stories)
  - [3.2. Impact Mapping.](#32-impact-mapping)
  - [3.3. Product Backlog.](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design.](#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming.](#411-design-level-eventstorming)
        - [4.1.1.1 Candidate Context Discovery.](#4111-candidate-context-discovery)
        - [4.1.1.2 Domain Message Flows Modeling.](#4112-domain-message-flows-modeling)
        - [4.1.1.3 Bounded Context Canvases.](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping.](#412-context-mapping)
    - [4.1.3. Software Architecture.](#413-software-architecture)
        - [4.1.3.1. Software Architecture System Landscape Diagram.](#4131-software-architecture-system-landscape-diagram)
        - [4.1.3.2. Software Architecture Context Level Diagrams.](#4132-software-architecture-context-level-diagrams)
        - [4.1.3.3. Software Architecture Container Level Diagrams.](#4133-software-architecture-container-level-diagrams)
        - [4.1.3.4. Software Architecture Deployment Diagrams.](#4134-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
        - [4.2.X.1. Domain Layer.](#42x1-domain-layer)
        - [4.2.X.2. Interface Layer.](#42x2-interface-layer)
        - [4.2.X.3. Application Layer.](#42x3-application-layer)
        - [4.2.X.4. Infrastructure Layer.](#42x4-infrastructure-layer)
        - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.](#42x5-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams.](#42x6-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.](#42x61-bounded-context-domain-layer-class-diagrams)
            - [4.2.X.6.2. Bounded Context Database Design Diagram.](#42x62-bounded-context-database-design-diagram)

## Student Outcome

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

JF Technologies es una startup de base tecnológica orientada al desarrollo de soluciones digitales innovadoras en el ámbito de la salud y el bienestar, con un enfoque en la integración de tecnologías emergentes y modelos escalables.

La empresa se posiciona como un actor en la intersección entre tecnología, data y salud, buscando transformar la manera en que las personas gestionan su información relacionada con hábitos y calidad de vida. Su enfoque estratégico se basa en el uso inteligente de datos para generar valor, mejorar la toma de decisiones y optimizar la experiencia del usuario.

La startup se proyecta como una organización capaz de diseñar, desarrollar y evolucionar productos digitales complejos, integrando equipos multidisciplinarios y aplicando metodologías modernas de ingeniería de software que permiten adaptarse a entornos dinámicos y altamente competitivos.

## Misión

Desarrollar soluciones tecnológicas innovadoras que integren datos y herramientas digitales para mejorar la gestión del bienestar, promoviendo experiencias eficientes, accesibles y centradas en el usuario mediante el uso de metodologías modernas de ingeniería y desarrollo ágil.

## Visión

Ser una startup referente en el desarrollo de productos digitales orientados a la salud y el bienestar, destacando por su capacidad de innovación, escalabilidad y aplicación de tecnologías emergentes para generar impacto sostenible en la calidad de vida de las personas.
#### 1.1.2. Perfiles de integrantes del equipo

- Mathias Bueno Perales - u202313433 (Ingeniería de Software)

<p align="center">
    <img src="assets/fotos/foto-mathias.png" alt="foto-mathias" width="170px"/>
</p>

Soy una persona optimista y responsable al cumplir mis labores para-con el grupo. Tengo experiencia respecto a proyectos previamente hechos en la rama de Ingenieria de Software y conocimientos en programacion como en HTML y CSS. Siempre procuro lo mejor para el equipo y ayudar en todo lo que este en mi alcance.

- Jhon Alexander Galvez Chambi - u202323270 (Ingeniería de Software)

<p align="center">
    <img src="assets/fotos/jhonfoto.jpg" alt="foto-jhon" width="170px"/>
</p>

Soy una persona responsable y comprometida con la consecución de los mejores resultados en trabajo en equipo. Poseo experiencia en diversos lenguajes de programación, incluyendo Python, JavaScript y C++, así como en varios de los frameworks asociados a estos lenguajes. Además, tengo conocimientos en tecnologías emergentes como Cloud Computing e Internet de las Cosas (IoT), y estoy dispuesto a aportar mi experiencia en estas áreas para contribuir al éxito de los proyectos en los que participo.

- Fabrizio Alberto Paredes Santos - u202310914 (Ingeniería de Software)

<p align="center">
    <img src="assets/fotos/fabriziofoto.jpg" alt="foto-fabrizio" width="170px"/>
</p>

Profesional en formación con experiencia en desarrollo de aplicaciones web y móviles utilizando stacks modernos como Vue.js y .NET, Angular y Spring Boot, además de desarrollo móvil con Flutter y Kotlin. También he trabajado en la creación de páginas web con React, Next.js y Tailwind CSS, enfocadas en rendimiento y experiencia de usuario. Me caracterizo por ser proactivo, responsable y orientado a resultados, con capacidad para adaptarme a entornos dinámicos y contribuir eficazmente en equipos de desarrollo.


### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

En los últimos años, los hábitos alimenticios inadecuados continúan siendo un factor determinante en el desarrollo de enfermedades no transmisibles, como la obesidad y la diabetes, las cuales representan una preocupación creciente en salud pública a nivel global (Organización Mundial de la Salud [OMS], 2025).

En respuesta a este contexto, el uso de aplicaciones digitales para el monitoreo nutricional ha crecido significativamente. Sin embargo, investigaciones recientes evidencian que muchas de estas herramientas aún dependen del registro manual de alimentos, lo que introduce limitaciones importantes en términos de precisión, usabilidad y sostenibilidad en el tiempo. Estudios actuales destacan que los métodos tradicionales de autoreporte son propensos a errores, sesgos y omisiones, afectando la confiabilidad de los datos recolectados (Arefeen et al., 2025).

Asimismo, se ha identificado que la experiencia de uso en aplicaciones de nutrición se ve afectada por la carga operativa que implica el registro constante de información, lo que reduce la adherencia del usuario y limita el impacto de estas soluciones en la mejora de hábitos alimenticios (Gioia et al., 2023).

En consecuencia, persiste la necesidad de replantear los enfoques actuales hacia modelos que permitan reducir la intervención manual del usuario, mejorar la calidad de los datos y facilitar un monitoreo nutricional más eficiente y sostenible.

Para comprender mejor el problema, se utiliza la técnica de las 5 W’s y 2 H’s:

What:  
El problema principal radica en la dificultad que tienen muchas personas para realizar un seguimiento preciso y constante de su ingesta nutricional. Las herramientas digitales actuales suelen depender del registro manual, lo que introduce errores y limita la precisión de los datos, además de generar fricción en la experiencia del usuario.

Who:  
La problemática afecta a dos segmentos principales. Por un lado, usuarios finales que buscan mejorar su alimentación, incluyendo personas interesadas en optimizar sus hábitos nutricionales, deportistas o individuos con rutinas laborales que requieren controlar su ingesta. Por otro lado, profesionales de la salud, como nutricionistas o entrenadores, que necesitan información confiable para realizar seguimiento y brindar recomendaciones a sus pacientes o clientes.

When:  
El problema se presenta de manera constante en la vida diaria, especialmente cada vez que el usuario consume alimentos y debe registrar dicha información. Su relevancia ha aumentado en los últimos años debido al mayor interés en el autocuidado y el uso de herramientas digitales para la gestión de la salud.

Where:  
La problemática ocurre en múltiples entornos cotidianos, como el hogar, el trabajo o espacios de consumo alimenticio, lo que evidencia que se trata de una necesidad transversal e independiente del contexto físico.

Why:  
La causa principal es la dependencia de procesos manuales y estimaciones subjetivas, sumada a la falta de herramientas automatizadas que faciliten el registro de información nutricional. Esto genera baja adherencia, errores en los datos y una experiencia poco sostenible en el tiempo.

How:  
El problema se manifiesta a través de registros incompletos, inconsistentes o abandonados, así como en la generación de datos poco confiables que dificultan el análisis y la toma de decisiones informadas sobre la alimentación.

How Much:  
El impacto de esta problemática es significativo. Estudios recientes evidencian que los métodos de autoreporte en nutrición presentan limitaciones importantes en términos de precisión y confiabilidad, afectando la calidad de los datos utilizados para el monitoreo y análisis (Arefeen et al., 2025). Asimismo, se ha identificado que la carga operativa en aplicaciones de salud influye directamente en la disminución de la adherencia del usuario a largo plazo (Gioia et al., 2023). A nivel global, las enfermedades asociadas a hábitos alimenticios inadecuados continúan siendo una de las principales causas de mortalidad (Organización Mundial de la Salud [OMS], 2025).


#### 1.2.2 Lean UX Process.
El Lean UX Process es un enfoque ágil centrado en el usuario que permite validar de manera iterativa las decisiones de diseño mediante la formulación de hipótesis y la experimentación continua. Este enfoque se basa en el ciclo construir–medir–aprender, permitiendo al equipo reducir la incertidumbre y asegurar que la solución propuesta responda a necesidades reales del usuario.
##### 1.2.2.1. Lean UX Problem Statements.
**Domain**  
Gestión del monitoreo nutricional y seguimiento de la ingesta alimentaria en contextos personales y profesionales de salud.

**Customer Segments**  
- Usuarios orientados a la mejora de su alimentación  
- Profesionales de la salud (nutricionistas, entrenadores)

**Problem / Pain Points**  
Se ha identificado que los usuarios presentan dificultades para registrar y monitorear su ingesta nutricional de manera precisa y constante, lo que genera:

- Baja precisión en los datos registrados  
- Abandono del uso de aplicaciones de nutrición  
- Falta de visibilidad clara sobre hábitos alimenticios  
- Dificultad para tomar decisiones informadas  
- Limitada capacidad de seguimiento por parte de profesionales de la salud  

**Gap**  
Existe una brecha entre la necesidad de contar con información nutricional precisa, continua y confiable, y la disponibilidad de herramientas digitales que reduzcan la carga manual del usuario y mejoren la calidad de los datos recolectados.

**Vision / Strategy**  
Desarrollar una solución digital que permita automatizar y optimizar el monitoreo de la ingesta nutricional, reduciendo la intervención manual del usuario y mejorando la precisión de los datos, facilitando la toma de decisiones y promoviendo hábitos alimenticios sostenibles tanto en usuarios finales como en profesionales de la salud.

**Initial Segment**  
Usuarios urbanos en Perú interesados en mejorar su alimentación y que utilizan dispositivos móviles como principal medio de acceso digital.

**Problem Statement**  
¿Cómo podríamos facilitar el monitoreo preciso y constante de la ingesta nutricional de los usuarios, al mismo tiempo que brindamos información confiable a los profesionales de la salud, reduciendo la carga manual y mejorando la calidad de los datos para apoyar la toma de decisiones?

##### 1.2.2.2. Lean UX Assumptions.
Las siguientes suposiciones han sido definidas en base al entendimiento preliminar del problema y serán validadas mediante el proceso iterativo del Lean UX.


**Business Assumptions**

- Se asume que existe una creciente demanda por soluciones digitales orientadas al monitoreo de la salud y la nutrición.  
- Se asume que los usuarios perciben valor en herramientas que reduzcan el esfuerzo requerido para registrar su alimentación.  
- Se asume que la automatización del registro nutricional puede mejorar la retención de usuarios.  
- Se asume que los profesionales de la salud requieren herramientas más precisas para el seguimiento de sus pacientes.  
- Se asume que los profesionales están dispuestos a adoptar herramientas digitales que mejoren la calidad del seguimiento nutricional.  
- Se asume que el mercado peruano presenta oportunidades para soluciones digitales en el ámbito de la salud y bienestar.  
- Se asume que una solución basada en datos puede generar valor tanto para usuarios finales como para profesionales.  


**User Assumptions**

- Se asume que los usuarios experimentan frustración al tener que registrar manualmente su alimentación.  
- Se asume que los usuarios valoran la facilidad de uso y la rapidez en el registro de información.  
- Se asume que los usuarios están dispuestos a adoptar herramientas digitales si estas son intuitivas.  
- Se asume que los usuarios desean mejorar sus hábitos alimenticios pero carecen de herramientas eficientes.  
- Se asume que los profesionales de la salud necesitan datos confiables para brindar recomendaciones adecuadas.  
- Se asume que los profesionales valoran herramientas que optimicen su tiempo y mejoren el seguimiento de pacientes.  
- Se asume que los usuarios prefieren soluciones que reduzcan el esfuerzo requerido para el monitoreo nutricional.  

##### 1.2.2.3. Lean UX Hypothesis Statements.
Creemos que los usuarios orientados a la mejora de su alimentación podrán realizar un seguimiento más constante y preciso de su ingesta nutricional si se reduce la necesidad de registro manual, lo que mejorará su adherencia al uso de la herramienta.

Sabremos que esto es cierto cuando al menos el 70% de los usuarios registre su alimentación de manera continua durante una semana.

Creemos que los usuarios podrán tomar mejores decisiones sobre su alimentación si cuentan con información clara, precisa y accesible, lo que permitirá mejorar sus hábitos alimenticios.

Sabremos que esto es cierto cuando más del 60% de los usuarios indique que comprende mejor su alimentación y realiza cambios en sus hábitos.

Creemos que los profesionales de la salud podrán mejorar la calidad de sus recomendaciones si cuentan con datos más precisos y actualizados sobre la ingesta nutricional de sus pacientes, lo que permitirá un seguimiento más efectivo.

Sabremos que esto es cierto cuando al menos el 70% de los profesionales indique que la herramienta mejora su capacidad de análisis y toma de decisiones.

Creemos que los usuarios adoptarán la solución si esta ofrece una experiencia simple, rápida y accesible desde dispositivos móviles, lo que permitirá su uso continuo.

Sabremos que esto es cierto cuando la tasa de retención supere el 60% después de la primera semana.
##### 1.2.2.4. Lean UX Canvas.

<p align="center">
    <img src="assets/recursos/Lean UX Canvas-IoT.png" alt="Lean-UX-Canvas" width="400px"/>
</p>

Link: https://canva.link/55j2m2akga2iwr8
### 1.3. Segmentos objetivo.

Los siguientes segmentos han sido definidos a partir del análisis del dominio del problema y del contexto actual en el Perú, considerando tendencias en el uso de tecnologías digitales, hábitos de salud y necesidades de monitoreo nutricional. La selección de estos segmentos busca maximizar el impacto de la solución, abordando tanto la demanda de los usuarios finales como las necesidades de los profesionales del sector salud.


### Segmento objetivo 1: Usuarios orientados a la mejora de su alimentación

| Aspectos demográficos | Aspectos geográficos | Aspectos psicográficos |
|----------------------|--------------------|------------------------|
| Sexo: Masculino y Femenino | Nacionalidad: Peruana | Motivaciones: Mejorar hábitos alimenticios, controlar peso, optimizar rendimiento físico y realizar seguimiento de su ingesta nutricional como apoyo en el manejo de condiciones de salud. |
| Edades: 18 – 55 años | Ubicación: Principalmente zonas urbanas (Lima Metropolitana, Arequipa, Trujillo) | Estilo de vida: Activo, semi-activo, sedentario, con interés en el bienestar personal |
| Nivel socioeconómico: A, B y C | Acceso a tecnología: Alto acceso a smartphones e internet móvil | Preocupaciones: Falta de control preciso sobre su alimentación y dificultad para mantener hábitos constantes |
| Ocupación: Estudiantes, profesionales, trabajadores dependientes e independientes | | Adaptación a la tecnología: Alta, familiarizados con aplicaciones móviles |
| Ingresos: Variables, con predominancia de ingresos estables en zonas urbanas | | Interés por la personalización: Alto interés en soluciones que se adapten a sus objetivos de salud |

**Sustento:**  
En el Perú, el acceso a tecnologías digitales ha crecido de manera significativa en los últimos años. Según el Instituto Nacional de Estadística e Informática (INEI, 2023), más del 70% de la población utiliza internet, siendo el teléfono móvil el principal medio de acceso. Este contexto favorece la adopción de aplicaciones móviles orientadas a la salud, especialmente en población joven y adulta en zonas urbanas.



### Segmento objetivo 2: Profesionales de la salud (nutrición y bienestar)

| Aspectos demográficos | Aspectos geográficos | Aspectos psicográficos |
|----------------------|--------------------|------------------------|
| Sexo: Masculino y Femenino | Nacionalidad: Peruana | Motivaciones: Mejorar la calidad de atención y seguimiento de sus pacientes |
| Edades: 25 – 60 años | Ubicación: Zonas urbanas con presencia de clínicas y consultorios (Lima, Arequipa, Trujillo) | Estilo de vida: Profesional orientado al servicio y bienestar de terceros |
| Nivel socioeconómico: B y C | Acceso a tecnología: Alto acceso a herramientas digitales e internet | Preocupaciones: Falta de datos confiables y herramientas eficientes para el monitoreo de pacientes |
| Ocupación: Nutricionistas, médicos generales, entrenadores, profesionales de salud | | Adaptación a la tecnología: Media-alta, con interés en herramientas que optimicen su trabajo |
| Educación: Formación técnica o universitaria en salud o bienestar | | Interés por la personalización: Alto interés en soluciones que permitan seguimiento individualizado |

**Sustento:**  
El sector salud en el Perú viene experimentando un proceso de digitalización progresiva, impulsado por la necesidad de mejorar la eficiencia en la atención y el seguimiento de pacientes. En este contexto, los profesionales de la salud muestran una creciente apertura hacia el uso de herramientas tecnológicas que les permitan optimizar su práctica, especialmente en entornos urbanos con mayor acceso a infraestructura digital (INEI, 2023; OMS, 2025).



## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores.

#### 2.1.1. Análisis competitivo.

#### 2.1.2. Estrategias y tácticas frente a competidores.

### 2.2. Entrevistas.

#### 2.2.1. Diseño de entrevistas.

#### 2.2.2. Registro de entrevistas.

#### 2.2.3. Análisis de entrevistas.

### 2.3. Needfinding.

#### 2.3.1. User Personas.

#### 2.3.2. User Task Matrix.

#### 2.3.3. User Journey Mapping.

#### 2.3.4. Empathy Mapping.

### 2.4. Big Picture EventStorming.

### 2.5. Ubiquitous Language.

## Capítulo III: Requirements Specification

### 3.1. User Stories.

### 3.2. Impact Mapping.

### 3.3. Product Backlog.

## Capítulo IV: Solution Software Design

### 4.1. Strategic-Level Domain-Driven Design.

#### 4.1.1. Design-Level EventStorming.

##### 4.1.1.1 Candidate Context Discovery.

##### 4.1.1.2 Domain Message Flows Modeling.

##### 4.1.1.3 Bounded Context Canvases.

#### 4.1.2. Context Mapping.

#### 4.1.3. Software Architecture.

##### 4.1.3.1. Software Architecture System Landscape Diagram.

##### 4.1.3.2. Software Architecture Context Level Diagrams.

##### 4.1.3.2. Software Architecture Container Level Diagrams.

##### 4.1.3.3. Software Architecture Deployment Diagrams.

### 4.2. Tactical-Level Domain-Driven Design

#### 4.2.X. Bounded Context: &lt;Bounded Context Name&gt;

##### 4.2.X.1. Domain Layer.

##### 4.2.X.2. Interface Layer.

##### 4.2.X.3. Application Layer.

##### 4.2.X.4. Infrastructure Layer.

##### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams.

##### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams.

###### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams.

###### 4.2.X.6.2. Bounded Context Database Design Diagram.


### 4.3 Referencias Bibliográficas

Organización Mundial de la Salud. (2025). Noncommunicable diseases.  
https://www.who.int/news-room/fact-sheets/detail/noncommunicable-diseases  

Arefeen, A., et al. (2025). MealMeter: Using multimodal sensing and machine learning for automatically estimating nutrition intake.  
https://arxiv.org/abs/2503.11683  


Gioia, S., et al. (2023). Mobile apps for dietary and food timing assessment.  
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10337248/ 

Instituto Nacional de Estadística e Informática (INEI). (2023).  
Las Tecnologías de Información y Comunicación en los Hogares: Oct-Nov-Dic 2023.  
https://www.gob.pe/institucion/inei/informes-publicaciones/5408920-las-tecnologias-de 