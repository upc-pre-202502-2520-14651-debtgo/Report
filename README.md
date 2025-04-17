<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2025-1</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles - WX53</strong><br>
    <strong>Profesor: David Gerardo Quevedo Velasco</strong><br>
    <br>INFORME DE TRABAJO FINAL - TB1
</p>

</p>

<p align="center">
    <strong>Startup: Apple Mobile</strong><br>
    <strong>Producto: DebtGo</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Chavarri Zarzosa, Daniel Jhared</td>
            <td>U202211108</td>
        </tr>
        <tr>
            <td>Becerra Llempen, Fabiola Dayane</td>
            <td>U20171a518</td>
        </tr>
        <tr>
            <td>Burga Loarte, Anaely Zarely</td>
            <td>U202118264</td>
        </tr>
        <tr>
            <td>Rivera Ticllacuriv, Omar Harold</td>
            <td>U202214214</td>
        </tr>
        <tr>
            <td>Góngora Sánchez, Marco Antonio </td>
            <td>U20211a085</td>
        </tr>
        <tr>
            <td>Escalante Baygorrea, Janiel Franz</td>
            <td>U201912668</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Abril, 2025</strong>
</p>
<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>24/04/2025</td>
                <td>
                    <ul>
          <li>Daniel Chávarri</li>
          <li>Fabiola Becerra</li>
          <li>Anaely Burga</li>
          <li>Omar Rivera</li>
          <li>Marco Góngora</li>
          <li>Janiel Escalante</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo I: Presentación</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Solution Software Design</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
      <tr>
                <th>TP</th>
                <td>15/05/2025</td>
                <td>
                    <ul>
          <li>Daniel Chávarri</li>
          <li>Fabiola Becerra</li>
          <li>Anaely Burga</li>
          <li>Omar Rivera</li>
          <li>Marco Góngora</li>
          <li>Janiel Escalante</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo V: Solution UI/UX Design</li>
          <li>Product Implementation, Validation & Deployment</li>
          <li>Sprint 1</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
  <tr>
                <th>TB2</th>
                <td>19/06/2025</td>
                <td>
                    <ul>
          <li>Daniel Chávarri</li>
          <li>Fabiola Becerra</li>
          <li>Anaely Burga</li>
          <li>Omar Rivera</li>
          <li>Marco Góngora</li>
          <li>Janiel Escalante</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Sprint 2</li>
          <li>Validation Interviews</li>
          <li>Diseño de Entrevistas</li>
          <li>Registro de Entrevistas</li>
          <li>Evaluaciones según heurísticas</li>
          <li>Video About-the-Product</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
  <tr>
                <th>TF</th>
                <td>17/11/2024</td>
                <td>
                    <ul>
          <li>Daniel Chávarri</li>
          <li>Fabiola Becerra</li>
          <li>Anaely Burga</li>
          <li>Omar Rivera</li>
          <li>Marco Góngora</li>
          <li>Janiel Escalante</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Sprint 3</li>
          <li>Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
</tbody>
</table>

# Contenido
[Student Outcome](#student-outcome)

[Capítulo I: Presentación](#capitulo-i-presentación)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
- [4.1. Strategic-Level-Domain-Driven Design](#41-strategic-level-domain-driven-design)
  - [4.1.1. EventStorming](#411-eventstorming)
  - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
  - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
  - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
- [4.1.2 Context Mapping](#412-context-mapping)
- [4.1.3 Software Architecture](#413-software-architecture)
  - [4.1.3.1. Software Architecture Context Level Diagramas](#4131-software-architecture-context-level-diagrams)
  - [4.1.3.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
  - [4.1.3.3. Software Architecture Deployment Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
  - [4.2.1. Bounded Context: <Bounded Context Name>](#421-bounded-context)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
      - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

[Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ui/ux-design)
- [5.1. Product Design](#51-product-design)
  - [5.1.1. Style Guidelines](#511-style-guidelines)
      - [5.1.1.1. General Style Guidelines](#5111-general-style-guidelines) 
  - [5.1.2. Information Architecture](#512-information-architecture)
      - [5.1.2.1. Organization Systems](#5121-organization-systems)
      - [5.1.2.2 Labelling Systems](#5122-labelling-systems)
      - [5.1.2.3 SEO Tags and Meta Tags](#5123-seo-tags-and-meta-tags)
      - [5.1.2.4 Searching Systems](#5124-searching-systems)
      - [5.1.2.5 Navigation Systems](#5125-navigation-systems)
  - [5.1.3. Landing Page UI Design](#513-landing-page-ui-design)
    - [5.1.3.1. Landing Page Wireframe](#5131-landing-page-wireframe)
    - [5.1.3.2. Landing Page Mock-up](#5132-landing-page-mock-up)
  - [5.1.4. Mobile Applications UX/UI Design](#514-mobile-applications-ux/ui-design)
    - [5.1.4.1. Mobile Applications Wireframes](#5141-mobile-applications-wireframes)
    - [5.1.4.2. Mobile Applications Wireflow Diagrams](#5142-mobile-applications-wireflow-diagrams)
    - [5.1.4.3. Mobile Applications Mock-ups](#5143-mobile-applications-mock-ups)
    - [5.1.4.4. Mobile Applications User Flow Diagrams](#5144-mobile-applications-user-flow-diagrams)
    - [5.1.4.5. Mobile Applications Prototyping](#5145-mobile-applications-prototyping)

[Capítulo VI: Product Implementation, Validations & Deployment](#capítulo-vi-product-implementation-validations-&-deployment)
- [6.1. Software Configuration Management](#61-software-configuration-management)
    - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
    - [6.1.2. Source Code Management](#612-source-code-management)
    - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-guide-&-conventions)
    - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
- [6.2. Landing Page & Mobile Application Implementation](#62-landing-page-&-mobile-application-implementation)
- [6.2.1. Sprint n](#621-sprint-n)
    - [6.2.1.1. Sprint Planning n](#6211-sprint-planning-n)
    - [6.2.1.2. Sprint Backlog n](#6212-sprint-backlog-n)
    - [6.2.1.3. Development Evidence for Sprint Review](#6213-development-evidence-for-sprint-review)
    - [6.2.1.4. Testing Suite Evidence for Sprint Review](#6214-testing-suite-evidence-for-sprint-review)
    - [6.2.1.5. Execution Evidence for Sprint Review](#6215-execution-evidence-for-sprint-review)
    - [6.2.1.6. Services Documentation Evidence for Sprint Review](#6216-services-documentation-evidence-for-sprint-review)
    - [6.2.1.7. Software Deployment Evidence for Sprint Review](#6217-software-deployment-evidence-for-sprint-review)
    - [6.2.1.8. Team Collaboration Insights during Sprint](#6218-team-collaboration-insights-during-sprint)
- [6.3. Validation Interviews](#63-validation-interviews)
- [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
- [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
- [6.3.3. Evaluaciones según Heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Video About-the-Product](#64-video-about-the-product)    

[Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome
ABET – EAC - Student Outcome 7

Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas. 

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
    </thead>
  <tbody>
    <tr>
      <td><b>Trabaja en equipo para
proporcionar liderazgo en
forma conjunta</b></td>
      <td>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
        <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p</p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Becerra Llempen, Fabiola Dayane</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Burga Loarte, Anaely Zarely</b></p>
        <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Rivera Ticllacuriv, Omar Harold</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Góngora Sánchez, Marco Antonio</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Escalante Baygorrea, Janiel Franz</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p>.</p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p></p>
        <p><strong>TP1:</strong></p>
        <p></p>
        <p><strong>TB2:</strong></p>
        <p></p>
        <p><strong>TF:</strong></p>
        <p></p>
      </td>
    </tr>
    <tr>
      <td>Crea un entorno colaborativo e
inclusivo, establece metas,
planifica tareas y cumple
objetivos</td>
      <td>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
        <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Becerra Llempen, Fabiola Dayane</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></b></p>
        <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Burga Loarte, Anaely Zarely</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p></p>
        <p><b>TB2:</b></p>
        <p></p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Rivera Ticllacuriv, Omar Harold</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Góngora Sánchez, Marco Antonio</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p></p>
        <p><b>Escalante Baygorrea, Janiel Franz</b></p>
       <p><b>TB1:</b></p>
        <p></p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p></p>
      </td>
       <td>
        <p><strong>TB1:</strong></p>
        <p></p>
        <p><strong>TP1:</strong></p>
        <p></p>
        <p><strong>TB2:</strong></p>
        <p></p>
        <p><strong>TF:</strong></p>
        <p></p>
      </td>
    </tr>
  </tbody>
</table>

# Capítulo I: Presentación
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

DebtGo es una aplicación que revoluciona la manera en que las personas acceden a préstamos empresariales y manejan sus deudas personales. Esta startup impulsa la implementación de una aplicación intuitiva, brindando a los usuarios las herramientas necesarias para gestionar sus deudas de manera efectiva y mejorar su conocimiento financiero. La aplicación ofrece herramientas avanzadas para la gestión de deudas, seguimiento de ingresos y gastos, y el asesoramiento personalizado por parte de consultores financieros expertos.

Hoy en día las obligaciones económicas desde muy temprana edad son una realidad y DebtGo es el mejor aliado para ayudar tanto a jóvenes empresarios como a personas con deudas personales a gestionar sus finanzas y economía para gozar de un bienestar financiero.

Nuestro modelo de negocio digital se centra principalmente en ofrecer servicios de consultoría financiera personalizada y talleres en línea, que los usuarios pueden adquirir por una tarifa adicional. Estos servicios permiten a los usuarios recibir asesoramiento adaptado a sus necesidades específicas y participar en sesiones educativas especializadas. Además, ofrecemos un servicio de suscripción, donde los usuarios pagan una tarifa mensual o anual para acceder a características premium, como análisis financieros detallados, planes de pago personalizados, y contenido educativo exclusivo. Este enfoque diversificado garantiza que DebtGo sea independiente y sostenible, proporcionando un flujo de ingresos continuo mientras se centra en la creación de valor para el usuario.

DebtGo no se basa en el comercio electrónico ni en la publicidad, sino que permite mantener una experiencia de usuario limpia y enfocada en el bienestar financiero. Además, el componente innovador del modelo radica en la personalización avanzada de los presupuestos y recomendaciones financieras adaptadas a las necesidades y hábitos de gasto de los usuarios, lo que distingue DebtGo de otras aplicaciones en el mercado.

A manera de escalabilidad, proponemos introducir a futuro el uso de inteligencia artificial para personalizar aún más las recomendaciones financieras y proveer retroalimentación a los usuarios en su progreso educativo.

### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       Soy estudiante de la UPC, tengo 19 años. Estoy en la carrera de Ingeniería de Software, ya que, siempre me gustó la tecnología, los videojuegos, las páginas web, pero sobre todo 
       cómo crearlos. Estoy cursando el 5 ciclo de la carrera y mis habilidades son C++, Python, HTML y JavaScript. También soy bueno en ser responsable con cada curso y organizar mi 
       tiempo en ellos.
      </p>
    </td>
  </tr>
   <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Becerra Llempen, Fabiola Dayane</b></p>
      <p>
        
      </p>
    </td>
  </tr>
     <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Burga Loarte, Anaely Zarely</b></p>
      <p>
      
      </p>
    </td>
  </tr>
     <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Rivera Ticllacuriv, Omar Harold</b></p>
      <p>
      
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Góngora Sánchez, Marco Antonio</b></p>
      <p>
       
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" width="800px">
    </th>
    <td valign="top">
      <p><b>Escalante Baygorrea, Janiel Franz</b></p>
      <p>
       
      </p>
    </td>
  </tr>
</table>

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

Muchas personas enfrentan la falta de conocimiento y claridad en relación con el estado de sus finanzas, lo cual es un problema que afecta a una gran parte de la población. Esta situación no solo se debe a la falta de educación financiera, sino también a la complejidad con la que a menudo se presentan los términos y condiciones de los productos crediticios. Como resultado, muchas personas desconocen no solo las fuentes exactas de sus deudas, sino también los montos originales, los intereses acumulados, y las posibles penalidades por pagos tardíos o incumplimientos. Por otro lado, los emprendedores enfrentan el desafío de los préstamos bancarios, sus condiciones y lo que implica pagar estos préstamos de vuelta, o no pagarlos a tiempo.  

Esta falta de información clara y accesible puede llevar a situaciones en las que los individuos no recuerdan cuándo adquirieron una deuda específica, cómo se calcularon los intereses o qué entidad financiera está gestionando sus pagos. Además, la carencia de recordatorios efectivos o herramientas que faciliten la gestión de sus obligaciones financieras puede hacer que las personas pierdan de vista las fechas de vencimiento de los pagos, lo que a su vez incrementa el riesgo de caer en mora. Este desconocimiento no solo afecta su historial crediticio, sino que también puede generar estrés significativo, impactos negativos en su salud mental y dificultades en su vida cotidiana.

A medida que las deudas se acumulan y se vuelven más difíciles de manejar, muchas personas se encuentran atrapadas en un ciclo de endeudamiento, donde la falta de claridad y organización agrava su situación financiera. Esto puede llevar a tomar decisiones desesperadas, como adquirir nuevas deudas para pagar las existentes, lo que finalmente incrementa la carga financiera y perpetúa un círculo vicioso de deuda. Es fundamental abordar este problema mediante la educación financiera, la transparencia en la información proporcionada por las instituciones crediticias, y el desarrollo de herramientas que permitan a los usuarios gestionar y entender mejor sus deudas. Solo así se podrá reducir la incidencia de problemas financieros graves y mejorar la calidad de vida de las personas afectadas.

**5Ws y 2Hs:**

**Qué:** La falta de educación financiera en el público general conlleva a varios problemas en el futuro de las personas, y afecta sus prospectos al momento de adquirir préstamos - sean estos préstamos personales o empresariales. DebtGo es una aplicación innovadora que proporciona a los usuarios una plataforma para interactuar directamente con consultores financieros expertos, que ofrecen atención personalizada a los casos específicos de cada usuario. Adicionalmente, cuenta con herramientas avanzadas para comprender, monitorear y gestionar sus deudas de manera intuitiva, mientras fortalecen su educación financiera. Ofrece funcionalidades como la creación de presupuestos personalizados, seguimiento de ingresos y gastos, y acceso a contenido educativo.

**Quién:** Está dirigida a dos segmentos principales: consultores financieros, y emprendedores. El primer segmento está comprendido por jóvenes profesionales, entre 20-30 años, que están entrando en el mercado laboral en carreras de finanzas. El segundo segmento abarca a emprendedores que requieren soluciones efectivas para manejar la adquisición de préstamos, deudas y mejorar su flujo de efectivo.

**Dónde:** El problema nace de la falta de educación financiera, lo que afecta a las personas a largo plazo, y se observa más comúnmente en la creación de deudas por falta de pagos

**Cuándo:** Este problema se visualiza durante los procesos de obtención de préstamos y cancelación de deudas, lo que para varios de los afectados, ocurre una vez el problema ha existido por largo tiempo, y lo hace más difícil revertir.

**Por qué:** La falta de conocimiento financiero y la complejidad en la gestión de deudas lleva a muchas personas a enfrentar estrés y dificultades financieras debido a la falta de claridad en sus obligaciones crediticias, lo que puede llevar a decisiones financieras deficientes y un ciclo de endeudamiento. La aplicación ofrece una solución integral para mejorar el bienestar financiero.

**Cómo:** La falta de educación financiera lleva a las personas a tomar decisiones desinformadas, lo que a su vez afecta su bienestar económico. Algunas de las consecuencias más comunes son la acumulación de deudas y la pérdida de ahorros. Esta situación de inestabilidad financiera impide alcanzar oportunidades y beneficios futuros. Mejorar la educación financiera es clave para romper estos patrones.

**Cuánto:** Miles de personas enfrentan problemas financieros por falta de educación financiera todos los días. En Estados Unidos, por ejemplo, la deuda total de tarjetas de crédito supera el trillón de dólares, y el consumidor promedio tiene más de $6000 de deuda. Mejorar la educación financiera es crucial para minimizar la brecha creada por este problema.


### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

Nuestra aplicación, DebtGo, está diseñada para ofrecer a los usuarios una herramienta poderosa que les permita gestionar sus deudas de manera efectiva, al mismo tiempo que fortalece su educación financiera. DebtGo se presenta como una oportunidad para que los usuarios mejoren su situación financiera, adoptando hábitos saludables que les permitan alcanzar sus objetivos económicos y evitar el ciclo de endeudamiento.

Sin embargo, hemos identificado ciertos factores que podrían ser desafíos significativos para la adopción de nuestra aplicación. Uno de los principales retos es la desconfianza que algunos usuarios pueden tener hacia una nueva empresa tecnológica. Esta desconfianza podría surgir del temor a que la aplicación no cumpla con sus expectativas o que no proporcione los resultados prometidos.

Ante estos desafíos, es crucial que abordemos las siguientes preguntas:

¿Cómo podemos construir confianza y credibilidad entre nuestros usuarios potenciales? Es fundamental demostrar que DebtGo es una herramienta confiable, segura y efectiva para la gestión de deudas. Estrategias como testimonios de usuarios, demostraciones de resultados tangibles, y certificaciones pueden ser claves para eliminar esta desconfianza.

¿Qué tan esencial es una aplicación de educación financiera en el contexto actual? Considerando el aumento del endeudamiento y la falta de educación financiera en diversos segmentos de la población, es primordial mostrar cómo DebtGo no solo facilita la gestión de deudas, sino que también empodera a los usuarios mediante el conocimiento, ayudándoles a tomar decisiones financieras informadas.

¿Cómo podemos motivar a las personas a reconocer el valor de nuestra aplicación? Es necesario comunicar claramente los beneficios y el impacto positivo que DebtGo puede tener en la vida financiera de los usuarios. El uso de casos de éxito, la oferta de pruebas gratuitas, y la integración de contenido educativo relevante pueden motivar a los usuarios a probar y adoptar la aplicación como una herramienta esencial en su vida diaria.

Al abordar estas preguntas de manera proactiva, buscamos no solo atraer a usuarios a DebtGo, sino también convertirnos en un aliado confiable en su camino hacia la estabilidad y el bienestar financiero.

#### 1.2.2.2. Lean UX Assumptions

1. Nuestros clientes una aplicación que no solo les ayude a gestionar sus deudas de manera efectiva, sino que también les ofrezca herramientas y recursos educativos para mejorar su 
   conocimiento financiero. DebtGo está diseñada para facilitar este proceso, permitiendo a los usuarios tomar el control de su situación financiera con mayor confianza y seguridad.

2. La aplicación busca empoderar a los jóvenes adultos con las habilidades necesarias para gestionar sus deudas y mejorar su educación financiera. La aplicación no solo les 
   proporcionará las herramientas para administrar sus finanzas, sino que también los educará sobre conceptos clave que les ayudarán a evitar futuras dificultades financieras.

3. Los usuarios iniciales de DebtGo serán personas mayores de 18 años que buscan una solución intuitiva y educativa para gestionar sus deudas. Este grupo incluye tanto a jóvenes adultos 
   que recién están comenzando a asumir responsabilidades financieras como a personas que desean mejorar su control sobre sus finanzas personales.

4. DebtGo planea generar ingresos a través de un modelo premium, donde los usuarios pueden acceder a funciones avanzadas mediante una suscripción. Esto nos permitirá monetizar a medida 
   que crece la base de usuarios y estos reconocen el valor adicional de las funciones premium.

5. Adquiriremos la mayoría de nuestros clientes a través de alianzas estratégicas con instituciones educativas, universidades, y organizaciones sin fines de lucro que promueven la 
   educación financiera. Ofreceremos seminarios y talleres gratuitos sobre gestión de deudas y finanzas personales, integrando el uso de DebtGo como una herramienta clave en estos 
   programas. Además, lanzaremos campañas de sensibilización en comunidades y foros en línea especializados en finanzas personales, donde podremos interactuar
   directamente con nuestro público objetivo, ofreciendo demostraciones y acceso a recursos exclusivos dentro de la aplicación.

6. Nuestra competencia incluye otras aplicaciones de gestión de deudas y educación financiera que ya están establecidas en el mercado. Sin embargo, DebtGo se diferencia por su enfoque 
   en la simplicidad, la personalización, y la educación financiera continua, que juntas ofrecen una experiencia única y valiosa para los usuarios.

7. Superaremos a nuestra competencia ofreciendo una aplicación que es altamente intuitiva y eficiente, diseñada para ser accesible incluso para aquellos sin conocimientos tecnológicos 
   avanzados. Además, la personalización de los planes de pago y la oferta de contenido educativo relevante nos posicionarán como la opción preferida entre los usuarios.

8. El mayor riesgo para DebtGo radica en la fuerte competencia en el mercado, lo que podría afectar nuestra rentabilidad. Con tantas opciones disponibles, los usuarios pueden optar por 
   aplicaciones más conocidas, lo que dificultará nuestra penetración y crecimiento en el mercado.

9. Para mitigar los riesgos, realizaremos un análisis exhaustivo de las fortalezas y debilidades de nuestra aplicación en comparación con las de la competencia. Utilizaremos esta 
   información para mejorar continuamente DebtGo, enfocándonos en optimizar la experiencia del usuario, ampliar la funcionalidad, y fortalecer nuestra propuesta de valor, asegurando así 
   la calidad y rentabilidad de la aplicación.

#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que al implementar más herramientas de notificaciones en la aplicación DebtGo, brindaremos a los usuarios alertas más eficaces sobre sus pagos pendientes. Éxito: Sabremos que hemos tenido éxito cuando el 80% de las llamadas registradas no presenten deudas pendientes.

Creemos que al añadir un mecanismo de categorización que permita a los usuarios seleccionar si son empresas o particulares, y que ajuste las funcionalidades de la aplicación según esa selección, mejoraremos la experiencia del usuario. Éxito: Sabremos que hemos tenido éxito cuando el 100% de los usuarios y empresas estén registrados formalmente en la plataforma.

Creemos que al ofrecer recompensas a los usuarios que paguen sus deudas de forma anticipada y sin retrasos, incentivaremos un comportamiento de pago puntual. Éxito: Sabremos que hemos tenido éxito cuando el porcentaje de deudas hacia la empresa disminuya en un 35%.

Creemos que al registrar de manera precisa a los usuarios que pagan y a los que no, reduciremos las llamadas innecesarias y optimizaremos el uso del tiempo. Éxito: Sabremos que hemos tenido éxito cuando el registro de usuarios de las empresas aumente en un 65%.

Creemos que la falta de actualizaciones o implementaciones de software tempranas en la aplicación afectará negativamente la gestión de deudas. Fracaso: Sabremos que hemos fracasado cuando las deudas de las empresas aumenten en un 25%.

Creemos que al no contar con un sistema de seguridad actualizado y moderno en nuestra aplicación, seremos vulnerables a ataques cibernéticos o intentos de hackeo. Fracaso: Sabremos que hemos fracasado cuando los ataques cibernéticos al sistema DebtGo aumenten en un 48%.

#### 1.2.2.4. Lean UX Canvas

 <img src="assets/Chapter-1/canva1.png" width="800px">

 *Imagen (N°1). Elaboración propia. Realizado en Canva*

## 1.3. Segmentos objetivo

<strong>1. Consultores financieros:</strong>

Descripción: Este segmento incluye a jóvenes jóvenes profesionales, que se encuentran entrando al mercado laboral, o que se encuentren en los últimos ciclos de la universidad para carreras de finanzas, economía y afines. (20-30 años). Estas personas van a estar interesadas en adquirir ganancias extras y adquirir experiencia relevante en el mercado laboral.

Necesidades Satisfechas: DebtGo les ofrece la oportunidad para comprartir sus conocimientos de manera flexible y conveniente, mientras adquieren experiencia en el sector de consultoría que pueden utilizar para ampliar sus experiencias y habilidades al momento de aplicar para otros empleos en el futuro.

<strong>2. Emprendedores</strong>
   
Descripción: Este segmento abarca a personas con emprendedimientos o propietarios de pequeñas empresas, y aquellos que necesitan préstamos para iniciar o expandir sus negocios. Estos individuos enfrentan situaciones financieras apremiantes y buscan soluciones rápidas y efectivas para gestionar sus negocios, sus deudas y mejorar su flujo de efectivo.

Necesidades Satisfechas: DebtGo les proporciona una plataforma centralizada para gestionar y consolidar sus deudas, crear planes de pago personalizados, y evitar el pago de intereses adicionales. Además, se ofrece el servicio de consultoría personalizada con consultores financieros expertos, que tienen experiencia en el rubro y la habilidad para ayudar a estos emprendedores a realizar sus objetivos.
