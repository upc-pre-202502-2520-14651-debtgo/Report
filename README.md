<hr>

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"" alt="Logo de UPC" />
</div>

# <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

### <p align="center">Carrera de Ingeniería de Software</p>

<p align="center"><strong>Período:</strong> 202520</p>

<p align="center"><strong>1ASI0732 | Diseño de Experimentos de Ingeniería de Software </strong> </p>
<p align="center"><strong>NRC:</strong>14651</p>
<p align="center"><strong>Docente:</strong>Juan Carlos Tinoco Licas</p>

---

# <p align="center">Informe de Trabajo final</p>

<p align="center">
    <strong>Startup: DebtGo</strong><br>
    <strong>Producto: Luxus </strong>
</p>

<div style="text-align:center;">
    <h3>Relación de integrantes:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Integrante</th>
            <th style="text-align:center;">Código</th>
        </tr>
        <tr>
            <td>Chavarri Zarzosa, Daniel Jhared</td>
            <td>U202211108</td>
        </tr>
        <tr>
            <td>Peña Riofrio, Maria Fernanda</td>
            <td>U202113279</td>
        </tr>
        <tr>
            <td>Gamarra Vega, Anderson José William</td>
            <td>U202016154</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Noviembre, 2025</strong>
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
                <th>Avance 1</th>
                <td>20/09/2025</td>
                <td><ul>
                  <li>Daniel Chávarri</li>
                  <li>Maria Fernanda Peña</li>
                  <li>Adriana Campos</li>
                  <li>Anderson Gamarra</li>
                <ul></td>
              <td><ul>
                <li>Capítulo I: Introducción</li>
                <li>Capítulo II: Requirements Elicitation & Analysis</li>
                <li>Capítulo III: Requirements Specification</li>
                <li>Capítulo IV: Product Design</li>
                <li>Capítulo V: Product Implementation</li>
                <li>Avance de Conclusiones, Bibliografía y Anexos</li>
              </ul></td>
            </tr>
        </tbody>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>10/10/2025</td>
                <td><ul>
                  <li>Daniel Chávarri</li>
                  <li>Maria Fernanda Peña</li>
                  <li>Anderson Gamarra</li>
                <ul></td>
              <td><ul>
                <li>Capítulo III: Requirements Specification</li>
                <li>Capítulo V: Product Implementation</li>
                <li>Capítulo VI: Product Verification & Validation</li>
                <li>Capítulo VII: DevOps Practices</li>
                <li>Avance de Conclusiones, Bibliografía y Anexos</li>
              </ul></td>
            </tr>
        </tbody>
         <tbody>
            <tr>
                <th>Avance 2</th>
                <td>13/10/2025</td>
                <td><ul>
                  <li>Daniel Chávarri</li>
                  <li>Maria Fernanda Peña</li>
                  <li>Anderson Gamarra</li>
                <ul></td>
              <td><ul>
                <li>Capítulo VI: Product Verification & Validation</li>
                <li>Capítulo VII: DevOps Practices</li>
                <li>Capítulo VIII: Experiment-Driven Development</li>
                <li>Avance de Conclusiones, Bibliografía y Anexos</li>
              </ul></td>
            </tr>
        </tbody>
</table>

# Contenido
[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capitulo-i-introducción)
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
- [3.3. Product Backlog](#33-product-backlog)
- [3.4. Impact Mapping](#34-impact-mapping)

[Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
    - [4.1.3.1. IOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
    - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labelling Systems](#422-labelling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-ux/ui-design)
  - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
  - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
  - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
  - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
- [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
  - [4.5.1 Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
  - [4.5.2 IOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
- [4.6. Web Applications UX/UI Design](#46-web-applications-ux/ui-design)
  - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
  - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
  - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
  - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
- [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
- [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture) 
  - [4.8.1. Software Architecture Context Level Diagramas](#4131-software-architecture-context-level-diagrams)
  - [4.8.2. Software Architecture Container Level Diagrams](#4132-software-architecture-container-level-diagrams)
  - [4.8.3. Software Architecture Components Diagrams](#4133-software-architecture-deployment-diagrams)
- [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
  - [4.9.1. Class Diagrams](#491-class-diagrams)
  - [4.9.2. Class Dictionary](#492-class-dictionary)
- [4.10. Database Design](#410-database-design)
  - [4.10.1. Relational/No-Relational Database Diagram](#4101-relational/no-relational-database-diagram)

[Capítulo V: Product Implementation](#capítulo-v-solution-ui/ux-design)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-guide-&-conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Product Implementation & Deployment](#52-product-implementation-&-deployment)
  - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
  - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
  - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
  - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio-saas)
  - [5.2.5. Implemented Native-Mobile-Application Evidence](#524-implemented-native-mobile-application-evidence)
  - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-and/or-serverless-backend-evidence)
  - [5.2.7. RESTful API documentation](#526-restful-api-documentation)
  - [5.2.8. Team Collaboration Insights](#527-team-collaboration-insights)
 - [5.3. Video About-the-Product](#53-video-about-the-product)
      
[Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification-&-validation)
- [6.1. Testing Suites & Validation](#61-testing-suites-&-validation)
  - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
  - [6.1.2. Core Integration Tests](#612-core-integration-tests)
  - [6.1.3. Core Behavior-Driven-Development](#613-core-behavior-driven-development)
  - [6.1.4. Core System Tests](#614-core-system-tests)
- [6.2. Static testing & verfication](#62-static-testing--verification)
  - [6.2.1. Static Code Analysis](#621-static-code-analysis)
  - [6.2.1.1. Coding standard & Code conventions](#6211-coding-standard--code-conventions)
  - [6.2.1.2. Code Quality & Code Security](#6212-code-quality--code-security)
  - [6.2.2. Reviews](#622-reviews)
- [6.3. Validation Interviews](#63-validation-interviews)
  - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
  - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
  - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
- [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
  - [6.4.1. Auditoría realizada](#641-auditoría-realizada)
    - [6.4.1.1. Información del grupo auditado](#6411-información-del-grupo-auditado)
    - [6.4.1.2. Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)
    - [6.4.1.3. Contenido de auditoría realizada](#6413-contenido-de-auditoría-realizada)
  - [6.4.2. Auditoría recibida](#642-auditoría-recibida)
    - [6.4.2.1. Información del grupo auditor](#6421-información-del-grupo-auditor)
    - [6.4.2.2. Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)
    - [6.4.2.3. Contenido de auditoría recibida](#6423-contenido-de-auditoría-recibida)
    - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)

[Capítulo VII: DevOps Practices](capítulo-vii-devops-practices)
- [7.1. Continuous Integration](#71-continuous-integration)
  - [7.1.1. Tools and Practices](#711-tools-and-practices)
  - [7.1.2. Build & Test Suite Pipeline Components](#712-build-&-test-suite-pipeline-components)
- [7.2. Continuous Delivery](#72-continuous-delivery)
  - [7.2.1. Tools and Practices](#721-tools-and-practices)
  - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
- [7.3. Continuous Deployment](#73-continuous-deployment)
   - [7.3.1. Tools and Practices](#731-tools-and-practices)
   - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
- [7.4. Continuous Monitoring](#74-continuous-monitoring)
  - [7.4.1. Tools and Practices](#741-tools-and-practices)
  - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
  - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
  - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)

[Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
- [8.1. Experiment Planning](#81-experiment-planning)
  - [8.1.1. As-Is Summary](#811-as-is-summary)
  - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
  - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
  - [8.1.4. Question Backlog](#814-question-backlog)
  - [8.1.5. Experiment Cards](#815-experiment-cards)
- [8.2. Experiment Design](#82-experiment-design)
  - [8.2.1. Hypotheses](#821-hypotheses)
  - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
  - [8.2.3. Measures](#823-measures)
  - [8.2.4. Conditions](#824-conditions)
  - [8.2.5. Scale Calculations and Decisions](#825-scale-calculations-and-decisions)
  - [8.2.6. Methods Selection](#826-methods-selection)
  - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)
  - [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
- [8.3. Experimentation](#83-experimentation)
  - [8.3.1. To-Be User Stories](#831-to-be-user-stories)
  - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)


[Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome
ABET – EAC - Student Outcome 4

Criterio: La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de Ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
    </thead>
  <tbody>
    <tr>
      <td><b>4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software</b></td>
      <td>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
        <p><b>Avance 1:</b></p>
        <p>Hice el Capítulo I, Capítulo II, Capítulo III y Capítulo IV, de igual manera, me aseguré de que todo vaya de acorde a los puntos indicados para la tb1.</p>
        <p><b>TB1:</b></p>
        <p>Configure el control de acceso por rol y protección de credenciales (hashing de contraseñas, variables de entorno</p>
        <p><b>Avance 2:</b></p>
        <p>Aseguró accesibilidad básica en la web (contraste, semántica, etiquetas) para no excluir usuarios</p>
        <p><b>Peña Riofrio, Maria Fernanda</b></p>
        <p><b>Avance 1:</b></p>
        <p>Realice una entrevista y desarrolle su respectivo análisis, con esto se reconoció la importancia de manejar la información de la entrevista con responsabilidad.</p>
        <p><b>TB 1:</b></p>
        <p>Prepare plan de respuesta a incidentes (contención, comunicación al usuario, remediación).</p>
        <p><b>Avance 2:</b></p>
        <p>Documentó políticas de registro de auditoría (quién hizo qué y cuándo) para trazabilidad y resolución de incidentes.</p>
        <p><b>Gamarra Vega, Anderson José William</b></p>
        <p><b>Avance 1:</b></p>
        <p>Realicé una entrevista y desarrollé algunos de los puntos establecidos en la TB1, asegurándome de manejar de manera ética la información recopilada.</p>
        <p><b>TB1:</b></p>
        <p>Lideró revisiones estáticas (estilo, seguridad, dependencia) y checklist de privacidad por diseño en PRs.</p>
        <p><b>Avance 2:</b></p>
        <p>Validó términos y avisos de privacidad en registro e inicio de sesión (transparencia en tratamiento de datos).</p>
      </td>
      <td>
        <p><strong>Avance 1:</strong></p>
        <p>Para la primera entrega, se realizó la investigación de los respectivos capítulos, manteniendo la responsabilidad ética y profesional en el desarrollo.</p>
        <p><strong>TB 1:</strong></p>
        <p>Para la segunda entrega, se probaron flujos con datos ficticios, reforzando accesibilidad, consentimiento y revisiones de seguridad en PR..</p>
        <p><strong>Avance 2:</strong></p>
        <p>Para la tercera entrega, con CI/CD y escaneo de dependencias, el equipo demostró cumplimiento sistemático de prácticas éticas y operativas (auditoría, gestión de incidentes, minimización de PII).</p>
      </td>
    </tr>
    <tr>
      <td><b>4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales</b></td>
      <td>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
        <p><b>Avance 1:</b></p>
        <p>Hice el Capítulo I, Capítulo II, Capítulo III y Capítulo IV, de igual manera, me aseguré de que todo vaya de acorde a los puntos indicados para la tb1.</p>
        <p><strong>TB 1:</strong></p>
        <p>Evalue riesgos de sobre-endeudamiento en funcionalidades (mensajes educativos, límites y advertencias).</p>
        <p><strong>Avance 2:</strong></p>
        <p>Priorice eficiencia de recursos en el backend (costo/energía) y reutilización de infraestructura.</p>
        <p><b>Peña Riofrio, Maria Fernanda</b></p>
        <p><b>Avance 1:</b></p>
        <p>A partir del análisis del video, se reflexionó sobre cómo una solución futura de software respondería a las necesidades del segmento entrevistado.</p>
        <p><strong>TB 1:</strong></p>
        <p>Analice el impacto económico y social de planes (Basic/Premium) para inclusión financiera y transparencia de precios..</p>
        <p><strong>Avance 2:</strong></p>
        <p>Realice que los dark patterns se evitarán en UX (opt-in real, cancelación visible), favoreciendo decisiones informadas del usuari</p>
        <p><b>Gamarra Vega, Anderson José William</b></p>
        <p><b>Avance 1:</b></p>
        <p>Realicé una entrevista y participé en el desarrollo de diferentes puntos de la TB1, considerando el impacto que tendría una futura solución de software en los aspectos sociales y económicos del contexto estudiado.</p>
        <p><strong>TB 1:</strong></p>
        <p>Consideró escalabilidad por regiones (latencia, regulaciones locales de datos) y localización (moneda, idioma).</p>
        <p><strong>Avance 2:</strong></p>
        <p>Propuso contenido educativo integrado (ahorro, presupuesto responsable) para beneficio social directo.</p>
      </td>
       <td>
        <p><strong>Avance 1:</strong></p>
        <p>Para la primera entrega, se realizaron los respectivos capítulos, donde se consideraron contextos globales en la presentación y elaboración de nuestro proyecto como una solución de ingeniería de software.</p>
        <p><strong>TB 1:</strong></p>
        <p>Para la segunda entrega, Los experimentos priorizaron métricas de bienestar del usuario (retención saludable, comprensión de riesgo) por encima de métricas de vanidad.</p>
        <p><strong>Avance 2:</strong></p>
        <p>Para la tercera entrega, Se consolidó un producto socialmente responsable, con educación financiera integrada, mensajes preventivos y operación eficiente con visión global (idioma/moneda/latencia).</p>
      </td>
    </tr>
  </tbody>
</table>

# Capítulo I: Introducción
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
      <img src="assets/Chapter-1/daniel.jpeg" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       Soy estudiante de la UPC, tengo 20 años. Estoy en la carrera de Ingeniería de Software, ya que, siempre me gustó la tecnología, los videojuegos, las páginas web, pero sobre todo 
       cómo crearlos. Estoy cursando el 6 ciclo de la carrera y mis habilidades son C++, Python, HTML y JavaScript. También soy bueno en ser responsable con cada curso y organizar mi 
       tiempo en ellos.
      </p>
    </td>
  </tr>
   <tr>
    <th>
      <img src="assets/Chapter-1/Mafer.jpg" width="800px">
    </th>
    <td valign="top">
      <p><b>Peña Riofrio, Maria Fernanda</b></p>
      <p>
        Soy estudiante de la UPC, tengo 21 años. Estudio la carrera de Ingeniería de Software, porque me gusta el desarrollo de web y mobile. Ando cursando el 7mo ciclo de la carrera y tengo conocimiento en en C++ y Pyhton. Ade
      </p>
    </td>
  </tr>
     <tr>
    <th>
      <img src="assets/Chapter-1/adriana.jpg"  width="800px">
    </th>
    <td valign="top">
      <p><b>Ramos Fuentes Rivera, Adriana Nicole</b></p>
      <p>
          Mi nombre es Adriana Nicole Ramos Fuentes Rivera, actualmente soy estudiante de la carrera de Ingeniería de Software en la UPC. Me interesa la tecnología y cómo su aplicación puede agilizar diversos procesos. Considero que mis conocimientos adquiridos a lo largo de la carrera, me ayudarán a aportar de manera activa al desarrollo del presente proyecto.
      </p>
    </td>
  </tr>
     <tr>
    <th>
      <img src="assets/Chapter-1/anderson.jpg" width="800px">
    </th>
    <td valign="top">
      <p><b>Gamarra Vega, Anderson José William</b></p>
      <p>
          Mi nombre es Anderson Jose Gamarra Vega, tengo 25 años , estudiante de Ingeniería de Software. Desde siempre he sentido una gran pasión por la tecnología, pero me decanto especialmente por el desarrollo de software, pues me fascina aprender nuevos lenguajes de programación, diseñar soluciones digitales y afrontar retos mediante código. Esta inclinación hacia el software fue lo que me motivó a elegir esta carrera, y actualmente estoy profundizando en áreas como backend, arquitectura de software, metodologías agile.
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

 <img src="assets/Chapter-1/canva.png" width="800px">

 *Imagen (N°1). Elaboración propia. Realizado en Canva*

## 1.3. Segmentos objetivo

<strong>1. Consultores financieros:</strong>

Descripción: Este segmento incluye a jóvenes jóvenes profesionales, que se encuentran entrando al mercado laboral, o que se encuentren en los últimos ciclos de la universidad para carreras de finanzas, economía y afines. (20-30 años). Estas personas van a estar interesadas en adquirir ganancias extras y adquirir experiencia relevante en el mercado laboral.

Necesidades Satisfechas: DebtGo les ofrece la oportunidad para comprartir sus conocimientos de manera flexible y conveniente, mientras adquieren experiencia en el sector de consultoría que pueden utilizar para ampliar sus experiencias y habilidades al momento de aplicar para otros empleos en el futuro.

<strong>2. Emprendedores</strong>
   
Descripción: Este segmento abarca a personas con emprendedimientos o propietarios de pequeñas empresas, y aquellos que necesitan préstamos para iniciar o expandir sus negocios. Estos individuos enfrentan situaciones financieras apremiantes y buscan soluciones rápidas y efectivas para gestionar sus negocios, sus deudas y mejorar su flujo de efectivo.

Necesidades Satisfechas: DebtGo les proporciona una plataforma centralizada para gestionar y consolidar sus deudas, crear planes de pago personalizados, y evitar el pago de intereses adicionales. Además, se ofrece el servicio de consultoría personalizada con consultores financieros expertos, que tienen experiencia en el rubro y la habilidad para ayudar a estos emprendedores a realizar sus objetivos.

# Capítulo II: Requirements Elicitation & Analysis 

## 2.1. Competidores

Comprender el panorama competitivo es crucial para el éxito de DebtGo. En esta sección, identificaremos y describiremos a nuestros principales competidores directos e indirectos que operan en el ámbito de la gestión de deudas y la educación financiera. Analizaremos sus modelos de negocio, estrategias de marketing, productos y servicios, y los canales de distribución que utilizan. Además, realizaremos un análisis comparativo detallado de sus fortalezas, debilidades, oportunidades y amenazas (SWOT) en relación con DebtGo. Este análisis nos permitirá entender mejor el entorno competitivo y ajustar nuestras estrategias para maximizar nuestra ventaja en el mercado.

1. Mint (Intuit): Mint es una aplicación popular para la gestión de finanzas personales que ofrece seguimiento de gastos, presupuestos y alertas financieras. Es conocida por su interfaz intuitiva y sus capacidades de agregación de datos financieros.

2. You Need a Budget (YNAB): YNAB se centra en la creación de presupuestos y la gestión de finanzas personales mediante un enfoque basado en la asignación de cada dólar a una tarea específica. Ofrece herramientas para planificar el gasto y gestionar las deudas.

3. Credit Karma: Credit Karma ofrece herramientas para el seguimiento del crédito, la gestión de deudas y la comparación de productos financieros. Aunque su enfoque principal es el monitoreo del crédito, también proporciona recomendaciones para la gestión de deudas.

## 2.1.1. Analisis competitivo

El análisis competitivo implica examinar detenidamente a nuestros competidores para identificar sus fortalezas, debilidades, oportunidades y amenazas. Esto nos proporcionará una visión clara de nuestro posicionamiento en el mercado y nos ayudará a desarrollar estrategias efectivas.

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">El análisis competitivo es fundamental para entender el entorno en el que DebtGo opera, identificar las fortalezas y debilidades de los competidores, y descubrir oportunidades y amenazas en el mercado. Este análisis ayuda a posicionar mejor nuestra startup en relación con los competidores y a definir estrategias que maximicen nuestra ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="3">Nombre y Logo</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        DebtGo
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/Chapter-2/debtgo-logo.png" alt="Logo DebtGo" style="width: 65;"></img>
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    Mint
    <div style="text-align: center;">
                <img src="assets/Chapter-2/mint-logo.png" alt="Logo Mint" style="width: 40;"></img>
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      YNAB
      <div style="text-align: center; margin-top: 20px;">
                <img src="assets/Chapter-2/ynab-logo.png" alt="Logo YNAB" style="width: 65;"></img>
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Credit Karma
      <div style="text-align: center; margin-top: 10px;">
                <img src="assets/Chapter-2/credit-karma-logo.png" alt="Logo Credit Karma" style="width: 65;"></img>
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Aplicación para gestionar deudas y educación financiera. Ofrece herramientas para seguimiento de ingresos, gastos y presupuestos.</td>
    <td colspan="1" valign="top">Plataforma para gestión de finanzas personales con seguimiento de gastos y presupuestos.</td>
    <td colspan="1" valign="top">Herramienta enfocada en la creación de presupuestos y asignación de fondos.</td>
    <td colspan="1" valign="top">Servicio de monitoreo de crédito con herramientas de gestión de deudas y recomendaciones financieras.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva¿Qué valor ofrece a los clientes?</td>
    <td colspan="1" valign="top">Personalización avanzada de presupuestos y recomendaciones financieras.</td>
    <td colspan="1" valign="top">Amplia integración con cuentas bancarias y tarjetas.</td>
    <td colspan="1" valign="top">Enfoque en la metodología de presupuesto y planificación.</td>
    <td colspan="1" valign="top">Monitoreo de crédito gratuito y recomendaciones personalizadas.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Jóvenes y adultos que desean mejorar su educación financiera y gestionar sus deudas.</td>
    <td colspan="1" valign="top">Usuarios interesados en el seguimiento de gastos y la gestión financiera.</td>
    <td colspan="1" valign="top">Personas que buscan un enfoque riguroso en la creación y seguimiento de presupuestos.</td>
    <td colspan="1" valign="top">Usuarios que desean monitorear su crédito y gestionar deudas.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Marketing digital dirigido a usuarios interesados en finanzas personales.</td>
    <td colspan="1" valign="top">Publicidad a través de canales digitales y colaboraciones con influencers financieros.</td>
    <td colspan="1" valign="top">Marketing basado en testimonios y demostraciones del enfoque de presupuesto.</td>
    <td colspan="1" valign="top">Publicidad a través de contenido educativo sobre crédito y finanzas personales.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Aplicación móvil con suscripción para características premium y servicios de consultoría financiera personalizada.</td>
    <td colspan="1" valign="top">Aplicación gratuita con opciones premium para características avanzadas.</td>
    <td colspan="1" valign="top">Suscripción mensual para acceso a herramientas de presupuesto y planificación.</td>
    <td colspan="1" valign="top">Aplicación gratuita con características premium para monitoreo avanzado y recomendaciones.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">Tarifa mensual o anual para suscripción premium, tarifas adicionales para consultoría y talleres.</td>
    <td colspan="1" valign="top">Gratuita con opciones de pago para características adicionales.</td>
    <td colspan="1" valign="top">Suscripción mensual o anual.</td>
    <td colspan="1" valign="top">Gratuita con opciones de pago para características avanzadas.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Web y móvil (iOS y Android).</td>
    <td colspan="1" valign="top">Web y móvil (iOS y Android).</td>
    <td colspan="1" valign="top">Web y móvil (iOS y Android).</td>
    <td colspan="1" valign="top">Web y móvil (iOS y Android).</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Innovación en personalización y enfoque en educación financiera.</td>
    <td colspan="1" valign="top">Amplia integración con bancos y tarjetas.</td>
    <td colspan="1" valign="top">Método comprobado de asignación de presupuesto.</td>
    <td colspan="1" valign="top">Monitoreo de crédito gratuito y recomendaciones personalizadas.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Falta de reconocimiento de marca en comparación con competidores establecidos.</td>
    <td colspan="1" valign="top">Dependencia de ingresos por publicidad y promociones.</td>
    <td colspan="1" valign="top">Curva de aprendizaje en la metodología de presupuesto.</td>
    <td colspan="1" valign="top">Limitación en la profundidad del análisis de finanzas más allá del crédito.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Creciente interés en la educación financiera y gestión de deudas.</td>
    <td colspan="1" valign="top">Expansión en mercados internacionales.</td>
    <td colspan="1" valign="top">Integración de características adicionales basadas en IA.</td>
    <td colspan="1" valign="top">Expansión en servicios de planificación financiera.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Competencia creciente y posibles cambios en regulaciones financieras.</td>
    <td colspan="1" valign="top">Competencia de aplicaciones de finanzas personales más integrales.</td>
    <td colspan="1" valign="top">Competencia de plataformas con características similares.</td>
    <td colspan="1" valign="top">Cambios en regulaciones de crédito y competencia de herramientas de gestión financiera.</td>
  </tr>
</table>

## 2.1.2. Estrategias y tácticas frente a competidores

Desarrollar estrategias y tácticas sólidas para enfrentar a nuestros competidores es fundamental para alcanzar una ventaja competitiva sostenible. En esta sección, exploraremos cómo podemos diferenciarnos y destacarnos en el mercado.

<strong>Estrategias y Tácticas Preliminares de DebtGo:</strong>

#1 Diferenciación a través de Persoanlización Avanzada:
- **Estrategia:** Posicionar a DebtGo como la opción más avanzada en personalización de presupuestos y recomendaciones financieras.
- **Táctica:** Desarrollar y promocionar funcionalidades de inteligencia artificial que ofrezcan recomendaciones financieras ultra-personalizadas. Realizar campañas de marketing que destaquen esta capacidad única y cómo se traduce en mejores resultados financieros para los usuarios.

#2 Enfoque en Educación Financiera:
- **Estrategia:** Aprovechar el interés creciente en la educación financiera para atraer usuarios que buscan mejorar su bienestar financiero a través de conocimientos prácticos y personalizados.
- **Táctica:** Ofrecer contenido educativo exclusivo y talleres interactivos como parte del paquete premium. Publicar estudios de caso y testimonios de usuarios que han logrado mejorar sus finanzas utilizando DebtGo.

#3 Optimización de la Experiencia de Usuario (UX):
- **Estrategia:** Garantizar que la experiencia de usuario sea superior y sin distracciones, en comparación con competidores que dependen de modelos basados en publicidad.
- **Táctica:** Implementar una interfaz de usuario intuitiva y realizar pruebas continuas para optimizar la navegación y la usabilidad. Recolectar y analizar feedback de usuarios para realizar mejoras continuas.

#4 Innovación Tecnológica:
- **Estrategia:** Utilizar la tecnología de vanguardia para mantener una ventaja competitiva y diferenciarse en el mercado.
- **Táctica:** Invertir en el desarrollo de tecnologías emergentes, como el aprendizaje automático y la inteligencia artificial, para ofrecer características innovadoras que los competidores aún no tienen. Lanzar nuevas funcionalidades en fases para mantener el interés y la retención de los usuarios.
 
#5 Vigilancia y Adaptación Continua:
- **Estrategia:** Monitorear continuamente el panorama competitivo para adaptar las estrategias y tácticas en función de las tendencias y cambios del mercado.
- **Tácticas:** Establecer un equipo dedicado a la investigación competitiva y al análisis del mercado. Ajustar las estrategias de marketing y producto basadas en la evolución de las ofertas de los competidores y las expectativas de los usuarios.

Estas estrategias y tácticas nos ayudarán a posicionar a DebtGo de manera efectiva en el mercado, aprovechando sus fortalezas y oportunidades mientras se enfrentan a las debilidades y amenazas que presentan los competidores.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

**Segmento Objetivo: Consultores financieros:**

1. ¿Cuál es su nombre completo?
2. ¿Cuál es su edad?
3. ¿En qué distrito reside actualmente?
4. ¿Cuál es su ocupación/profesión y cuántos años de experiencia tiene en el campo de la economía o la consultoría financiera?
5. ¿Está familiarizado con el término "educación financiera"? ¿Cómo lo definiría en su propio contexto profesional?
6. ¿Qué dispositivos tecnológicos utiliza con mayor frecuencia en su trabajo diario? ¿Cuál considera más esencial para su actividad profesional?
7. ¿Qué redes sociales utiliza para mantenerse actualizado en temas financieros o económicos? ¿Cómo las utiliza en su práctica profesional?
8. ¿Ha visto algún tipo de anuncio o promoción relacionada con aplicaciones de gestión financiera en su dispositivo? ¿Cuál fue su impresión?
9. ¿En su rol actual, gestiona o asesora sobre responsabilidades económicas de empresas o individuos? ¿Podría darme un ejemplo?
10. ¿Conoce INFOCORP u otras bases de datos de informes crediticios? ¿Qué importancia les da en su práctica profesional?
11. ¿Qué desafíos ve en la gestión de finanzas personales de sus clientes o en su propia vida financiera?
12. ¿Ha utilizado o recomendado alguna aplicación para la gestión de finanzas personales o empresariales? ¿Qué características le parecen más útiles?
13. En su opinión, ¿cuál es la necesidad más importante en la educación financiera de las personas actuales? ¿Cómo cree que una app como DebtGo podría abordar esta necesidad?
14. ¿Considera que una aplicación de gestión financiera personalizada puede tener un impacto significativo en la mejora de las finanzas personales de los usuarios? ¿Por qué sí o por qué no?

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

1. ¿Cuál es su nombre completo?
2. ¿Cuál es su edad?
3. ¿En qué distrito reside actualmente?
4. ¿Qué tipo de empresa estás interesado en iniciar?
5. ¿Cuál es tu nivel de conocimiento de finanzas? 
6. ¿Has trabajado con consultores financieros anteriormente? ¿Crees que deberían tener experiencia en tu rubro para poder asesorarte?
7. ¿Tienes alguna experiencia en la obtención de préstamos?
8. ¿Está familiarizado con términos financieros como crédito, interés, liquidez, etc.? 
9. ¿Qué pasos en el proceso de la obtención de préstamos resultan más confusos?
10. ¿Qué te preocupa más al momento de solicitar préstamos para tu negocio? (ie.  interés, condiciones, etc)
11. ¿A qué plataformas consideras acudir para adquirir préstamos? ¿Por qué?
12. ¿Qué criterios utilizas para identificar si una publicidad de préstamos es real, o si es un intento de estafa?
13. ¿Utilizas aplicaciones de banca móvil? ¿Cómo te sientes acerca del nivel de seguridad ofrecido por estas aplicaciones?
14. ¿A qué nivel estarías dispuesto a compartir tus datos financieros en una aplicación de consultas financieras?
15. ¿Qué condiciones o garantías lo harían sentir más seguro al momento de compartir información financiera?

### 2.2.2. Registro de entrevistas

**Segmento Objetivo: Consultores financieros:**

**Entrevista #1**

- Nombre: George Garcia Durand
- Edad: 20 años
- Distrito: Rimac
- Duración: 4:57

![image](assets/Chapter-2/George.png)

[Entrevista 1 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQ77TmeMzZxLv83IOvsXFtMBa3PM7kygfpVsY93jZnukZg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=ReJpXc)

Resumen:
En la entrevista realizada a George Garcia Durand , graduado en finanzas de 20 años y residente en Rímac, se abordaron temas relacionados a la gestión financiera personal y empresarial. George destacó la importancia de la educación financiera para tomar decisiones informadas sobre el manejo del dinero y señaló que su herramienta principal de trabajo es la laptop, aunque también utiliza su celular. Se actualiza en temas financieros a través de LinkedIn, Twitter y YouTube. Comentó que, aunque es escéptico respecto a muchas aplicaciones de finanzas debido a la publicidad engañosa, ha utilizado y recomendado Monefy y Fintonic, valorando su utilidad para el control de gastos e ingresos, aunque considera que deberían ofrecer más opciones de planificación de inversiones. Señaló como principal desafío financiero la falta de cultura de ahorro y planificación en el Perú, y considera que DatGo podría ser una solución efectiva si proporciona asesoría personalizada, seguimiento de deudas y educación financiera, ayudando a mejorar significativamente la gestión financiera de los usuarios.




**Entrevista #2**
- Nombre: Andrea Rodriguez
- Edad:  25
- Distrito: Lima Metropolitana
- Duración: 4:16

![image](assets/Chapter-2/entrevista2.png)

[Entrevista 2 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20171a518_upc_edu_pe/EU1lsdp9xb1LhrNE8agEurYBKbswyKpiqfpP9_WjLU-68w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=eU3MGz)

Resumen: 
Andrea Rodriguez, consultora financiera con 4 años de experiencia, reside en Lima y trabaja activamente asesorando a emprendedores y particulares en temas económicos. Tiene un fuerte conocimiento del concepto de educación financiera, que aplica como herramienta clave para tomar decisiones económicas informadas.

En su práctica diaria, utiliza principalmente dispositivos móviles por su practicidad, y se mantiene actualizada en temas financieros a través de redes sociales como LinkedIn y X. Ha notado la presencia de promociones de apps de gestión financiera, considerándolas útiles para el control de gastos.

Andrea usa bases de datos como INFOCORP para evaluar historiales crediticios y ha recomendado aplicaciones como YNAB y Mint por sus funciones prácticas. Identifica como principal desafío financiero la falta de planificación, y cree que una app como DebtGo podría cubrir necesidades actuales mediante recordatorios y seguimiento personalizado. Considera que una aplicación de este tipo sí puede mejorar significativamente las finanzas personales si se utiliza correctamente.


**Entrevista #3**
- Nombre: Yacori Lucero 
- Edad: 23
- Distrito: Surco
- Duración: 3:53

![image](assets/Chapter-1/entrevista.png)

[Entrevista 3 - video](https://upcedupe-my.sharepoint.com/personal/u202118264_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202118264%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%20consultores%20financieros%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Eea5089e2%2D9f76%2D48a9%2D97f4%2D880c95a88826&isDarkMode=false): https://shorturl.at/M76Qv

Resumen: 

La entrevistada, consultora financiera junior de 23 años, define la educación financiera como herramientas para tomar mejores decisiones con el dinero. Usa principalmente su laptop y se informa por LinkedIn y Twitter. Ha visto anuncios de apps financieras en Instagram, aunque muchos le parecen generales. Asesora a emprendedores en la organización de sus finanzas y considera clave usar INFOCORP para evaluar historiales crediticios. Cree que muchas personas no entienden sus deudas ni controlan sus gastos, por lo que recomienda apps como Fintonic. Opina que la educación financiera debe enfocarse en explicar intereses y deudas, y que una app como DebtGo puede ser útil si brinda seguimiento claro y personalizado.

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

**Entrevista #1**

- Nombre: Emilio Chávarri
- Edad: 54 años
- Distrito: San Juan de Lurigancho 
- Duración: 4:38 minutos

![image](assets/Chapter-2/Entrevista1.JPG)

[Entrevista 1 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211108_upc_edu_pe/EYsHot_bR4FLtZs1tok9abIBf1ZfOJsBVIy0KEwKFc6AEA?e=bER0c8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifSwicGxheWJhY2tPcHRpb25zIjp7InN0YXJ0VGltZUluU2Vjb25kcyI6Mi40OH19): https://shorturl.at/M76Qv

Resumen:

Emilio Chávarri, de 55 años, es una persona que quiere emprender en el rubro de comunicaciones, tiene experiencia en la obtención de préstamos a entidades bancarias pero presenta dificultades en cuanto a firma de documentos de préstamos, ya que hay muchos términos que se tiene que leer y entender. Lo que más le preocupa de solicitar préstamos es el interés que va a pagar por el mismo. El criterio que utiliza para identificar si una publicidad de préstamo es real, primeramente ve qué empresa es la que está publicitando, y luego por medio del internet va al mercado de valores para ver la condición financiera de la empresa. También utiliza ciertas aplicaciones de banca móvil y a su vez, siente que es muy segura y que conforme pasa el tiempo los bancos van mejorando en cuestión de seguridad. Finalmente, las condiciones con las que se sentiría seguro al momento de compartir información financiera es la seguridad de la misma aplicación, ver cuántas restricciones tiene para acceder a su información, conocer más a la empresa, su ubicación, el software que está utilizando, que tan fácil es usarlo.

**Entrevista #2** 
- Nombre: Anderson Gonza
- Edad: 22 años
- Distrito: Villa El Salvador
- Duración: 6:24 minutos

![image](assets/Chapter-2/ander_interview.png)

[Entrevista 2 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211a085_upc_edu_pe/Edu_0dP5NCxBuyzn5nvd06gB_mYaiu180sc8nROeIBoA7A?e=oqPL3o&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Resumen:

Anderson Gonza, de 22 años y residente en Villa El Salvador, está interesado en iniciar un negocio de cafetería con enfoque en coworking. Tiene conocimientos básicos de finanzas adquiridos en la universidad y, aunque no ha trabajado con consultores financieros, considera importante que tengan experiencia en su rubro. Solo ha gestionado préstamos personales y está aprendiendo sobre préstamos empresariales, sintiendo confusión principalmente al elegir el tipo adecuado y entender completamente las condiciones. Le preocupan los intereses, las condiciones de los contratos y el riesgo de endeudamiento. Prefiere plataformas reconocidas como BCP e Interbank, y verifica la autenticidad de las ofertas de préstamos buscando reseñas y comprobando su regulación ante la SBS. Utiliza aplicaciones como Yape, Plin y BCP, confiando en ellas pero tomando precauciones adicionales. Estaría dispuesto a compartir información básica como ingresos, gastos y metas financieras, siempre que la aplicación sea segura, regulada, transparente y cuente con buenas reseñas.

**Entrevista #3**
- Nombre: Maria Pilares Pocochuanca
- Edad: 26 años
- Distrito: Los Olivos
- Duración: 5:05

![image](assets/Chapter-2/Entrevista3_Segm2.png)

[Entrevista 3 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113279_upc_edu_pe/Ea0th-UAr9JBrljOSf-yPTIBE_7YfuXWx3s9Yz9cgeTWGQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=humfYy)

Resumen: Maria Paula Pilares, emprendedora de 26 años que reside en Los Olivos, busca iniciar un negocio de productos ecológicos. Aunque tiene conocimientos financieros intermedios, reconoce que los procesos de préstamo suelen resultarle confusos, sobre todo en lo relacionado con intereses, comisiones y cláusulas poco claras. Ha tenido experiencias previas con préstamos y consultoría, y considera importante que los asesores financieros comprendan el rubro en el que se desarrolla su negocio. Sus principales preocupaciones al solicitar créditos son las altas tasas de interés, las penalidades por atrasos y la seguridad de las plataformas financieras. A pesar de usar con frecuencia la banca móvil, exige garantías de seguridad y transparencia antes de compartir sus datos. En general, valora soluciones digitales como aplicaciones de gestión de deudas, siempre que ofrezcan respaldo confiable y un manejo claro de la información.

### 2.2.3. Análisis de entrevistas

**Segmento Objetivo: Consultores financieros:**

*Perfil Profesional y Uso de Herramientas:*

Utilizan laptops y dispositivos móviles para gestionar finanzas y asesorar a clientes, priorizando herramientas digitales prácticas.

*Educación Financiera y Retos:*

Consideran la educación financiera esencial y destacan como retos la falta de cultura de ahorro y planificación financiera en Perú.

*Percepción de Aplicaciones Financieras:*

Valoran apps como Monefy, Fintonic, YNAB y Mint por su utilidad, aunque piden más funciones de inversión y personalización.

*Uso de Infocorp y Control Crediticio:*

INFOCORP es clave en sus evaluaciones crediticias para asesorar con mayor precisión a clientes y emprendedores.

*Tecnología y Redes Sociales:*

Usan LinkedIn, YouTube y X para estar actualizados en temas económicos y detectar tendencias útiles para su práctica profesional.

*Potencial de DebtGo:*

Creen que DebtGo puede ser efectiva si combina asesoría personalizada, control de deudas y educación financiera continua.

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

1. Conocimiento y Experiencia Financiera

Todos los entrevistados reconocen la importancia de tener asesores financieros con experiencia en el rubro específico de sus negocios, y aunque algunos tienen un nivel básico de conocimiento, también muestran inseguridad y confusión, especialmente en temas como intereses, tipos de préstamos y condiciones de contractuales, especialmente al momento de emprender.

2. Preocupaciones al Solicitar Préstamos

El interés, las condiciones del préstamo y el riesgo de endeudamiento son factores clave de preocupación para todos los entrevistados. Hay una necesidad de mayor claridad y seguridad en estos aspectos para reducir el miedo a incumplir o ser engañados.

3. Confianza en Plataformas y Aplicaciones Bancarias: 

Todos los entrevistados utilizan banca móvil y confían en su seguridad, especialmente con el uso de huellas digitales o sistemas de autenticación robustos. Aunque confían en la seguridad de las aplicaciones bancarias, hay una cierta desconfianza hacia plataformas nuevas o no tradicionales para la obtención de préstamos. Es importante ofrecer un nivel de transparencia y garantías de seguridad adicional en cualquier aplicación de asesoría financiera.

4. Disponibilidad para Compartir Datos Financieros

La privacidad y el control sobre los datos financieros son importantes para todos. Para fomentar la confianza en la plataforma, sería esencial ofrecer medidas de seguridad robustas, transparencia sobre qué datos se recolectan (limitándose a información básica como ingresos, gastos y metas financieras) y garantías de control sobre el tiempo que la información estará disponible.

5. Percepciones sobre Publicidad y Estafas

Los tres entrevistados adoptan un enfoque prudente para evitar estafas. La plataforma de asesoría financiera debe ofrecer transparencia en cuanto a sus políticas y contar con testimonios de clientes reales para aumentar la confianza.

## 2.3. Needfinding
### 2.3.1. User Personas

Para esta sección se han creado personajes ficticios, cada uno diseñado para representar a un segmento específico de usuarios. La información utilizada para desarrollar estos "User personas" proviene de entrevistas previas realizadas a cada segmento objetivo. Estas entrevistas tenían como objetivo comprender mejor a las personas a las que se dirige la aplicación. Se consideraron datos demográficos, metas, motivaciones frustraciones, marcas relacionadas con el tema de la aplicación canales digitales más utilizados, entre otros. La creación de esta sección se llevó a cabo utilizando la plataforma UXPressia.

**Segmento Objetivo: Consultores financieros:**

#### User Persona 1: 

![image](assets/Chapter-2/userpersona4.png)
*Imagen (N°2). Elaboración propia. Realizado en UXPRESSIA*

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

#### User Persona 2:

![image](assets/Chapter-2/User1.png)
*Imagen (N°3). Elaboración propia. Realizado en UXPRESSIA*

<!-- ![image](assets/Chapter-2/User3.png)
*Imagen (N°). Elaboración propia. Realizado en UXPRESSIA* -->

### 2.3.2. User Task Matrix
En esta sección se presenta el user task matrix, herramienta centrada en los segmentos objetivos, que nos permitirá identificar las tareas y objetivos claves de los usuarios. Además, nos permitirá priorizar características y funcionalidades al momento de realizar el product backlog. Para la frecuencia se han considerado cinco opciones:nunca ,casi nunca, a veces, a menudo ,siempre; y para la importancia tres opciones: bajo, medio, alto". En relación con la matriz de tareas de los usuarios, podemos identificar tanto las tareas de mayor frecuencia como las de mayor importancia, así como las diferencias y similitudes entre los diferentes tipos de usuarios.

<table>
<tr><th rowspan="2" valign="top">
<b><i>User task Matrix</i></b></th>
<th colspan="2" valign="top">
<b><i>Segmento 1</i></b></th>
<th colspan="2" valign="top"><p>
<b><i>Segmento 2</i></b>
 <p><p><b><i></i></b></p>
 </th></tr>
<tr><td valign="top"><b><i>Frecuencia</i></b> </td>
<td valign="top"><b><i>Importancia</i></b></td>
<td valign="top"><b><i>Frecuencia</i></b> </td>
<td valign="top"><b><i>Importancia</i></b></td>
</tr>
<tr><td>Registrarse en la plataforma </td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Medio</i></b></td>
</tr>
<tr><td>Completar perfil de usuario</td>
<td><b><i>Amenudo</i></b></td>
<td><b><i>Alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Medio</i></b></td>
</tr>
<tr><td>Indicar nivel de experiencia en gestión financiera</td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Muy alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Muy alta</i></b></td></tr>
<tr><td>Consultar deudas pendientes</td>
<td><b><i>Alta</i></b></td>
<td><b><i>Medio</i></b></td>
<td><b><i>Siempre</i></b></td>
<td><b><i>Alta</i></b></td>
</tr>
<tr><td>Elegir opción entre gestión de deudas o gastos personales </td>
<td><b><i>Alta</i></b></td>
<td><b><i>Alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Alta</i></b></td>
</tr>
<tr><td>Interactuar con un asesor financiero online</td>
<td><b><i>Casi nunca</i></b></td>
<td><b><i>Baja</i></b></td>
<td><b><i>Casi nunca</i></b></td>
<td><b><i>Baja</i></b></td>
</tr>
<tr><td>Seleccionar servicios</td>
<td><b><i>Alta</i></b></td>
<td><b><i>Alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Alta</i></b></td>
</tr>
<tr><td>Explorar artículos</td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Alta</i></b></td>
<td><b><i>A menudo</i></b></td>
<td><b><i>Alta</i></b></td>
</tr>
</table>

### 2.3.3. User Journey Mapping
En esta sección, explicaremos en detalle los user journey mapping para dos tipos de usuarios distintos: Consultores Financieros/Economistas y Gestores de Deudas y Emprendedores. Estos mapas proporcionarán una visión exhaustiva de cómo cada segmento de usuario interactúa con la plataforma, desde su primer contacto hasta su uso continuo y el análisis de resultados. Mejoraremos la presentación de estos mapas, destacando las etapas clave y las necesidades específicas de cada usuario para garantizar una comprensión clara y concisa de su experiencia a lo largo de su viaje:

**Segmento Objetivo: Consultores financieros:**

![image](assets/Chapter-2/journeymap4.png)

*Imagen (N°4). Elaboración propia. Realizado en UXPRESSIA* 

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

![image](assets/Chapter-2/seg2.png)

*Imagen (N°5). Elaboración propia. Realizado en UXPRESSIA.*

<!-- ![image](assets/Chapter-2/JourneyMap3.png)

*Imagen (N°). Elaboración propia. Realizado en UXPRESSIA. -->

### 2.3.4. Empathy Mapping

**Segmento objetivo: Consultores financieros**

![image](assets/Chapter-2/empathymap_2.png)
*Imagen (N°6). Elaboración propia. Realizado en UXPRESSIA.*

**Segmento objetivo: Emprendedores**

![image](assets/Chapter-2/emprendedores.png)
*Imagen (N°7). Elaboración propia. Realizado en UXPRESSIA.*

### 2.3.5. As-is Scenario Mapping

**Segmento objetivo: Consultores financieros**
![image](assets/Chapter-2/asisMap-consultores.jpg)
*Imagen (N°8). Elaboración propia. Realizado en [Miro](https://miro.com/app/board/uXjVKilDDEs=/?share_link_id=237055566961).*


**Segmento objetivo: Emprendedores**
![image](assets/Chapter-2/asisMap-emprendedores.png)
*Imagen (N°9). Elaboración propia. Realizado en [Miro](https://miro.com/app/board/uXjVKilDDEs=/?share_link_id=237055566961).*

<!-- ![image](assets/Chapter-2/ScenarioMapping3.jpg)
*Imagen (N°). Elaboración propia. Realizado en [Miro](https://miro.com/app/board/uXjVKisf19Y=/).*
 -->
## 2.4. Ubiquitous Language

<strong>1. Debt Management (Gestión de Deudas):</strong> Proceso mediante el cual los usuarios monitorean, controlan y organizan el pago de sus deudas personales o empresariales para evitar caer en mora o aumentar los intereses acumulados.

<strong>2. Financial Literacy (Educación Financiera):</strong> Nivel de conocimiento que los usuarios tienen sobre conceptos financieros básicos, como cómo funcionan los préstamos, los intereses y cómo se gestionan las deudas de manera efectiva.

<strong>3. Custom Payment Plans (Planes de Pago Personalizados):</strong> Soluciones de pago que DebtGo ofrece a los usuarios, adaptadas a sus necesidades financieras específicas, con el fin de ayudarlos a saldar sus deudas de manera eficiente y estructurada.

<strong>4. Income and Expense Tracking (Seguimiento de Ingresos y Gastos):</strong> Funcionalidad de DebtGo que permite a los usuarios registrar y monitorear sus ingresos y gastos diarios para obtener una visión clara de su situación financiera.

<strong>5. Financial Consultants (Consultores Financieros):</strong> Profesionales especializados que proporcionan asesoramiento personalizado a los usuarios de DebtGo para ayudarlos a mejorar su gestión de deudas y finanzas personales.

<strong>6. Personalized Budgeting (Presupuestación Personalizada):</strong> Herramienta que permite a los usuarios crear presupuestos ajustados a su realidad económica, ayudándoles a manejar sus ingresos, gastos y deudas de forma organizada.

<strong>7. Financial Workshops (Talleres Financieros):</strong> Sesiones educativas en línea ofrecidas por DebtGo para mejorar el conocimiento financiero de los usuarios, capacitándolos en la gestión de deudas y en la toma de decisiones financieras informadas.

<strong>8. Debt Cycle (Ciclo de Endeudamiento):</strong> Situación en la que los usuarios adquieren nuevas deudas para pagar deudas anteriores, lo que incrementa su carga financiera y perpetúa el problema de la deuda.

<strong>9. Interest Accumulation (Acumulación de Intereses):</strong> Proceso por el cual los intereses sobre una deuda se incrementan con el tiempo si los pagos no se realizan puntualmente.

<strong>10. Debt Reminders (Recordatorios de Deuda):</strong> Notificaciones automáticas que DebtGo envía a los usuarios para recordarles las fechas de vencimiento de los pagos de sus deudas y evitar penalidades por retraso.

<strong>11. Financial Stress (Estrés Financiero):</strong> Estado emocional negativo que experimentan los usuarios debido a la incapacidad de gestionar sus deudas de manera efectiva, lo que puede tener consecuencias graves en su bienestar personal y salud mental.

<strong>12. Debt Consolidation (Consolidación de Deudas):</strong> Estrategia de gestión de deudas que permite a los usuarios combinar múltiples deudas en una sola, con condiciones de pago más favorables.

<strong>13. Subscription Model (Modelo de Suscripción):</strong> Estructura de pago en la que los usuarios de DebtGo pueden acceder a características premium, como análisis financieros avanzados y contenido educativo exclusivo, mediante una tarifa mensual o anual.

<strong>14. Financial Advisory (Asesoría Financiera):</strong> Servicio ofrecido por DebtGo que proporciona recomendaciones y planes personalizados a los usuarios para ayudarles a tomar decisiones financieras informadas.

<strong>15. Credit Score (Historial Crediticio):</strong> Registro de la capacidad de un usuario para pagar sus deudas, que influye en su elegibilidad para obtener futuros créditos o préstamos.

<strong>16. Debt Accumulation (Acumulación de Deudas):</strong> Proceso mediante el cual los usuarios incrementan la cantidad total de sus deudas debido a la falta de pagos o al uso constante de crédito sin una gestión adecuada.

<strong>17. Default Risk (Riesgo de Mora):</strong> Posibilidad de que los usuarios no puedan cumplir con sus obligaciones financieras, lo que puede resultar en penalidades o acciones legales.

<strong>18. Artificial Intelligence (Inteligencia Artificial):</strong> Tecnología que DebtGo planea integrar para personalizar aún más las recomendaciones financieras y mejorar la experiencia del usuario mediante el análisis avanzado de su comportamiento financiero.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

**Segmento objetivo: Consultores financieros**
![image](assets/Chapter-3/tobeMap-consultores.jpg)
*Imagen (N°10). Elaboración propia. Realizado en [Miro](https://miro.com/app/board/uXjVKilDDEs=/?share_link_id=237055566961).*

**Segmento objetivo: Emprendedores**
![image](assets/Chapter-3/tobeMap-emprendedores.jpg)
*Imagen (N°11). Elaboración propia. Realizado en [Miro](https://miro.com/app/board/uXjVKilDDEs=/?share_link_id=237055566961).*

## 3.2. User Stories

### EPICS

  <div style="text-align:center;">
    <table align="center" border="1" cellpadding="10" cellspacing="0">
        <tr>
            <td style="text-align:center;" colspan="1">EPIC ID</td>
            <td style="text-align:center;" colspan="1">TÍTULO</td>
           <td style="text-align:center;" colspan ="1"> DESCRIPCIÓN</td>
        </tr>
        <tr>
            <td>EP01</td> 
            <td>Visita a landing page</td>
            <td><b>Como</b> visitante <b>deseo</b> visualizar los distintos beneficios y oportunidades de la aplicación <b>para</b> entender el propósito del producto y si este se adecúa a mis necesidades </td>
        </tr>
        <tr>
            <td>EP02</td> 
            <td>Normas de seguridad y registro</td>
            <td><b>Como</b> visitante <b>deseo</b> comprender las medidas de seguridad <b>para</b> decidir si compartiré mis datos personales y financieros </td>
        </tr>
        <tr>
            <td>EP03</td> 
            <td>Registro en aplicación y gestión de cuenta</td>
            <td><b>Como</b> usuario <b>deseo</b> registrarme y gestionar mi cuenta <b>para</b> interactuar con la aplicación</td>
        </tr>
        <tr>
            <td>EP04</td> 
            <td>Opciones de servicio</td>
            <td><b>Como</b> usuario <b>deseo</b> visualizar todas las opciones de servicio <b>para</b> elegir el asesoramiento más adecuado</td>
        </tr>
        <tr>
            <td>EP05</td> 
            <td>Creación y seguimiento de casos</td>
            <td><b>Como</b> usuario <b>deseo</b> crear, modificar y cerrar casos <b>para</b> lograr mis propósitos en la aplicación</td>
        </tr>
        <tr>
            <td>EP06</td> 
            <td>Evaluación de servicios</td>
            <td><b>Como</b> usuario <b>deseo</b> evaluar los servicios ofrecidos <b>para</b> mejorar el servicio en general ofrecido en la aplicación</td>
        </tr>
        <tr>
            <td>EP07</td> 
            <td>Funcionalidades adicionales</td>
            <td><b>Como</b> usuario <b>deseo</b> contar con herramientas adicionales y de educación <b>para</b> incrementar el conocimiento financiero</td>
        </tr>
       </table>
</div>

### USER STORIES

| Story ID | Titulo | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) | 
|---|---|------|------|---|
|US01|Demostración de la aplicación|**Como** visitante, **deseo** ver una demostración de la aplicación **para** entender rápidamente lo que ofrece|**Dado que** el visitante se encuentra en el landing page **Cuando** navega a la sección About-the-Product **Entonces** encuentra un video informativo del producto|EP01| 
|US02|Reseñas de la aplicación|**Como** visitante, **deseo** visualizar reseñas de la aplicación **para** decidir si quiero utilizarla|**Dado que** el visitante se encuentra en el landing page **cuando** navega a la sección Reviews **entonces** visualiza las reseñas realizadas por usuarios|EP01|
|US03|Planes de la aplicación |**Como** visitante, **deseo** visualizar los planes de suscripción **para** decidir el más adecuado a mis necesidades|**Dado que** el visitante se encuentra en el landing page **cuando** navega a la sección Plans **entonces** visualiza de modo comparativo los planes de suscripción|EP01|
|US04|Soporte de la aplicación|**Como** visitante, **deseo** poder contactarme con equipo de soporte **para** resolver cualquier duda o acceder a información adicional|**Dado que** el visitante se encuentra en el landing page **cuando** navega a la sección Contact **entonces** ingresa su correo para recibir mayor información|EP01|
|US05|Información de servicios|**Como** visitante del segmento consultor financiero, **deseo** ofrecer mis servicios **para** tener una fuente adicional de dinero | **Dado que** el visitante de segmento consultor financiero se encuentra en el landing page **cuando** ingresa a la sección Offer-Services **entonces** visualiza la explicación de los servicios ofrecidos|EP01|
|US06|Normas de privacidad|**Como** visitante del segmento emprendedor, **deseo** conocer las normas de privacidad **para** contar con la seguridad que mis datos serán protegidos |**Dado que** el visitante de segmento emprendedor se encuentra en el landing page **cuando** ingresa a la sección Benefits **entonces** visualiza las normas de privacidad |EP02|
|US07|Pago por servicios|**Como** visitante del segmento consultor financiero, **deseo** visualizar una explicación del sistema de pago a consultores **para** entender el proceso antes de ofrecer mis servicios|**Dado que** el visitante de segmento consultor financiero se encuentra en el landing page **cuando** ingresa a la sección Offer-Services **entonces** visualiza la explicación de sistema de pago|EP02|
|US08|Registro en aplicación|**Como** visitante, **deseo** registrarme en la aplicación **para** utilizar las funcionalidades ofrecidas|**Escenario 1: Ingreso desde landing page** <br/> **Dado que** el visitante se encuentra en la landing page **cuando** ingresa a la sección Start-Now **entonces** será redirigido a la página de login de la aplicación **e** ingresa su rol e información de registro <br/><br/> **Escenario 2: Ingreso desde landing page** <br/> **Dado que** el visitante se encuentra en la página principal de la aplicación **cuando** hace click en "Sign-in" **entonces** es redirigido a la página de login de la aplicación **e** ingresa su rol e información de registro|EP03|
|US09|Creación de perfil - Consultor financiero|**Como** consultor financiero, **deseo** ingresar mi experiencia e información relevante **para** atraer posibles clientes|**Dado que** el consultor está registrado exitosamente con rol consultor **cuando** accede por primera vez **entonces** la aplicación pide ingresar información para su perfil |EP03|
|US10|Creación de perfil - Emprendedor|**Como** emprendedor, **deseo** registrar mi emprendimiento y mis necesidades **para** empezar a utilizar la aplicación|**Dado que** el emprendedor está registrado exitosamente con rol emprendedor **cuando** accede por primera vez **entonces** la aplicación pide ingresar información para su perfil|EP03|
|US11|Elección y actualización de plan|**Como** emprendedor **deseo** registrar y/o modificar mi plan de suscripción **para** que se adecúe a mis necesidades| **Escenario 01: Ingreso de plan** <br/> **Dado que** el emprendedor está registrado exitosamente con rol emprendedor **cuando** accede por primera vez **entonces** la aplicación le pide elegir su plan de suscripción <br/><br/>  **Escenario 02: Modificación de plan** **Dado que** el emprendedor ingresa a la aplicación con rol emprendedor **cuando** ingresa a sección "Settings" Y a sección "Subscription-Plan" **entonces** modifica el plan actual de acuerdo a su preferencia|EP03|
|US12|Elección de pagos por servicios|**Como** consultor financiero, **deseo** ingresar el método de pago de servicios **para** recibir el pago de los mismos|**Escenario 01: Ingreso de datos de pago** <br/>**Dado que** el consultor está registrado exitosamente con rol consultor **cuando** accede por primera vez **entonces** la aplicación le pide ingresar sus datos de pago<br/><br/>**Escenario 02: Modificación de datos de pago** <br/> **Dado que** el consultor ingresa a la aplicación con rol consultor **cuando** ingresa a sección "Settings" Y a sección "Payment-Method" **entonces** modifica los datos actuales de acuerdo a su preferencia|EP03|
|US13|Búsqueda de consultores|**Como** emprendedor, **deseo** encontrar a un consultor que tenga experiencia en mi rubro **para** que comprenda mis necesidades|**Dado que** el emprendedor accede con rol emprendedor **cuando** utiliza la funcionalidad de filtrado por rubro de experiencia **entonces** visualiza  consultores especializados|EP04|
|US14|Lista de servicios guardados|**Como** emprendedor, **deseo** poder comparar los servicios de distintos consultores **para** elegir el más adecuado|**Escenario 1: Adición de servicios a lista** <br/>**Dado que** el emprendedor se encuentra en la búsqueda de servicios **cuando** visualiza ofertas que le atraen **entonces** las agrega a una lista privada<br/><br/> **Escenario 2: Visualización de servicios en lista** <br/>**Dado que** el emprendedor cuenta con una lista de servicios **cuando** ingresa a su perfil **entonces** puede visualizar la lista privada de servicios guardados|EP04|
|US15|Publicación de servicios|**Como** consultor financiero, **deseo** publicar distintos servicios y los precios correspondientes **para** ofrecer varias opciones dependiendo de la necesidad del cliente|**Dado que** el consultor financiero accede con rol consultor **cuando** ingresa a su perfil de consultor **entonces** puede agregar y editar sus servicios disponibles|EP04|
|US16|Establecimiento de horario|**Como** consultor financiero, **deseo** establecer mis horas de trabajo **para** no recibir notificaciones fuera de mi horario laboral|**Dado que** el consultor financiero accede con rol consultor **cuando** ingresa a su perfil de consultor **entonces** hace click en Editar y agrega sus horarios de trabajo|EP04|
|US17|Inicio de caso|**Como** emprendedor, **deseo** tener acceso a asesoramiento personalizado **para** poder acceder a préstamos que se adecuen a mis necesidades|**Dado que** el emprendedor accede a la aplicación con rol emprendedor **cuando** elige un consultor e inicia el ticket del caso **entonces** explica su caso y sus necesidades|EP04|
|US18|Aceptación de caso |**Como** consultor financiero, **deseo** hablar con el emprendedor antes de aceptar el caso **para** entender sus necesidades|**Dado que** el consultor recibe nuevos casos **cuando** lee los detalles del caso **entonces** elige si aceptar o denegar el caso|EP04|
|US19|Visualización de servicios|**Como** consultor financiero, **deseo** visualizar todas las ofertas de servicios de otros consultores **para** poder comparar mis servicios|**Dado que** el consultor financiero accede con rol consultor **cuando** ingresa a la sección servicios **entonces** puede visualizar servicios de otros consultores|EP04|
|US20|Sistema de mensajes y casos|**Como** consultor financiero, **deseo** comunicarme directamente con los clientes **para** ofrecer asesoramiento adecuado|**Escenario 1: Ingreso a mensajes por bandeja** <br/>**Dado que** el consultor accede a la plataforma **cuando** ingresa a la sección Bandeja **entonces** revisa sus mensajes con los clientes<br/><br/>**Escenario 2: Ingreso a mensajes por perfil** <br/>**Dado que** el consultor accede a la plataforma **cuando** ingresa al perfil de un cliente **entonces** puede entrar a los mensajes con el cliente|EP05|
|US21|Historial de casos|**Como** consultor financiero, **deseo** ver el historial de mensajes **para** hacer seguimiento al caso|**Escenario 1: Ingreso a casos por sección Casos**<br/>**Dado que** el consultor ingresa a la aplicación **cuando** ingresa a la sección Casos **entonces** puede revisar sus casos activos y archivados<br/><br/>**Escenario 2: Ingreso a casos por perfil de cliente**<br/>**Dado que** el consultor se encuentra en el perfil del cliente **cuando** ingresa a la sección mensajes **entonces** visualiza todos los mensajes |EP05|
|US22|Envío de documentos adjuntos |**Como** consultor financiero, **deseo** poder enviar documentos a través de la aplicación **para** apoyar al cliente y darle información necesaria|**Dado que** el consultor necesita enviar información relevante **cuando** ingresa al Caso con el cliente **entonces** adjunta el/los documentos a través de la aplicación|EP05|
|US23|Actualizaciones de solicitudes|**Como** emprendedor, *deseo* recibir actualizaciones de mis solicitudes **para** estar al tanto del progreso de las mismas|**Dado que** el emprendedor activa las notificaciones **cuando** el consultor responde al caso **entonces** el emprendedor recibe una notificación|EP05|
|US24|Alertas de fechas importantes|**Como** emprendedor, **deseo** recibir alertas sobre fechas importantes **para** poder cumplir con los requisitos a tiempo|**Dado que** el emprendedor acepta una solución del caso **cuando** se acerca una fecha importante **entonces** la aplicación envía una notificación|EP05|
|US25|Pedidos de reseñas|**Como** consultor financiero, **deseo** recibir reseñas de mis servicios **para** atraer a clientes|**Dado que** el consultor financiero provee una solución final **cuando** cierra el caso **entonces** indica que desea una reseña del caso|EP06|
|US26|Reseñas de servicios realizados|**Como** emprendedor, **deseo** calificar a los consultores **para** ayudar a otros emprendedores a tomar decisiones informadas|**Escenario 1: Reseña desde cierre de caso** <br>**Dado que** el emprendedor ha aceptado la solución del caso **cuando** aprueba el cierre del mismo **entonces** el sistema muestra una pantalla de reseña de servicios<br><br>**Escenario 2: Reseñas desde sección Casos** <br>**Dado que** el emprendedor cuenta con varios casos cerrados **cuando** ingresa a la sección Casos y a Casos-Archivados **entonces** hace click en Dejar-Reseña|EP06|
|US27|Visualización de métricas propias|**Como** consultor financiero, **deseo** visualizar métricas de mi desempeño **para** mejorar mis servicios|**Dado que** el consultor ha trabajado por más de 1 mes **cuando** ingresa la sección Métricas en su perfil **entonces** visualiza las métricas del último mes|EP06|
|US28|Terminación de contrato - consultor financiero|**Como** consultor financiero, **deseo** poder terminar el contrato si el cliente no sigue las recomendaciones indicadas **para** no ver mis métricas afectadas |**Dado que** el consultor ha provisto una solución que fue rechazada **cuando** se rechaza una segunda solución **entonces** el consultor apela al Cancelamiento-por-Incumplimiento|EP06|
|US29|Terminación de contrato - emprendedor|**Como** emprendedor, **deseo** poder cancelar el contrato si el consultor no cumple las estipulaciones **para** no verme afectado|**Dado que** el emprendedor no recibe respuesta por más de 7 días **cuando** ingresa al Caso, y a Más Opciones **entonces** apela al Cancelamiento-por-Incumplimiento|EP06|
|US30|Articulos financieros|**Como** emprendedor, **deseo** tener acceso a artículos relacionados **para** incrementar mi conocimiento del tema|**Dado que** el emprendedor no tiene casos activos **cuando** ingresa a la sección Explorar **entonces** visualiza artículos relacionados a su rubro|EP07|
|US31|Herramientas de simulación|**Como** emprendedor, **deseo** tener acceso a simuladores de pagos y cuotas **para** estimar los pagos de mis deudas|**Dado que** el emprendedor adquiere una suscripción premium **cuando** ingresa a la sección Herramientas **entonces** utiliza los simuladores de pago|EP07|
|US32|Talleres gratuitos|**Como** consultor financiero, **deseo** otorgar talleres financieras gratuitos **para** atraer a posibles clientes|**Dado que** el consultor financiero desea proveer el servicio de talleres gratuitos **cuando** ingresa a su perfil de consultor **entonces** agrega el servicio "Talleres Gratuitos"|EP07|
|US33|Seguimiento de Ingresos y Gastos|**Como** emprendedor, **deseo** una herramienta que me permita rastrear mis ingresos y gastos de manera eficiente, **para** tener una visión clara de mi situación financiera y poder tomar decisiones informadas|**Dado que** el emprendedor quiere hacer seguimiento a sus gastos, **cuando** ingresa a la sección Herramienta y a Tracker, **entonces** utiliza la herramienta para ingresar entradas y salidas de dinero|EP07|
|US34|Creación de presupuestos|**Como** emprendedor, **deseo** poder crear presupuestos personalizados basados en mis ingresos y gastos, **para** administrar mejor mi dinero y evitar el endeudamiento excesivo|**Dado que** el emprendedor tiene subscripción premium **cuando** utiliz la aplicación por más de un mes **entonces** visualiza planes de presupuesto|EP07|

### Technical Stories

#### US01 - Demostración de la aplicación
| Story ID | Titulo | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) | 
|---|---|------|------|---|
|TS01|Endpoint para video de demostración|**Como** developer, **deseo** implementar un endpoint en el RESTful API que gestione la entrega del video de demostración **para** la sección About-the-Product|Escenario 1: Successful video request <br> **Dado que** el visitante realiza un GET request al endpoint /api/demo-video **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y el link del video en formato compatible (.mp4) <br>Escenario 2: Video no encontrado <br>**Dado que** el visitante realiza un GET request al endpoint /api/demo-video **cuando** el video no está disponible **entonces** el API devuelve un response con status 404 Not Found|EP01|
|TS02|Endpoint para obtener reseñas de usuarios|**Como** developer **deseo** crear un endpoint **para** obtener las reseñas de los usuarios y mostrarlas en la sección Reviews de la aplicación|**Escenario 1:** Fetch reviews successfully <br> **Dado que** el visitante realiza un GET request al endpoint /api/reviews **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y una lista de reseñas en formato JSON <br> **Escenario 2:** No reviews available <br> **Dado que** el visitante realiza un GET request al endpoint /api/reviews **cuando** no existen reseñas en la base de datos **entonces** el API devuelve un response con status 204 No Content.| EP01|
|TS03|Endpoint para obtener planes de suscripción|**Como** developer **deseo** implementar un endpoint **para** gestionar la entrega de los planes de suscripción|**Escenario 1:** Fetch subscription plans successfully <br> **Dado que** el visitante realiza un GET request al endpoint /api/plans **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y una lista de planes de suscripción en formato JSON <br> **Escenario 2:** No subscription plans available <br> **Dado que** el visitante realiza un GET request al endpoint /api/plans **cuando** no existen planes de suscripción **entonces** el API devuelve un response con status 204 No Content|EP01|
|TS04|Endpoint para solicitud de contacto con soporte|**Como** developer **deseo** crear un endpoint **para** enviar las solicitudes de contacto al equipo de soporte|**Escenario 1:** Contact request sent successfully <br> **Dado que** el visitante realiza un POST request al endpoint /api/contact con su correo electrónico **cuando** el request es válido **entonces** el API devuelve un response con status 200 OK y un mensaje de confirmación de que el soporte ha sido notificado.<br>**Escenario 2:** Invalid email format <br> **Dado que** el visitante realiza un POST request al endpoint /api/contact con un formato de correo inválido **cuando** el formato de correo es incorrecto **entonces** el API devuelve un response con status 400 Bad Request y un mensaje de error especificando que el correo no es válido|EP01|
|TS05|Endpoint para información de servicios ofrecidos|**Como** Developer **deseo** crear un endpoint **para** mostrar la información de los servicios financieros que pueden ofrecerse a través de la plataforma| **Escenario 1:** Fetch services information successfully<br>**Dado que** el visitante realiza un GET request al endpoint /api/services **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y una lista de servicios en formato JSON.<br>**Escenario 2:** No services available<br>**Dado que** el visitante realiza un GET request al endpoint /api/services **cuando** no existen servicios en la base de datos **entonces** el API devuelve un response con status 204 No Content.|EP01|
|TS06|Endpoint para normas de privacidad|**Como** Developer **deseo** implementar un endpoint **para** gestionar la entrega de las normas de privacidad|**Escenario 1:** Fetch privacy policies successfully<br>**Dado que** el visitante realiza un GET request al endpoint api/privacy-policies **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y las normas de privacidad en formato JSON.<br>**Escenario 2:** Privacy policies not found<br>**Dado que** el visitante realiza un GET request al endpoint api/privacy-policies **cuando** no existen normas de privacidad en la base de datos **entonces** el API devuelve un response con status 404 Not Found.|EP02|
|TS07|Endpoint para obtener información del sistema de pago|**Como** Developer **deseo** implementar un endpoint **para** obtener la información del sistema de pago a consultores financieros.|**Escenario 1:** Fetch payment system information successfully<br>**Dado que** el visitante realiza un GET request al endpoint /api/payment-system **cuando** el request es exitoso **entonces** el API devuelve un response con status 200 OK y la información del sistema de pago en formato JSON.<br>**Escenario 2:** Payment system information not found<br>**Dado que** el visitante realiza un GET request al endpoint /api/payment-system **cuando** no hay información del sistema de pago disponible **entonces** el API devuelve un response con status 404 Not Found.|EP02|
|TS08|Endpoint para registro de usuarios|**Como** Developer **deseo** implementar un endpoint **para** registrar nuevos usuarios, capturando su rol y la información de registro.|**Escenario 1:** User registration successful<br> **Dado que** el visitante realiza un POST request al endpoint /api/register con su información de registro **cuando** el request es válido **entonces** el API devuelve un response con status 201 Created y el usuario es registrado exitosamente.<br>**Escenario 2:** User registration fails due to missing data<br> **Dado que** el visitante realiza un POST request al endpoint /api/register con información incompleta **cuando** falta información requerida **entonces** el API devuelve un response con status 400 Bad Request especificando los campos faltantes.|EP03|
|TS09|Endpoint para creación de perfil de consultor financiero|**Como** Developer **deseo** crear un endpoint **para** permitir al consultor financiero ingresar su experiencia y otra información relevante para su perfil.|**Escenario 1:** Consultant profile created successfully<br> **Dado que** el consultor realiza un POST request al endpoint /api/profile/consultant con su experiencia e información relevante **cuando** el request es válido **entonces** el API devuelve un response con status 201 Created y el perfil del consultor se crea exitosamente.<br> **Escenario 2:** Consultant profile creation fails<br> **Dado que** el consultor realiza un POST request al endpoint /api/profile/consultant **cuando** la información proporcionada es incompleta o incorrecta **entonces** el API devuelve un response con status 400 Bad Request indicando los errores.|EP03|
|TS10|Endpoint para creación de perfil de emprendedor|**Como** Developer **deseo** crear un endpoint **para** permitir al emprendedor registrar su emprendimiento y necesidades para crear su perfil.|**Escenario 1:** Entrepreneur profile created successfully<br>**Dado que** el emprendedor realiza un POST request al endpoint /api/profile/entrepreneur con la información de su emprendimiento **cuando** el request es válido **entonces** el API devuelve un response con status 201 Created y el perfil del emprendedor se crea exitosamente.<br>**Escenario 2:** Entrepreneur profile creation fails<br>**Dado que** el emprendedor realiza un POST request al endpoint /api/profile/entrepreneur **cuando** la información proporcionada es incompleta o incorrecta **entonces** el API devuelve un response con status 400 Bad Request indicando los errores|EP03|
|TS11|Gestión de Planes de Suscripción|**Como** Developer **deseo** implementar la funcionalidad **para** que los emprendedores puedan elegir o modificar su plan de suscripción mediante la API REST, asegurando la correcta validación y actualización de datos.|**Escenario 1:** Ingreso de un nuevo plan de suscripción<br>**Dado que** que el usuario está autenticado con rol de emprendedor, **cuando** envía una solicitud POST /subscription con los datos del plan, **entonces** la API debe registrar el nuevo plan asociado al user_id del emprendedor **y** devolver un código de estado 201 con el mensaje "Plan registrado exitosamente"<br>**Escenario 2:** Modificación de un plan existente<br>**Dado que** que el emprendedor está autenticado, **cuando** envía una solicitud PUT /subscription con los datos actualizados **entonces** la API debe actualizar los detalles del plan asociado al user_id **y** devolver un código de estado 200 con el mensaje "Plan actualizado exitosamente".|EP03|
|TS12|Gestión de Métodos de Pago|**Como** Developer **deseo** implementar la funcionalidad **para** que los consultores puedan registrar y modificar sus métodos de pago mediante la API REST, asegurando la correcta validación y cifrado de los datos.|**Escenario 1:** Ingreso de un nuevo método de pago<br>**Dado que** que el usuario está autenticado como consultor, **cuando** envía una solicitud POST /payment-method con los detalles del método de pago (número de tarjeta, vencimiento, etc.), **entonces** la API debe registrar el método de pago asociado al user_id del consultor **y** devolver un código de estado 201 con el mensaje "Método de pago registrado exitosamente"<br>**Escenario 2:** Modificación de un método de pago existente<br>**Dado que** que el consultor está autenticado, **cuando** envía una solicitud PUT /payment-method con los datos actualizados del método de pago,**entonces** la API debe actualizar los detalles del método de pago existente, **y** devolver un código de estado 200 con el mensaje "Método de pago actualizado exitosamente".|EP03|
|TS13|Búsqueda y Filtrado de Consultores|**Como** Developer **deseo** implementar la funcionalidad de búsqueda de consultores en la API, **para** filtrar los resultados por su rubro de experiencia.|**Escenario 1:** Búsqueda de consultores por rubro de experiencia<br>**Dado que** que el emprendedor está autenticado **cuando** envía una solicitud GET /consultants?experience={rubro} **entonces** la API debe devolver una lista de consultores que coinciden con el rubro especificado, **y** devolver un código de estado 200 con los resultados filtrados.<br>**Escenario 2:** No hay consultores que coincidan con el filtro<br> **Dado que** que el emprendedor está autenticado, **cuando** envía una solicitud GET /consultants?experience={rubro} con un rubro inexistente, **entonces** la API debe devolver un código de estado 404 con el mensaje "No se encontraron consultores"|EP04|
|TS14|Gestión de Lista de Servicios Guardados|**Como** Developer **deseo** implementar la funcionalidad de agregar y visualizar servicios guardados por el emprendedor en la API REST, **para** asegurar que solo el usuario pueda acceder a su lista privada.|**Escenario 1:** Agregar un servicio a la lista de servicios guardados<br>**Dado que** que el emprendedor está autenticado, **cuando** envía una solicitud POST /saved-services con el service_id, **entonces** la API debe agregar el servicio a la lista privada del emprendedor, **y** devolver un código de estado 201 con el mensaje "Servicio guardado exitosamente".<br>**Escenario 2:** Visualizar lista de servicios guardados<br>**Dado que** que el emprendedor está autenticado, **cuando** envía una solicitud GET /saved-services, **entonces** la API debe devolver la lista de servicios guardados por el usuario,**y** devolver un código de estado 200 con los resultados.|EP04|
|TS15|Publicación de servicios en RESTful API|**Como** Developer **deseo** implementar un endpoint que permita a los consultores financieros publicar y editar sus servicios en el sistema **para** que los consultores puedan ofrecer varias opciones según las necesidades del cliente. |**Escenario 1:** Publicación de un nuevo servicio<br>**Dado que** el consultor financiero ha ingresado a su perfil **cuando** envía una solicitud POST al endpoint /api/services con los detalles del servicio **entonces** el sistema debe almacenar los detalles del servicio en la base de datos y devolver un código 201 con la información del servicio publicado.<br>**Escenario 2:** Modificación de un servicio existente<br>**Dado que** el consultor financiero ha ingresado a su perfil **cuando** envía una solicitud PUT al endpoint /api/services/{serviceId} con los detalles actualizados **entonces** el sistema debe actualizar los detalles del servicio en la base de datos y devolver un código 200 con la información actualizada.|EP04|
|TS16|Establecimiento de horario en RESTful API|**Como** Developer **deseo** crear un endpoint que permita a los consultores financieros configurar sus horarios laborales **para** que puedan establecer sus horas de trabajo y no recibir notificaciones fuera de esas horas.|**Escenario 1:** Configuración inicial de horario laboral<br>**Dado que** el consultor financiero está en su perfil **cuando** envía una solicitud POST al endpoint /api/work-schedule con los detalles de su horario **entonces** el sistema debe guardar el horario laboral en la base de datos y devolver un código 201 con la confirmación del horario registrado.<br>**Escenario 2:** Actualización del horario laboral<br>**Dado que** el consultor financiero necesita modificar su horario **cuando** envía una solicitud PUT al endpoint /api/work-schedule/{consultantId} con el nuevo horario **entonces** el sistema debe actualizar el horario en la base de datos y devolver un código 200 con la confirmación del horario actualizado.|EP04|
|TS17|Inicio de caso en RESTful API|**Como** Developer **deseo** implementar un endpoint que permita a los emprendedores iniciar casos con los consultores financieros **para** que puedan recibir asesoramiento personalizado para acceder a préstamos.|**Escenario 1:** Creación de un nuevo caso<br>**Dado que** el emprendedor ha seleccionado un consultor **cuando** envía una solicitud POST al endpoint /api/cases con los detalles del caso **entonces** el sistema debe crear el caso en la base de datos y devolver un código 201 con la información del caso creado.<br>**Escenario 2:** Visualización del caso creado<br>**Dado que** el emprendedor quiere ver los detalles del caso **cuando** envía una solicitud GET al endpoint /api/cases/{caseId} **entonces** el sistema debe devolver la información del caso con un código 200.|EP04|
|TS18|Aceptación de caso en RESTful API|**Como** Developer **deseo** implementar un endpoint que permita a los consultores financieros aceptar o rechazar los casos iniciados por los emprendedores **para** que puedan entender las necesidades del cliente antes de aceptar el caso.|**Escenario 1:** Aceptación del caso<br>**Dado que** el consultor financiero revisa un nuevo caso **cuando** envía una solicitud PUT al endpoint /api/cases/{caseId}/accept **entonces** el sistema debe actualizar el estado del caso a "aceptado" en la base de datos y devolver un código 200 con la confirmación.<br>**Escenario 2:** Rechazo del caso<br>**Dado que** el consultor financiero revisa un nuevo caso **cuando** envía una solicitud PUT al endpoint /api/cases/{caseId}/reject **entonces** el sistema debe actualizar el estado del caso a "rechazado" en la base de datos y devolver un código 200 con la confirmación.|EP04|
|TS19|Visualización de servicios en RESTful API|**Como** Developer **deseo** implementar un endpoint que permita a los consultores visualizar los servicios publicados por otros consultores **para** que puedan comparar sus servicios con los de los demás|**Escenario:** Visualización de servicios<br>**Dado que** el consultor financiero accede a la sección de servicios **cuando** envía una solicitud GET al endpoint /api/services **entonces** el sistema debe devolver una lista de servicios de otros consultores con un código 200|EP04|
|TS20|Sistema de mensajes en RESTful API|**Como** Developer **deseo** crear endpoints que permita enviar y recibir mensajes entre consultores y emprendedores **para** que puedan comunicarse directamente a través de la aplicación.|**Escenario 1:** Enviar mensaje<br>**Dado que** el consultor financiero necesita comunicarse con un emprendedor **cuando** envía una solicitud POST al endpoint /api/messages con los detalles del mensaje **entonces** el sistema debe guardar el mensaje en la base de datos y devolver un código 201 con la confirmación.<br>**Escenario 2:** Visualización de mensajes<br>**Dado que** el consultor financiero necesita revisar sus mensajes **cuando** envía una solicitud GET al endpoint /api/messages?consultantId={id} **entonces** el sistema debe devolver una lista de mensajes relacionados con el consultor con un código 200.|EP05|
|TS21|Historial de casos en RESTful API|**Como** Developer **deseo** implementar un endpoint que permita a los consultores visualizar el historial de casos y mensajes **para** que puedan dar seguimiento a sus interacciones con los emprendedores.|**Escenario:** Visualización del historial de casos<br>**Dado que** el consultor financiero necesita revisar su historial de casos **cuando** envía una solicitud GET al endpoint /api/cases/history?consultantId={id} **entonces** el sistema debe devolver una lista de casos anteriores con un código 200.|EP05|
|TS22|Envío de documentos adjuntos en RESTful API|**Como** Developer **deseo** crear un endpoint que permita a los consultores enviar documentos adjuntos a través de la plataforma **para** que puedan proporcionar información adicional a sus clientes.|**Escenario:** Envío de documento<br>**Dado que** el consultor financiero necesita enviar un documento a un cliente **cuando** envía una solicitud POST al endpoint /api/documents con el archivo adjunto **entonces** el sistema debe guardar el documento y devolver un código 201 con la confirmación del envío|EP05|
|TS23|Implementación de endpoint para notificaciones de actualizaciones|**Como** Developer **deseo** implementar un endpoint en la API **para** enviar notificaciones de actualizaciones de solicitudes cuando el consultor responde.|**Escenario:** Enviar notificación de actualización de solicitud<br>**Dado que** el consultor responde a una solicitud **cuando** la respuesta es almacenada en la base de datos **entonces** se envía una notificación al emprendedor asociado a la solicitud **y** el emprendedor recibe el mensaje de actualización|EP04|
|TS24|Endpoint para envío de alertas de fechas importantes|**Como** Developer **deseo** crear un endpoint **para** que gestione el envío de alertas de fechas importantes cuando el plazo se acerque.|**Escenario:** Enviar alerta por fecha límite cercana<br>**Dado que** el emprendedor tiene una fecha límite asociada a una solicitud **cuando** la fecha límite está a 3 días de distancia **entonces** el sistema envía una alerta de fecha al emprendedor **y** el emprendedor recibe la notificación.|EP05|
|TS25|Endpoint para solicitud de reseñas al cerrar un caso|**Como** Developer **deseo** implementar un endpoint **para** que los consultores puedan solicitar reseñas al cerrar un caso.|**Escenario:** Solicitar reseña tras cerrar un caso<br>**Dado que** el consultor ha cerrado un caso **cuando** el caso se marca como "Cerrado" en la base de datos **entonces** se envía una solicitud de reseña al emprendedor asociado **y** el consultor puede ver la reseña una vez completada|EP06|
|TS26|Endpoint para envío y almacenamiento de reseñas|**Como** Developer **deseo** crear un endpoint que permita a  los emprendedores enviar y almacenar reseñas de los consultores tras el cierre de un caso o desde la sección de Casos Archivados|**Escenario 1:** Enviar reseña tras cierre de caso<br>**Dado que** el emprendedor ha aceptado la solución del caso **cuando** el caso se cierra **entonces** el sistema muestra un formulario de reseña **y** el emprendedor envía su reseña sobre el consultor<br>**Escenario 2:** Enviar reseña desde Casos Archivados<br>**Dado que** el emprendedor tiene casos cerrados **cuando** ingresa a la sección Casos Archivados **entonces** puede seleccionar un caso y hacer click en Dejar Reseña **y** el sistema permite enviar la reseña.|EP06|
|TS27|Endpoint para consulta de métricas del consultor|**Como** Developer **deseo** crear un endpoint **para** que los consultores puedan visualizar sus métricas de desempeño de los últimos 30 días.|**Escenario:** Consultar métricas del último mes<br> **Dado que** el consultor ha trabajado por más de un mes **cuando** ingresa a la sección de Métricas en su perfil **entonces** el sistema consulta y devuelve las métricas del último mes **y** las métricas son visibles en la interfaz del consultor.|EP06|
|TS28|Endpoint para terminación de contrato por parte del consultor|**Como** Developer **deseo** crear un endpoint **para** que los consultores puedan terminar el contrato cuando el cliente no siga las recomendaciones.|**Escenario:** Terminar contrato por incumplimiento<br>**Dado que** el consultor ha enviado dos soluciones rechazadas **cuando** el consultor desea finalizar el contrato **entonces** puede apelar al "Cancelamiento por Incumplimiento" **y** el contrato se termina en el sistema. |EP06|
|TS29|Endpoint para terminación de contrato por parte del emprendedor|**Como** Developer **deseo** implementar un endpoint **para** que los emprendedores puedan cancelar el contrato si el consultor no responde en más de 7 días.|**Escenario:** Cancelar contrato por falta de respuesta<br>**Dado que** el emprendedor no ha recibido respuesta del consultor por 7 días  **cuando** ingresa a la sección "Más Opciones" del caso **entonces** puede seleccionar la opción de "Cancelamiento por Incumplimiento" **y** el contrato se cancela en el sistema.|EP06|
|TS30|Endpoint para consulta y visualización de artículos financieros|**Como** Developer **deseo** crear un endpoint **para** poder consultar y visualizar artículos financieros relacionados cuando no hay casos activos.|**Escenario:** Visualizar artículos financieros relacionados <br> **Dado que** el emprendedor no tiene casos activos **cuando** ingresa a la sección Explorar **entonces** el sistema consulta artículos relacionados a su rubro **y** los artículos son visibles en la interfaz.|EP07|
|TS31|Endpoint para acceso a herramientas de simulación de pagos|**Como** Developer **deseo** crear un endpoint **para** que tenga el acceso a simuladores de pagos cuando el emprendedor tiene una suscripción premium.|**Escenario:** Acceso a simuladores de pagos <br> **Dado que** el emprendedor tiene una suscripción premium **cuando** ingresa a la sección Herramientas **entonces** puede acceder a los simuladores de pagos y cuotas **y** puede calcular los pagos de sus deudas.|EP07|
|TS32|Endpoint para generación y envío de resúmenes financieros semanales|**Como** Developer **deseo** implementar un endpoint **para** que genere y envíe resúmenes financieros semanales a los emprendedores con casos activos.|**Escenario:** Enviar resumen semanal de casos activos <br> **Dado que** el emprendedor tiene casos activos **cuando** comienza una nueva semana **entonces** el sistema genera un resumen de los avances de sus casos **y** el resumen se envía al emprendedor.|EP07|
|TS33|Implementación de herramienta de seguimiento de ingresos y gastos|**Como** Developer **deseo** crear una herramienta dentro de la aplicación que permita a los emprendedores rastrear sus ingresos y gastos de manera eficiente **para** que puedan gestionar sus finanzas.|**Escenario:** Rastreo de ingresos y gastos <br>**Dado que** el emprendedor accede a la sección Herramienta **y** selecciona la opción Tracker **cuando** el emprendedor ingresa una nueva entrada o salida de dinero **entonces** el sistema almacena la información financiera **y** el emprendedor puede visualizar un resumen de sus ingresos y gastos.|EP07|
|TS34|Creación de herramienta para generar presupuestos personalizados|**Como** Developer **deseo** implementar una herramienta que permita a los emprendedores con suscripción premium crear presupuestos personalizados basados en sus ingresos y gastos **para** ayudarlos a administrar su dinero de manera efectiva.|**Escenario:** Crear presupuesto personalizado <br> **Dado que** el emprendedor tiene una suscripción premium **y** ha utilizado la aplicación por más de un mes **cuando** accede a la herramienta de presupuestos **entonces** el sistema genera planes de presupuesto basados en los datos de ingresos y gastos del emprendedor **y** el emprendedor puede ajustar los presupuestos según sus necesidades.|EP07|

### Spike Stories

Las siguientes Spike Stories fueron redactadas para reducir incertidumbre técnica y funcional antes de la implementación de ciertas funcionalidades críticas de DebtGo. Cada Spike incluye un objetivo claro de investigación y criterios de aceptación que indican cuándo se considera completado el análisis.

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Story ID</th>
      <th>User</th>
      <th>Priority</th>
      <th>Epic</th>
      <th>Title</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SP-01</td>
      <td>Developer</td>
      <td>Alta</td>
      <td>Autenticación</td>
      <td>Investigar bibliotecas de autenticación OAuth2</td>
    </tr>
    <tr>
      <td>SP-02</td>
      <td>Frontend Dev</td>
      <td>Alta</td>
      <td>Evaluación de servicios</td>
      <td>Definir mejores prácticas para UI/UX en solicitudes y reseñas</td>
    </tr>
    <tr>
      <td>SP-03</td>
      <td>Backend Dev</td>
      <td>Alta</td>
      <td>Pagos y suscripción</td>
      <td>Validar integración de pasarelas de pago (Stripe vs PayPal)</td>
    </tr>
    <tr>
      <td>SP-04</td>
      <td>Product Owner</td>
      <td>Media</td>
      <td>Casos y asesorías</td>
      <td>Analizar flujo óptimo para seguimiento de casos con chat</td>
    </tr>
    <tr>
      <td>SP-05</td>
      <td>Backend Dev</td>
      <td>Media</td>
      <td>Métricas de desempeño</td>
      <td>Determinar estructura de almacenamiento para métricas</td>
    </tr>
  </tbody>
</table>

### Detalles de Spike Stories
### SP-01. Investigar bibliotecas de autenticación OAuth2

**Descripción:**
Como desarrollador quiero investigar bibliotecas de autenticación OAuth2 para determinar cuál es la más adecuada para integrar con la plataforma.

**Criterios de aceptación:**

- Se investiga un mínimo de 3 bibliotecas OAuth2 compatibles con Spring Boot.
- Se evalúan criterios como compatibilidad, facilidad de integración, documentación y comunidad.
- Se entrega un documento comparativo con una recomendación final.
- Se incluye un pequeño prototipo funcional o prueba de concepto.

### SP-02. UI/UX para Evaluación de Servicios

**Descripción:**
Como desarrollador frontend deseo explorar diseños de UI/UX que maximicen la tasa de respuesta en evaluaciones de servicios y solicitudes de reseñas.

**Criterios de aceptación:**

- Se analizan al menos 5 referencias de apps similares.
- Se prueba al menos 1 prototipo en Figma con usuarios.
- Se documentan mejoras sugeridas y decisiones de diseño.
- Se define el diseño definitivo para la pantalla de evaluación.

### SP-03. Integración de pasarelas de pago

**Descripción:**
Como backend developer deseo analizar la viabilidad técnica y comercial de integrar Stripe o PayPal para permitir el pago de servicios dentro de DebtGo.

**Criterios de aceptación:**

- Se comparan ambos servicios en cuanto a costos, facilidad de integración, documentación y soporte en Perú.
- Se realiza una prueba de conexión (sandbox) con ambas pasarelas.
- Se entrega un reporte técnico con la recomendación.
- Se define el endpoint para pagos.

### SP-04. Flujo óptimo para seguimiento de casos

**Descripción:**
Como product owner deseo analizar el flujo óptimo entre cliente y asesor para el seguimiento de un caso a través de mensajería y etapas del proceso.

**Criterios de aceptación:**

- Se definen claramente los estados del caso: creado, en revisión, asesorado, cerrado.
- Se documenta el flujo de mensajes y acciones posibles en cada estado.
- Se valida la coherencia con los roles (emprendedor / asesor).
- Se entrega un diagrama BPMN y descripción funcional.

### SP-05. Estructura de métricas de desempeño

**Descripción:**
Como backend developer deseo definir cómo almacenar las métricas de desempeño de los asesores financieros para visualizarlas en su perfil.

**Criterios de aceptación:**

- Se identifican las métricas relevantes: casos atendidos, evaluaciones, reseñas.
- Se elige la estructura de base de datos (tabla relacional o documento).
- Se presenta el modelo ER o JSON.
- Se implementa una consulta de prueba para visualización.


## 3.4. Product Backlog

| Sprint | ID   | Título                                   | Descripción                                                                                                          | Story Points (1 / 2 / 3 / 5 / 8) |
|--------|------|------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------|
| 1      | US08 | Registrarse en la aplicación             | Como visitante, deseo registrarme en la aplicación para utilizar las funcionalidades ofrecidas.                      | 5                                |
| 1      | US10 | Registrar perfil como emprendedor        | Como emprendedor, deseo registrar mi emprendimiento y mis necesidades para empezar a utilizar la aplicación.         | 5                                |
| 1      | US12 | Registrar método de pago por servicios   | Como consultor financiero, deseo ingresar el método de pago de servicios para recibir el pago de los mismos.         | 5                                |
| 1      | US09 | Registrar perfil como consultor financiero| Como consultor financiero, deseo ingresar mi experiencia e información relevante para atraer posibles clientes.     | 5                                |
| 1      | US16 | Establecer horario de atención           | Como consultor financiero, deseo establecer mis horas de trabajo para no recibir notificaciones fuera de mi horario. | 3                                |
| 1      | US20 | Comunicarse mediante mensajes y casos    | Como consultor financiero, deseo comunicarme directamente con los clientes para ofrecer asesoramiento adecuado.      | 8                                |
| 1      | US22 | Enviar documentos adjuntos               | Como consultor financiero, deseo poder enviar documentos a través de la aplicación para apoyar al cliente.           | 3                                |
| 1      | US17 | Iniciar un caso de asesoría              | Como emprendedor, deseo tener acceso a asesoramiento personalizado para poder acceder a préstamos adecuados.         | 5                                |
| 1      | US18 | Aceptar un caso de asesoría              | Como consultor financiero, deseo hablar con el emprendedor antes de aceptar el caso.                                 | 3                                |
| 1      | US01 | Ver una demostración de la aplicación    | Como visitante, deseo ver una demostración de la aplicación para entender rápidamente lo que ofrece.                 | 2                                | 
| 1      | US02 | Visualizar reseñas de la aplicación      | Como visitante, deseo visualizar reseñas de la aplicación para decidir si quiero utilizarla.                         | 3                                |
| 1      | US03 | Consultar planes de la aplicación        | Como visitante, deseo visualizar los planes de suscripción para decidir el más adecuado.                             | 3                                |
| 1      | US06 | Conocer normas de privacidad             | Como visitante, deseo conocer las normas de privacidad para asegurar que mis datos serán protegidos.                 | 2                                |
| 2      | US11 | Elegir o actualizar plan de suscripción  | Como emprendedor, deseo registrar o modificar mi plan de suscripción.                                                | 5                                |
| 2      | US07 | Visualizar proceso de pago por servicios | Como consultor, deseo visualizar el sistema de pago para entenderlo antes de ofrecer mis servicios.                  | 2                                |
| 2      | US05 | Ofrecer servicios como consultor financiero| Como consultor financiero, deseo ofrecer mis servicios para tener una fuente adicional de ingresos.                | 3                                |
| 2      | US15 | Publicar servicios y precios             | Como consultor financiero, deseo publicar distintos servicios y sus precios.                                         | 5                                |
| 2      | US13 | Buscar consultores según necesidades     | Como emprendedor, deseo encontrar un consultor con experiencia en mi rubro.                                          | 5                                |
| 2      | US14 | Comparar servicios guardados             | Como emprendedor, deseo comparar servicios para elegir el más adecuado.                                              | 3                                |
| 2      | US04 | Contactar con soporte de la aplicación   | Como visitante, deseo contactarme con soporte para resolver dudas.                                                   | 3                                |
| 2      | US21 | Consultar historial de casos             | Como consultor financiero, deseo ver el historial de mensajes para seguimiento.                                      | 3                                |
| 2      | US23 | Recibir actualizaciones de solicitudes   | Como emprendedor, deseo recibir actualizaciones del estado de mis solicitudes.                                       | 5                                |
| 2      | US24 | Recibir alertas de fechas importantes    | Como emprendedor, deseo recibir alertas sobre fechas importantes.                                                    | 5                                |
| 2      | US25 | Solicitar reseñas de servicios           | Como consultor financiero, deseo recibir reseñas de mis servicios.                                                   | 3                                |
| 2      | US26 | Calificar servicios recibidos            | Como emprendedor, deseo calificar a los consultores que me atendieron.                                               | 3                                |
| 2      | US27 | Visualizar métricas de desempeño         | Como consultor financiero, deseo visualizar métricas sobre mis servicios.                                            | 8                                |
| 2      | US28 | Terminar contrato como consultor financiero| Como consultor financiero, deseo terminar un contrato para no afectar mis métricas.                                | 3                                |
| 2      | US29 | Cancelar contrato como emprendedor       | Como emprendedor, deseo cancelar un contrato si el consultor no cumple.                                              | 3                                |
| 2      | US30 | Leer artículos financieros               | Como emprendedor, deseo acceder a artículos financieros educativos.                                                  | 2                                |
| 2      | US31 | Usar herramientas de simulación          | Como emprendedor, deseo usar simuladores para estimar pagos.                                                         | 8                                |
| 2      | US32 | Ofrecer talleres financieros gratuitos   | Como consultor financiero, deseo ofrecer talleres gratuitos para atraer clientes.                                    | 5                                |
| 2      | US33 | Hacer seguimientos de ingresos y gastos  | Como emprendedor, deseo rastrear mis ingresos y gastos.                                                              | 8                                |
| 2      | US34 | Crear presupuestos personalizados        | Como emprendedor, deseo crear presupuestos personalizados según mis ingresos y gastos.                               | 5                                |

## 3.3. Impact Mapping

En esta sección, se presenta el Impact Mapping elaborado para DebtGo, que busca alcanzar el objetivo de aumentar la base de usuarios activos a 10,000 en los próximos 12 meses, con al menos un 30% suscritos a la tarifa mensual premium. El Impact Mapping se ha desglosado en función de dos segmentos de usuarios clave: Consultores Financieros y Gestores de Deudas y Emprendedores. Para cada segmento, se han identificado impactos específicos que contribuyen al logro del objetivo, junto con entregables necesarios para provocar dichos impactos. Además, se han definido historias de usuario que guiarán el desarrollo de las características y funcionalidades requeridas. Este enfoque asegura que DebtGo pueda proporcionar valor y cumplir con las expectativas de sus diversos usuarios, facilitando su crecimiento y sostenibilidad en el mercado. Esta sección se llevó a cabo utilizando la plataforma UXPressia.

**Segmento Objetivo: Consultores financieros:**

#### Impact Mapping 1: 

![image](assets/Chapter-3/Impact%20map%201.png)
*Imagen (N°12). Elaboración propia. Realizado en UXPRESSIA*

**Segmento Objetivo: Gestores de Deudas y Emprendedores**

#### Impact Mapping 2: 

![image](assets/Chapter-3/Impact%20map%202.png)
*Imagen (N°13). Elaboración propia. Realizado en UXPRESSIA*

# Capítulo IV: Product Design

### 4.1. Style Guidelines

Un Style Guidelines, o Guía de Estilo, es un documento que proporciona directrices claras y coherentes sobre la apariencia visual, la comunicación y la identidad de una marca o producto. Esta guía asegura que todos los elementos relacionados con la marca, como tipografía, colores, logotipos y tono de voz, se mantengan uniformes en todas las aplicaciones y plataformas, lo que ayuda a reforzar la identidad de la marca y garantiza una experiencia de usuario consistente y reconocible.

### 4.1.1. General Style Guidelines

**Branding:** 

La identidad visual de una marca, que incluye su logotipo, colores, tipografía y otros elementos visuales.La identidad de marca de DebtGo se basa en la misión de proporcionar educación financiera y ayudar a las personas a manejar sus deudas de manera efectiva. Valores clave incluyen la transparencia, la confianza y la accesibilidad. DebtGo debe proyectar una personalidad amigable, confiable y educativa, para que los usuarios sientan que están recibiendo orientación de un amigo de confianza.

**Logo**

El logo principal de DebtGo debe ser limpio y moderno, con un énfasis en la simplicidad y la claridad. Puede incorporar elementos que evocan finanzas, como gráficos de barras estilizados o un gráfico de línea ascendente para simbolizar el crecimiento financiero. Se pueden crear variaciones del logotipo para adaptarse a diferentes tamaños y plataformas, pero la esencia y los colores deben mantenerse coherentes.

<center> <img src="assets/Chapter-5/Logo.png" style="width: 200px;"/> </center>
<br>

**Tipografía:**

La elección tipográfica para DebtGo es un componente esencial que complementa la identidad visual de la marca. Se han seleccionado tres familias tipográficas para la marca: Urbanist, Merriweather Sans y Sora. Siendo la principal **Urbanist**.

<center> <img src="assets/Chapter-5/Urbanist.webp" style="width: 350px;"/> </center>
<br>

**Colores:** 

La paleta de colores de DebtGo ha sido cuidadosamente seleccionada para transmitir profesionalismo, confianza y accesibilidad. Cada color tiene un propósito específico y se utilizará de manera consistente en toda la identidad visual de la marca.

<center> <img src="assets/Chapter-5/paleta.png" style="width: 500px;"/> </center>
<br>

- #998EF7 (Lavanda suave): Este color se utilizará como el tono principal, predominando en el logotipo, encabezados y elementos clave de la interfaz como las llamadas a la acción (CTA), botones y elementos interactivos.

- #9B6CF0 (Lavanda): Se utilizará para fondos oscuros permitiendo resaltar los elementos claves con el tono principal.

- #7960F2 (Lavanda profunda): Este tono servirá para complementar al contraste de los elementos principales.

- #000000 (Negro): Utilizado para títulos en fondos claros.

- #FFFFFF (Blanco): Utilizado para títulos en fondos con las tonalidades principales.

- #F3F3FF (Gris suave): Para subtítulos en fondos con las tonalidades principales.

- #939393 (Gris medio): Se utilizará para cuerpo y textos de menor jerarquía.

- #3D3D3D (Gris oscuro): Este color será empleado en subtítulos con fondos claros.

**Tono de comunicación y lenguaje aplicado:**

 El estilo de comunicación que se utiliza en el diseño, que puede ser divertido/serio, formal/casual, respetuoso/irreverente o entusiasta/sereno.

 - Memorable y reconocible: La identidad de marca debe ser única y fácilmente identificable. Esto ayudará a que la empresa se destaque de la competencia y sea recordada por los clientes.
- Confiable y profesional: La identidad de marca debe transmitir la idea de que la empresa es confiable y profesional. Esto ayudará a que los clientes se sientan seguros de confiar en la empresa con sus finanzas.
- Atractiva y llamativa: La identidad de marca debe ser atractiva y llamativa. Esto ayudará a captar la atención de los clientes y a atraerlos a la empresa.

**Lenguaje aplicado:**

 El lenguaje que se utiliza en el diseño, que debe ser claro, conciso y fácil de entender.

**Marca** 

El nombre de la empresa, "DebtGo", es un juego de palabras con la palabra "Debt" (deuda en inglés). El uso de la letra "g" en lugar de la "d" crea un sonido similar, pero también sugiere una acción, como "go" (ir). Esto transmite la idea de que la empresa puede ayudarte a eliminar tus deudas.

**Spacing** 

El espaciado entre los elementos del logotipo es uniforme y equilibrado. Esto crea una sensación de orden y armonía. El espaciado entre las letras del nombre de la empresa es lo suficientemente amplio para que sean legibles, pero no tanto como para que se vean demasiado separadas.

### 4.1.2. Web Style Guidelines

Se definió estándares visuales y de interacción para la **Web App/Landing** de DebtGo, asegurando consistencia, accesibilidad (WCAG 2.1 AA) y buen rendimiento en **responsive**.

### Estructura y Layout
- **Grid:** 12 columnas, `max-width` 1200–1280px en desktop, gutters de 24px.
- **Breakpoints:**  
  - `≤576px` (mobile), `>576px` (phablet), `≥768px` (tablet), `≥992px` (laptop), `≥1200px` (desktop).
- **Espaciado:** sistema 8px (8/16/24/32/48). Áreas grandes: 64–96px.
- **Contenedores:** `padding` horizontal 16px (mobile), 24–32px (tablet/desktop).

### Diseño de página
- **Navbar fija** con enlaces: *Resumen*, *Beneficios*, *Cómo funciona*, *Precios* (si aplica), *FAQ* y CTA (*Crear cuenta*).  
  En mobile: **menú hamburguesa** deslizable.
- **Hero** con título claro, subtítulo y CTA; ilustración/imagen optimizada.
- **Secciones**: tarjetas con iconos para beneficios, pasos del flujo, y una sección de **FAQ** expandible.
- **Footer** con enlaces a *Términos*, *Privacidad*, correo de soporte y redes; badge de seguridad/SSL.

### Responsive
- **CSS3 + media queries** con unidades relativas (`rem`, `%`, `vh/vw`).
- Elementos clave (navbar, footer, grids) reordenan y cambian densidad en pantallas pequeñas.
- Tablas → listas apiladas o tarjetas en mobile.

### Tipografía
- **Primaria:** Inter / Poppins / Roboto (sans).  
- Escala recomendada: `H1 40–48px`, `H2 32–36px`, `H3 24–28px`, `Body 16–18px`, `Caption 12–14px`.
- **Contraste mínimo:** 4.5:1; tamaños fluidos con `clamp()`.

### Colores
- Usar **tokens** y tema claro/oscuro:
  - `--color-primary`, `--color-secondary`, `--color-bg`, `--color-surface`, `--color-success`, `--color-warning`, `--color-error`.
- Estados: hover/focus/disabled definidos; foco visible (`outline` accesible).

### Imágenes y Medios
- Formatos: **WebP** preferido; fallback **JPEG/PNG**.  
- Compresión y `loading="lazy"`; `srcset`/`sizes` para responsive.

### Componentes e Interacción
- **Botones:** primario (filled), secundario (outlined), terciario (text). Altura 40–48px, radios 8–12px.
- **Forms:** validación en tiempo real, mensajes claros, máscaras de entrada (monto/fecha).  
- **Animaciones:** sutiles (150–250ms, `ease-out`), sin bloquear contenido; respetar *prefers-reduced-motion*.

### Navegación
- Breadcrumbs en secciones internas.  
- Enlaces de redes en footer accesibles con `aria-label`.  
- Atajos de teclado para acciones frecuentes (opcional).

### Recursos
- Repositorio de **assets** (logos, íconos, ilustraciones).  
- Archivo de **tokens de diseño** (CSS variables/JSON).  
- Fuentes y guía de uso (peso, fallback).

### 4.1.3. Mobile Style Guidelines

Garantizar coherencia visual y funcional en **iOS** y **Android**, respetando patrones nativos y manteniendo la identidad de DebtGo.

Reglas comunes:
- **Sistema de espaciado:** base 8px.  
- **Tamaños táctiles mínimos:** 44×44pt (iOS) / 48×48dp (Android).  
- **Accesibilidad:** tamaños dinámicos (Dynamic Type / Font Scaling), contraste ≥4.5:1, soporte *screen readers* (VoiceOver/TalkBack).

#### 4.1.3.1. iOS Mobile Style Guidelines

**Principios (HIG):** claridad, deferencia al contenido y profundidad.

#### Navegación
- **Navigation Bar**: título centrado o alineado a la izquierda según jerarquía; acciones a la derecha (*Guardar*, *Editar*).
- **Tab Bar** (hasta 5 tabs): icono + etiqueta (texto corto). Badges para estados relevantes (p. ej., notificaciones).

#### Interacción
- **Botones:** estilo *filled* y *tinted*; radio 12pt; altura 44–48pt.
- **Feedback:** cambio de opacidad y **haptic** sutil en acciones principales.
- **Gestos:** *swipe* para acciones en listas (p. ej., marcar pagado/posponer).

#### Tipografía
- **SF Pro** (San Francisco).  
  - Títulos: 17pt (semibold) con Dynamic Type.  
  - Cuerpo: 15pt (regular).  
  - Subtítulos/labels: 13pt.

#### Colores y Espaciado
- Tokens iOS: `label`, `secondaryLabel`, `systemBackground`, `secondarySystemBackground`, `separator`.  
- **Contraste** AA y estados claros (enabled/disabled/error/success).

#### Iconografía
- **SF Symbols** priorizado para coherencia y adaptabilidad (peso/escala).  
- Íconos de acción consistentes entre pantallas (ej.: calendario, campana, tarjeta).

#### Patrones de DebtGo
- **Flujo “Registrar deuda”**: formulario paso a paso con validación por campo.  
- **“Programar recordatorios”**: controles de fecha/hora nativos + switches de canales (push/email/SMS).  
- **Dashboard**: tarjetas de deuda con chips de estado (Vencida/Próxima/Al día).

#### 4.1.3.2. Android Mobile Style Guidelines

**Principios (Material Design 3):** jerarquía clara, movimiento significativo y personalización (Material You).

#### Navegación
- **App Bar** (Top App Bar): título a la izquierda; acciones en **overflow (⋮)** cuando superen 2.  
- **Bottom Navigation**: 3–5 destinos; estados activos con **indicator** y color de énfasis.  
- **Navigation Drawer** para accesos secundarios (perfil, ajustes).

#### Interacción
- **Botones (MD3):**  
  - **Filled**: acción primaria (pago/guardar).  
  - **Outlined**: secundaria.  
  - **Text**: terciaria.  
  - Altura 48dp; radios según MD3 (8–12dp).
- **Feedback:** **Ripple** táctil; transiciones 200–250ms.

#### Tipografía
- **Roboto** o **Roboto Flex**.  
  - Title Large ~22sp, Title Medium ~16–18sp, Body ~14–16sp.  
  - Respeto a *fontScale* del sistema.

#### Colores y Elevación
- **Material Theming** con `primary`, `secondary`, `tertiary`, `error`, `surface`, `on*`.  
- **Elevación** para jerarquía: `Card` 1–3dp, `FAB` 6dp.  
- Soporte de **tema dinámico** (Material You) cuando el sistema lo permita.

#### Iconografía
- **Material Icons** (Filled/Outlined/Rounded); tamaño 24dp en controles, 20dp en listas densas.

#### Patrones de DebtGo
- **Flujo “Registrar deuda”**: `TextField` MD3 con helper/error; teclado numérico para monto y `DatePicker`.  
- **“Programar pagos”**: `SegmentedButtons` para frecuencia + `TimePicker`.  
- **Notificaciones**: switches por canal; `Snackbar/Toast` para feedback.

## 4.2. Information Architecture
La Arquitectura de la Información (AI, por sus siglas en inglés) es una disciplina y una práctica de diseño que se ocupa de optimizar la forma en que se organiza, estructura, etiqueta y conecta la información en entornos digitales. Esta arquitectura es esencialmente una especie de ‘mapa’ que se usa para ayudar a los usuarios a comprender dónde se encuentran en un entorno digital, cómo llegaron allí y cómo pueden continuar hacia otras secciones relacionadas o importantes.

El objetivo clave de la Arquitectura de la Información es lograr un equilibrio entre las necesidades y las capacidades del usuario y los objetivos del negocio. Facilita la navegación eficiente y efectiva a través de la complejidad de la información que encontramos en las aplicaciones de software, sitios web, intranets, plataformas en línea, etc. Por tanto, su propósito principal es diseñar una estructura de información coherente, comprensible y utilizable, que permita a los usuarios alcanzar sus objetivos de manera fácil y rápida.

Además, la Arquitectura de la Información también es relevante para hacer que la información sea más entendible y utilizable. Esto se logra simplificando su estructura y su contenido, lo que ayuda a los usuarios a interpretar la información presentada, a tomar decisiones informadas y finalmente a interactuar con el sistema de una manera más efectiva e intuitiva.

Por lo tanto, una buena Arquitectura de la Información puede mejorar significativamente la experiencia del usuario, y puede jugar un papel vital en el éxito de cualquier producto o servicio digital.

### 4.2.1. Organization Systems

Los sistemas de organización se encargan de la estructura y los procesos que se implementan en una empresa u organización para mejorar la eficiencia y la productividad.

El objetivo principal del sistema de organización es establecer métodos y procedimientos claros para gestionar los recursos disponibles, tanto humanos como materiales, de manera eficiente. Esto implica organizar tareas, establecer responsabilidades, distribuir recursos y coordinar actividades para lograr los objetivos de la organización de manera efectiva.

**Algunos de los beneficios de implementar un sistema de organización incluyen:**

- Eficiencia: Un sistema de organización ayuda a optimizar el uso de los recursos disponibles, lo que se traduce en una mayor eficiencia en el trabajo realizado. Al establecer tareas y roles claros, se evita la duplicación de esfuerzos y se minimizan los errores.
- Productividad: Al contar con un sistema de organización efectivo, se establecen rutinas y procesos que permiten esfuerzos más enfocados y una mayor productividad en el cumplimiento de metas y objetivos.
- Coordinación: Un sistema de organización facilita la coordinación entre diferentes miembros de la organización. Al establecer una estructura clara de comunicación y responsabilidades, se asegura una sincronización adecuada de las actividades en equipo.
- Planificación estratégica: Los sistemas de organización ayudan a establecer metas y objetivos claros, y permiten una planificación estratégica efectiva. Esto implica definir la visión y los valores de la organización, así como establecer planes y acciones específicas para alcanzar esos objetivos.
- Control: Los sistemas de organización facilitan el seguimiento y control de las actividades y el rendimiento de la organización. Esto permite identificar áreas de mejora, corregir desviaciones y asegurar la conformidad con los estándares establecidos.

Los sistemas de organización son fundamentales para establecer procesos eficientes y coordinados en una organización, lo que resulta en una mayor productividad y logro de objetivos. Ayudan a definir roles y responsabilidades, optimizar el uso de recursos, establecer una estructura de comunicación clara y permiten una planificación estratégica efectiva.

### 4.2.2. Labelling Systems

Un Labelling System o sistema de etiquetado, se enfoca en un conjunto de técnicas y herramientas utilizadas para identificar y clasificar datos o elementos. El objetivo principal de un Labelling System es asignar etiquetas descriptivas a los datos, lo que facilita su organización búsqueda y procesamiento posterior.

Los Labelling Systems son comúnmente utilizados en diferentes industrias y aplicaciones, como la clasificación de productos, el etiquetado de información en bases de datos, el marcado de imágenes o el análisis de texto. Algunas de las áreas en las que se utilizan con frecuencia son:

- Aprendizaje automático (Machine Learning): En el campo del aprendizaje automático, los Labelling Systems son utilizados para etiquetar conjuntos de datos que serán utilizados para entrenar modelos de machine learning. Esto implica asignar etiquetas a los datos de entrenamiento para que el sistema pueda aprender a reconocer patrones y realizar predicciones precisas.

- Clasificación de productos: En el comercio electrónico y la logística, los Labelling Systems se utilizan para etiquetar productos con información como códigos de barras, números de lote, fechas de caducidad, etc. Esto facilita su identificación y seguimiento a lo largo de la cadena de suministro.

- Organización de archivos y documentos: Los Labelling Systems también son útiles para etiquetar archivos y documentos electrónicos, facilitando su organización y búsqueda rápida. Las etiquetas pueden incluir información como el tema, la fecha, el remitente, entre otros.

- Anotación de imágenes y videos: En el campo de la visión por computadora, los Labelling Systems se utilizan para etiquetar y anotar imágenes y videos para tareas como reconocimiento de objetos, segmentación de imágenes, detección de rostros, entre otros. Estas etiquetas proporcionan información descriptiva sobre los elementos presentes en las imágenes y facilitan el entrenamiento y la evaluación de algoritmos.

Los Labelling Systems son sistemas o técnicas de etiquetado utilizadas para clasificar y organizar datos, productos o elementos. Su objetivo principal es asignar etiquetas descriptivas que faciliten la organización, búsqueda y procesamiento posterior.

### 4.2.3. SEO Tags and Meta Tags

**SEO Tags**

SEO (Search Engine Optimization) Tags son elementos de HTML que ayudan a los motores de búsqueda a entender el contenido y la estructura de una página web. Estos tags influyen en cómo los motores de búsqueda indexan y clasifican tu sitio en los resultados de búsqueda. 

**Algunos ejemplos importantes de SEO Tags incluyen:**

**Title Tag:**

Es el título de la página web que aparece en la pestaña del navegador y como el título del enlace en los resultados de búsqueda. Importancia: Es crucial porque es uno de los factores más influyentes en el ranking de la página. Debe ser relevante, contener palabras clave, y tener una longitud de entre 50 y 60 caracteres. 

*Ejemplo:* 
``` html
<title>Compra Ropa de Moda Online - Tienda XYZ</title>
``` 


**Header Tags (H1, H2, H3, etc.):** 

Son etiquetas utilizadas para definir los encabezados y subencabezados dentro del contenido de la página. El H1 es el encabezado principal y es el más importante en términos de SEO. Importancia: Ayudan a organizar el contenido y permiten a los motores de búsqueda comprender la jerarquía y el tema principal de la página. 

*Ejemplo:*
```html
<h1>Las Mejores Ofertas en Ropa de Moda</h1>
```

**Alt Tags:**

Son atributos utilizados en imágenes para describir su contenido. Aunque los usuarios no pueden ver este texto directamente, los motores de búsqueda lo utilizan para entender el contenido de la imagen. Importancia: Mejoran la accesibilidad y también son importantes para el SEO, especialmente en la búsqueda de imágenes.

**Meta Tags**

Los Meta Tags son fragmentos de texto que describen el contenido de la página; no aparecen en la página misma, pero se encuentran en el código HTML de la página. Los motores de búsqueda y los navegadores utilizan estos tags para obtener información adicional sobre la página. Algunos de los Meta Tags más relevantes para SEO son:

**Meta Description Tag:**

Proporciona un resumen breve del contenido de la página. Aunque no afecta directamente al ranking de búsqueda, es importante porque aparece en los resultados de búsqueda bajo el título de la página. Importancia: Una meta descripción atractiva puede aumentar la tasa de clics (CTR) desde los motores de búsqueda. 

Originalmente, se utilizaba para listar palabras clave relevantes para la página. Sin embargo, hoy en día, la mayoría de los motores de búsqueda ya no utilizan este tag para el ranking. Importancia: Es menos relevante en la actualidad, pero puede ser utilizado por algunos motores de búsqueda secundarios. 

**Meta Robots Tag:**

Indica a los motores de búsqueda cómo deben indexar o seguir los enlaces en la página. Importancia: Se utiliza para controlar la indexación de la página. Por ejemplo, si no quieres que una página específica sea indexada, puedes usar este tag. 

*Ejemplo:*
```
 Viewport Tag
```
 Especifica cómo se ajustará la página a la pantalla del dispositivo (especialmente importante para dispositivos móviles). 
 
 Importancia: Crucial para la optimización móvil, ya que garantiza que el sitio web se visualice correctamente en dispositivos de diferentes tamaños.

 ### 4.2.4. Searching Systems

 Un Searching Systems, también conocido como sistema de búsqueda o motor de búsqueda, es una aplicación automática diseñada para buscar y recuperar información almacenada en una base de datos o en internet. Su principal objetivo es encontrar y mostrar resultados relevantes que coincidan con las palabras clave o términos de búsqueda ingresados por el usuario.

El funcionamiento básico de un Searching System consiste en rastrear y analizar grandes cantidades de contenido o información estructurada, como páginas web, documentos, imágenes, videos, etc. Luego, utilizando algoritmos y técnicas de indexación, organiza esta información de manera que pueda ser rápida y fácilmente accesible cuando un usuario realiza una consulta de búsqueda.

El objetivo principal de un Searching System es brindar respuestas relevantes y precisas a las consultas de los usuarios. Para lograr esto, utilizan algoritmos de ranking que evalúan la relevancia y la calidad de los resultados en función de varios factores, como la coincidencia de palabras clave, la autoridad de la fuente, la popularidad del contenido, entre otros.

Los Searching Systems, se utilizan en una amplia variedad de aplicaciones y servicios en línea, como motores de búsqueda web (como Google, Bing, Yahoo), motores de búsqueda de sitios web internos, directorios de archivos locales, sistemas de recuperación de información, entre otros. También se utilizan en diferentes industrias, como el comercio electrónico, la investigación académica, la búsqueda y recuperación de documentos legales, la búsqueda de imágenes, entre muchos otros casos de uso.

Uns Searching System es una herramienta informática que permite buscar y recuperar información relevante almacenada en una base de datos o en internet. Su objetivo es proporcionar respuestas precisas y relevantes a las consultas de los usuarios.

### 4.2.5. Navigation Systems

Un sistema de navegación, también conocido como sistema de posicionamiento y navegación, es una tecnología utilizada para determinar la ubicación, la dirección y la ruta más adecuada para llegar a un destino específico. Su objetivo principal es ayudar a las personas a navegar de manera eficiente y precisa, ya sea en vehículos, aviones, barcos u otros medios de transporte.
El sistema de navegación utiliza una variedad de tecnologías como el GPS (Sistema de Posicionamiento Global), sensores inerciales y otros sistemas de comunicación para obtener información sobre la posición del vehículo en tiempo real. Estos datos se utilizan para calcular la ruta óptima hacia el sistema solicitado.

Además de proporcionar indicaciones de manejo paso a paso, los sistemas de navegación también pueden ofrecer información adicional, como el estado del tráfico, el tiempo estimado de llegada, la presencia de puntos de interés cercanos y la información actualizada del mapa.

El objetivo principal de un sistema de navegación es facilitar la navegación y mejorar la experiencia del usuario al proporcionar una guía precisa y confiable en el proceso de desplazarse de un lugar a otro. Esto ayuda a ahorrar tiempo, evitar posibles desvíos o atascos de tráfico, y proporcionar una sensación de seguridad al conocer la ruta y la ubicación en todo momento.

Un sistema de navegación es una herramienta tecnológica que utiliza varios sistemas para proporcionar información y guía para llegar a un destino específico de la manera más eficiente posible. Su objetivo es mejorar la experiencia de navegación al ofrecer indicaciones precisas y actualizadas, así como otros datos útiles relacionados con la ruta.

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

El prototipado de la landing page cuenta diversas secciones:
- Header: Incluye botones para facilitar la navegación
- Hero: Con 2 CTA, uno para cada segmento objetivo, un título y una imagen de fondo.
- Segmentos y beneficios: Para cada segmento se tiene un título, una breve descripción, un CTA y una imagen. Debajo de cada sección se detallan los beneficios que se ofrecen.
- Testimonios: Consta de un título y subtítulo, así como de unos testimonios de usuarios de cada segmento, lo que aumenta la confianza en los potenciales clientes.
- Contacto: Tiene un título y subtítulo, un pequeño input para la introducción de un email y un botón para el envio del correo.
- Footer: Sección que da fin a la landing page, cuenta con las redes sociales de la plataforma.

**Wireframe Destkop**

<img src="assets/Chapter-5/Wireframe-Desktop.png">

*Imagen(N°14). Elaboración propia. Realizado en figma*

**Wireframe Mobile** <br>
En la versión mobile el navbar se reemplaza por un menu desplegable.

<div align="center">
<img src="assets/Chapter-5/Wireframe-Mobile.png">

*Imagen(N°15). Elaboración propia. Realizado en figma*
</div>

### 4.3.2 Landing Page Mock-up

Siguiendo los wireframes de la landing page se realizaron los mockups:
- Header y Segmentos: Se utilizan los colores primarios de la plataforma especificados.
- Hero: Cuenta con una imagen relacionada a la plataforma, además se tiene dos CTA en versiones alternativas para la diferenciación.
- Beneficios: Incluye iconos relacionados con los beneficios ofrecidos y con el color principal, además el fondo es claro alternando con la sección de Segmentos para una mejor separación.
- Testimonios: Con un fondo de color principal para constrastar con las tarjetas de cada testimonio.
- Contacto: Se tiene un CTA en color primario, siendo notorio al estar en un fondo claro.
- Footer: Al igual que el header, utiliza los colores primarios de la plataforma para dar un fin estético a la página.

**Mock-up Destkop**

<img src="assets/Chapter-5/Mockup-Desktop.png">

*Imagen(N°16). Elaboración propia. Realizado en figma*

**Mock-up Mobile** <br>
En la versión mobile el navbar se reemplaza por un menu desplegable.

<div align="center">
<img src="assets/Chapter-5/Mockup-Mobile.png">

*Imagen(N°17). Elaboración propia. Realizado en figma*
</div>

## 4.4. Mobile Applications UX/UI Design
### 4.4.1. Mobile Applications Wireframes
#### Payment BC
![image](assets/Chapter-4/PaymentWireflow.png)
#### Notification BC
![image](assets/Chapter-4/NotificationWireframe.png)
### 4.4.2. Mobile Applications Wireflow Diagrams
#### Payment BC
**User Goal**: El usuario quiere registrar una nueva deuda para poder visualizarla, hacer seguimiento y gestionarla desde la aplicación.
![image](assets/Chapter-4/PaymentWireflow1.png)
**User Goal**: El usuario desea configurar cómo pagará sus deudas (tarjeta, monto, frecuencia) y poder modificar esta configuración si es necesario.
![image](assets/Chapter-4/PaymentWireflow2.png)
### 4.4.3. Mobile Applications Mock-ups
#### Payment BC
![image](assets/Chapter-4/Payment%20Mockup.png)
#### Notification BC
![image](assets/Chapter-4/NotificationMockup.png)

### 4.4.4. Mobile Applications User Flow Diagrams

**User Persona: Emprendedor**

**User Goal:** Registrar una deuda y configurar notificaciones personalizadas para evitar moras.


<img src="assets/Chapter-5/userflow_diagrams.png" width="800px"> <br> <br>

Este User Flow cubre el objetivo principal del usuario emprendedor de registrar deudas, configurar recordatorios y visualizar el estado de sus pagos. Se incluyen tanto el camino esperado (happy path) como rutas alternativas (unhappy paths) que muestran errores de conexión, advertencias de canales desactivados y confirmaciones exitosas. Las pantallas fueron diseñadas para guiar visualmente al usuario con feedback claro, colores distintivos y navegación intuitiva.

## 4.5. Mobile Applications Prototyping

El prototipo desarrollado para Android muestra cómo la aplicación se adapta a las guías de diseño de esta plataforma, respetando principios de usabilidad como botones accesibles, tipografía legible y navegación intuitiva. En Android, se prioriza la simplicidad en el flujo de registro, inicio de sesión y gestión de pagos, lo cual garantiza que los usuarios puedan interactuar fácilmente con la aplicación.

### Registration And Login (Registro e Inicio de Sesión)
![image](assets/Chapter-5/registro-inicio-sesion.png)

En esta sección se muestra la pantalla de registro o inicio de sesión para acceder a la app.

### Payment Plans (Planes de Pago)
![image](assets/Chapter-5/planes-pago.png)

Una vez que haya finalizado el registro o inicio de sesión le mostrará la sección de planes de pago, en el cuál podrá visualizar y elegir entre los dos planes de pago (Básico o Premium).

### Home (Inicio de la App)
![image](assets/Chapter-5/inicio-app.png)

Después de haber hecho estos pasos entrará a la pantalla principal de la app, con botones de acceso rápido a las funciones clave, entre otras cosas más.

### Notifications (Notificaciones)
![image](assets/Chapter-5/notificaciones.png)

Dentro de la app hay una sección de notificaciones, puedes entrar ya sea en el ícono de notificación o en "View All". Dentro del centro de notificaciones, el usuario puede ver alertas, recordatorios y mensajes, puedes editar a tu gusto personal también.

### Payment Management (Gestión de Pagos)
![image](assets/Chapter-5/gestion-pagos.png)

Otra herramienta que cuenta Debtgo es la gestión de pagos, allí podrás ver los pagos realizados, los pagos pendientes e inclusive programar nuevos pagos.

### Add New Debt (Añadir Nueva Deuda)
![image](assets/Chapter-5/nueva-deuda.png)

Al igual que contamos con la gestión de pagos, también contamos exclusivamente lo que es añadir una nueva deuda, podrás registrar una nueva deuda, ingresando detalles como el monto, la fecha y las condiciones que creas pertinente.

### Financial Education (Educación Financiera)
![image](assets/Chapter-5/educacion-financiera.png)

Dentro de la app contamos también en un apartado de "Educación Financiera", en el cuál podrás inscribirte a los cursos que contamos, ver videos, les lecciones que hay en cada curso, así podrás aprender aún más a gestionar correctamente tus finanzas de una manera segura y eficiente.

### Course 1: Master Your Finances (Domina Tus Finanzas)
![image](assets/Chapter-5/domina-tus-finanzas.png)
![image](assets/Chapter-5/lecciones-curso1.png)
![image](assets/Chapter-5/lecciones-parte2-curso1.png)

Pasamos al primer curso que se llama **"Master Your Finances"** o en español **"Domina Tus Finanzas"**, cuenta con 6 lecciones, aprenderás a poder controlar, gestionar, adquirir conocimientos suficientes sobre las finanzas y su importancia. Al terminar las 6 lecciones te aparecerá un mensaje de que has terminado el curso satisfactoriamente y te mandará a la sección principal de Educación Financiera.

### Course 2: Make Your Money Grow (Haz Crecer Tu Dinero)
![image](assets/Chapter-5/haz-crecer-tu-dinero.png)
![image](assets/Chapter-5/lecciones-curso2.png)
![image](assets/Chapter-5/lecciones-parte2-curso2.png)

Seguidamente tenemos al segundo curso llamado **"Make Your Money Grow"** o en español **"Haz Crecer Tu Dinero"**, cuenta también con 6 lecciones, este curso está enfocado en las inversiones, ahorros y estrategias para aumentar el dinero.  Al terminar las 6 lecciones te aparecerá un mensaje de que has terminado el curso satisfactoriamente y te mandará a la sección principal de Educación Financiera.

### Course 3: Smart Financial Planning (Planificación Financiera Inteligente)
![image](assets/Chapter-5/planificacion-financiera-inteligente.png)
![image](assets/Chapter-5/lecciones-curso3.png)
![image](assets/Chapter-5/lecciones-parte2-curso3.png)

Finalmente tenemos al 3er y último curso llamado **"Smart Financial Planning"** o en español **"Planificación Financiera Inteligente"**, cuenta con 6 lecciones al igual que los 2 cursos anteriores, este curso está enfocado en ayudar a las personas a poder organizar metas y recursos. Al terminar las 6 lecciones te aparecerá un mensaje de que has terminado el curso satisfactoriamente y te mandará a la sección principal de Educación Financiera.

### Additional Course 1: Personal Budget Mentory (Asesoría Presupuestaria Personalizada)
![image](assets/Chapter-5/asesoria-presupuestaria-personalizada.png)

También tenemos 3 cursos adicionales por si quieres adquirir más conocimientos de lo que ya tienes, el primer curso se llama **"Personal Budget Mentory"** o en español **"Asesoría Presupuestaria Personalizada"**, es un aporte más con respecto a mejorar su presupuesto. Te registras mediante un formulario y te llegará una notificación de que tu solicitud ha sido aceptada.

### Additional Course 2: Advanced Investment Workshop (Taller De Inversión Avanzada)
![image](assets/Chapter-5/taller-inversion-avanzada.png)

Este segundo curso adicional llamado **"Advanced Investment Workshop"** o en español **"Taller De Inversión Avanzada"**, son más que todo talleres, dirigido a estudiantes con mayor experiencia, que tengan una noción más específica. Te registras mediante un formulario y te llegará una notificación de que tu solicitud ha sido aceptada.

### Additional Course 3: Creating Financial Content (Creación De Contenido Financiero)
![image](assets/Chapter-5/contenido-financiero.png)

Este último curso adicional llamado **"Creating Financial Content"** o en español **"Creación De Contenido Financiero"** es de entorno educativo e informativo relacionado a las finanzas y su importancia. Te registras mediante un formulario y te llegará una notificación de que tu solicitud ha sido aceptada.

### Financial Consultant Exam (Examen de Consultor Financiero)
![image](assets/Chapter-5/consultor-certificado.png)

En esta parte ya es para aquellas personas que se sientan preparadas para tomar el examen del Consultor Financiero, donde demostrarás todo lo que has aprendido a lo largo de los 3 cursos que tenemos y los 3 cursos adicionales que te hemos proporcionado. Te registras mediante un formulario y te llegará una notificación de que tu solicitud ha sido aceptada y así podrás tomar el examen.

### Profile (Perfil)
![image](assets/Chapter-5/perfil.png)

En en inicio de la app también hay una sección de **"Profile"** o en español **"Perfil"** donde se visualiza la información personal, preferencias y opciones de configuración del usuario.

### My Workspace (Mi Centro De Trabajo)
![image](assets/Chapter-5/centro-trabajo.png)

Al darle click a **"My Workspace"**, entrarás a este apartado donde verás la información del usuario registrado o mediante el inicio de sesión, también verás 2 botones, uno de **"Reviews"** y el otro de **"Messages"**, más abajo verás otros dos botones, uno de **"Edit Service"** y el otro de **"Post New Service"**, más adelante se explicará cada botón y para qué sirve.

### Reviews (Reseñas) y Messages (Mensajes)
![image](assets/Chapter-5/reseña-mensajes.png)

En estas secciones se visualizan las reseñas y los mensajes donde te puedes comunicar con otros usuarios o con los consultores financieros de la app, en reseñas son comentarios de nuestros usuarios hacia DebtGo y en mensajes son preguntas que te hacen los usuarios o los consultores financieros acerca de la gestión de finanzas, les puedes responder e inmediatamente te responderán.

### Edit Service (Editar Servicio)
![image](assets/Chapter-5/editar-servicio.png)

En esta sección verás cómo se puede editar los servicios que ofrece DebtGo, puedes cambiar el precio, la descripción o los detalles de cada servicio.

### Post New Service (Publicar Nuevo Servicio)
![image](assets/Chapter-5/publicar-nuevo-servicio.png)

En esta sección verás cómo puedes publicar un nuevo servicio aparte de lo que te brinda DebtGo, puede ser como otras consultorías, características de algo en específico, etc.

### 4.5.1. Android Mobile Applications Prototyping

El prototipo también ha sido diseñado para iOS, específicamente tomando como referencia dispositivos iPhone 13 & 14. Se ha cuidado la estética minimalista, los márgenes seguros, y la coherencia visual con las Human Interface Guidelines. Esto asegura que la experiencia del usuario en iOS sea clara, moderna y con una navegación fluida.

### Registration And Login (Registro e Inicio de Sesión)
![image](assets/Chapter-5/registro-inicio-sesion.png)

### 4.5.2. iOS Mobile Applications Prototyping

El prototipo desarrollado para iOS no solo contempla las funciones básicas de registro, inicio de sesión y gestión de pagos, sino que también incorpora las características diseñadas específicamente para el segmento de emprendedores, quienes constituyen un pilar clave en el uso de la aplicación DebtGo.

En esta versión se muestran funcionalidades avanzadas como:

- Búsqueda de emprendedores filtrando por rubro, lo que facilita encontrar asesorías especializadas.
- Reseñas de usuarios que permiten validar la calidad de los servicios ofrecidos.
- Comparación de servicios para evaluar distintas opciones disponibles.
- Alertas de fechas, enfocadas en reuniones, pagos y vencimientos importantes.
- Calificación de servicios, lo que fomenta la retroalimentación y mejora continua.
- Cancelación de contratos de asesores, en caso de que los servicios no cumplan con lo esperado.

Además, se incluyen elementos de confianza y seguridad como la visualización de los Términos y Condiciones, garantizando la transparencia en el uso de la aplicación y la protección de los datos de los usuarios.

### Búsqueda de Emprendedores
![image](assets/Chapter-4/Busca-Emprendedores.png) <br><br><br>

### Reseñas de Usuarios
![image](assets/Chapter-4/Reseña.png) <br><br><br>

### Comparación de Servicios
![image](assets/Chapter-4/comparar-servicios.png) <br><br><br>

### Alertas de Fechas
![image](assets/Chapter-4/alerta-fechas.png) <br><br><br>

### Calificación de Servicios
![image](assets/Chapter-4/calificar-servicio.png) <br><br><br>

### Cancelación de Contratos
![image](assets/Chapter-4/cancelar-contrato.png) <br><br><br>

## 4.6. Web Applications UX/UI Design
### 4.6.1. Web Application Wireframes

Los wireframes representan la primera etapa visual del diseño web, mostrando la estructura de los elementos principales sin estilos gráficos. Estas maquetas de baja fidelidad permitieron definir la distribución de componentes como formularios, botones de acción, menús y secciones de perfil antes de avanzar al diseño visual final.

Dentro de los wireframes diseñados se incluyen los siguientes escenarios principales:

- **Registro de usuario:** formulario básico con campos de nombre, correo, contraseña y aceptación de términos y condiciones.
- **Inicio de sesión:** pantalla simple con email y contraseña, con opción de recordar sesión.
- **Selección de plan:** presentación de planes disponibles con características y botón de aceptación.
- **Proceso de pago (checkout):** formulario con campos de tarjeta, fecha de vencimiento, código de seguridad y correo.
- **Mensajería:** panel con lista de conversaciones y espacio para el chat en tiempo real.
- **Perfil de usuario:** sección con datos básicos del usuario y su organización.
- **Organización y servicios:** espacio para mostrar información de la organización, simulaciones y publicación de servicios.

### Registro de Usuario
![image](assets/Chapter-4/frame1.png) <br><br><br>

### Inicio de Sesión
![image](assets/Chapter-4/frame2.png) <br><br><br>

### Selección de Plan
![image](assets/Chapter-4/frame3.png) <br><br><br>

### Proceso de Pago
![image](assets/Chapter-4/frame4.png) <br><br><br>

### Mensajería 
![image](assets/Chapter-4/mensajeC.png) <br><br><br>

### Perfil de Usuario
![image](assets/Chapter-4/perfil2.png) <br><br><br>

### Organización y Servicios
![image](assets/Chapter-4/servicios1.png) <br><br><br>
![image](assets/Chapter-4/servicios2.png) <br><br><br>

### 4.6.2. Web Applications Wireflow Diagrams

Los wireflows explican cómo los usuarios navegan entre pantallas en diferentes escenarios. En esta etapa se visualizaron rutas clave como el registro, inicio de sesión, edición de perfil, eliminación de cuenta y uso del workspace para consultores. Gracias a estos diagramas fue posible validar la lógica de navegación y anticipar posibles puntos de fricción.

En el caso de la aplicación web, los wireflows incluyen los siguientes escenarios principales:

- **Registro e inicio de sesión:** El usuario puede registrarse con sus datos personales y aceptar los términos, o bien iniciar sesión si ya cuenta con una cuenta.
- **Selección de plan y proceso de pago:** Tras registrarse, el usuario elige entre los planes disponibles (Básico o Premium) y completa el proceso de pago a través del formulario de checkout.
- **Gestión de perfil, organización, mensajería, comunicación y publicación de servicios:** Una vez logueado, el usuario puede acceder a su perfil, editar su información, visualizar su organización y gestionar los servicios vinculados. Desde la sección de organización, el usuario puede acceder al        panel de mensajes para interactuar con asesores u otros usuarios de la plataforma. Los emprendedores pueden publicar, editar o eliminar servicios a través de formularios específicos, vinculados directamente a su workspace.

Estos wireflows fueron diseñados tanto en baja fidelidad (en blanco y negro) como en alta fidelidad (con estilo visual aplicado), lo que permite contrastar la evolución desde la definición estructural hasta el diseño final.

### Registro e Inicios de Sesión
![image](assets/Chapter-4/registrar.png) <br><br><br>
![image](assets/Chapter-4/inicio.png) <br><br><br>

### Selección de Plan y Proceso de Pago
![image](assets/Chapter-4/diagram1.png) <br><br><br>

### Gestión de Perfil, Organización, Mensajería, COmunicación y Publicación de Servicios
![image](assets/Chapter-4/diagram2.png) <br><br><br>

### 4.6.3. Web Applications Mock-ups

Los mockups en alta fidelidad muestran la versión final del diseño de la aplicación web, con colores, tipografía e íconos consistentes con la identidad de DebtGo. Estos mockups reflejan la experiencia visual que tendrá el usuario en producción y fueron creados para evidenciar cómo evolucionan los wireframes iniciales hacia un diseño atractivo y funcional.

Las pantallas principales diseñadas incluyen:

- **Inicio de sesión (Log in):** Pantalla en la que el usuario ingresa sus credenciales de correo electrónico y contraseña, con la opción de recordar la sesión. Se incorpora un fondo degradado en tonos morados que refuerza la identidad visual de la aplicación.
- **Registro (Register):** Formulario que solicita nombre, correo electrónico, rol y contraseña, con validaciones de seguridad (mínimo un número y al menos 8 caracteres). Incluye la aceptación de términos y condiciones como requisito para crear la cuenta.
- **Selección de plan (Select a plan):** Sección donde el usuario puede elegir entre dos planes:
- **Plan Básico (S/ 80 mensual):** Incluye herramientas de gestión de deudas, seguimiento de ingresos y gastos, creación de presupuestos y acceso a materiales de educación financiera estándar.
- **Plan Premium (S/ 150 mensual):** Incluye todas las funciones del plan básico más consultoría financiera personalizada y soporte prioritario.
- **Perfil de usuario (My Profile):** Área donde el usuario puede visualizar y editar su información personal (nombre, correo, contraseña, plan contratado). Incluye la opción de eliminar la cuenta y el acceso directo a su espacio de trabajo (Workspace).
- **Espacio de trabajo (My Workspace):** Sección personalizada para cada usuario o emprendedor, donde se muestran sus servicios publicados, métricas de rendimiento (gráficas), y herramientas de comunicación (enviar mensajes, recibir reseñas).
- **Publicación de servicio (Post new service):** Formulario emergente donde el usuario puede ingresar título, descripción, precio y adjuntar archivos para publicar un nuevo servicio dentro de su workspace.
- **Mensajería (Messages):** Módulo de comunicación que permite visualizar contactos, historial de casos y chatear en tiempo real con otros usuarios de la plataforma.
- **Herramientas financieras (Financial tools):** Acceso a módulos de analítica, presupuestos y cursos de educación financiera, diseñados para apoyar la gestión económica del usuario.
- **Servicios disponibles (Services):** Sección donde se presentan los servicios publicados en la plataforma, como “Presupuestos personales” y “Ahorro e inversión”, con imágenes representativas para facilitar la navegación.

### Inicio de Sesión
![image](assets/Chapter-4/mock1.png) <br><br><br>

### Registro
![image](assets/Chapter-4/mock2.png) <br><br><br>

### Selección de Plan Básico y Plan Premium
![image](assets/Chapter-4/mock3.png) <br><br><br>

### Perfil de Usuario
![image](assets/Chapter-4/mock4.png) <br><br><br>

### Espacio de Trabajo
![image](assets/Chapter-4/mock5.png) <br><br><br>

### Publicación de Servicio
![image](assets/Chapter-4/mock6.png) <br><br><br>

### Mensajería
![image](assets/Chapter-4/mock7.png) <br><br><br>

### Herramientas Financieras
![image](assets/Chapter-4/mock9.png) <br><br><br>

### Servicios Disponibles
![image](assets/Chapter-4/mock10.png) <br><br><br>


### 4.6.4. Web Applications User Flow Diagrams

Los user flows representan de manera simplificada las rutas que los usuarios siguen en la aplicación. A diferencia de los wireflows, que incluyen pantallas completas, los user flows se centran en la lógica de interacción.

En el caso de DebtGo, este diagrama permitió identificar los flujos principales (happy path), como el registro, selección de plan y acceso al workspace, así como las rutas alternativas (unhappy path), como errores de pago o credenciales incorrectas. Gracias a este análisis se pudieron definir los posibles escenarios que enfrentará un usuario y cómo la aplicación debe responder ante cada caso.

![image](assets/Chapter-4/user-flow-diagram.jpg) <br><br><br>

## 4.7. Web Applications Prototyping

El prototipo web desarrollado integra todas las pantallas en un flujo navegable mediante Figma, permitiendo simular la interacción real de los usuarios con la aplicación. Este prototipo facilitó la validación temprana de la experiencia de usuario, al permitir realizar pruebas de usabilidad y recoger retroalimentación antes de la implementación final.

En este flujo navegable se conectaron pantallas clave como: login, registro, selección de plan, proceso de pago, perfil de usuario, workspace, publicación de servicios, mensajería y gestión de servicios. De esta manera, se logró visualizar la experiencia completa del usuario y asegurar la coherencia en la navegación.

![image](assets/Chapter-4/web-application-prototyping.JPG) <br><br><br>

## 4.8. Domain-Driven Software Architecture
### 4.8.1. Software Architecture Context Diagram
![image](assets/Chapter-4/diagram_context.png) <br>
*Imagen (N°19). Elaboración propia. Realizado en Structurizr.* <br>

### 4.8.2. Software Architecture Container Diagrams
![image](assets/Chapter-4/container-diagram2.png) <br>
*Imagen (N°20). Elaboración propia. Realizado en Structurizr.* <br>

![image](assets/Chapter-4/consulting-bc.png) <br>
*Imagen (N°21). Elaboración propia. Realizado en Structurizr.* <br>

![image](assets/Chapter-4/education-bc.png) <br>
*Imagen (N°22). Elaboración propia. Realizado en Structurizr.* <br>

![image](assets/Chapter-4/payment-bc.png) <br>
*Imagen (N°24). Elaboración propia. Realizado en Structurizr.* <br>

![image](assets/Chapter-4/user-bc.png) <br>
*Imagen (N°26). Elaboración propia. Realizado en Structurizr.* <br>

**Contenedores principales:**
***Aplicación Web:*** Interfaz para usuarios (login, servicios). <br>
***API REST (C#):*** Conecta frontend con backend. <br>
***Base de Datos (MySQL):*** Almacena datos de la plataforma. <br>
***Sistemas externos:*** Visa/MasterCard, Email System. <br>

**Flujo:**
Web App → API REST → Database ↔ Sistemas externos.

### 4.8.3. Software Architecture Components Diagrams
![image](assets/Chapter-4/subscription-bc.png) <br>
*Imagen (N°27). Subscription BC Component* <br>

![image](assets/Chapter-4/user-bc.png) <br>
*Imagen (N°28). User BC Component* <br>

![image](assets/Chapter-4/consulting-bc.png) <br>
*Imagen (N°29). Consulting BC Component* <br>

![image](assets/Chapter-4/payment-bc.png) <br>
*Imagen (N°30). Payments BC Component* <br>

![image](assets/Chapter-4/notification-bc.png) <br>
*Imagen (N°31). Notification BC Component* <br>

## 4.9. Software Object-Oriented Design
### 4.9.1. Class Diagrams
<img src="assets/Chapter-4/class-diagram.png">

### 4.9.2. Class Dictionary
**Class User**

| Attribute       | Type          | Description                  |
|-----------------|---------------|------------------------------|
| id              | int           | Unique identifier for the user |
| name            | string        | Name of the user             |
| email           | string        | Email address of the user    |
| password        | string        | Password for user authentication |
| role            | RoleType      | Role of the user |
| subscriptionId  | int           | Identifier for the subscription |
| paymentCard     | PaymentCard   | Details of the payment card used |


**Class Entrepreneur**

| Attribute       | Type          | Description                                      |
|-----------------|---------------|--------------------------------------------------|
| businessName    | string        | The name of the business                        |
| industry        | string        | The industry in which the business operates     |
| financialGoals  | string[]      | A list of financial goals for the business       |
| viewedCourses   | int[]         | A list of IDs for the courses that have been viewed |

**Class Advisor**

| Attribute       | Type          | Description                                      |
|-----------------|---------------|--------------------------------------------------|
| expertise       | string[]      | A list of areas of expertise of the advisor     |
| experienceYears | int           | Number of years of experience the advisor has   |
| reviews         | Review[]      | An array of reviews given to the advisor        |

**Class Course**

| Attribute      | Type           | Description                                    |
|----------------|----------------|------------------------------------------------|
| id             | int            | Unique identifier for the course               |
| title          | string         | Title of the course                            |
| description    | string         | Description of the course                      |
| duration       | int            | Duration of the course in hours                |
| level          | CourseLevelType| Difficulty level of the course                 |
| comments       | Comment[]      | Array of comments related to the course        |

**Class Comment**

| Attribute       | Type          | Description                              |
|-----------------|---------------|------------------------------------------|
| id              | int           | Unique identifier for the comment        |
| entrepreneurId  | int           | Identifier of the entrepreneur who made the comment |
| comment         | string        | The content of the comment               |

**Class AdviceSession**

| Attribute       | Type                    | Description                                     |
|-----------------|-------------------------|-------------------------------------------------|
| id              | int                     | Unique identifier for the advice session       |
| entrepreneurId  | int                     | Identifier of the entrepreneur participating in the session |
| advisorId       | int                     | Identifier of the advisor conducting the session |
| scheduledDate   | string                  | Date and time when the session is scheduled    |
| status          | AdviceSessionStatusType | Current status of the advice session           |

**Class Review**

| Attribute       | Type          | Description                                      |
|-----------------|---------------|--------------------------------------------------|
| id              | int           | Unique identifier for the review                |
| entrepreneurId  | int           | Identifier of the entrepreneur who received the review |
| comment         | string        | The content of the review                       |
| score           | int           | Score given in the review |


**Class PaymentCard**

| Attribute       | Type          | Description                                      |
|-----------------|---------------|--------------------------------------------------|
| id              | int           | Unique identifier for the payment card          |
| cardNumber      | int           | Credit or debit card number                     |
| expirationDate  | string        | Expiration date of the payment card             |
| securityCode    | int           | Security code (CVV) of the payment card         |

**Class Subscription**

| Attribute    | Type                    | Description                                    |
|--------------|-------------------------|------------------------------------------------|
| id           | int                     | Unique identifier for the subscription         |
| userId       | int                     | Identifier of the user associated with the subscription |
| planId       | int                     | Identifier of the subscription plan            |
| status       | SubscriptionStatusType | Current status of the subscription             |

**Class Plan**

| Attribute    | Type   | Description                          |
|--------------|--------|--------------------------------------|
| id           | int    | Unique identifier for the plan       |
| name         | string | Name of the plan                     |
| description  | string | Description of the plan              |
| price        | float  | Price of the plan                    |

**Class Payment**

| Attribute       | Type   | Description                                 |
|-----------------|--------|---------------------------------------------|
| id              | int    | Unique identifier for the payment           |
| subscriptionId  | int    | Identifier of the associated subscription   |
| paymentCardId   | int    | Identifier of the payment card used         |
| paymentDate     | string | Date of the payment                         |

## 4.10. Database Design
### 4.10.1. Relational/Non-Relational Database Diagram
<img src="assets/Chapter-4/database-diagram.png">

## Capítulo V: Product Implementation 
### 5.1. Software Configuration Management

Este apartado se detalla las decisiones, herramientas y convenciones adoptadas por el equipo para garantizar consistencia en el desarrollo, las pruebas y en el despliegue de la aplicación.

### 5.1.1. Software Development Environment Configuration

| Producto de Software        | Propósito en el Proyecto                                       | Tipo de Software |
|----------------------------|----------------------------------------------------------------|------------------|
| Visual Studio 2022         | Desarrollo de Web Services en .NET (C#)                        | IDE              |
| Android Studio Giraffe     | Desarrollo de app móvil en Kotlin (Jetpack Compose)            | IDE              |
| GitHub                     | Control de versiones y repositorios                            | SaaS             |                                   
| Figma                      | Diseño de interfaces UI/UX                                     | SaaS             |                                   
| Miro                       | EventStorming, Context Mapping, User Flows                     | SaaS             |                                   
| UXPressia                  | User Personas, Journey Mapping, Impact Mapping                 | SaaS             |
| Postman                    | Pruebas de APIs RESTful                                        | Desktop          |

---

### 5.1.2. Source Code Management

**Repositorios Oficiales**:
- [Landing Page (Frontend Web)](https://github.com/upc-pre-202502-2520-14651-debtgo/Landing-Page)
- [Web Services (Backend API .NET)](https://github.com/upc-pre-202502-2520-14651-debtgo/Back-End-DebtGo)
- [Aplicación Móvil (Android Kotlin)](https://github.com/upc-pre-202502-2520-14651-debtgo/App-Mobile-DebtGo)

**Workflow Adoptado GitFlow**
- Ramas principales:
    - `main`: rama de producción
    - `develop`: rama de integración
- Ramas auxiliares:
    - `feature/<nombre>` (ej. `feature/payment-tracking`)
    - `release/<version>` (ej. `release/1.1.0`)
    - `hotfix/<nombre>` (ej. `hotfix/login-error`)

**Versionado Semántico (Semantic Versioning 2.0.0)**:
- Formato: `MAJOR.MINOR.PATCH` (ej. `v1.2.0`)

**Convenciones de Commits (Conventional Commits)**:
    - `feat`: nueva funcionalidad
    - `fix`: corrección de errores
    - `docs`: documentación
    - `style`: formato (espacios, punto y coma, etc.)
    - `refactor`: reestructuración sin cambio funcional

---

### 5.1.3. Source Code Style Guide & Coding Conventions

**C# / ASP.NET Core (Backend)**:
- Guía: [Microsoft C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)
- PascalCase para clases y métodos, camelCase para variables.

**Kotlin / Jetpack Compose (App Móvil)**:
- Guía: [Kotlin Coding Conventions](https://kotlinlang.org/docs/coding-conventions.html)
- CamelCase para nombres.

**HTML/CSS (Landing Page)**:
- Guía: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)
- Convención BEM para CSS.

**Gherkin (.feature files)**:
- Guía: [Gherkin Style Guide](https://cucumber.io/docs/gherkin/reference/)
- Escenarios en inglés, legibles y estructurados.

---

### 5.1.4. Software Deployment Configuration

#### Productos y configuración de despliegue:

**Landing Page**:
- Hosting: GitHub Pages
- CI/CD: GitHub Actions, despliegue automático al hacer push a `main`.

**Aplicación Móvil (Android)**:

**Web Services (API .NET)**:


#### Diagrama de Despliegue (C4 Model):

<img src="assets/Chapter-5/Deployment Diagram.png">

## 5.2. Product Implementation & Deployment
### 5.2.1. Sprint Backlogs
#### 5.2.1.2. Sprint Backlog 1  
| **User Story**                           | **Work-item/Task**            | **Descripción**                                                                          | **Estimación (Horas)** | **Assigned To**  | **Status** |
| ---------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------- | ---------------------- | ---------------- | ---------- |
| E1-US01 Demostración de la aplicación    | W01 Integrate demo playback    | Integrar un video de demostración o prototipo interactivo en la página de inicio         | 4                      | Daniel Chávarri     | Done       |
| E1-US02 Reseñas de la aplicación         | W02 Display user reviews       | Construir un carrusel/componente de reseñas con datos reales                             | 6                      | María Fernanda Peña  | Done       |
| E1-US03 Planes de la aplicación          | W03 Show subscription plans    | Crear la sección de planes con detalles de precios                                       | 5                      | Adriana Ramos    | Done       |
| E1-US04 Soporte de la aplicación         | W04 Implement support form     | Desarrollar el formulario de contacto y la lógica de backend para solicitudes de soporte | 4                      | Ánderson Gamarra   | Done       |
| E1-US05 Información de servicios         | W05 Services info section      | Añadir descripciones detalladas de los servicios ofrecidos por consultores               | 3                      | Adriana Ramos | Done       |
| E2-US06 Normas de privacidad             | W06 Privacy policy page        | Redactar e integrar el contenido de la política de privacidad                            | 2                      | María Fernanda Peña    | Done       |
| E2-US07 Pago por servicios               | W07 Explain payment process    | Desarrollar una guía paso a paso del proceso de pago en la interfaz                      | 5                      | Daniel Chávarri  | Done       |
| E2-US08 Registro en aplicación           | W08 Build registration form    | Crear el formulario de registro con validación y confirmación por correo electrónico     | 8                      | Ánderson Gamarra     | Done       |
| E3-US09 Creación de perfil - Consultor   | W09 Consultant profile form    | Implementar formulario para ingresar experiencia e información del consultor             | 6                      | Adriana Ramos | Done       |
| E3-US10 Creación de perfil - Emprendedor | W10 Entrepreneur profile form | Crear formulario para registrar datos del emprendimiento y necesidades                   | 6                      | María Fernanda Peña    | Done       |
| E3-US11 Elección y actualización de plan | W11 Plan selection component  | Desarrollar componente para elegir y modificar planes de suscripción                     | 4                      | Daniel Chávarri     | Done       |
| E3-US12 Elección de pagos por servicios  | W12 Payment method input      | Implementar interfaz para ingresar y validar método de pago                              | 5                      | Ánderson Gamarra  | Done       |
| E4-US15 Publicación de servicios         | W13 Publish services module   | Desarrollar módulo para publicar servicios y fijar precios                               | 5                      | Adriana Ramos      | Done       |
| E4-US16 Establecimiento de horario       | W14 Set availability hours    | Crear funcionalidad para definir y guardar horario de trabajo                            | 3                      | María Fernanda Peña | Done       |
| E5-US20 Sistema de mensajes y casos      | W15 Messaging system backend  | Implementar backend de mensajería entre consultor y cliente                              | 8                      | Daniel Chávarri   | Done       |
| E5-US21 Historial de casos               | W16 Case history view         | Desarrollar vista para mostrar historial completo de conversaciones                      | 4                      | Adriana Ramos     | Done       |
| E5-US22 Envío de documentos adjuntos     | W17 Document upload feature   | Implementar carga y gestión de archivos en chat y casos                                  | 4                      | Ánderson Gamarra  | Done       |
| E7-US30 Artículos financieros            | W18 Articles section          | Crear sección para mostrar artículos financieros con filtro y búsqueda                   | 3                      | María Fernanda Peña      | Done       |
| E7-US32 Talleres gratuitos               | W19 Free workshops module     | Desarrollar módulo para inscripción y gestión de talleres gratuitos                      | 5                      | Daniel Chávarri | Done       |

<br>

Durante este sprint se completó con éxito la construcción y publicación de la landing page (integrando el video de demostración, el carrusel de reseñas, la sección de planes y el formulario de contacto) así como la redacción e integración de la política de privacidad y el proceso de registro. Además, se desplegó el backend en producción y se avanzó con la primera entrega de la aplicación móvil, garantizando una experiencia fluida y coherente para el usuario.

Enlace a la landing page desplegada: [DebtGo Landing Page](https://upc-pre-202501-cc238-365-debtgo.github.io/Landing-Page/)

Enlace al backend desplegado: [DebtGo Backend](http://debt2go.runasp.net/swagger/index.html)

![Evidence 1](assets/Chapter-6/img-evidence-1.png)

![Evidence 2](assets/Chapter-6/img-evidence-2.png)

![Evidence 3](assets/Chapter-6/img-evidence-3.png)

![Evidence 4](assets/Chapter-6/img-evidence-4.png)

![Evidence 5](assets/Chapter-6/img-evidence-5.png)

![Evidence 6](assets/Chapter-6/img-evidence-6.png)

En esta sección presentamos los endpoints preparados durante el sprint. Se adjuntan capturas de la UI de swagger con OpenAPI.

| **Controller** | **Swagger** |
|----------------|-------------|
| Authentication |![Authentication Swagger](assets/Chapter-6/img-authentication-swagger.png)|
| Notification |![Notification Swagger](assets/Chapter-6/img-notification-swagger.png)|
| Subscription |![Subscription Swagger](assets/Chapter-6/img-subscription-swagger.png)|

En este sprint se puso en marcha la infraestructura de despliegue continuo tanto para landing page como para backend, garantizando que cada cambio en main se refleje inmediatamente en producción:

- Git & GitFlow: Control de versiones y flujo de trabajo por ramas de características y releases, con Pull Requests revisados por pares.
- GitHub: Almacenamiento de código y gestión de issues, PRs y revisiones.
- Vercel: Despliegue automático de la landing page al hacer merge en main, con previews en cada PR.
- MonsterASP.NET: Proveedor de hosting en Windows especializado en aplicaciones ASP.NET/.NET.

- Durante el Sprint 1, todo el equipo participó activamente en la implementación de la Landing Page, los Web Services y la primera entrega de la aplicación móvil, trabajando en ramas de feature individuales, revisando pull requests en pares y registrando contribuciones constantes en GitHub; a continuación se muestran los principales analíticos de colaboración, seguidos de nuestra interpretación de cómo estos reflejan el reparto de trabajo y la eficacia en la coordinación del equipo.

**Landing Page**
Network graph:
![Network Graph](assets/Chapter-6/img-network-github-landing-page.png)

Code frecuency:
![Code Frecuency](assets/Chapter-6/img-code-frecuency-landing-page.png)

**Backend**
Network graph:
![Network Graph](assets/Chapter-6/img-network-github-backend.png)

Code frecuency:
![Code Frecuency](assets/Chapter-6/img-code-frecuency-backend.png)

**App Mobile**
Network graph:
![Network Graph](assets/Chapter-6/img-network-github-app-mobile.png)

Code frecuency:
![Code Frecuency](assets/Chapter-6/img-code-frecuency-app-mobile.png)

#### Sprint Backlog 2
**Introducción**
Durante el Sprint 2 del proyecto DebtGo, el equipo se centró en consolidar las funcionalidades clave de la aplicación móvil y backend, orientadas a brindar una experiencia completa de registro, configuración de perfiles, interacción mediante mensajería, y planificación de servicios. El objetivo principal fue asegurar que los usuarios puedan completar sus flujos de registro, gestionar sus servicios y comunicarse eficazmente dentro de la plataforma.

| **User Story**                                 | **Work-item/Task**                     | **Descripción**                                                                   | **Estimación (Horas)**  | **Assigned To**  | **Status**  |
| ----------------------------------------       | -----------------------------------    | --------------------------------------------------------------------------------  | ----------------------  | ---------------  | ----------  |
| E6-US13 Buscar emprendedores según necesidades   | W20 Entrepreneurs search tool             | Implementar búsqueda de emprendedores según experiencia en el rubro del emprendedor |	          5	            | Daniel Chávarri  | Done        |
| E6-US14 Comparar servicios guardados           | W21 Service comparison module          | Crear componente para comparar servicios guardados y elegir el más adecuado	      |           5             | Ánderson Gamarra     | Done        |
| E6-US23 Recibir actualizaciones de solicitudes | W22 Request status notifications       | Implementar notificaciones sobre actualizaciones del estado de las solicitudes	  |           5	            | Adriana Ramos	   | Done        |
| E6-US24 Recibir alertas de fechas importantes  | W23 Alerts for important deadlines	  |	Enviar alertas al emprendedor sobre fechas importantes (reuniones, pagos, vencimientos) |	  4	            | María Fernanda Peña | Done        |  
| E6-US26 Calificar servicios recibidos          | W24 Rate received services	          |	Permitir que el emprendedor califique los servicios de los asesores al finalizar la asesoría | 3         | Daniel Chábarri	   | Done        |
| E6-US29 Cancelar contrato como asesor     | W25 Cancel contract as entrepreneur	      | Habilitar la opción de cancelar el contrato si el asesor no cumple con lo esperado |	       3	        | Adriana Ramos  | Done        |
| E6-US31 Usar herramientas de simulación        | W26 Payment simulation tool		      | Crear herramienta para simular pagos, cuotas o préstamos en base a distintos escenarios	|      8	        | Ánderson Gamarra     | Done        |
| E6-US33 Hacer seguimiento de ingresos y gastos | W27 Income & expense tracking          | Desarrollar módulo para registrar y visualizar ingresos y gastos del emprendedor   |		   6	        | María Fernanda Peña | Done        |
| E6-US34 Crear presupuestos personalizados      | W28 Budget planning module	          | Crear componente para planificación de presupuestos según ingresos, gastos y metas del usuario | 6	        | Marco Góngora	   | Done        |

Este Sprint 2 fue planificado con un total de 45 horas estimadas, y la distribución de tareas está alineada con el Sprint Goal propuesto para esta iteración.

Durante este sprint se completaron con éxito las funcionalidades de registro de usuarios, gestión de perfiles (consultor y emprendedor) y la experiencia de reserva de servicios. En concreto:

- Registro de usuarios: Se validó el flujo completo de alta, confirmación de correo y persistencia de datos en el backend.
- Perfiles: Cada usuario puede elegir su rol (consultor o emprendedor), rellenar su información de perfil y subir foto de avatar.
- Reserva de servicios: Desde la app móvil, el usuario emprendedor puede listar consultores disponibles, seleccionar fecha y hora, confirmar la reserva y visualizar el estado de la misma. La lógica de negocio en el backend procesa correctamente la creación y consulta de reservas.

Enlace a la versión móvil de prueba: [Prueba-Final-DebtGo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211108_upc_edu_pe/Ea8gW4LZhERInneOSI8r5psBuHhK49qR94IdRyxEFMFfiw?e=wqS6W6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Enlace al backend desplegado: [DebtGo Backend](http://debt2go.runasp.net/swagger/index.html)


Evidencia de la app DebtGo en Flutter

 ![image](assets/Chapter-6/buscar-emprendedores.JPG)


![image](assets/Chapter-6/comparar-servicios.JPG)


![image](assets/Chapter-6/notificaciones.JPG)


![image](assets/Chapter-6/alerta-fechas.JPG)


![image](assets/Chapter-6/calificar-servicio.JPG)


![image](assets/Chapter-6/cancelar-contrato.JPG)


![image](assets/Chapter-6/simulador-pago.JPG)


![image](assets/Chapter-6/ingresos-gastos.JPG).


![image](assets/Chapter-6/presupuesto.JPG)

En esta sección presentamos los endpoints preparados durante el sprint. Se adjuntan capturas de la UI de swagger con OpenAPI.

| **Controller** | **Swagger** |
|----------------|-------------|
| Authentication |![Authentication Swagger](assets/Chapter-6/img-authentication-swagger.png)|
| Notification |![Notification Swagger](assets/Chapter-6/img-notification-swagger.png)|
| Subscription |![Subscription Swagger](assets/Chapter-6/img-subscription-swagger.png)|

En este sprint se puso en marcha la infraestructura de despliegue continuo tanto para landing page como para backend, garantizando que cada cambio en main se refleje inmediatamente en producción:

- Git & GitFlow: Control de versiones y flujo de trabajo por ramas de características y releases, con Pull Requests revisados por pares.
- GitHub: Almacenamiento de código y gestión de issues, PRs y revisiones.
- Vercel: Despliegue automático de la landing page al hacer merge en main, con previews en cada PR.
- MonsterASP.NET: Proveedor de hosting en Windows especializado en aplicaciones ASP.NET/.NET.

- Durante el Sprint 2, todo el equipo participó activamente en la implementación de la Landing Page, los Web Services y la segunda entrega de la aplicación móvil, trabajando en ramas de feature individuales, revisando pull requests en pares y registrando contribuciones constantes en GitHub; a continuación se muestran los principales analíticos de colaboración, seguidos de nuestra interpretación de cómo estos reflejan el reparto de trabajo y la eficacia en la coordinación del equipo.

**Landing Page**

Network graph:
![Network Graph](assets/Chapter-6/Landing.png)

Code frecuency:
![Code Frecuency](assets/Chapter-6/Landing_2.png)


**Backend**
Network graph:
![Network Graph](assets/Chapter-6/img-network-github-backend.png)

Code frecuency:
![Code Frecuency](assets/Chapter-6/Back.png)

**App Mobile**
Network graph:
![Network Graph](assets/Chapter-6/Mobile.png)

Code frecuency:
Code frecuency:
![Code Frecuency](assets/Chapter-6/Mobile2.png)

![Sprint 3](assets/Chapter-6/sprint-3.JPG)

Durante el Sprint Backlog 3 del proyecto DebtGo, el equipo se enfocó en completar las funcionalidades restantes del Product Backlog, asegurando una experiencia completa de interacción entre consultores y emprendedores. Se trabajó en los módulos pendientes relacionados con la gestión de asesorías, visualización de métricas, comparación de servicios y recolección de retroalimentación. El objetivo principal fue cerrar el ciclo de asesoría financiera, permitiendo a los usuarios iniciar y finalizar casos, acceder a métricas clave, y brindar herramientas para mejorar continuamente la calidad del servicio ofrecido por los consultores.

| **User Story**                                 | **Work-item/Task**                     | **Descripción**                                                                   | **Estimación (Horas)**  | **Assigned To**  | **Status**  |
| ----------------------------------------       | -----------------------------------    | --------------------------------------------------------------------------------  | ----------------------  | ---------------  | ----------  |
| E6-US17 Iniciar solicitud de asesoría          | W31 Start request adviser              | Crear interfaz para que el emprendedor inicie una solicitud de asesoría           |	          4	            | Adriana Ramos     | Done        |
| E6-US18 Aceptar solicitud de asesoría          | W32 Accept request adviser             | Implementar la lógica para que el emprendedor acepte las asesorias	              |           4             | Ánderson Gamarra    | Done        |
| E6-US19 Visualización de servicios             | W33 View other consultants             | Permitir a los consultores visualizar servicios de otros consultores para comparación   |           3	    | Daniel Chávarri | Done        |
| E6-US25 Solicitar reseñas                      | W34 Request reviews	                  |	Habilitar funcionalidad para que el emprendedor solicite reseñas a los clientes   |	           3	        | María Fernanda Peña  | Done        |  
| E6-US27 Visualizar métricas                    | W35 Performance dashboard	          |	Crear panel para mostrar métricas de rendimiento de los emprendedores             |            8            | Ánderson Gamarra	   | Done        |

Este Sprint Backlog 3 fue planificado con un total de 22 horas estimadas, y la distribución de tareas está alineada con el Sprint Goal propuesto para esta iteración.

Evidencia en DebtGo Flutter:

![image](assets/Chapter-6/solicitud-asesoria.JPG)


![image](assets/Chapter-6/solicitud-asesores.JPG)


![image](assets/Chapter-6/servicios-asesores.JPG)


![image](assets/Chapter-6/solicitar-reseñas.JPG)


![image](assets/Chapter-6/metrica-desempeño.JPG)

#### 5.2.2. Implemented Landing Page Evidence

La Landing Page de DebtGo fue implementada utilizando HTML5, CSS3 y JavaScript puro en Visual Studio Code. Esta página es totalmente responsiva y está diseñada para captar la atención del usuario con una propuesta de valor clara: el control de las finanzas personales mediante una experiencia atractiva e intuitiva.


**Link al repositorio de la lading page:**
[Landing Page (Frontend Web)](https://github.com/upc-pre-202502-2520-14651-debtgo/Landing-Page)

**Características principales:**

- Encabezado con navegación clara (About, How It Works, Testimonials, Contact).
- Imágenes de fondo representativas del tema financiero.
- Llamados a la acción: Start Advising Today y Get Financial Consulting.
- Beneficios de la plataforma explicados en secciones separadas.

  ![image](assets/Chapter-5/img-evidence-1.png) <br><br><br>
  
  ![image](assets/Chapter-5/img-evidence-2.png) <br><br><br>

  ![image](assets/Chapter-5/landing3.png) <br><br><br>

  ![image](assets/Chapter-5/landing4.png) <br><br><br>

  ![image](assets/Chapter-5/landing5.png) <br><br><br>

#### 5.2.3. Implemented Frontend-Web Application Evidence

El frontend de la aplicación web de DebtGo fue construido en Vue.js, permitiendo una interfaz moderna, modular y altamente reactiva. Se brindó una experiencia de usuario fluida, centrada en la navegación intuitiva y la gestión clara de las funcionalidades.

**Link al repositorio del Front-End**
[Front-End (aplicación web)](https://github.com/upc-pre-202502-2520-14651-debtgo/Front-End-DebtGo)

**Características principales:**

- Registro con validaciones (mínimo de 8 caracteres, número, términos aceptados).
- Módulo de educación financiera con progreso visual.
- Acceso a asesorías y seguimiento del avance.
- Mensajería tipo chat con retroalimentación de usuarios.

![image](assets/Chapter-5/Loginyregister.png) <br><br><br>

![image](assets/Chapter-5/Mensaje.png) <br><br><br>

### 5.2.4. Acuerdo de Servicio - SaaS 

Este Acuerdo de Servicio (“**Acuerdo**”) establece los derechos, responsabilidades y restricciones aplicables a los usuarios de **DebtGo**, una plataforma **SaaS** orientada a la **gestión de deudas personales/empresariales, programación de pagos y recordatorios** (push/email/SMS).

---

**1. Aceptación del Acuerdo**

Al usar **DebtGo** (la “**Plataforma**”), el **Usuario** acepta este Acuerdo y sus futuras actualizaciones. Si el Usuario no está de acuerdo con alguno de los términos, debe abstenerse de utilizar la Plataforma.

---

**2. Descripción del Servicio**

**DebtGo** ofrece una solución en la nube para:
- Registrar deudas y obligaciones (monto, entidad, fecha de vencimiento).
- Programar pagos y configurar reglas de notificación/recordatorios.
- Visualizar paneles de estado (vencidas, próximas, al día) y reportes básicos.
- Integrarse, cuando aplique, con **pasarelas de pago** y servicios de mensajería/notificación.

> **Aviso**: DebtGo **no es una entidad financiera** ni brinda asesoría financiera, tributaria o legal. Las decisiones de pago son responsabilidad del Usuario.

---

**3. Derechos y Responsabilidades del Usuario**

**3.1 Uso del Servicio**

- **Licencia**: DebtGo otorga una licencia **no exclusiva, intransferible y revocable** para uso interno, conforme a este Acuerdo.
- **Cuenta y credenciales**: el Usuario debe resguardar sus credenciales y notificar usos no autorizados.

**3.2 Restricciones**

El Usuario no podrá:
- Copiar, revender, sublicenciar o crear obras derivadas de la Plataforma.
- Realizar **ingeniería inversa**, escaneo de vulnerabilidades sin autorización o sobrecarga del servicio.
- Usar la Plataforma con fines ilícitos o que infrinjan derechos de terceros.
- Registrar información falsa o de terceros sin autorización.

**3.3 Contenido y exactitud**

El Usuario es responsable de la **veracidad** de la información registrada y de mantenerla actualizada.

---

**4. Responsabilidades de DebtGo**

**4.1 Provisión del servicio**

DebtGo mantendrá el servicio disponible salvo **mantenimientos programados** o causas de fuerza mayor. Se buscará una disponibilidad objetivo razonable (p. ej., **99.5%** mensual), sin garantizar disponibilidad absoluta.

**4.2 Seguridad y protección de datos**

- Cifrado en tránsito (HTTPS) y medidas de seguridad acordes a prácticas de la industria.
- Gestión de **copias de seguridad** y controles de acceso.
- El Usuario debe mantener copias de respaldo propias cuando sea crítico para su operación.

**4.3 Cumplimiento normativo**

DebtGo cumplirá la normativa aplicable de protección de datos y privacidad (p. ej., **GDPR** si corresponde y **leyes locales**). DebtGo no venderá datos personales del Usuario a terceros sin su consentimiento, salvo obligación legal.

**4.4 Integraciones de terceros**

El uso de pasarelas de pago, SMS/email u otros servicios de terceros se rige por los **términos de dichos terceros**. DebtGo no controla su disponibilidad ni tiempos de respuesta.

---

**5. Tarifas y Facturación**

**5.1 Precios**

El acceso puede estar sujeto a **planes de suscripción** (gratuito y/o de pago) publicados en los canales oficiales de DebtGo.

**5.2 Facturación**

La facturación puede ser **mensual o anual**. Los importes pagados **no son reembolsables** salvo disposición legal. El impago puede derivar en suspensión o limitación del servicio.

---

**6. Duración y Terminación**

**6.1 Vigencia**

Este Acuerdo rige desde el primer uso de la Plataforma hasta su terminación.

**6.2 Terminación**

- El Usuario puede cancelar su cuenta en cualquier momento.
- DebtGo puede suspender o terminar el acceso ante incumplimiento del Acuerdo, fraude, abuso o riesgo para la seguridad.
- A solicitud del Usuario y cuando sea técnicamente viable, se podrá **exportar** la información principal asociada a su cuenta antes de la terminación.

---

**7. Limitación de Responsabilidad**

DebtGo no será responsable por **daños indirectos, incidentales, especiales, punitivos o consecuentes**, incluyendo pérdida de datos o lucro cesante. La responsabilidad total de DebtGo, de existir, se limita al **monto efectivamente pagado** por el Usuario en los **últimos 12 meses** previos al evento.

---

**8. Modificaciones del Acuerdo**

DebtGo puede actualizar este Acuerdo en cualquier momento. Las modificaciones se publicarán en la sección “Términos y Condiciones” y serán **efectivas desde su publicación**. El uso continuado de la Plataforma implica aceptación de los cambios.

---

**9. Legislación Aplicable y Jurisdicción**

Este Acuerdo se regirá por las **leyes de la República del Perú** (o la jurisdicción donde opere el titular del servicio, si se especifica en los T&C públicos), sin perjuicio de sus normas de conflicto de leyes. Cualquier controversia será sometida a los **tribunales competentes** del domicilio del proveedor.

---

**10. Contacto**

Consultas sobre este Acuerdo o el servicio: **support@debtgo.app** (o el canal de soporte oficial indicado en la Plataforma).


#### 5.2.5. Implemented Native-Mobile Application Evidence

DebtGo también cuenta con una versión adaptada a dispositivos móviles, desarrollada en Kotlin o adaptando el frontend Vue a formato responsive para dispositivos. Las funcionalidades son consistentes con la versión web, con énfasis en la experiencia móvil.

**Link al repositorio del Front-End Mobile**
[Front-End (aplicación móvil)](https://github.com/upc-pre-202502-2520-14651-debtgo/App-Mobile-DebtGo)

**Características destacadas:**

- Registro y login optimizado para dispositivos móviles.
- Visualización de progreso en cursos de educación financiera.
- Interacción directa con los consultores financieros vía chat.

  ![image](assets/Chapter-5/img-evidence-3.png) <br><br><br>
  
  ![image](assets/Chapter-5/img-evidence-4.png) <br><br><br>

  ![image](assets/Chapter-5/img-evidence-5.png) <br><br><br>

#### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

El backend fue desarrollado con ASP NET CORE, bajo el enfoque RESTful. La API permite registrar usuarios, autenticarlos, administrar notificaciones y suscripciones, todo siguiendo las mejores prácticas de seguridad y estructura por capas.

**Tecnologías y características:**

- Autenticación con JWT.
- Uso de Bcrypt para encriptación de contraseñas.
- Control de acceso y validación en endpoints.
- Documentación Swagger para facilitar pruebas y exploración.

  ![image](assets/Chapter-5/img-evidence-6.png) <br><br><br>

#### 5.2.7. RESTful API documentation

La API de DebtGo se documentó mediante Swagger UI, ofreciendo una interfaz interactiva y profesional para desarrolladores. Esta documentación permite visualizar, probar y validar los servicios RESTful disponibles.

**Secciones disponibles en Swagger:**

- Autenticación (sign-up, sign-in)
- Notificaciones (GET, POST, por ID)
- Suscripciones (GET, POST, por ID)

  ![image](assets/Chapter-5/img-evidence-6.png) <br><br><br>

#### 5.2.8. Team Collaboration Insights

El desarrollo del sistema DebtGo se realizó mediante metodologías ágiles (Scrum), con herramientas colaborativas como:

- **GitHub:** control de versiones y ramas.
- **Trello:** gestión de tareas y sprints.

**Aspectos destacados:**

- **División clara de roles:** frontend, backend, diseño UI/UX y documentación.
- Reuniones semanales para revisión de avance.
- Resolución ágil de conflictos y retroalimentación constante.
- Trabajo colaborativo con enfoque en pruebas funcionales e iterativas.

  ![image](assets/Chapter-5/sprint1.png) <br><br><br>
  
  ![image](assets/Chapter-5/sprint2.png) <br><br><br>

  ![image](assets/Chapter-5/sprint-3.JPG) <br><br><br>

## 5.3 Video About-the-Product
[Link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211108_upc_edu_pe/EWTv9b_CulxJjdwTSq3upFEBnz2RD8X1LcOhCr5Oeyywjg?e=PGLqcC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) 
https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211108_upc_edu_pe/EWTv9b_CulxJjdwTSq3upFEBnz2RD8X1LcOhCr5Oeyywjg?e=PGLqcC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

# Capítulo VI: Product Verification & Validation
## 6.1. Testing suites & Validations
### 6.1.1. Core Entities Unit tests.
Esta sección agrupa las pruebas unitarias del backend de DebtGo para los componentes clave del dominio. Cada caso verifica el comportamiento y la gestión de estado de servicios y modelos —como Advisory, Simulation, ConsultantProfile, Payment, Education y Review— garantizando que la lógica de negocio responda como se espera. Se validan construcción de objetos, actualización de propiedades, reglas de cálculo (p. ej., simulaciones y calificación), manejo de escenarios límite y métodos utilitarios. Los resultados muestran ejecuciones exitosas por servicio, asegurando una base estable para las funcionalidades de registro de deudas, asesoría y valoración de consultores.

**UNIT TEST EVIDENCES**
![unit](assets/Chapter-6/UNIT%20TEST.jpg)


### 6.1.2. Core Integration Tests. 

Esta sección reúne las **pruebas de integración del núcleo web de DebtGo**, enfocadas en los **controladores**. Usamos `@WebMvcTest` con **MockMvc** y **ObjectMapper**, aislando la capa web mediante `@MockBean` de los servicios de dominio (p. ej., `AdvisoryService`).

**Qué validamos**
- **Contratos HTTP**: rutas, métodos, códigos de estado y encabezados.
- **Serialización/Deserialización JSON**: estructura y tipos esperados en requests/responses.
- **Validaciones**: reglas de entrada (campos obligatorios, formatos, rangos).
- **Manejo de errores**: mensajes y códigos para casos inválidos o excepciones.
- **Orquestación del controlador**: interacción correcta con el servicio mockeado.

**Cobertura (ejemplos)**
- `AdvisoryControllerWebMvcTest`: creación y consulta de asesorías.
- `ConsultantAppServiceControllerWebMvcTest`: endpoints para consulta de consultores/perfiles.

**Resultado actual**
- Ejecución exitosa de los casos (p. ej., *Tests run: 4, Failures: 0, Errors: 0, Skipped: 0*), lo que confirma que la capa de control expone contratos estables y listos para promover a entornos superiores.

> Con estas pruebas aseguramos que los componentes centrales del sistema se comporten de forma coherente como una **unidad**, cumpliendo los requisitos funcionales de negocio y aportando **confianza** para despliegues a producción.

**INTEGRATION TEST EVIDENCES**

![int](assets/Chapter-6/UNIT%20TEST.jpg)

### 6.1.3. Core Behavior-Driven Development 

**EPIC 01 - US01- Demostración de la aplicación**
![US01](assets/Chapter-6/US01.png) <br><br><br>

**EPIC 02 - US07 - Pago por servicios**
![US07](assets/Chapter-6/US07.png) <br><br><br>

**EPIC 03 - US11 - Elección y actualización de plan**
![US11](assets/Chapter-6/US11.png) <br><br><br>

**EPIC 05 - US23 - Actualización de solicitudes**
![US23](assets/Chapter-6/US23.png) <br><br><br>

**EPIC 06 - US27 - Visualización de métricas propias**
![US27](assets/Chapter-6/US27.png) <br><br><br>

**EPIC 07 - US34 - Creación de presupuestos**
![US34](assets/Chapter-6/US34.png) <br><br><br>

### 6.1.4. Core System Tests. 

**Consultant Profile Service Test**
![CST](assets/Chapter-6/consultant_serv_test.jpeg)<br><br><br>

**Dashboard Service Test**
![DaST](assets/Chapter-6/dashboard_serv_test.jpeg)<br><br><br>

**Debt Service Test**
![CST](assets/Chapter-6/debt_serv_test.jpeg)<br><br><br>

**Education Service Test**
![CST](assets/Chapter-6/education_serv_test.jpeg)<br><br><br>

**Payment Service Test**
![CST](assets/Chapter-6/payment_serv_test.jpeg)<br><br><br>

**Review Service Test**
![CST](assets/Chapter-6/review_serv_test.jpeg)<br><br><br>

**Simulation Service Test**
![CST](assets/Chapter-6/simulation_serv_test.jpeg)<br><br><br>

**User Service Test**
![CST](assets/Chapter-6/user_serv_test.jpeg)<br><br><br>

## 6.2. Static testing & Verification
### 6.2.1. Static Code Analysis
#### 6.2.1.1. Coding standard & Code conventions.

DebtGo utiliza Java 17 y Spring Boot 3 con una arquitectura por capas (controller, service, repository, domain, dto). El estilo de código sigue una convención simple: paquetes en minúsculas con el prefijo com.debtgo.`debtgo_backend`, clases e interfaces en PascalCase (por ejemplo, `AdvisoryController`, `ConsultantService`) y miembros/métodos en camelCase. La indentación es de cuatro espacios, los imports se mantienen ordenados y sin comodines, y se evita superar las 120 columnas para preservar la legibilidad. Cada archivo contiene una sola clase pública.

En la superficie de la API, los controladores REST agrupan endpoints por agregado de dominio y exponen rutas en plural, aplicando los verbos HTTP de forma idempotente cuando corresponde. Las entidades JPA nunca se exponen directamente; la entrada y salida se modela con DTOs validados con jakarta.validation para asegurar contratos explícitos. Los errores se estandarizan mediante un `@ControllerAdvice`, de modo que los clientes reciben códigos y mensajes consistentes.

A nivel de dominio y persistencia, las entidades residen en domain y los repositorios Spring Data en repository, mientras que la lógica de aplicación se concentra en service con transacciones donde haga falta. Lombok se usa para eliminar boilerplate (getters, setters y builders), evitando @Data en entidades para no comprometer igualdad y hash. La documentación mínima se mantiene con JavaDoc en APIs públicas y se fomenta el nombrado expresivo sobre comentarios redundantes. El resultado es un código uniforme, fácil de revisar y listo para automatizar con herramientas como Checkstyle/Spotless o SonarLint cuando el equipo lo requiera.

#### 6.2.1.2. Code Quality & Code Security.

En DebtGo la calidad y seguridad del código se controlan de extremo a extremo desde la integración continua. Cada *push* o *pull request* dispara un flujo en **GitHub Actions** que compila el backend con Maven y ejecuta la batería de pruebas con **JUnit 5** y **Mockito** (además de tests web con Spring MockMvc). Este circuito *fail-fast* evita que lleguen a la rama principal cambios que rompan la construcción o el comportamiento esperado.

La cadena de dependencias se vigila con alertas automáticas de **GitHub** (Dependabot) y con escaneos de vulnerabilidades en tiempo de construcción (por ejemplo, **OWASP Dependency-Check**). Así se detectan CVEs conocidas y transitives desactualizadas, proponiendo upgrades seguros. A nivel de repositorio también se activa secret scanning para impedir que llaves o tokens se filtren por accidente.

En el código se aplican prácticas defensivas coherentes con DDD y Spring: validación de entrada con `jakarta.validation` en DTOs, manejo centralizado de errores con `@ControllerAdvice`, serialización segura evitando exponer entidades JPA, límites de paginación para prevenir abusos, configuración por variables de entorno (credenciales nunca en el repositorio) y despliegue en **Dokploy** con secretos gestionados como *environment variables*. Con esta combinación de pruebas, análisis estático y escaneo de dependencias, el proyecto mantiene un ciclo de mejora continua que reduce deuda técnica y riesgos antes de llegar a producción.

### 6.2.2. Reviews

El flujo de trabajo de DebtGo se basa en **Pull Requests** con ramas protegidas. Todo cambio pasa por revisión cruzada: al menos un revisor valida el código antes de fusionarlo a `main`. La PR debe aprobar checks obligatorios: compilación Maven, pruebas **(JUnit 5, Mockito/MockMvc)** y análisis estático con SonarQube/SonarScanner. Si hay hallazgos críticos, la PR queda bloqueada hasta corregirlos.

Las revisiones combinan lectura manual y evidencias del pipeline. Nuestro checklist se centra en: (a) cumplimiento de convenios de código y arquitectura, (b) contrato REST (nombres, estatus HTTP, DTOs validados con `jakarta.validation`), (c) cobertura mínima de pruebas por capa, (d) seguridad básica (no exponer entidades, manejo de errores con `@ControllerAdvice`, secretos fuera del repo) y (e) impacto en rendimiento/paginación.

Al seguir **DDD**, la revisión prioriza la correcta separación por **bounded contexts** (deuda, educación, pagos, asesoría), la integridad de **agregados/entidades** y el bajo acoplamiento entre módulos. Este proceso mantiene la calidad, reduce deuda técnica y evita regresiones antes del despliegue en Dokploy.

## 6.3. Validation Interviews.
Validar si DebtGo **reduce fricción** en el alta de deudas, **mejora recordatorios** (canal y timing) y **aumenta pagos a tiempo**. Las entrevistas se enfocan en comportamiento real y decisiones financieras cotidianas.

### 6.3.1. Diseño de Entrevistas.

- **Formato:** semi-estructuradas (15–25 min), con tareas cortas (pensamiento en voz alta).
- **Muestra:** 6–8 entrevistas por segmento (mín. 12 totales).
- **Ética:** consentimiento informado; no recolectar datos sensibles (montos reales opcionales/anónimos).

**Segmentos Objetivo**

1) **Segmento Objetivo: Consultores financieros:**  
   Estudiantes, jóvenes profesionales o jefes de hogar con pagos recurrentes (servicios, tarjetas, préstamos).

2) **Segmento Objetivo: Gestores de Deudas y Emprendedores**  
   Quienes administran pagos a proveedores/servicios y necesitan control de vencimientos.

**Preguntas generales**

¿Cuál es tu nombre?
¿Cuáles son tus apellidos?
¿Cuál es tu edad?
¿En qué distrito resides?

**Segmento Objetivo: Consultores financieros:**
1. ¿Te resulta claro cómo entrar con tu correo y contraseña? ¿Agregarías “continuar con Google/Apple”?
2. ¿Entiendes qué datos debes completar y las reglas de contraseña antes de registrarte?
3. ¿Aceptarías los Términos/Política desde esa vista sin dudas? ¿Qué te haría confiar más?
4. ¿Queda claro lo que incluye Basic vs Premium y el precio mensual? ¿Cuál elegirías y por qué?
5. Al hacer clic, ¿qué esperas que ocurra (pago, prueba gratis, más detalles)?
6. ¿Es sencillo ver y editar tu nombre, correo y contraseña? ¿Qué mejorarías del flujo?
7. ¿Te queda claro tu plan actual y cómo cancelar o cambiar de plan?
8. Al entrar a My Workspace, ¿sabes qué acciones están disponibles (métricas, presupuestos, cursos)?
9. En Financial tools, ¿entiendes qué hay en Analytics, Budgets y Courses? ¿Qué te falta?
10. ¿Te resulta fácil iniciar conversación con un consultor y entender el historial del caso?
11. ¿La jerarquía (títulos, botones, tarjetas) te guía sin perderte? ¿Dónde hubo confusión o clics extra?
12. ¿Qué señales aumentarían tu confianza para manejar datos financieros (sellos, 2FA, explicación de seguridad)?


**Segmento Objetivo: Gestores de Deudas y Emprendedores** 
1. ¿Puedes iniciar sesión y llegar a tu Workspace sin pasos confusos?
2. ¿Editar nombre/correo/contraseña es directo? ¿Dónde cambiarías disponibilidad u horario?
3. ¿Entiendes de inmediato dónde ver reseñas, mensajes y métricas?
4. ¿Distingues claramente Edit service de Post new service?
5. En Post new service, ¿los campos (título, descripción, precio, archivos) son suficientes y claros?
6. ¿El selector de precio es claro (moneda, unidad, por sesión/hora)? ¿Qué formato ayudaría?
7. ¿Dónde te gustaría ver y gestionar reseñas y calificaciones (responder, reportar, destacar)?
8. ¿Puedes localizar contactos, adjuntar archivos y seguir el historial del caso sin perder contexto?
9. ¿Qué indicadores necesitas (tasa de respuesta, conversiones, ingresos, NPS)?
10. ¿La sección Courses te motiva para mejorar perfil/ingresos? ¿Qué certificación te sería útil?
11. ¿La sección Courses te motiva para mejorar perfil/ingresos? ¿Qué certificación te sería útil?
12. ¿Qué te falta para sentir seguridad al ofrecer servicios (verificación de identidad, términos claros, protección al consultor)?


### 6.3.2. Registro de Entrevistas.

**Segmento Objetivo: Consultores financieros:**

**Entrevista #1**

- Nombre: Maria Pilares Pocochuanca
- Edad: 26 años
- Distrito: Los Olivos
- Duración: 5:05

![image](assets/Chapter-6/Entrevista1_Segm1_validation.png)
[Entrevista 1 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214214_upc_edu_pe/EQ77TmeMzZxLv83IOvsXFtMBa3PM7kygfpVsY93jZnukZg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=ReJpXc)

Resumen: Como consultor financiero Maria Pilares, el front web de DebtGo le guía de forma natural: el ingreso/registro es limpio, la pantalla de planes con tarjetas “Basic” y “Premium” explica beneficios sin ruido visual y el botón “Start” reduce fricción. En “Profile” veo de inmediato plan activo y datos del cliente; desde “My Workspace” puedo abrir reseñas o enviar “Mensaje” sin perder el contexto. El estilo minimal con bloques bien contrastados y call-to-actions morados hace que cada recomendación termine en una acción clara. 


**Segmento Objetivo: Gestores de Deudas y Emprendedores**

**Entrevista #2**
- Nombre: George Garcia Durand
- Edad: 20 años
- Distrito: Rimac
- Duración: 4:57


![image](assets/Chapter-2/George.png)

[Entrevista 3 - video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202113279_upc_edu_pe/Ea0th-UAr9JBrljOSf-yPTIBE_7YfuXWx3s9Yz9cgeTWGQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=humfYy)

Resumen: Desde la mirada de un gestor de deudas, George cree que la interfaz favorece el trabajo diario porque concentra todo en vistas muy directas. En “My Workspace” tiene la cabecera del cliente con foto, horario y acceso rápido a “Reseñas” y “Mensaje”; debajo, los paneles “Services” y “Metrics” separan ejecución y seguimiento: puedo “Post new service” con un modal simple (título, descripción, precio y archivos) y, a la vez, monitorear el avance con gráficos de la sección Metrics. La pantalla “Messages” replica el patrón de herramientas profesionales: lista de contactos a la izquierda, historial al centro y caja de envío con adjuntos, ideal para registrar acuerdos o solicitar comprobantes. Para cerrar el circuito operativo, propondría una vista tipo tablero dentro de “Services” que agrupe por estado (pendiente, en negociación, reprogramado, cerrado) y atajos en cada tarjeta para “Registrar pago” o “Enviar recordatorio”, alineados con el mismo estilo visual del resto del front.

### 6.3.3. Evaluaciones según heurísticas.

**1) Consistencia y estándares**

**Descripción.** Mantener patrones uniformes en diseño y flujos.

**Hallazgos.**
- Tipografías y espaciados son consistentes, pero el grosor de botones (p. ej., `Log in`, `Register`, `Start`) varía levemente entre pantallas.
- En “Profile” el label “Acount” está mal escrito (**Account**), rompiendo consistencia lingüística.
- Iconos (ojo de contraseña, campana, idioma) mantienen estilo, pero su tamaño no es uniforme en todas las vistas.

**Evidencia.**  
“En **Register** el botón principal se ve más alto que en **Log in** y en **Select a plan**.”  

**Recomendaciones.**
- Unificar tokens de diseño (altura de botón, padding horizontal, radio y sombra) en un Design System.
- Revisión de UX writing (ortografía y terminología: *Account*, *Plan*, *Messages*, etc.).
- Definir escala de iconos (p. ej., 20/24/28 px) y aplicarla globalmente.

**Severidad:** 2 (Moderado)

**2) Control y libertad del usuario**

**Descripción.** Permitir deshacer/rehacer y corregir acciones con facilidad.

**Hallazgos.**
- En **Post new service** falta feedback claro tras “Confirm” (no se indica éxito/fracaso ni CTA de retorno).
- En **Messages** el “This chat is empty” no ofrece acciones rápidas (crear/adjuntar primer mensaje).
- En **Select a plan** no hay confirmación secundaria para evitar clics accidentales en *Start*.

**Evidencia.**  
“Confirmé un servicio y no supe si se publicó ni a dónde volver.”  

**Recomendaciones.**
- Añadir snackbar/toast con resultado y botón “Ver servicio”.
- En **Messages**, CTA “Start conversation” y atajo para adjuntar archivos.
- Diálogo de confirmación al elegir plan y opción “Cambiar plan” en **Profile**.

**Severidad:** 3 (Alto)

**3) Prevención de errores**

**Descripción.** Evitar errores mediante validaciones y mensajes oportunos.

**Hallazgos.**
- Validación de **Email/Password** no indica reglas mínimas (p. ej., longitud/formatos) antes de intentar enviar.
- En **Password** el icono “ojo” carece de etiqueta accesible (*aria-label*) y estado visible.
- En **Post new service** el precio no explicita moneda/decimales; puede provocar registros inconsistentes.

**Evidencia.**  
“Probé registrarme con una clave corta; el formulario solo se limpió sin explicar por qué.”  

**Recomendaciones.**
- Validación en tiempo real con mensajes claros y ejemplos (email válido, 8+ caracteres, etc.).
- Etiquetas accesibles y estados de *show/hide password*.
- Campo **Price** con máscara numérica, selector de moneda (S/ o $) y validación de rango.

**Severidad:** 2 (Moderado)

**4) Flexibilidad y eficiencia de uso**

**Descripción.** Atajos y personalización para usuarios frecuentes.

**Hallazgos.**
- Falta **Remember me** persistente visible en **Register** (solo en **Log in**).
- No hay atajos de teclado (p. ej., `Enter` para enviar en **Messages**, `Esc` para cerrar modales).
- En **Workspace** las “Metrics” son maquetas estáticas; no permiten filtros o periodos rápidos (última semana/mes).

**Evidencia.**  
“Quisiera enviar con *Enter* y filtrar métricas por mes sin ir a otra pantalla.”  

**Recomendaciones.**
- Unificar persistencia de sesión y preferencias por usuario.
- Atajos básicos (`Enter`, `Esc`) y foco gestionado en modales.
- Filtros de periodo y exportación rápida (CSV/PDF) en “Metrics”.

**Severidad:** 2 (Moderado)

**5) Diseño estético y minimalista**

**Descripción.** Mostrar solo lo necesario y jerarquizar bien.

**Hallazgos.**
- El gradiente de fondo es correcto, pero en pantallas amplias reduce contraste de algunos textos secundarios.
- En **Profile** la foto y el bloque de datos compiten por atención; falta jerarquía de títulos y espaciado vertical.
- En **Services** (listado) los *thumbnails* grandes desplazan el texto; se sugiere rejilla con cards más compactas.

**Evidencia.**  
“En **Profile**, lo que más resalta es la foto; el nombre y plan quedan en segundo plano.”  

**Recomendaciones.**
- Ajustar contraste mínimo (WCAG AA) para textos secundarios.
- Reordenar **Profile**: título > nombre > plan > acciones; foto en soporte, no foco primario.
- Cards compactas con título, breve descripción y CTA consistente.

**Severidad:** 1 (Bajo)

---

**Resumen de priorización**

| Heurística                      | Severidad | Recomendación clave                                  |
|---------------------------------|-----------|-------------------------------------------------------|
| Control y libertad              | **3**     | Feedback y confirmaciones + CTAs de retorno           |
| Consistencia y estándares       | 2         | Unificar tokens/estilos e idioma                      |
| Prevención de errores           | 2         | Validación en tiempo real + mensajes claros           |
| Flexibilidad y eficiencia       | 2         | Atajos, persistencia y filtros en métricas            |
| Diseño estético/minimalista     | 1         | Mejorar contraste y jerarquía en **Profile/Services** |

**Conclusión.** DebtGo presenta una base visual coherente y clara. Las mejoras con mayor impacto UX a corto plazo se concentran en **control/libertad del usuario** (feedback y confirmaciones), **validaciones preventivas** y **consistencia de componentes**. Al abordar estos puntos, el flujo de registro, publicación de servicios y mensajería ganará confianza, velocidad y accesibilidad.


## 6.4. Auditoría de Experiencias de Usuario.


### 6.4.1. Auditoría realizada.

#### 6.4.1.1. Información del grupo auditado.


#### 6.4.1.2. Cronograma de auditoría realizada.


#### 6.4.1.3. Contenido de auditoría realizada.


### 6.4.2. Auditoría recibida.


#### 6.4.2.1. Información del grupo auditor.


#### 6.4.2.2. Cronograma de auditoría recibida.


#### 6.4.2.3. Contenido de auditoría recibida.

#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos.


# Capítulo VII: DevOps Practices
## 7.1. Continuous Integration
### 7.1.1. Tools and Practices

En DebtGo empleamos un conjunto de herramientas y prácticas que sostienen nuestro flujo de integración continua y aseguran la calidad del producto. A continuación se detallan las herramientas clave y cómo aportan al proceso de desarrollo del sistema de registro de deudas, programación de pagos y notificaciones.

| Herramienta | Descripción | Propósito | Imagen de Referencia |
| ----------- | ----------- | --------- | -------------------- |
|JUnit        | Framework de pruebas unitarias para Java | Verificar, de forma aislada, el comportamiento de componentes como cálculo de montos, validación de fechas de vencimiento y reglas de negocio del módulo de deudas. | ![JUnit](https://upload.wikimedia.org/wikipedia/commons/5/59/JUnit_5_Banner.png)|
| Mockito | Librería para crear objetos simulados (mocks) en pruebas.  |  Simular servicios externos (por ejemplo, pasarela de pagos o servicio de notificaciones) para probar casos de error y de latencia sin depender de integraciones reales. | ![mck](https://upload.wikimedia.org/wikipedia/commons/2/2c/Mockito_Logo.png) |
| Cucumber  | Framework BDD (Behavior-Driven Development) para definir pruebas legibles por negocio. |  Escribir escenarios Gherkin que describen flujos como “registrar deuda”, “programar recordatorios” o “marcar como pagado”, asegurando que el sistema cumple lo acordado con el equipo y stakeholders. | ![cucumber](https://cdn.iconscout.com/icon/free/png-256/free-cucumber-icon-svg-download-png-1175199.png)  |
| GitHub | Plataforma CI/CD nativa de GitHub. | Orquestar pipelines de build, pruebas (unitarias/BDD/API) y despliegues. Ejecuta workflows por push/PR, impone checks obligatorios antes del merge y publica artefactos y reportes. | ![GitHub](https://static.wikia.nocookie.net/windows/images/0/01/GitHub_logo_2013.png/revision/latest/thumbnail/width/360/height/450?cb=20231201024220)  |

**Prácticas utilizadas**

- **Commits tempranos y frecuentes.** Trabajamos con cambios pequeños y atómicos para reducir conflictos y facilitar la integración continua. Usamos mensajes con *Conventional Commits* (`feat:`, `fix:`, `docs:`) y referencia a UG/US (p. ej., `UG03`).

- **Revisiones por Pull Request.** Todo cambio entra vía PR hacia `develop` o `main`. Requiere al menos 1 revisor, discusión técnica y verificación de checklist (lint, build, pruebas). Los PR enlazan su User Goal/Story y evidencias.

- **Pruebas automáticas en CI.** En cada *push* y PR, el pipeline ejecuta pruebas **unitarias** (JUnit/Mockito) y **BDD** (Cucumber) para flujos clave de DebtGo: registrar deudas, programar pagos y enviar notificaciones. El merge se bloquea si falla alguna prueba o si la cobertura mínima no se cumple.

- **Protecciones de rama.** `main` y `develop` con PR obligatoria, squash merge y *status checks* requeridos.
- **Calidad estática.** Linter y análisis (p. ej., SpotBugs/Detekt/ESLint) como *gates* del pipeline.

### 7.1.2. Build & Test Suite Pipeline Components

El pipeline de Integración Continua (CI) de **DebtGo** automatiza la verificación de calidad para backend y frontend en cada `push` y `pull request` a `develop` y `main`. A continuación se detallan los componentes y validaciones incluidas.

#### Alcance general
- **Disparadores:** `push` y `pull_request` sobre `develop` y `main`.
- **Ejecución:** GitHub Actions en runners `ubuntu-latest`.
- **Artefactos de salida (CI):** reportes de pruebas y cobertura, paquetes compilados y, cuando aplica, el directorio de build del frontend.
- **Criterios de aprobación:** todos los jobs deben finalizar en estado *success* antes de permitir el merge.

---

#### Backend CI (Java/Gradle)
**Objetivo:** garantizar que la API de DebtGo compila, pasa controles estáticos y cumple pruebas.

**Etapas**
1. **Setup & cache:** configuración de JDK 17 y caché de Gradle para acelerar builds.
2. **Lint / Static checks:** ejecución de verificaciones (`check`) excluyendo pruebas.
3. **Build:** compilación y generación de artefactos (`assemble`).
4. **Tests + Coverage:** pruebas unitarias con JUnit/Mockito y reporte de cobertura (JaCoCo).
5. **Publicación de artefactos:** exporte de reportes JUnit/JaCoCo y binarios generados.
6. **Resumen de ejecución:** publicación de tiempos por etapa en el Job Summary.

**Validaciones**
- Compilación sin errores y análisis estático sin fallos bloqueantes.
- Pruebas unitarias exitosas y cobertura mínima acordada para módulos críticos.
- Reportes disponibles para auditoría posterior.

---

#### Frontend CI (Node/Vite)
**Objetivo:** asegurar que la Web App de DebtGo instala dependencias, construye correctamente y, si existen, ejecuta pruebas de UI.

**Etapas**
1. **Install:** instalación limpia (`npm ci`) con caché de dependencias.
2. **Lint:** reglas de estilo y calidad (ESLint u otra herramienta definida).
3. **Build:** construcción de artefactos (`npm run build`) con optimización.
4. **Tests (opcional/si existen):** ejecución de pruebas con el *test runner* del proyecto (Vitest/Jest).
5. **Publicación de artefactos:** exporte de reportes (coverage/JUnit) y carpeta `dist/`.
6. **Resumen de ejecución:** tiempos por etapa en el Job Summary.

**Validaciones**
- Build reproducible sin *warnings* críticos.
- Pruebas de UI (si aplican) exitosas y cobertura reportada.

![CI/CD](assets/Chapter-6/CI-CD.jpg)

## 7.2. Continuous Delivery
### 7.2.1. Tools and Practices.


| Herramienta | Función | Imagen de Referencia |
| ----------- | ----------- | -------------------- |
| GitHub  | Aloja los repos por producto (Landing, Web, Mobile, API). Gestiona issues/PR, _releases_ y ejecuta pipelines con Actions para build, pruebas y despliegues.| ![GH](https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png)|
| Docker | Conteneriza la API y dependencias (BD, mensajería) para mantener paridad entre entornos. Usamos imágenes versionadas y `docker-compose` para levantar el stack local/CI. | ![docker](https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/97_Docker_logo_logos-512.png) |
| Postman  | Colecciones para pruebas de API (unitarias, contract y E2E). Se ejecutan con **Newman** en CI/CD con variables por ambiente (dev/test/prod).| ![postman](https://upload.wikimedia.org/wikipedia/commons/c/c2/Postman_%28software%29.png?20211024200826)  |
| Swagger / OpenAPI | Contrato único de la API: documentación interactiva, validación de _schemas_ y generación de _clients_ para Web/Mobile. Facilita _mocking_ temprano y pruebas automatizadas. |  ![swagger](https://iconlogovector.com/uploads/images/2024/10/lg-67058d65d1040-Swagger.webp)  |

- **Github Repositories Deployment**
Se puede obervar los reposiotrios del Front y del Back para el despliegue de estos.
  ![deploy](assets/Chapter-6/repo_deploys.png)

- **swagger OpenAPI**
Se puede observar el CRUD de los endpoints
  ![image](assets/Chapter-6/SWAGGER.jpg) <br><br><br>

### 7.2.2. Stages Deployment Pipeline Components.

| Etapa | Herramientas | Objetivo/Proceso | Imagen de Referencia |
| ----------- | ----------- | -------------------- |-----|
|  **1. Build** |   Gradle/Maven (API), Node+Vite (Web), Android Gradle (Mobile)  | • Compilar código y resolver dependencias.  • Generar artefactos versionados (`.jar/.war`, `dist/`, `.apk`). • Validaciones básicas (lint, formateo, análisis estático). |  ![maven](https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Apache_Maven_logo.svg/1200px-Apache_Maven_logo.svg.png) |
| **2. Test**  | JUnit + Mockito, Postman/Newman, Cucumber  |  • Pruebas unitarias (≥80% cobertura en módulos críticos). • Pruebas de integración de la API. • Escenarios BDD y smoke E2E sobre endpoints clave (registrar deuda, programar pago, notificaciones).  | ![junit](https://upload.wikimedia.org/wikipedia/commons/5/59/JUnit_5_Banner.png)  |
|   **3. Staging**   | Docker, GitHub Actions | • Despliegue en entorno espejo con contenedores: `backend-api`, `web-app`, `db` (y servicios auxiliares). • Orquestación vía `docker-compose.staging.yml`. • Semillas/datos de prueba y variables por ambiente. |  ![docker](https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/97_Docker_logo_logos-512.png) |
| **4. QA / UAT**   |Checklist de validación, gestor de issues (Jira/GitHub Projects)   |  • Verificación funcional y de usabilidad. • Revisión de performance básica y accesibilidad. • Aprobación por checklist antes de _release_.  | ![jira](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/Jira_Logo.svg/2560px-Jira_Logo.svg.png)  |
|  **5. Production**   |  Dockploy | • Despliegue de contenedores Docker del Backend API y servicios auxiliares. <br> • Estrategia **Blue/Green** o **Rolling** administrada desde Dokploy (dos stacks/servicios). <br> • *Health checks* y verificación de estado antes del *switch* de tráfico. <br> • **Rollback** inmediato a la imagen anterior si hay fallos.  |  ![dockploy](https://ph-files.imgix.net/06e930c7-ab5c-4507-922d-4c113570ea80.png?auto=compress&codec=mozjpeg&cs=strip&auto=format&w=400&h=210&fit=max&frame=1) |

**Descripción del pipeline**

El flujo de entrega continua de **DebtGo** automatiza desde la construcción hasta el monitoreo en vivo, utilizando herramientas estándar de la industria. Cada etapa valida aspectos críticos: primero se compilan los artefactos y se ejecutan pruebas unitarias/BDD y de integración; luego se despliega en **staging** con contenedores para asegurar paridad entre entornos. La fase **QA/UAT** combina validación manual guiada por *checklists* con resolución de hallazgos en el gestor de issues, garantizando que solo versiones estables pasen a producción. Finalmente, El pipeline de despliegue continuo de DebtGo integra herramientas estándar en un flujo automatizado que garantiza calidad y confiabilidad. Cada etapa valida aspectos críticos del software, desde la construcción inicial hasta el monitoreo en producción. La combinación de pruebas automatizadas y validación manual asegura que solo versiones estables lleguen a los usuarios finales. La estrategia **Blue/Green en Dokploy** minimiza riesgos durante despliegues, mientras que los contenedores Docker proporcionan consistencia entre entornos. Este enfoque sistemático reduce errores y acelera la entrega de valor.


## 7.3. Continuous deployment
La implementación continua (Continuous Deployment, CD) es el proceso automatizado de llevar cambios de código desde un repositorio hasta entornos de producción, asegurando entregas rápidas y confiables. A diferencia de Continuous Delivery, la CD no requiere aprobación manual (todo se despliega automáticamente si pasa las pruebas).
### 7.3.1. Tools and Practices.

**Herramientas**

| Herramienta | Función | Prácticas | Logo |
|---|---|---|---|
| **Dockploy** | Plataforma de entrega continua enfocada en *frontends*. Se integra con GitHub para construir y publicar automáticamente la **Web App / Landing**. | - *Auto-deploy* al hacer push a `main` y *preview deployments* por cada PR. <br> - Dominios personalizados y SSL gestionados por la plataforma. <br> - Builds optimizados con caché para mejores tiempos de respuesta. | ![dockploy](https://ph-files.imgix.net/06e930c7-ab5c-4507-922d-4c113570ea80.png?auto=compress&codec=mozjpeg&cs=strip&auto=format&w=400&h=210&fit=max&frame=1) |
| **Dokploy** |  PaaS auto-gestionado para ejecutar el **Backend API** y servicios de apoyo en contenedores **Docker**. Facilita despliegue, variables de entorno y gestión de dominios/SSL en un servidor propio. | - Integración con GitHub para *auto-deploy* por rama/PR. <br> - Gestión centralizada de **Environment Variables** y **Secrets** por ambiente. <br> - Despliegue de imágenes Docker y plantillas `docker-compose`. <br> - Logs en vivo y *health checks* para supervisión básica. | ![dockploy](https://ph-files.imgix.net/06e930c7-ab5c-4507-922d-4c113570ea80.png?auto=compress&codec=mozjpeg&cs=strip&auto=format&w=400&h=210&fit=max&frame=1) |
| **GitHub Pages** | Hosting de sitios estáticos directamente desde el repo (ideal para **documentación** o landing estática). | - Publicación automática desde la rama `gh-pages` (o `main` con acción de build). <br> - Configuración de dominio propio y HTTPS sin costo. | ![GitHub Pages](https://ugeek.github.io/blog/images-blog/githubpages.png) |

### 7.3.2. Production Deployment Pipeline Components

Para asegurar un despliegue continuo y confiable en **producción**, definimos los componentes del pipeline utilizando:
- **Vercel** para Frontend Web (Web App / Landing si aplica Next.js).
- **Dokploy** para **Backend API** y servicios de soporte.
- **GitHub Pages** para la **Landing** estática o documentación.

---

**Trigger**
- `push`/`merge` a `main` del repo del frontend o aprobación de un PR con _checks_ verdes.

**Build**
- `npm ci && npm run build`, optimización de assets y validación de rutas.

**Testing**
- Pruebas unitarias/integración de UI (si están configuradas).

**Deployment**
- Publicación automática en **Vercel**, dominio personalizado y SSL.
- **Preview URLs** por PR.

**Post-Deployment**
- Invalidación de caché/CDN y monitoreo de métricas (Core Web Vitals).

---

**2) Backend API (Railway)**

**Trigger**
- `push`/`merge` a `main` del repo del backend.

**Build**
- Construcción de imagen **Docker** o build nativo y *push* al registry configurado.

**Testing**
- Pruebas **unitarias** y **de integración** (DB/servicios externos).
- (Opcional) *Contract tests* contra OpenAPI.

**Deployment**
- Despliegue automático en **Dokploy** usando imagen Docker o `docker-compose` plantilla.  
- Gestión de **variables de entorno** y **secrets** por ambiente.  
- Configuración de **dominio** y **SSL** desde Dokploy.

**Post-Deployment**
- **Smoke tests** a endpoints críticos.  
- Revisión de **logs** y *health checks* desde el panel de Dokploy.

---

**3) Landing estática / Documentación (GitHub Pages)**

**Trigger**
- `push` a `main` o `gh-pages`.

**Build**
- Generación de artefactos estáticos y minificación de recursos.

**Deployment**
- Publicación en **GitHub Pages** con **HTTPS** y dominio propio (opcional).

**Post-Deployment**
- Validación de enlaces/recursos y verificación de sitemap.

---

**Prácticas para Continuous Deployment**

**Automatización de Pipelines**
- Workflows en **GitHub Actions** para build, pruebas y despliegues por ambiente (`dev`, `staging`, `prod`).

**Feature Flags**
- Activación/desactivación de funcionalidades en producción sin desplegar nuevamente.

**Rollbacks**
- Monitoreo continuo; ante fallas críticas, revertir a la última versión estable.

**Blue-Green / Canary**
- Estrategias de liberación gradual y conmutación entre entornos para minimizar riesgos.

**Integración entre componentes**
- Webhooks/notificaciones para coordinar la liberación entre frontend y backend.

**Seguridad**
- Escaneo de vulnerabilidades (Dependabot/Snyk) y políticas de secretos en CI.


## 7.4. Continuous Monitoring

El **monitoreo continuo** en DebtGo asegura que las APIs de backend (Spring Boot) y los servicios de soporte mantengan **disponibilidad, rendimiento y seguridad** tras cada despliegue en **Dokploy**. Monitoreamos de forma proactiva la salud del servicio, latencia de endpoints, tasas de error y estado de la base de datos (MySQL).
El monitoreo se aplica en **staging y producción**, y alimenta un ciclo de mejora: cuando un indicador cae bajo umbrales, se crea una tarea técnica (issue) y se ejecutan fixes o rollbacks controlados.

### 7.4.1. Tools and Practices

**A) Runtime & Availability**

|Objetivo|Herramienta|¿Qué revisa?|Acción ante falla|
|-|-|-|-|
|Health de la app|**Spring Boot Actuator** `(/actuator/health)`|Liveness/Readiness|Reinicio del contenedor en Dokploy|
|Estado en despliegue|**Dokploy health checks**|Disponibilidad del servicio|Restart / bloquear release|
|Observación de errores|**Logback** con correlation-id|Errores y trazas por request|Análisis y hotfix|

**B) Code Quality en CI/CD**

|Objetivo|	Herramienta	|¿Cuándo corre?	|Criterio de bloqueo|
|--|--|--|--|
|Build y pruebas|**GitHub Actions** (build + tests)|En cada push/PR|Falla pipeline ⇒ no hay merge|
|Seguridad de dependencias|**Dependabot / Alerts**|Automático|Actualizar versión vulnerable|
|Smoke funcional|**Postman Collections**|Post-deploy|Rollback si falla algún smoke|

**C) Datos & Performance**

|Objetivo|Herramienta|Métrica clave|Umbral de alerta|
|--|--|--|--|
|Métricas de API|	**Micrometer**|	p95 latencia, tasa 4xx/5xx|p95 > 600 ms o errores > 2%|
|Base de datos	|**MySQL monitor + Backups**|	Pool de conexiones, latencia, backups diarios|Uso pool > 80% o backup fallido|
|Carga/estrés	|**JMeter**	|Throughput y errores bajo concurrencia|No cumplir SLA definido|


### 7.4.2. Monitoring Pipeline Components

El pipeline de monitoreo de **DebtGo** cubre todo el ciclo: desde la instrumentación en la app hasta la visualización y respuesta operativa. Así aseguramos salud, rendimiento y experiencia de usuario en producción (Dokploy) y pre-producción.

**1) Instrumentación (fuente de datos)**

- El backend Spring Boot expone **Actuator** (`/actuator/health`, `/actuator/metrics`, `/actuator/info`) y métricas **Micrometer** (latencias p95/p99, throughput, tasa 4xx/5xx, uso del pool JDBC).
- El logger **Logback** añade un correlation-id por petición para trazar errores extremo a extremo.
- Pruebas de carga con **JMeter** generan series de rendimiento bajo concurrencia antes de promover un release.

**2) Recolección y transporte**

- Los health checks de **Dokploy** consultan `/actuator/health` para decidir restart/rollback del contenedor.
- Las métricas de **Micrometer** se publican en el endpoint de scrape (formato Prometheus-compatible), listo para ser consumido por un recolector de series temporales si se configura uno; en paralelo, se registran contadores/resúmenes clave en logs para auditoría mínima.

**3) Almacenamiento**

- Los artefactos de cada despliegue (build log, resultados de pruebas, reporte de JMeter/Postman) quedan versionados en **GitHub Actions** como evidencias del estado del release.
- Backups automáticos de **MySQL** (semanales) preservan datos operativos y permiten comparar métricas históricas (tamaño, tiempos de consulta, errores de conexión).

**4) Análisis y alertamiento**

- Reglas operativas (SLOs) sobre las métricas base: `latencia p95 < 600 ms`, `errores 5xx < 2%`, `uso del pool JDBC < 80%`.
- Si una regla se incumple, Dokploy marca el servicio como no saludable y dispara restart o bloquea la promoción.

**5) Visualización**

- Panel básico con Actuator/Micrometer (endpoints JSON) para ver salud y métricas por versión (`/actuator/info` incluye el commit).
- Logs estructurados (Logback) se consultan desde Dokploy para analizar trazas por correlation-id durante incidentes.
- Reportes de **JMeter** y resultados de **Postman** (smoke tests) se adjuntan al release en GitHub para lectura rápida del estado.

**6) Feedback loop (operación → mejora)**

- Incidentes y breaches de SLO se registran como issues; el commit desplegado se identifica con el SHA del **Actuator** `/info`.
- Hallazgos de monitoreo alimentan tareas de optimización (índices SQL, pool sizing, reducción de N+1, circuit breakers si aplica) y pruebas adicionales en el siguiente ciclo.

**7) Validación continua de performance**

- En cada cambio relevante de backend se ejecuta **JMeter** en pre-producción para validar throughput y estabilidad. Si los resultados empeoran contra la línea base, el release no se promueve a Dokploy.

> Resultado: con esta cadena (Actuator/Micrometer → Dokploy health checks → evidencias en GitHub Actions + JMeter/Postman → Quality Gate SonarQube) mantenemos visibilidad operacional, prevenimos degradaciones y reaccionamos rápido ante fallos en DebtGo.

### 7.4.3. Alerting Pipeline Components

El **pipeline de alertas** de DebtGo combina señales de la aplicación, del despliegue y del CI/CD para notificar incidentes con rapidez y contexto accionable.

**Fuentes de alerta.**

**(1)** La app expone **Spring Boot Actuator** y **Micrometer**: si la latencia p95 de `/api/**` supera 600 ms, si el ratio de errores 5xx > 2% sostenido o si el pool JDBC supera 80% de uso, se dispara una alerta.

**(2)** **Dokploy** evalúa liveness/readiness; si el healthcheck falla (servicio unhealthy), marca el despliegue como no saludable y aplica restart automático.

**(3)** **GitHub Actions** marca como failed el build/test o el post-deploy smoke (colección Postman); esto alerta de regresiones funcionales o de un release defectuoso.

**(4)** Dependabot crea avisos ante CVE en dependencias y abre PR de actualización.

**Ruteo y notificación.**

Los fallos de CI/CD y Dependabot llegan por las notificaciones nativas de **GitHub** (web, correo o app). Los estados unhealthy y reinicios de **Dokploy** quedan visibles en el panel y se comunican al equipo como incidente operativo. Cuando se configure un recolector de métricas (p. ej., Prometheus) y un notifier (Alertmanager), las métricas de **Micrometer** podrán enviarse a canales como correo/Slack para alertas en tiempo real.

**Contenido mínimo de la alerta.**

Cada alerta incluye **endpoint/servicio afectado**, **métrica/umbral violado**, **timestamp**, **entorno** (staging/producción) y **versión desplegada** (commit SHA expuesto en /actuator/info). Esto permite reproducir, trazar y decidir **rollback** o hotfix sin pérdida de tiempo.

**Propiedad y respuesta.**

Los incidentes crean un **issue** con el enlace al job o a los logs y un checklist de runbook: revisar health, confirmar versión, inspeccionar trazas con correlation-id, decidir rollback, y abrir tarea raíz (optimización de consulta, límites de paginación, ajuste de pool, etc.). Con este circuito, las anomalías de rendimiento, disponibilidad o seguridad se detectan y atienden antes de impactar de forma sostenida a los usuarios.

### 7.4.4. Notification Pipeline Components.

En DebtGo, las notificaciones del pipeline se gestionan con **GitHub Actions** y el entorno de **Dokploy** para informar, en tiempo real, el estado de build, pruebas y despliegue.

**Eventos notificados.**  
Cada *push* o *pull request* ejecuta CI: si **compila** y pasan las **pruebas** (JUnit/MockMvc), GitHub marca la PR con checks en verde y notifica por web/correo/app. Si falla la compilación, un test o el **quality gate** (Sonar), la PR queda bloqueada y los autores reciben el aviso con enlace directo al log y a las anotaciones del job.

**Despliegue y post-deploy.**  
Al fusionar a `main`, el job CD construye la imagen y ordena el **deploy en Dokploy**. Si no pasan los *health checks* o fallan los **smoke tests** (Postman) posteriores, el job marca **failed** y GitHub notifica a quienes participaron en el cambio. Dokploy muestra el estado (healthy/unhealthy), facilitando confirmar el incidente y decidir **rollback**.

**Alertas de seguridad y dependencias.**  
**Dependabot** emite notificaciones cuando detecta **CVE** en librerías y abre PRs de actualización, avisando a los responsables. Estas alertas llegan al inbox de GitHub y por correo.

**Trazabilidad del release.**  
Cada despliegue publica el **commit SHA** y la versión en `/actuator/info`. Ante una incidencia, el equipo sigue la notificación del job/PR, verifica el SHA desplegado y ejecuta **rollback** o *hotfix*; el resultado queda documentado en el hilo de la PR.

**Resumen operativo.**  
- GitHub Actions notifica **éxito/fallo** de CI/CD con enlaces a logs y artefactos.  
- Sonar/Dependabot generan avisos **proactivos** antes de producción.  
- Dokploy aporta la **señal post-deploy** (health) para decidir rollback.

Este circuito asegura respuestas rápidas, con evidencia suficiente (logs, reportes y commit exacto en producción) para reducir el tiempo de resolución.
# Capítulo VIII: Experiment-Driven Development


## 8.1. Experiment Planning
### 8.1.1. As-Is Summary.

**DebtGo** es una plataforma web y móvil para gestión de deudas personales que ofrece: registro e inicio de sesión, selección de planes (Básico/Premium), panel con progreso de deuda y próximos pagos, configuración de pagos recurrentes, alta de nuevas deudas, centro de notificaciones (email/SMS/push) y un módulo de educación financiera con cursos.

**Problemas identificados (situación actual):**

- **Adopción inicial moderada:** fricción en el primer uso y en la selección de plan; algunos usuarios abandonan antes de completar el registro o el checkout.
- **Onboarding y captura de datos financieros:** el alta de deudas requiere varios campos; hay dudas sobre terminología (tasa, pago mínimo, frecuencia).
- **Adherencia a pagos y recordatorios:** parte de los usuarios desactiva notificaciones o las ignora; faltan métricas finas por canal (email/SMS/push).
- **Experiencia web/móvil inconsistente:** diferencias menores en navegación y estados de carga; tiempos de respuesta variables en endpoints de pagos/consultas.
- **Analítica limitada:** tracking básico de eventos; no hay panel unificado de funnels (registro → plan → primer pago) ni de éxito de recordatorios.
- **Contenido educativo desconectado del flujo de deuda:** los cursos no siempre se relacionan con el contexto financiero actual del usuario.

**Objetivos de mejora (To-Be):**

- **Incrementar la tasa de finalización de registro/checkout** en ≥15% mediante mejoras UX (validaciones en vivo, ayudas contextuales y autocompletado).
- **Reducir el tiempo de onboarding** (crear cuenta + registrar primera deuda) a ≤3 min con formularios progresivos y campos inteligentes.
- **Elevar la tasa de pago a tiempo** en ≥10% optimizando la lógica de recordatorios (canal, frecuencia y contenido) y la configuración de pagos recurrentes.
- **Unificar la experiencia web/móvil** logrando LCP ≤2.5 s en vistas críticas (Login, Dashboard, Add Debt) y estados de carga coherentes.
- **Ampliar la analítica de producto** con funnels de conversión y cohortes de retención para decisiones basadas en datos.
- **Vincular educación con el estado de la deuda**, recomendando módulos y tips según tipo de deuda y progreso (p. ej., “reducción de intereses” cuando APR alto).

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.

**Assumptions**

- Los usuarios con deudas múltiples valorarán un onboarding guiado que calcule automáticamente pagos (mínimo/óptimo) y fechas sugeridas.
- Recordatorios multicanal (email/SMS/push) aumentarán el pago a tiempo y reducirán la morosidad.
- Un checkout simple (planes Básico/Premium) mejorará la conversión sin requerir registro extenso previo.
- Recomendar cursos financieros según el estado de la deuda incrementará la retención y el uso semanal.
- Un dashboard claro con “próximo pago”, “saldo restante” y “progreso” será suficiente para el 80% de consultas diarias.

**Knowledge Gaps**
- ¿Qué canal de notificación (email, SMS, push) produce mayor acción de pago por segmento de usuario?
- ¿Qué campos del alta de deuda generan más abandono (monto, tasa, pago mínimo, frecuencia)?
- ¿Qué barreras perciben los usuarios para registrar su primera deuda (confianza, tiempo, desconocimiento de términos)?
- ¿Qué métricas del dashboard son más útiles (proyección, intereses ahorrados, calendario de pagos)?
- ¿Cómo impacta el contenido educativo contextual (tips/módulos sugeridos) en la reducción de impagos?

**Ideas**

- Onboarding progresivo con validación en vivo y textos aclaratorios (glosario simple para APR, cuota mínima, etc.).
- Asistente de configuración de pagos con simulación “¿qué pasa si…?” (monto variable y fecha límite).
- Motor de recordatorios adaptativos (canal + frecuencia según respuesta previa del usuario).
- Recomendaciones educativas vinculadas al tipo de deuda (tarjeta, préstamo estudiantil, auto).
- Mini-widgets de atajos en Home: “Añadir deuda”, “Registrar pago”, “Editar recordatorios”.

**Claims**

- Simplificar el onboarding reducirá el abandono en el primer uso en ≥15%.
- Optimizar recordatorios multicanal aumentará los pagos a tiempo en ≥10% en 30 días.
- Un checkout más directo elevará la conversión a plan Básico/Premium en ≥12%.

### 8.1.3. Experiment-Ready Questions.

Estas preguntas guían la validación de nuestras hipótesis a través de experimentos controlados. Se priorizan con cuatro criterios: **Confianza**, **Riesgo**, **Impacto** e **Interés**; la suma determina el **Total**.

| Pregunta                                                                                                        | Confianza | Riesgo | Impacto | Interés | Total |
|---|---:|---:|---:|---:|---:|
| ¿Los recordatorios **multicanal adaptativos** (email/SMS/push) aumentan los **pagos a tiempo**?                | 6 | 3 | 9 | 9 | **27** |
| ¿Simplificar el **onboarding** (formularios progresivos + validación en vivo) reduce el **abandono inicial**?  | 7 | 3 | 8 | 8 | **26** |
| ¿Un **asistente de configuración de pagos** (“¿qué pasa si…?”) reduce **pagos omitidos** en el primer mes?     | 6 | 4 | 8 | 7 | **25** |
| ¿Un **checkout directo** para planes Básico/Premium mejora la **conversión** de visitantes a suscriptores?     | 6 | 2 | 8 | 7 | **23** |
| ¿Las **recomendaciones educativas contextuales** elevan el **uso semanal** y disminuyen **impagos recurrentes**?| 5 | 3 | 7 | 6 | **21** |

### 8.1.4. Question Backlog.

Este backlog prioriza las preguntas críticas para los próximos ciclos de experimentación. Se ordenan por **prioridad estratégica** (1 = más alta), alineadas a los objetivos de DebtGo: aumentar pagos a tiempo, reducir abandono inicial y mejorar conversión a planes.

| # | Pregunta                                                                                                       | Prioridad |
|---:|---|---:|
| 1 | ¿Los recordatorios **multicanal adaptativos** (email/SMS/push) aumentan los **pagos a tiempo**?               | 1 |
| 2 | ¿Simplificar el **onboarding** (formularios progresivos + validación en vivo) reduce el **abandono inicial**? | 2 |
| 3 | ¿Un **asistente de configuración de pagos** (“¿qué pasa si…?”) reduce **pagos omitidos** en el primer mes?    | 3 |
| 4 | ¿Un **checkout directo** para planes Básico/Premium mejora la **conversión** de visitantes a suscriptores?    | 4 |
| 5 | ¿Las **recomendaciones educativas contextuales** elevan el **uso semanal** y disminuyen **impagos**?          | 5 |

### 8.1.5. Experiment Cards.

Las siguientes tarjetas describen los experimentos planificados a partir del **Question Backlog**. Cada experimento se estructura con **Question, Why, What, Hypothesis** para asegurar trazabilidad y resultados medibles.

---

#### Experimento 1: Recordatorios multicanal adaptativos
| Campo | Detalle |
|---|---|
| **Question** | ¿Los recordatorios multicanal adaptativos (email/SMS/push) aumentan los pagos a tiempo? |
| **Why** | Muchos usuarios olvidan fechas de pago o no ven un solo canal (p. ej., correo). Un esquema adaptativo, que prioriza el canal con mejor respuesta por usuario, podría elevar la puntualidad y reducir intereses moratorios. |
| **What** | Activar una regla que envíe recordatorios 5/2/1 días antes del vencimiento y el mismo día. Se probarán combinaciones (solo email vs. email+SMS+push) con asignación aleatoria por usuario. |
| **Hypothesis** | Los usuarios expuestos a recordatorios multicanal adaptativos incrementarán su **on-time payment rate** en **≥12 p.p.** y reducirán pagos atrasados en **≥20%** durante 4 semanas. |

---

#### Experimento 2: Onboarding simplificado y validación en vivo
| Campo | Detalle |
|---|---|
| **Question** | ¿Simplificar el onboarding (formularios progresivos + validación en vivo) reduce el abandono inicial? |
| **Why** | Formularios largos y validaciones tardías generan fricción y abandono en el registro. Dividir en pasos cortos y validar en tiempo real debería disminuir errores y fricción cognitiva. |
| **What** | Reemplazar el formulario único por 3 pasos (cuenta → perfil → primer objetivo de deuda) con validación inline y autocompletado de bancos comunes. A/B test contra la versión actual. |
| **Hypothesis** | El **completion rate** de onboarding aumentará **≥15 p.p.** y el **tiempo a completar** se reducirá **≥25%** en nuevos usuarios durante 2 semanas. |

---

#### Experimento 3: Asistente de configuración de pagos (“¿qué pasa si…?”)
| Campo | Detalle |
|---|---|
| **Question** | ¿Un asistente de configuración de pagos reduce pagos omitidos en el primer mes? |
| **Why** | Usuarios indecisos sobre montos/frecuencias terminan sin programar pagos o configurándolos mal. Un asistente que simule escenarios puede dar claridad y compromiso. |
| **What** | Desplegar un wizard con simulación de fechas, montos y proyección de intereses; al final, crear la regla de pago recurrente en un click. Cohorte treatment vs. control sin asistente. |
| **Hypothesis** | La **tasa de usuarios con pago recurrente activo** subirá **≥18 p.p.** y los **pagos omitidos en el primer ciclo** bajarán **≥25%**. |

---

#### Experimento 4: Checkout directo para planes (Básico/Premium)
| Campo | Detalle |
|---|---|
| **Question** | ¿Un checkout directo para planes mejora la conversión de visitantes a suscriptores? |
| **Why** | Pasos intermedios (redirecciones, confirmaciones redundantes) elevan la caída en compra. Un checkout embebido, con menos campos y medios locales, puede convertir mejor. |
| **What** | Implementar un **checkout en una sola vista** con guardado de tarjeta y medios locales; medir conversión desde el landing y desde paywall in-app. |
| **Hypothesis** | La **plan conversion rate** aumentará **≥20%** y el **abandono del checkout** disminuirá **≥30%** en 3 semanas. |

---

#### Experimento 5: Recomendaciones educativas contextuales
| Campo | Detalle |
|---|---|
| **Question** | ¿Las recomendaciones educativas contextuales elevan el uso semanal y disminuyen impagos? |
| **Why** | Micro-contenidos en el momento de la decisión (p. ej., antes de configurar un pago) pueden mejorar comprensión y hábitos, impactando uso y puntualidad. |
| **What** | Mostrar cápsulas educativas (≤60s) ligadas a acciones clave (crear deuda, programar pago, revisar proyección). Medir consumo y efecto en comportamiento vs. grupo sin cápsulas. |
| **Hypothesis** | Los **WAU** crecerán **≥10%** y los **pagos atrasados** caerán **≥12%** en usuarios que consumen ≥2 cápsulas por semana. |

## 8.2. Experiment Design

El **Experiment Design** define cómo validaremos, con evidencia, que las mejoras de DebtGo impactan en los resultados que importan: puntualidad de pagos, reducción de atrasos, adopción de planes y uso sostenido de la app.  
Trabajaremos con ciclos cortos de experimentación (2–4 semanas) usando cohortes control–tratamiento, medición estandarizada y tableros de seguimiento.  
Cada experimento especifica **qué** cambiamos (intervención), **por qué** lo hacemos (racional), **cómo** lo medimos (métricas y ventanas de observación) y **cuál** es la hipótesis a contrastar.

Principios operativos:
- **Validez y comparabilidad**: asignación aleatoria cuando sea posible; mismas ventanas de medición y segmentos comparables.
- **Métricas accionables**: on-time payment rate, pagos atrasados, completion rate de onboarding, conversión a planes, WAU/MAU, consumo de cápsulas educativas, configuración de pagos recurrentes.
- **Ejecución segura**: feature flags y guardrails (p. ej., límites de envío de SMS/email, reintentos).
- **Cierre de ciclo**: decisión explícita (escalar, iterar o descartar) basada en resultados y confianza estadística.

### 8.2.1. Hypotheses.

Las hipótesis se derivan de los problemas y oportunidades priorizados (puntualidad de pagos, fricción en el onboarding, configuración de pagos, conversión de planes y educación financiera contextual). Cada tabla resume **Question, Belief, Hypothesis y Null Hypothesis**.

### Hypothesis 1: Recordatorios multicanal adaptativos

| Campo | Hypothesis |
|---|---|
| **Question** | ¿Los recordatorios multicanal adaptativos (email/SMS/push) aumentan los pagos a tiempo? |
| **Belief** | Usuarios distintos reaccionan mejor a canales distintos; combinar y adaptar por respuesta individual mejorará la puntualidad. |
| **Hypothesis** | La **on-time payment rate** del grupo con recordatorios adaptativos aumentará **≥ 12 p.p.** y los pagos atrasados caerán **≥ 20%** frente al control en 4 semanas. |
| **Null Hypothesis** | No habrá diferencias estadísticamente significativas en puntualidad ni en atrasos frente al control. |

### Hypothesis 2: Onboarding simplificado con validación en vivo

| Campo | Hypothesis |
|---|---|
| **Question** | ¿Simplificar el onboarding (pasos progresivos + validación en vivo) reduce el abandono inicial? |
| **Belief** | Menos campos por vista y feedback inmediato disminuyen la fricción cognitiva y los errores. |
| **Hypothesis** | El **completion rate** del onboarding subirá **≥ 15 p.p.** y el **tiempo a completar** bajará **≥ 25%** respecto a la versión actual. |
| **Null Hypothesis** | No se observan mejoras significativas ni en finalización ni en tiempo de completado. |

### Hypothesis 3: Asistente de configuración de pagos (“¿qué pasa si…?”)

| Campo | Hypothesis |
|---|---|
| **Question** | ¿Un asistente que simula escenarios reduce pagos omitidos en el primer mes? |
| **Belief** | Ver el impacto de montos/fechas en intereses y duración aumenta la confianza para activar pagos recurrentes. |
| **Hypothesis** | La **tasa de usuarios con pago recurrente activo** crecerá **≥ 18 p.p.** y los **pagos omitidos del primer ciclo** caerán **≥ 25%** frente al control. |
| **Null Hypothesis** | No hay cambios significativos en activación de pagos recurrentes ni en omisiones. |

### Hypothesis 4: Checkout directo de planes (Básico/Premium)

| Campo | Hypothesis |
|---|---|
| **Question** | ¿Un checkout embebido de un solo paso mejora la conversión a planes? |
| **Belief** | Reducir redirecciones y campos, y ofrecer medios locales de pago disminuye el abandono. |
| **Hypothesis** | La **plan conversion rate** aumentará **≥ 20%** y el **abandono del checkout** disminuirá **≥ 30%** vs. el flujo actual. |
| **Null Hypothesis** | La conversión y el abandono no difieren de manera significativa respecto al flujo actual. |

### Hypothesis 5: Recomendaciones educativas contextuales

| Campo | Hypothesis |
|---|---|
| **Question** | ¿Cápsulas educativas contextuales elevan el uso y reducen impagos? |
| **Belief** | Micro-contenidos en el momento de la decisión mejoran comprensión y hábitos de pago. |
| **Hypothesis** | Los **WAU** crecerán **≥ 10%** y los **pagos atrasados** bajarán **≥ 12%** en usuarios que consumen ≥ 2 cápsulas/semana frente al control. |
| **Null Hypothesis** | No hay diferencia significativa en uso semanal ni en atrasos frente al control. |

### 8.2.2. Domain Business Metrics

Esta sección alinea la medición de los experimentos con los objetivos de negocio de **DebtGo**.  
Todas las hipótesis y Experiment Cards solo pueden referirse a métricas definidas aquí.  
Cada métrica incluye **definición**, **fórmula de cálculo**, **técnica de recolección** y **meta**.  
Segmentaciones estándar: `plan` (Básico/Premium), `plataforma` (Web/Móvil), `cohorte_alta`, `país`, `edad_de_cuenta` (0–7, 8–30, 31–90 días).

**Resultados de negocio (Pagos y cartera)**

| Métrica | Definición | Fórmula | Recolección | Meta |
|---|---|---|---|---|
| **On-Time Payment Rate (OTPR)** | Porcentaje de pagos realizados en o antes de su fecha de vencimiento. | `pagos_on_time / pagos_programados` | Webhooks/procesador de pagos + cron diario que marca `on_time=true` si `fecha_pago ≤ due_date`. | **≥ 75%** (tratamiento H1). |
| **Late Payment Rate** | Porcentaje de pagos con atraso. | `pagos_atrasados / pagos_programados` | Igual que OTPR, con `fecha_pago > due_date`. | **≤ 20%**. |
| **Missed Payment Count (MPC)** | Número de pagos no realizados dentro de la ventana de gracia. | `count(pagos saltados)` en **t+7** días | Job semanal; compara `pagos_programados` vs. `pagos_realizados`. | **−25%** en H3. |
| **Average Days Past Due (DPD)** | Días promedio de atraso por pago. | `avg(max(0, fecha_pago − due_date))` | Query mensual por cohorte. | **≤ 3 días**. |
| **Interés evitado** | Intereses potenciales no incurridos por adelantar pagos o mantener al día. | `∑(tasa_diaria * saldo * días_ev)` | Simulador financiero + registros de pago. | Tendencia **↑** trimestral. |


**Adopción y activación de funcionalidades**

| Métrica | Definición | Fórmula | Recolección | Meta |
|---|---|---|---|---|
| **Recurring Payment Activation Rate (RPAR)** | Usuarios activos que habilitan pagos recurrentes. | `usuarios_con_recurrente / usuarios_activos` | Evento `payment_recurring_enabled` (Web/Móvil). | **≥ 35%** (H3). |
| **Plan Conversion Rate (PCR)** | Visitas a checkout que terminan en suscripción (Básico/Premium). | `suscripciones / sesiones_checkout` | Evento `checkout_completed`. | **+20%** vs. baseline (H4). |
| **Onboarding Completion Rate (OCR)** | Usuarios que finalizan el onboarding en ≤ 24 h. | `usuarios_onboarding_ok / usuarios_onboarding_iniciado` | Evento de paso final + temporizador. | **≥ 85%** (H2). |
| **Onboarding Time (p50/p90)** | Tiempo desde inicio hasta fin del onboarding. | `percentil(t_fin − t_inicio)` | Timestamps de pasos de onboarding. | **−25%** (H2). |

**Uso y compromiso del producto**

| Métrica | Definición | Fórmula | Recolección | Meta |
|---|---|---|---|---|
| **WAU / MAU** | Usuarios activos semanal/mensual. | Distintos `user_id` con sesión/acción en ventana. | Eventos de sesión y acciones clave. | **WAU/MAU ≥ 0.55**. |
| **Educational Capsules Consumption** | Usuarios que ven ≥2 cápsulas/semana. | `usuarios_2plus_caps / usuarios_activos` | Evento `capsule_viewed`. | **≥ 30%** (H5). |
| **Feature Adoption – “Manage Payments”** | Sesiones con uso del módulo de pagos. | `sesiones_con_manage_payments / sesiones_totales` | Evento `manage_payments_opened`. | **≥ 40%**. |

**Notificaciones y comunicación (para H1)**

| Métrica | Definición | Fórmula | Recolección | Meta |
|---|---|---|---|---|
| **Open Rate** | Aperturas sobre envíos por canal. | `aperturas / envíos` | Proveedor de email/SMS/push. | **Email ≥ 35%**, **Push ≥ 20%**, **SMS ≥ 90% entrega**. |
| **CTA Click/Deep-Link Rate** | Clics hacia “Pagar ahora” u acción objetivo. | `clics / aperturas` | UTM + deep links. | **≥ 12%**. |
| **Lift en OTPR atribuible** | Mejora de OTPR en 7 días post-recordatorio vs. control. | `OTPR_trat − OTPR_ctrl` | Experimento con cohortes. | **≥ +12 p.p.**. |

**Satisfacción y salud del servicio (guardrails)**

| Métrica | Definición | Fórmula | Recolección | Meta |
|---|---|---|---|---|
| **CSAT post-pago** | Satisfacción tras completar un pago. | Promedio escala 1–5 | Encuesta in-app tras pago. | **≥ 4.4**. |
| **Crash-Free Sessions (Móvil)** | Sesiones sin crash / sesiones totales. | `1 − (crashes / sesiones)` | SDK de errores. | **≥ 99.5%**. |
| **Latency p95 – API pagos** | p95 de `POST /payments` end-to-end. | Medición APM | Instrumentación backend. | **≤ 600 ms**. |
| **Error Rate – API** | 5xx / requests. | `errores_5xx / requests` | Logs + APM | **≤ 0.3%**. |

**Mapeo hipótesis ↔ métricas**

| Hypothesis | Métricas primarias | Métricas secundarias |
|---|---|---|
| **H1** Recordatorios adaptativos | OTPR, Late Payment Rate, Lift en OTPR | Open/Click Rate, DPD |
| **H2** Onboarding simplificado | OCR, Onboarding Time p50/p90 | WAU/MAU (primer mes) |
| **H3** Asistente de configuración | RPAR, Missed Payment Count | Late Payment Rate, DPD |
| **H4** Checkout de un paso | PCR, Abandono de checkout | WAU/MAU, CSAT post-pago |
| **H5** Educación contextual | WAU, Consumo de cápsulas | Late Payment Rate, Interés evitado |

**Notas de implementación**

- **Granularidad**: diario para pagos/alertas; semanal para adopción/uso; mensual para impacto financiero.  
- **Privacidad**: anonimización de `user_id` en analítica; opt-in de notificaciones; retención de datos según política.  
- **Éxito de experimento**: diferencia mínima detectable (MDE) y nivel de significancia definidos por experimento; detener si se violan guardrails (latencia, error rate o quejas).

### 8.2.3. Measures.

Para evaluar si las hipótesis de **DebtGo** se cumplen, definimos métricas que miden de forma objetiva el impacto del producto sobre adopción, retención, conversión y salud financiera del usuario. Todas las métricas se calculan con datos del backend (servicios `auth`, `user`, `payment`, `debt`, `notifications`, `education`, `consultant`) y con eventos de frontend enviados a Analytics.

**Métricas primarias**

- **Tasa de conversión a plan (CVR Plan)**  
  **Fórmula:** usuarios que pagan un plan / usuarios que visitan *Select a plan*.  
  **Fuente:** `payment` + eventos `plan_view`, `plan_purchase`.

- **Tiempo de onboarding hasta primer valor (TTV)**  
  **Definición:** minutos desde primer login hasta completar el tutorial y registrar la primera deuda o presupuesto.  
  **Fuente:** `auth`, eventos `tutorial_completed`, `debt_created`, `budget_created`.

- **Pago a tiempo (On-Time Payment Rate)**  
  **Fórmula:** pagos realizados ≤ fecha de vencimiento / total de pagos con vencimiento en el período.  
  **Fuente:** `payments(due_date, paid_at)`.

- **Retención a 7/30 días (D7/D30)**  
  **Fórmula:** usuarios activos día 7/30 con al menos 1 evento clave (pago, simulación, avance de curso) / usuarios instalados.  
  **Fuente:** `activity_log`.

- **Exactitud percibida del simulador**  
  **Definición:** puntuación (1–5) en encuesta in-app sobre claridad y utilidad del resultado.  
  **Fuente:** `education/surveys`.

**Métricas secundarias**

- **Engagement con recordatorios**  
  **Definición:** tasa de apertura/click de notificaciones (push, email, SMS) y % de usuarios que ajustan preferencias.  
  **Fuente:** `notifications(sent, opened, clicked, settings_updated)`.

- **Tiempo de resolución de incidencias de pago**  
  **Fórmula:** horas desde `payment_failed` hasta `payment_resolved`.  
  **Fuente:** `payments`, `support_tickets` (si aplica).

- **Progreso en educación financiera**  
  **Definición:** % de cursos iniciados/completados, lecciones vistas por sesión, nota de evaluación final.  
  **Fuente:** `education`.

- **Actividad en consultoría**  
  **Definición:** mensajes por usuario/semana, servicios publicados, ratio *contacto → cita*.  
  **Fuente:** `consultant`, `messages`, `services`.

- **Satisfacción general (CSAT/NPS interno)**  
  **Definición:** encuesta post-acción (pago, simulación, compra de plan) con escala 1–5 y pregunta NPS.  
  **Fuente:** `surveys`.


**Medidas por pregunta de experimento**

**Measure 1 — ¿Reducirá el tiempo de onboarding un tutorial interactivo?**

| Campo       | Definición                                                                                                                                                                     |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Question**| ¿Reducirá el tiempo de onboarding un tutorial interactivo?                                                                                                                     |
| **Measure** | Medir **TTV** desde primer login hasta (a) `tutorial_completed` y (b) primera acción de valor (`debt_created` o `budget_created`). Comparar medianas antes/después (A/B) y tasa de abandono del tutorial. |


**Measure 2 — ¿Mejorará la utilidad del simulador de deudas para planificar pagos?**

| Campo       | Definición                                                                                                                                             |
|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Question**| ¿Mejorará la utilidad del simulador de deudas para planificar pagos?                                                                                   |
| **Measure** | Trackear sesiones de simulación por usuario, % que guardan un plan (`plan_saved`) y **exactitud percibida** (encuesta 1–5). Éxito si ↑ plan guardado ≥ 20% y puntuación media ≥ 4.0. |


**Measure 3 — ¿Disminuirán los pagos tardíos con preferencias de notificación claras?**

| Campo       | Definición                                                                                                                                                       |
|-------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Question**| ¿Disminuirán los pagos tardíos con preferencias de notificación claras?                                                                                          |
| **Measure** | Comparar **On-Time Payment Rate** entre usuarios con preferencias configuradas (`notif_settings_on`) vs. control. Medir apertura/click y conversión *recordatorio → pago*. Meta: +10 pp en pagos a tiempo. |

**Measure 4 — ¿Aumentará la conversión mostrando comparación simple de planes?**

| Campo       | Definición                                                                                                                          |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------|
| **Question**| ¿Aumentará la conversión mostrando comparación simple de planes?                                                                     |
| **Measure** | Medir **CVR Plan** y tiempo en la vista de comparación. Éxito si CVR aumenta ≥ 15% y reembolsos no aumentan. Segmentar por dispositivo (web vs. mobile). |

**Measure 5 — ¿Incrementará el engagement permitir perfilar consultores y mensajería?**

| Campo       | Definición                                                                                                                                      |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Question**| ¿Incrementará el engagement permitir perfilar consultores y mensajería?                                                                          |
| **Measure** | Medir mensajes enviados/usuario, servicios publicados y ratio *primer mensaje → cita*. Meta: +25% mensajes y ≥ 10% *mensaje→cita*. CSAT post-conversación ≥ 4/5. |

**Recolección y validez**

- **Recolección:** eventos front (Web/Mobile) → Analytics; métricas de negocio desde servicios (`payments`, `debt`, `notifications`, `education`, `consultant`) consolidadas en un *warehouse* o vistas materializadas.  
- **Ventana de análisis:** semanal para indicadores operativos; quincenal/mensual para conversión y retención.  
- **Segmentación mínima:** dispositivo (web/mobile), plan (free/premium), cohortes por semana de alta.  
- **Criterios de éxito:** mejoras estadísticamente significativas (p < 0.05) o con efecto práctico definido en cada medida.

### 8.2.4. Conditions.

Para garantizar comparaciones válidas en los experimentos de **DebtGo**, definimos las siguientes condiciones generales y, luego, condiciones específicas por pregunta.

**Condiciones experimentales (generales)**
- **Grupo experimental:** cohorte de usuarios nuevos o existentes expuestos a la variante de producto (tutorial interactivo, simulador mejorado, preferencias de notificaciones, comparador de planes, perfil de consultores + mensajería). Se registran uso, conversión y encuestas durante una ventana definida (2–4 semanas).

**Condiciones de control (generales)**
- **Grupo de control:** cohorte comparable que usa la versión actual sin el cambio. Mantiene la misma ventana temporal y segmentación (web vs. mobile, plan, país).

**Condiciones controladas (constantes)**
- Mismo período de análisis por cohorte, mismas campañas y precios.
- Misma definición de eventos y fuentes de datos.
- Segmentación mínima: dispositivo (web/mobile), plan (free/premium), cohorte de alta semanal.

**Conditions — Q1: ¿Reducirá el tiempo de onboarding un tutorial interactivo?**

| Campo                    | Definición                                                                                                  |
|--------------------------|--------------------------------------------------------------------------------------------------------------|
| **Question**             | ¿Reducirá el tiempo de onboarding un tutorial interactivo?                                                  |
| **Condición Experimental** | Habilitar tutorial paso a paso en el primer login. **Éxito si** la mediana de **TTV** baja ≥ **25%** y la tasa de abandono del onboarding disminuye ≥ **15%**. |
| **Condición de Control** | Onboarding actual sin tutorial interactivo. TTV y abandono se mantienen en los valores de línea base.       |

**Conditions — Q2: ¿Mejorará la utilidad del simulador de deudas para planificar pagos?**

| Campo                    | Definición                                                                                                              |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------|
| **Question**             | ¿Mejorará la utilidad del simulador de deudas para planificar pagos?                                                    |
| **Condición Experimental** | Desplegar simulador con escenarios guardables y explicación de resultados. **Éxito si** ↑ de ≥ **20%** en `plan_saved` y **≥ 4.0/5** en exactitud percibida. |
| **Condición de Control** | Simulador actual o inexistente. Tasas de guardado y puntuación de utilidad permanecen en línea base.                    |

**Conditions — Q3: ¿Disminuirán los pagos tardíos con preferencias de notificación claras?**

| Campo                    | Definición                                                                                                                         |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| **Question**             | ¿Disminuirán los pagos tardíos con preferencias de notificación claras?                                                            |
| **Condición Experimental** | Mostrar centro de preferencias (canal y frecuencia) y recordatorios escalonados (−5d, −1d, día 0). **Éxito si** **On-Time Payment Rate** sube **≥ 10 pp** y apertura/click ≥ **25%/8%**. |
| **Condición de Control** | Recordatorios por defecto, sin configuración visible. On-Time se mantiene en línea base.                                           |

**Conditions — Q4: ¿Aumentará la conversión mostrando comparación simple de planes?**

| Campo                    | Definición                                                                                                       |
|--------------------------|-------------------------------------------------------------------------------------------------------------------|
| **Question**             | ¿Aumentará la conversión mostrando comparación simple de planes?                                                  |
| **Condición Experimental** | Incluir tabla comparativa y CTA persistente en *Select a plan*. **Éxito si** **CVR Plan** aumenta **≥ 15%** y el ratio de reembolso no sube. |
| **Condición de Control** | Pantalla de planes sin comparador. CVR se mantiene en línea base.                                                |

**Conditions — Q5: ¿Incrementará el engagement permitir perfilar consultores y mensajería?**

| Campo                    | Definición                                                                                                               |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------|
| **Question**             | ¿Incrementará el engagement permitir perfilar consultores y mensajería?                                                   |
| **Condición Experimental** | Habilitar perfiles de consultor, envío de mensaje y publicación de servicios. **Éxito si** mensajes/usuario **+25%** y ratio *mensaje→cita* **≥ 10%**, con **CSAT ≥ 4/5**. |
| **Condición de Control** | Sin perfil detallado ni mensajería directa. Volumen de mensajes y conversión se mantienen en línea base.                 |

### 8.2.5. Scale Calculations and Decisions.

Para que los resultados sean comparables y accionables, fijamos parámetros estadísticos y umbrales de decisión por hipótesis. Estas reglas se aplicarán a todos los experimentos A/B y pruebas controladas de DebtGo.

**Parámetros estadísticos**

- **Nivel de significancia (α):** 0.05 (confianza 95%).  
- **Potencia estadística (1−β):** 0.8–0.85 para detectar efectos mínimos con probabilidad alta.  
- **Efecto mínimo detectable (MDE):** definido por hipótesis:
  - **Pagos a tiempo:** +15 p.p. en tasa de pagos puntuales.
  - **Onboarding del Asesor de Presupuesto:** −30% en tiempo a completar el primer presupuesto.
  - **Añadir Deuda (UX):** +20 p.p. en tasa de éxito sin error y −40% en errores de validación.
  - **Consultorías financieras:** −25% en tiempo de respuesta y +10 p.p. en conversión a reserva.
  - **Educación financiera:** +20 p.p. en finalización de curso a 30 días.
- **Tamaño de muestra (guía):** determinado por *power analysis* por métrica; como referencia operativa, al menos **n≥60 usuarios por grupo** (control/experimento) para métricas de conversión por sesión y **≥200 eventos** por variante para tiempos/errores.


**Matriz de decisiones por hipótesis**

| **Scale Calculation / Métrica primaria** | **Decisión propuesta** | **Desfavorable** | **Aceptable** | **Ideal** | **Excelente** |
|---|---|---:|---:|---:|---:|
| **H1 – Recordatorios inteligentes de pago**  \> Métrica: **% Pagos a tiempo (On-Time Payment Rate)**; guardas: no aumentar opt-outs ni quejas. | Desplegar **multi-canal** (push/email/SMS) con A/B de cadencia y ventana “antes del vencimiento”. | Δ < +5 p.p. | +5 a +10 p.p. | +10 a +15 p.p. | **> +15 p.p.** sin incremento de opt-out/soporte |
| **H2 – Onboarding del Asesor de Presupuesto**  \> Métricas: **Tiempo al 1er presupuesto** y **% que completan onboarding**. | Implementar **stepper + tooltips + plantillas** y precarga de categorías. | Reducción < 15% o finalización < +5 p.p. | Reducción 15–25% | Reducción 25–30% | **Reducción > 30%** y finalización **> +10 p.p.** |
| **H3 – UX “Añadir nueva deuda”**  \> Métricas: **Task-Success Rate**, **Error Rate** y **Tiempo de tarea**. | Añadir **autocompletado** (emisor/tasa), validaciones in-line y ayuda contextual. | Éxito < +10 p.p. o errores −<20% | Éxito +10–15 p.p. | Éxito +15–20 p.p. y errores −30–40% | **Éxito > +20 p.p.**, **errores −>40%**, tiempo −>25% |
| **H4 – Marketplace y chat con consultores**  \> Métricas: **Mediana de tiempo de respuesta** y **% chats→reserva**. | Publicar **listado + chat** con disponibilidad y mensaje inicial guiado. | Resp. −<10% o conv. +<3 p.p. | Resp. −10–20% o conv. +3–6 p.p. | Resp. −20–25% y conv. +6–10 p.p. | **Resp. −>25%** y **conv. +>10 p.p.** |
| **H5 – Centro de Educación (gamificación)**  \> Métricas: **Finalización a 30 días** y **Re-engagement semanal**. | Activar **progreso visible**, logros y recordatorios de módulo. | Finalización +<8 p.p. | +8–15 p.p. | +15–20 p.p. | **> +20 p.p.** y re-engagement +>10 p.p. |

### 8.2.6. Methods Selection.

Esta sección define **cómo** investigaremos cada hipótesis de DebtGo siguiendo el principio **Simplest Useful Thing (SUT)**: el método más simple que aún sea suficiente para alcanzar el tamaño de muestra y las condiciones de validez requeridas.  
Diferenciamos **objeto de investigación** (la pregunta/hipótesis) del **método** (técnica para medirla).  
Normas operativas:
- No se ejecutan **experimentos simultáneos** sobre el mismo tema que expongan a la misma persona a múltiples variantes.
- Toda medición respeta principios éticos: **consentimiento informado** en pruebas moderadas, anonimización de datos y no causar daño (p. ej., no enviar recordatorios invasivos).

**Matriz de selección de métodos (SUT)**

| Id | Objeto de investigación (Hipótesis) | Método principal (SUT) | Asignación | Tamaño de muestra (meta) | Duración típica | Fuentes de datos | Métricas guardas |
|---|---|---|---|---|---|---|---|
| **H1** | Recordatorios inteligentes aumentan la **tasa de pagos a tiempo** | **A/B** de cadencia/canal de recordatorio (push/email/SMS) | Random 50/50 por usuario | ≥ 60 usuarios por grupo | 14 días (1 ciclo de vencimientos) | Eventos app/web (PostHog/GA4), logs de pagos (API) | Opt-out de notificaciones, tickets de soporte |
| **H2** | Onboarding guiado reduce el **tiempo al 1er presupuesto** | **A/B** de onboarding (stepper + plantillas vs. actual) | Random al primer inicio | ≥ 60 por grupo | 7–14 días | Telemetría de funnel, tiempos de tarea | Crash-free sessions, tasa de abandono del onboarding |
| **H3** | Mejoras UX en **Añadir deuda** aumentan tasa de éxito y reducen errores | **Prueba de usabilidad moderada** (5–8 usuarios) + **A/B** en producción de validaciones in-line | Convenience en test; Random en prod | Usab.: 5–8 por ronda; Prod: ≥ 60 por grupo | Usab.: 1–2 días; Prod: 14 días | Grabaciones de sesión (con consentimiento), eventos de errores de formulario | Error rate global del módulo, tiempo de respuesta del backend |
| **H4** | Marketplace + chat con consultores reduce **tiempo de respuesta** y aumenta **conversión a reserva** | **Rollout controlado** (feature flag) con **cuasi-experimento** (control vs. habilitado) | Por cohortes (región/antigüedad) | ≥ 80 control, 80 tratamiento | 14–21 días | Métricas de mensajería, reservas | SLA de respuesta del consultor, satisfacción post-chat |
| **H5** | Gamificación en **Educación financiera** aumenta **finalización a 30 días** | **A/B** de insignias/progreso + recordatorios | Random 50/50 | ≥ 60 por grupo | 30 días | Progreso de cursos, re-engagement semanal | Reportes de abuso/opt-out, carga de soporte |

**Criterio práctico:** elegir siempre el método más simple que logre el poder estadístico objetivo (α=0.05, 1−β≈0.8). Escalar a métodos más complejos (multi-variante, tests secuenciales) solo si el SUT no alcanza el MDE definido en 8.2.5 o si hay interferencias entre variantes.

### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection.

Para que cada experimento tenga impacto comprobable, definimos objetivos de analítica y un set mínimo de **KPIs/métricas** alineadas al dominio de DebtGo (gestión de deudas, educación y consultoría). Solo estas métricas podrán referenciarse en Experiment Cards y Measures.

**Objetivos de analítica**

- **Adopción y activación:** medir el *happy path* web (registro → plan → pago → primera deuda creada).
- **Salud financiera y cumplimiento:** seguimiento de configuraciones, recordatorios, puntualidad y moras.
- **Engagement educativo:** uso y finalización de cursos del Centro de Educación Financiera.
- **Eficiencia de consultoría:** uso del workspace (mensajería, reservas, publicaciones) y sus resultados.
- **Calidad de experiencia:** satisfacción, errores y performance percibida para priorizar mejoras.

**KPIs principales (tablero ejecutivo)**

| KPI | Definición | Fórmula / Cálculo | Fuente de datos | Frecuencia | Meta inicial |
|---|---|---|---|---|---|
| **Activation Rate (TTV ≤24h)** | % que alcanza valor en ≤24h (plan elegido + pago exitoso + 1ª deuda creada). | `Usuarios con plan+checkout+debt ≤24h ÷ Nuevos registros` | Eventos web (`/register_success`, `/plan_selected`, `/checkout_success`, `/debt_created`) | Diario / Semanal | ≥ 35% |
| **On-Time Payment Rate (OTPR)** | Pagos en o antes de la fecha objetivo. | `Pagos on_time ÷ Pagos programados` | `PaymentController` + eventos `/payment_due`, `/payment_made` | Semanal / Mensual | ≥ 75% |
| **Reminder CTR** | Efectividad de recordatorios. | `Clicks en recordatorio ÷ Recordatorios enviados` | `/notif_sent`, `/notif_click` | Semanal | ≥ 12% |
| **Course Completion Rate** | Finalización de cursos iniciados. | `Cursos completados ÷ Cursos iniciados` | `EducationController` + `/course_start`, `/course_complete` | Mensual | ≥ 40% |
| **Consultation Booking Rate** | Conversiones tras ver servicios. | `Usuarios con booking ÷ Visitantes de servicios` | `Consultant*Controller` + `/service_view`, `/booking_created` | Mensual | ≥ 8% |
| **DAU/MAU** | Profundidad de uso mensual. | `DAU promedio mes ÷ MAU` | Sesiones autenticadas web | Diario / Mensual | ≥ 0.22 |
| **NPS** | Disposición a recomendar. | `%Promotores − %Detractores` | Encuesta in-app | Mensual / Trimestral | ≥ +25 |

**Métricas de producto (operativas)**

| Métrica | Definición | Cálculo / Nota | Fuente |
|---|---|---|---|
| **Signup→Plan Conversion** | % de registros que eligen plan. | `/register_success → /plan_selected` | Front web |
| **Plan→Checkout Success** | % que finaliza pago. | `/plan_selected → /checkout_success` | `PaymentController` |
| **Tiempo a 1ª Deuda** | Minutos hasta primer `/debt_created` (P50/P90). | `t(debt_created) − t(register)` | Front + `DebtController` |
| **Payment Config Adoption** | % con ≥1 configuración activa. | `Usuarios con payment_config > 0` | `PaymentController` |
| **Missed Payment Rate** | % de pagos vencidos. | `Pagos late ÷ Programados` | `PaymentController` |
| **Reattempt Recovery ≤7d** | % de pagos tardíos recuperados ≤7 días. | `Late luego pagado ≤7d ÷ Late` | `PaymentController` |
| **Education Progress** | Avance promedio por curso. | `Lecciones completadas ÷ Totales` | `EducationController` |
| **Messaging Responsiveness** | Mediana de tiempo de respuesta. | `t(respuesta) − t(mensaje)` | `ConsultantRequestController` |
| **Service Post → Booking** | % de publicaciones con reserva. | `booking_created ÷ service_posted` | `Consultant*Controller` |

**Métricas de calidad y riesgo**

| Métrica | Definición | Umbral / Meta | Fuente |
|---|---|---|---|
| **Error Rate 5xx** | Errores servidor por 1 000 req. | ≤ 1 / 1000 | Logs/API |
| **Latency p95** | p95 respuesta en endpoints críticos. | ≤ 500 ms | APM/Logs |
| **Checkout Failure** | % de intentos de pago fallidos. | ≤ 2% | `PaymentController` |
| **Form Abandon Rate** | Abandono en login/registro/checkout. | Tendencia a la baja semanal | Front web |
| **CSAT Post-Task** | Satisfacción tras tarea clave (1–5). | ≥ 4.3/5 | Encuesta in-app |

**Relación con hipótesis y experimentos**

- **H1 – Activación mejora con UX guiada y planes claros:** Activation Rate, *Signup→Plan* y *Plan→Checkout*.
- **H2 – Recordatorios aumentan puntualidad:** OTPR, Reminder CTR y Reattempt Recovery.
- **H3 – Educación incrementa cumplimiento:** Course Completion Rate y variación de OTPR por cohorte “curso completado”.
- **H4 – Consultoría mejora resultados:** Booking Rate, Messaging Responsiveness y cambio de OTPR vs. cohorte sin consultoría.
- **H5 – Workspace web incrementa engagement:** DAU/MAU, Tiempo a 1ª Deuda y Payment Config Adoption.


### 8.2.8. Web and Mobile Tracking Plan.

**Objetivo.** Establecer un plan integral de tracking para web y móvil que permita medir con precisión la adopción, el cumplimiento de pagos, el avance educativo y la efectividad de consultoría en DebtGo. El plan define qué eventos capturar, cómo etiquetarlos, dónde almacenarlos y cómo analizarlos para guiar decisiones de producto.

**Fases del monitoreo**

**1) Implementación inicial (línea base)**

- **Instrumentación mínima viable (MVP de analítica):**
  - Autenticación y registro: `register_success`, `login_success`, `logout`.
  - Activación: `plan_selected`, `checkout_success`, `debt_created`.
  - Cumplimiento: `payment_config_created`, `payment_due`, `payment_made`, `payment_late`.
  - Educación: `course_start`, `lesson_complete`, `course_complete`.
  - Consultoría: `service_view`, `service_posted`, `booking_created`, `message_sent`.
  - Notificaciones: `notif_sent`, `notif_click`.
- **Línea base:** recolectar 2–4 semanas de datos previos a cambios relevantes (nuevos planes, recordatorios, flujos de pago) para comparar contra el estado posterior.

**2) Seguimiento continuo (iteración y mejora)**

- **Monitoreo en tiempo real:** dashboards operativos (DAU/MAU, funnel de activación, OTPR, abandono de checkout, tiempos a primer valor).
- **Segmentación analítica:** por dispositivo (web/móvil), plan (Basic/Premium), cohorte de alta, origen de tráfico, y rol (usuario/consultor).
- **Ciclos de revisión:** 
  - Diario: salud operativa (errores 5xx, latencia p95, fallos de checkout).
  - Semanal: KPIs de producto (Activation Rate, OTPR, Course Completion, Booking Rate).
  - Mensual: KPIs ejecutivos y NPS.

**Especificación de eventos y propiedades**

**Convención de nombres:** `snake_case`, verbo_en_pasado + objeto.  
**Contexto común (todas las plataformas):**
- `user_id` (hash), `session_id`, `platform` (`web|android|ios`), `app_version`, `locale`, `tz`, `ts`.
- `utm_source|utm_medium|utm_campaign` (si aplica).

**Eventos clave y payload recomendado:**

- `register_success` → `{ method, country, referral }`
- `plan_selected` → `{ plan_id, plan_name, price_pen, currency }`
- `checkout_success` → `{ plan_id, amount, provider, txn_id, status }`
- `debt_created` → `{ debt_id, category, amount, interest_rate, due_day }`
- `payment_config_created` → `{ config_id, frequency, amount, channel }`
- `payment_due` → `{ debt_id, due_date, amount }`
- `payment_made` → `{ debt_id, amount, method, on_time: boolean, days_delta }`
- `payment_late` → `{ debt_id, days_late, amount }`
- `notif_sent` / `notif_click` → `{ template, channel, topic }`
- `course_start` / `lesson_complete` / `course_complete` → `{ course_id, lesson_id, progress_pct }`
- `service_view` / `service_posted` → `{ service_id, price, category }`
- `booking_created` → `{ service_id, consultant_id, scheduled_at }`
- `message_sent` → `{ thread_id, from_role, has_attachment }`

**Embudos (funnels) obligatorios:**
1. **Activación:** `register_success → plan_selected → checkout_success → debt_created`
2. **Cumplimiento:** `payment_due → notif_sent/notif_click → payment_made`
3. **Educación:** `course_start → lesson_complete (≥70%) → course_complete`
4. **Consultoría:** `service_view → booking_created → message_sent`


**Métricas y tableros derivados**

- **Activation Rate (≤24h):** % que completa `checkout_success` y `debt_created` en 24h.
- **OTPR (On-Time Payment Rate):** `on_time / programados`.
- **Reattempt Recovery ≤7d:** pagos tardíos recuperados dentro de 7 días.
- **Course Completion Rate:** `course_complete / course_start`.
- **Consultation Booking Rate:** `booking_created / service_view`.
- **DAU/MAU**, **Abandono en Checkout**, **Tiempo a 1ª Deuda** (P50/P90).
- **Calidad técnica:** errores 5xx por 1 000 req, latencia p95 endpoints de `Auth`, `Payment`, `Debt`.

Cada tablero mostrará valores **por cohorte** (semana de registro) y **por plataforma** (web vs móvil).

**Arquitectura de datos (alto nivel)**

1. **Ingesta:** SDK web/móvil → colector (evento HTTP) → cola.
2. **Procesamiento:** normalización + enriquecimiento (UTM, geolight) → almacén (Data Warehouse).
3. **Modelos de métricas:** tablas derivadas por funnel y por cohorte.
4. **Visualización:** dashboards operativos y ejecutivos (tiempo real y acumulados).
5. **Gobernanza:** catálogo de eventos, control de cambios y revisión quincenal.

**Privacidad, seguridad y cumplimiento**

- **Principio de minimización:** no capturar PII sensible (números completos de tarjeta, documentos). 
- **Pseudonimización:** `user_id` hash; en pagos, solo metadatos no sensibles.
- **Consentimiento:** banner de cookies/tracking y centro de preferencias.
- **Retención:** eventos crudos 12 meses; agregados históricos 24+ meses.
- **Accesos:** solo lectura para analistas; segregación por rol.

**Criterios de calidad del tracking**

- **Cobertura:** ≥ 95% de sesiones con `session_id`.
- **Pérdida de eventos:** < 1% por lote.
- **Desfase máximo:** < 5 min (tiempo real) / < 24 h (batch).
- **Paridad web/móvil:** definiciones y payloads equivalentes.


## 8.3. Experimentation

En esta sección presentamos cómo validaremos la propuesta de valor de **DebtGo** mediante experimentos guiados por historias **To-Be**. Las historias se diseñan a partir del Project Statement y de las interfaces Web/Mobile compartidas (registro/login, planes de pago, onboarding, gestión de deudas y pagos, educación financiera, notificaciones, mensajería y “workspace” de consultores).
El objetivo es iterar rápido sobre lo esencial: **adopción**, **activación**, **retención** y **percepción de valor**(reducción de fricción para registrar deudas, configurar pagos y acceder a educación/asesoría). Cada historia incluye criterios de aceptación en estilo Gherkin para poder instrumentar pruebas y telemetría.

### 8.3.1. To-Be User Stories.

Convención de épicas:
**EP01** Autenticación y Cuenta • **EP02** Suscripción y Cobros • **EP03** Deudas y Pagos • **EP04** Educación Financiera • **EP05** Workspace del Consultor • **EP06** Mensajería/Reseñas • **EP07** Notificaciones

**Conjunto A — Usuario (ahorrista/deudor)**

| **User Story ID** | **Título** | **Descripción (Como / Quiero / Para)** | **Criterios de Aceptación (resumen Gherkin)** | **Epic** |
|---|---|---|---|---|
| UA01 | Registro e inicio de sesión simple | **Como** usuario nuevo, **quiero** registrarme y loguearme con validaciones mínimas y “remember me”, **para** empezar a usar DebtGo sin fricción. | **Given** estoy en `/register` **When** ingreso nombre, email, rol y contraseña válida **Then** veo confirmación y puedo **Log in**. **Given** marco “Remember me” **Then** la sesión persiste al volver. | EP01 |
| UA02 | Selección de plan y checkout | **Como** usuario, **quiero** elegir plan (Básico/Premium) y completar checkout, **para** activar funciones avanzadas. | **Given** elijo “Basic” o “Premium” **When** completo tarjeta y email **Then** el pago se valida y el plan queda **activo**; **And** recibo comprobante. | EP02 |
| UA03 | Onboarding de deudas | **Como** usuario, **quiero** registrar una nueva deuda (monto, tasa, pago mínimo, notas), **para** ver mi proyección y próximos pagos. | **Given** “Add New Debt” **When** completo campos obligatorios **Then** la deuda aparece en “Upcoming Payments” y en el progreso de deuda. | EP03 |
| UA04 | Configurar pagos recurrentes | **Como** usuario, **quiero** crear configuraciones de pago (monto, frecuencia, deuda objetivo), **para** automatizar mi planificación mensual. | **Given** “Manage Payments” **When** agrego configuración válida **Then** se guarda con frecuencia “Monthly”; **And** se recalculan proyecciones. | EP03 |
| UA05 | Preferencias de notificación | **Como** usuario, **quiero** activar/desactivar recordatorios y canales (email/SMS/push), **para** recibir solo alertas útiles. | **Given** “Notification Preferences” **When** guardo toggles **Then** veo “Your preferences have been saved successfully” **And** los eventos futuros usan esos canales. | EP07 |
| UA06 | Centro de educación financiera | **Como** usuario, **quiero** acceder a cursos con progreso, **para** mejorar mis hábitos y puntaje crediticio. | **Given** Education Center **When** entro a un curso **Then** veo temario y botón “Start/Continue”; **And** el porcentaje progresa tras completar lecciones. | EP04 |

**Conjunto B — Consultor Financiero**

| **User Story ID** | **Título** | **Descripción (Como / Quiero / Para)** | **Criterios de Aceptación (resumen Gherkin)** | **Epic** |
|---|---|---|---|---|
| UC01 | Perfil y Workspace del consultor | **Como** consultor, **quiero** ver y editar mi perfil y horario, **para** presentarme profesionalmente. | **Given** “Profile” **When** edito nombre/horario/avatar **Then** los cambios persisten y se reflejan en “My Workspace”. | EP05 |
| UC02 | Publicar servicios | **Como** consultor, **quiero** publicar servicios con título, descripción, precio y archivos, **para** ofrecer asesorías. | **Given** “Post new service” **When** envío un formulario válido **Then** el servicio aparece en el catálogo del consultor. | EP05 |
| UC03 | Mensajería con clientes | **Como** consultor, **quiero** conversar con mis clientes y adjuntar archivos, **para** dar seguimiento a casos. | **Given** “Messages” **When** envío un mensaje **Then** se visualiza en el hilo y el cliente recibe notificación; **And** puedo abrir “Case history”. | EP06 |
| UC04 | Métricas básicas del consultor | **Como** consultor, **quiero** ver métricas simples (contactos, reservas, ingresos estimados), **para** priorizar mis esfuerzos. | **Given** “Metrics” **When** accedo **Then** veo tarjetas con tendencias del último mes; **And** filtros por rango temporal. | EP05 |

**Conjunto C — Sistema / Seguridad**

| **User Story ID** | **Título** | **Descripción (Como / Quiero / Para)** | **Criterios de Aceptación (resumen Gherkin)** | **Epic** |
|---|---|---|---|---|
| SYS01 | Recuperación de contraseña | **Como** usuario, **quiero** recuperar mi contraseña, **para** volver a ingresar si la olvidé. | **Given** “Forgot password?” **When** envío mi email **Then** recibo enlace de reset válido por tiempo limitado. | EP01 |
| SYS02 | Eliminación de cuenta | **Como** usuario, **quiero** borrar mi cuenta desde el perfil, **para** controlar mis datos personales. | **Given** “Delete Account” **When** confirmo **Then** la cuenta se anonimiza y se revocan tokens/suscripciones. | EP01/EP02 |


### 8.3.2. To-Be Product Backlog

Escala de **Story Points**: 1 (muy pequeño), 2 (pequeño), 3 (mediano), 5 (grande).

| **Orden** | **User Story ID** | **Título** | **Descripción (Como / Quiero / Para)** | **Story Points** |
|---:|:---:|---|---|:---:|
| 1 | UA01 | Registro e inicio de sesión simple | **Como** usuario nuevo, **quiero** registrarme y loguearme con “remember me”, **para** empezar a usar DebtGo sin fricción. | 3 |
| 2 | UA02 | Selección de plan y checkout | **Como** usuario, **quiero** elegir plan (Básico/Premium) y pagar, **para** activar funciones avanzadas. | 5 |
| 3 | UA03 | Onboarding de deudas | **Como** usuario, **quiero** registrar una nueva deuda (monto, tasa, pago mínimo), **para** ver proyecciones y próximos pagos. | 5 |
| 4 | UA04 | Configurar pagos recurrentes | **Como** usuario, **quiero** crear configuraciones de pago (monto y frecuencia), **para** automatizar mi planificación mensual. | 5 |
| 5 | UA05 | Preferencias de notificación | **Como** usuario, **quiero** activar/desactivar recordatorios y canales (email/SMS/push), **para** recibir solo alertas útiles. | 3 |
| 6 | UA06 | Centro de educación financiera | **Como** usuario, **quiero** acceder a cursos con progreso, **para** mejorar mis hábitos y puntaje crediticio. | 3 |
| 7 | UC01 | Perfil y Workspace del consultor | **Como** consultor, **quiero** editar mi perfil y horario, **para** presentarme profesionalmente. | 2 |
| 8 | UC02 | Publicar servicios | **Como** consultor, **quiero** publicar servicios con precio y adjuntos, **para** ofrecer asesorías. | 3 |
| 9 | UC03 | Mensajería con clientes | **Como** consultor, **quiero** conversar y adjuntar archivos, **para** dar seguimiento a casos. | 3 |
| 10 | UC04 | Métricas del consultor | **Como** consultor, **quiero** ver contactos, reservas e ingresos estimados, **para** priorizar esfuerzos. | 2 |
| 11 | SYS01 | Recuperación de contraseña | **Como** usuario, **quiero** recuperar mi contraseña vía enlace temporal, **para** reingresar en caso de olvido. | 1 |
| 12 | SYS02 | Eliminación de cuenta | **Como** usuario, **quiero** borrar mi cuenta y revocar suscripciones, **para** controlar mis datos personales. | 2 |

# Conclusiones
## Conclusiones y recomendaciones

<strong>Conclusiones</strong> <br> <br>
<strong>Resultados frente a los Problem Statements</strong>
El equipo ha logrado abordar los desafíos definidos en los Problem Statements, logrando una comprensión profunda de las necesidades del usuario y los problemas subyacentes que afectan su experiencia. Los resultados obtenidos validan que el enfoque planteado desde el inicio es adecuado, aunque algunos ajustes deben ser considerados para mejorar aún más los resultados.

<strong>Assumptions frente al comportamiento real de los segmentos</strong>
Al comparar los assumptions iniciales con el comportamiento real de los segmentos de usuarios, se identificaron varias discrepancias. Esto fue fundamental para reajustar las estrategias y adaptar el producto a las necesidades reales de los usuarios, ya que permitió optimizar la experiencia y obtener una mayor aceptación.

<strong>Hypotheses Statements establecidos</strong>
Las hipótesis planteadas inicialmente fueron validadas en su mayoría, esto demuestra que la comprensión inicial de los problemas y necesidades era adecuada. Sin embargo, algunas hipótesis requirieron ajustes basados en las validaciones con usuarios, revelando oportunidades para iterar sobre el diseño y la funcionalidad del producto.

<strong>Criterios de éxito en el proceso de Lean UX</strong>
Los criterios de éxito establecidos en el proceso de Lean UX se cumplieron en gran medida, con métricas clave que indican mejoras significativas en la satisfacción del usuario y la usabilidad del producto. Sin embargo, algunas áreas aún necesitan mejoras adicionales para cumplir con los objetivos más ambiciosos de la organización.

<strong>Recomendaciones</strong>

Es crucial seguir ajustando los procesos de recolección de feedback para asegurarse de que reflejen de manera precisa las necesidades cambiantes de los usuarios. Esto permitirá que los futuros ciclos de desarrollo sean aún más alineados con el mercado.

Con base en los hallazgos obtenidos, se recomienda ajustar el roadmap de los productos digitales para priorizar características y funcionalidades que respondan a las nuevas necesidades identificadas durante las validaciones. También es importante tener en cuenta la implementación de mejoras continuas en áreas donde se encontraron deficiencias.

El equipo debe continuar adoptando un enfoque iterativo, incorporando los aprendizajes de las validaciones en cada ciclo de desarrollo. Esto asegurará que el producto continúe evolucionando de manera efectiva y se adapte a los cambios en el comportamiento y expectativas de los usuarios.

A medida que se avanza en el desarrollo, se recomienda aumentar la frecuencia de validaciones con usuarios reales. Esto ayudará a detectar posibles problemas de manera temprana y a iterar más rápido sobre las soluciones propuestas.

# Bibliografía

1. Conexión ESAN. (s. f.). 7 de cada 10 peruanos están endeudados y no pueden cubrir sus gastos: ¿Cuáles son los factores? Recuperado de: (https://www.esan.edu.pe/conexion-esan/7-de-cada-10-peruanos-estan-endeudados-y-no-pueden-cubrir-sus-gastos-cuales-son-los-factores)

2. Diario Oficial El Peruano. (s. f.). Peruanos tendrán más facilidades para pagar deudas por créditos. Recuperado de: (https://elperuano.pe/noticia/104634-peruanos-tendran-mas-facilidades-para-pagar-deudas-por-creditos)

3. El Comercio Perú. (2022, 26 de abril). InfoCorp: Consulte AQUÍ tu reporte de deudas solo con tu número de DNI. Recuperado de: (https://elcomercio.pe/economia/personal/infocorp-consulta-aqui-tu-reporte-de-deudas-solo-con-el-documento-nacional-de-identidad-como-saber-mi-estado-crediticio-como-salir-de-infocorp-rmmn-noticia/#google_vignette)

4. Infobae. (2022, 10 de octubre). Aumenta en más del 76% deuda morosa de los peruanos en los últimos tres años. Recuperado de: (https://www.infobae.com/america/peru/2022/10/10/aumenta-en-mas-del-76-deuda-morosa-de-los-peruanos-en-los-ultimos-tres-anos/)

5. Infobae. (2022, 25 de mayo). SBS: Deudas de peruanos son cuatro veces más altas que sus ingresos. Recuperado de: (https://www.infobae.com/america/peru/2022/05/25/sbs-deudas-de-peruanos-son-cuatro-veces-mas-altas-que-sus-ingresos/)
   
6. Periche-Delgado, G. S. (2020). La morosidad ante un confinamiento del Covid-19 en la Caja Rural de Ahorro y Crédito Raíz, Perú. Recuperado de: (https://www.redalyc.org/journal/5860/586066112004/html/)
   
7. RPP. (2018, 6 de junio). Endeudamiento de peruanos sube sostenidamente, advierte el Banco Central. Recuperado de: (https://rpp.pe/economia/economia/endeudamiento-de-peruanos-sube-sostenidamenteadvierte-el-banco-central-noticia-1127473?ref=rpp)
   
8. RPP. (2022, 18 de julio). Más de 7 de cada 10 peruanos no pueden cubrir todos sus gastos y tienen deudas. Recuperado de: (https://rpp.pe/economia/economia/mas-de-7-de-cada-10-peruanos-no-pueden-cubrir-todos-sus-gastos-y-tienen-deudas-noticia-1418691)
   
9. RPP. (2022, 22 de agosto). Deudas: ¿Cuántos peruanos presentan atraso en sus pagos a bancos y servicios? Recuperado de: (https://rpp.pe/economia/economia/deudas-cuanto-peruanos-presentan-atraso-en-sus-pagos-a-bancos-y-servicios-noticia-1425578?ref=rpp)

14. Terranova, J. (2023, 3 de enero). Economía familiar: 62% de peruanos se ha endeudado para cubrir gastos del hogar. Recuperado de: (https://gestion.pe/tu-dinero/economia-familiar-62-de-peruanos-se-ha-endeudado-paracubrir-gastos-del-hogar-noticia/)

# Anexos

[Frontend:](https://frontend-debtogo.homeservergv.com/) https://frontend-debtogo.homeservergv.com/

[Backend:](https://backend-debtogo.homeservergv.com/swagger-ui/index.html) https://backend-debtogo.homeservergv.com/swagger-ui/index.html