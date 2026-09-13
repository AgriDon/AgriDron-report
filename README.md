<div align="center">
<img src="assets/upc_logo.png" alt="UPC Logo" width="150"/>

## **Universidad Peruana de Ciencias Aplicadas**
### Carrera de Ingeniería de Software
<br>

**Curso: Desarrollo de Aplicaciones Open Source**

**NRC: 7760**

**Docente: FLORES MOROCCO; Juan Antonio**
<br>

### **Informe del Trabajo Final**

**Nombre de la Startup:** AgriDron

**Nombre del producto:** [NOMBRE DEL PRODUCTO]
<br>

### **Integrantes**

</div>

<table align="center" style="border-collapse: collapse; border: none; margin-left: auto; margin-right: auto;">
    <tr>
        <th style="border: none; padding: 0 18px 6px 0; text-align: center;">Código</th>
        <th style="border: none; padding: 0 0 6px 0; text-align: center;">Damacen Galindo, Italo Gianfranco</th>
    </tr>
    <tr>
        <td style="border: none; padding: 0 18px 4px 0; text-align: center;">[U20241G306]</td>
        <td style="border: none; padding: 0 0 4px 0; text-align: center;">Nicho Huillcañahui, Edwin Noe</td>
    </tr>
    <tr>
        <td style="border: none; padding: 0 18px 4px 0; text-align: center;">[CÓDIGO]</td>
        <td style="border: none; padding: 0 0 4px 0; text-align: center;">Ramirez Gutierrez, Gabriel</td>
    </tr>
    <tr>
        <td style="border: none; padding: 0 18px 4px 0; text-align: center;">U202422642</td>
        <td style="border: none; padding: 0 0 4px 0; text-align: center;">Sayago Vidal, Sebastian Leonardo</td>
    </tr>
    <tr>
        <td style="border: none; padding: 0 18px 4px 0; text-align: center;">U202222473</td>
        <td style="border: none; padding: 0 0 4px 0; text-align: center;">Vasquez Roncal, Alexander Felipe</td>
    </tr>
</table>
<br>
<div align="center">
<b><i>Septiembre, 2026</i></b>
</div>
<br>

---

## Registro de Versiones

| Versión | Fecha | Autor | Descripción |
| :--- | :--- | :--- | :--- |
| 0.1.0 | 05/09/2026 | Sebastián Sayago | Creación inicial del documento. |
| 0.2.0 | 06/09/2026 | Sebastián Sayago | Implementación inicial del capitulo 1 |



---

# Contenido

## Tabla de Contenido

- [Contenido](#contenido)
  - [Tabla de Contenido](#tabla-de-contenido)
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
  - [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)
  - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
  - [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
      - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
      - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
      - [4.2.1. Organization Systems](#421-organization-systems)
      - [4.2.2. Labeling Systems](#422-labeling-systems)
      - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      - [4.2.4. Searching Systems](#424-searching-systems)
      - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
      - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
      - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
      - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
      - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
      - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
      - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
      - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
      - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
      - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
      - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
      - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
      - [4.8.1. Database Diagrams](#481-database-diagrams)
  - [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
      - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
      - [5.1.2. Source Code Management](#512-source-code-management)
      - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
      - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
      - [5.2.1. Sprint 1](#521-sprint-1)
        - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
        - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
        - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
        - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.3. Validation Interviews](#53-validation-interviews)
      - [5.3.1. Interview Design](#531-interview-design)
      - [5.3.2. Interview Registry](#532-interview-registry)
      - [5.3.3. Heuristic Evaluations](#533-heuristic-evaluations)
    - [5.4. Video About-the-Product](#54-video-about-the-product)
  - [Conclusiones](#conclusiones)
  - [Bibliografía](#bibliografía)
  - [Anexos](#anexos)

---

## Student Outcome

> **[PEGAR AQUÍ EL STUDENT OUTCOME CORRESPONDIENTE A LA ENTREGA]**
>
> **Criterio:** [PEGAR AQUÍ EL CRITERIO]
>
> En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del Student Outcome.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>[CRITERIO ESPECÍFICO 1]</strong></td>
      <td>
        <p><b>[INTEGRANTE 1]</b><br></p>
        <p><em><b>AV1</b></em><br>[ACCIÓN REALIZADA]</p>
        <br>
        <b>[INTEGRANTE 2]</b><br>
        <em><b>AV1</b></em><br>[ACCIÓN REALIZADA]
        <br><br>
        <b>[REPETIR PARA TODOS LOS INTEGRANTES]</b>
      </td>
      <td>[CONCLUSIÓN]</td>
    </tr>
    <tr>
      <td><strong>[CRITERIO ESPECÍFICO 2]</strong></td>
      <td>
        <p><b>[INTEGRANTE 1]</b><br></p>
        <p><em><b>AV1</b></em><br>[ACCIÓN REALIZADA]</p>
        <br>
        <b>[INTEGRANTE 2]</b><br>
        <em><b>AV1</b></em><br>[ACCIÓN REALIZADA]
        <br><br>
        <b>[REPETIR PARA TODOS LOS INTEGRANTES]</b>
      </td>
      <td>[CONCLUSIÓN]</td>
    </tr>
  </tbody>
</table>
---

# Capítulo I: Introducción

## 1.1. Startup Profile

<p align="justify">

<strong>AgriDron Solutions</strong> es una startup tecnológica orientada a mejorar la gestión de cultivos mediante el uso de drones para fumigación y monitoreo. La plataforma busca facilitar estas tareas y hacer que las operaciones sean más rápidas y fáciles de controlar.

</p>

<p align="justify">

AgriDron Solutions ofrece una plataforma que permite planificar misiones de fumigación, monitorear el trabajo en tiempo real y consultar reportes de las operaciones realizadas. El objetivo es que agricultores y personal técnico puedan controlar estas tareas desde una sola aplicación.

</p>

**Misión:** Mejorar la gestión de cultivos mediante drones y una plataforma accesible que permita reducir costos y tiempo en las operaciones de fumigación.

**Visión:** Convertirnos en una solución tecnológica de confianza para el sector agrícola, ayudando a modernizar la forma en que se gestionan y supervisan las operaciones de fumigación.

Valores:

<ul>
  <li><strong>Innovación:</strong> buscamos utilizar nuevas tecnologías para mejorar las operaciones agrícolas.</li>
  <li><strong>Eficiencia:</strong> buscamos reducir el tiempo, los costos y el uso de recursos.</li>
  <li><strong>Confiabilidad:</strong> buscamos que las operaciones y los datos mostrados en la plataforma sean claros y precisos.</li>
  <li><strong>Compromiso:</strong> buscamos ofrecer una solución útil y accesible para agricultores y personal técnico.</li>
</ul>

### 1.1.1. Descripción de la Startup

<p align="justify">

<strong>AgriDron Solutions</strong> es una startup que busca mejorar la protección de cultivos mediante drones y una plataforma de monitoreo. El sistema permitirá gestionar las operaciones de fumigación desde una sola plataforma.

</p>

<p align="justify">

La plataforma permitirá registrar fincas y parcelas, seleccionar áreas de fumigación mediante un mapa, crear misiones, consultar el clima, monitorear los drones y revisar el historial de las operaciones.

</p>

Pilares de valor:

<ul>
  <li><strong>Innovación tecnológica:</strong> uso de drones aplicados a la agricultura.</li>
  <li><strong>Eficiencia operativa:</strong> reducción de costos y tiempos frente a métodos tradicionales de fumigación.</li>
  <li><strong>Confiabilidad de datos:</strong> información clara y disponible durante y después de las operaciones.</li>
  <li><strong>Compromiso social y ambiental:</strong> reducción de riesgos para los trabajadores y del impacto de la fumigación.</li>
</ul>

### 1.1.2. Perfiles de integrantes del equipo

> Para cada integrante, colocar foto, nombre, código, carrera, descripción y aporte/rol dentro del proyecto.

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/team/integrante_01.png" alt="Foto del integrante" width="500"/>
    </td>
  </tr>
  <tr>
    <td><b>Nombre:</b> Damacen Galindo, Italo Gianfranco</td>
  </tr>
  <tr>
    <td><b>Código:</b> U202421392 &nbsp;|&nbsp; <b>Carrera:</b> [CARRERA]</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      [DESCRIPCIÓN DEL PERFIL, CONOCIMIENTOS Y HABILIDADES.]
      <br/><br/>
      <b>Aporte y función dentro del equipo:</b><br/>
      [APORTE Y FUNCIÓN DENTRO DEL EQUIPO.]
    </td>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/team/integrante_02.png" alt="Foto del integrante" width="500"/>
    </td>
  </tr>
  <tr>
    <td><b>Nombre:</b> Nicho Huillcánahui, Edwin Noe</td>
  </tr>
  <tr>
    <td><b>Código:</b> U20241G306 &nbsp;|&nbsp; <b>Carrera:</b> [CARRERA]</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      [DESCRIPCIÓN DEL PERFIL, CONOCIMIENTOS Y HABILIDADES.]
      <br/><br/>
      <b>Aporte y función dentro del equipo:</b><br/>
      [APORTE Y FUNCIÓN DENTRO DEL EQUIPO.]
    </td>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/team/integrante_03.png" alt="Foto del integrante" width="500"/>
    </td>
  </tr>
  <tr>
    <td><b>Nombre:</b> Ramirez Gutierrez, Gabriel</td>
  </tr>
  <tr>
    <td><b>Código:</b> U202416053 &nbsp;|&nbsp; <b>Carrera:</b> [CARRERA]</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      [DESCRIPCIÓN DEL PERFIL, CONOCIMIENTOS Y HABILIDADES.]
      <br/><br/>
      <b>Aporte y función dentro del equipo:</b><br/>
      [APORTE Y FUNCIÓN DENTRO DEL EQUIPO.]
    </td>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/team/integrante_04.png" alt="Foto del integrante" width="500"/>
    </td>
  </tr>
  <tr>
    <td><b>Nombre:</b> Sayago Vidal, Sebastian Leonardo</td>
  </tr>
  <tr>
    <td><b>Código:</b> U202422642 &nbsp;|&nbsp; <b>Carrera:</b> [CARRERA]</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      [DESCRIPCIÓN DEL PERFIL, CONOCIMIENTOS Y HABILIDADES.]
      <br/><br/>
      <b>Aporte y función dentro del equipo:</b><br/>
      [APORTE Y FUNCIÓN DENTRO DEL EQUIPO.]
    </td>
  </tr>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/team/integrante_05.png" alt="Foto del integrante" width="500"/>
    </td>
  </tr>
  <tr>
    <td><b>Nombre:</b> Vasquez Roncal, Alexander Felipe</td>
  </tr>
  <tr>
    <td><b>Código:</b> U202222473 &nbsp;|&nbsp; <b>Carrera:</b> [CARRERA]</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      [DESCRIPCIÓN DEL PERFIL, CONOCIMIENTOS Y HABILIDADES.]
      <br/><br/>
      <b>Aporte y función dentro del equipo:</b><br/>
      [APORTE Y FUNCIÓN DENTRO DEL EQUIPO.]
    </td>
  </tr>
</table>

<br>

---

## 1.2. Solution Profile

<p align="justify">

<strong>AgriDron Solutions</strong> propone una plataforma que centraliza la planificación, ejecución y monitoreo de operaciones de fumigación agrícola mediante drones. El usuario podrá programar misiones, supervisar los drones y consultar información de las operaciones desde una sola plataforma.

</p>

<p align="justify">

El usuario podrá registrar sus fincas y parcelas, seleccionar en un mapa el área que desea fumigar y crear una misión. Antes de realizar la operación podrá consultar las condiciones meteorológicas mediante una API externa. Durante la misión podrá ver el estado y ubicación del dron. Después podrá revisar el historial y los reportes de las operaciones realizadas.

</p>

### 1.2.1. Antecedentes y problemática

1.2.1.1. What

<p align="justify">

El problema central es la presencia recurrente de plagas y parásitos en los cultivos, lo que reduce el rendimiento y la calidad de la cosecha. Los métodos tradicionales de fumigación, ya sean manuales o con tractor, pueden ser lentos, costosos e imprecisos. Además, pueden exponer a los trabajadores a productos químicos.

</p>

1.2.1.2. Where

<p align="justify">

La problemática se presenta en terrenos agrícolas donde no existe una correcta gestión y monitoreo de las operaciones. Esto puede dificultar el control de plagas y afectar la producción.

</p>

1.2.1.3. When

<p align="justify">

El problema de las plagas ocurre principalmente durante las temporadas de crecimiento de los cultivos. El monitoreo y las aplicaciones de fumigación se realizan durante todo el ciclo de cultivo, ya sea de forma preventiva o cuando aparecen signos de infestación.

</p>

1.2.1.4. Who

<p align="justify">

El ecosistema de AgriDron Solutions involucra a agricultores, cooperativas agrícolas, ingenieros agrónomos, técnicos de campo y operadores de drones. Los agricultores y cooperativas serán los principales clientes, mientras que el personal técnico podrá utilizar la plataforma para supervisar y gestionar las operaciones.

</p>

1.2.1.5. Why

<p align="justify">

La causa principal es la falta de un sistema que permita gestionar y monitorear las operaciones de fumigación de forma centralizada. Esto puede generar pérdidas económicas y aumentar la exposición de los trabajadores a los riesgos de los métodos tradicionales.

</p>

1.2.1.6. How

<p align="justify">

AgriDron Solutions abordará esta problemática mediante una plataforma web que permita gestionar fincas y parcelas, seleccionar áreas de fumigación en un mapa, crear misiones con drones, consultar información meteorológica, monitorear los drones y revisar reportes e historial de operaciones.

</p>

1.2.1.7. How much

<p align="justify">

Según la FAO (2023), se estima que hasta un 40% de la producción agrícola mundial se pierde cada año debido a plagas y enfermedades. Esto muestra la importancia de contar con mejores herramientas para el monitoreo y control de plagas.

</p>

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Problem Statement 1

<p align="justify">

Los agricultores necesitan una forma centralizada de gestionar sus fincas, parcelas y áreas de fumigación, debido a que estas actividades forman parte de la planificación de sus operaciones con drones y pueden requerir coordinación manual.

</p>

Problem Statement 2

<p align="justify">

Los responsables de las operaciones de fumigación necesitan consultar las condiciones meteorológicas antes de realizar una misión, debido a que esta información es relevante para la planificación de la operación.

</p>

Problem Statement 3

<p align="justify">

Los responsables de una misión necesitan realizar un seguimiento del estado y ubicación del dron durante una operación, debido a que requieren conocer el progreso de la misión.

</p>

Problem Statement 4

<p align="justify">

Los usuarios necesitan consultar el historial y los reportes de las misiones realizadas, debido a que requieren mantener un registro de las operaciones de fumigación gestionadas.

</p>

#### 1.2.2.2. Lean UX Assumptions

**1.2.2.2.1. ¿Quién es el usuario?**

<p align="justify">

Los principales usuarios de la solución son agricultores, operadores y técnicos relacionados con la planificación, ejecución y supervisión de operaciones de fumigación agrícola mediante drones.

</p>

<p align="justify">

La plataforma se utilizará como una herramienta de apoyo para gestionar las operaciones de fumigación agrícola. Permitirá centralizar actividades como el registro de parcelas, la planificación de misiones, la consulta de condiciones meteorológicas, el monitoreo de drones y la consulta de reportes.

</p>

**1.2.2.2.3. ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

<ul> 
    <li><strong>Gestión dispersa de la información:</strong> centralizar la información de fincas, parcelas y misiones dentro de una misma plataforma.</li> 
    <li><strong>Dificultad para definir el área de fumigación:</strong> utilizar un mapa interactivo para seleccionar el área que será fumigada.</li> 
    <li><strong>Consulta de condiciones meteorológicas:</strong> integrar una API externa para obtener información climática.</li> 
    <li><strong>Seguimiento de las misiones:</strong> incorporar un módulo de monitoreo con datos simulados sobre el estado y ubicación del dron.</li> 
    <li><strong>Consulta de operaciones anteriores:</strong> almacenar el historial y generar reportes de las misiones realizadas.</li> 
</ul>

**1.2.2.2.4. ¿Cuándo y cómo es usado nuestro producto?**

<p align="justify">

La plataforma será utilizada antes, durante y después de una operación de fumigación. Antes de la misión, el usuario podrá gestionar la parcela, definir el área de fumigación, crear la misión y consultar las condiciones meteorológicas. Durante la operación podrá consultar el estado y ubicación del dron. Después de la misión podrá consultar el historial y los reportes generados.

</p>

#### 1.2.2.2. Lean UX Assumptions

**1.2.2.2.1. Business Assumptions**

<ul> 
    <li>Gestión de fincas y parcelas.</li> 
    <li>Mapa interactivo para definir áreas de fumigación.</li> 
    <li>Creación y gestión de misiones.</li> <li>Consulta de condiciones meteorológicas mediante una API externa.</li> 
    <li>Monitoreo del estado y ubicación de los drones.</li> <li>Historial y reportes de las operaciones.</li> 
    <li>Gestión de roles de usuario.</li> 
</ul>

**1.2.2.2.6. ¿Cómo debe verse nuestro producto y cómo debe comportarse?**

<p align="justify">

La plataforma debe presentar una interfaz web clara y organizada, que permita a los usuarios acceder de manera sencilla a las principales funciones relacionadas con la gestión de sus operaciones. La información de las parcelas, misiones, condiciones meteorológicas y monitoreo deberá presentarse de manera comprensible, diferenciando las funcionalidades disponibles según el rol del usuario.

<ul>
  <li>Reducción del 40% en el tiempo y costo de la aplicación de pesticidas frente a los métodos tradicionales.</li>
  <li>Reducción en el tiempo de respuesta ante una infestación de plagas gracias al monitoreo continuo de los cultivos.</li>
  <li>Aumento del 25% en la retención de clientes después del primer ciclo de cultivo.</li>
  <li>Incremento del 40% en la adopción de funciones premium tras el periodo de prueba gratuito.</li>
</ul>

**1.2.2.2.3. User Assumptions**

<ul>
  <li>Los usuarios principales son pequeños y medianos agricultores (PyMAs), así como ingenieros agrónomos y técnicos de campo.</li>
  <li><strong>Necesidad:</strong> los agricultores priorizan soluciones que les ahorren tiempo y reduzcan la incertidumbre en el manejo de plagas.</li>
  <li><strong>Comportamiento:</strong> los usuarios están dispuestos a adoptar nuevas tecnologías si la interfaz es intuitiva y el entrenamiento es mínimo.</li>
  <li><strong>Dolor:</strong> la falta de datos en tiempo real sobre las operaciones de fumigación es un problema para la toma de decisiones.</li>
  <li><strong>Contexto:</strong> los agricultores y técnicos prefieren supervisar operaciones desde dispositivos móviles debido a la distancia de las zonas de cultivo.</li>
</ul>

**1.2.2.2.4. User Outcome and Benefit Assumptions**

<ul>
  <li>Evitar pérdidas económicas por plagas.</li>
  <li>Tener control de sus campos y parcelas.</li>
  <li>Acceder a datos en tiempo real sobre las operaciones.</li>
  <li>Mejorar la productividad y rentabilidad.</li>
  <li>Reducir la exposición de los trabajadores a químicos peligrosos.</li>
</ul>

**1.2.2.2.5. Feature Assumptions**

<ul>
  <li><strong>Funcionalidad:</strong> los drones autónomos cubrirán las hectáreas de cultivo con mayor precisión y velocidad que los métodos tradicionales.</li>
  <li><strong>Tecnología:</strong> la plataforma permitirá controlar y monitorear las operaciones de los drones desde la aplicación en tiempo real.</li>
  <li><strong>Experiencia:</strong> la plataforma web/móvil será adoptada rápidamente incluso por usuarios con baja alfabetización digital.</li>
  <li><strong>Integración:</strong> los reportes automáticos de fumigación, incluyendo área cubierta, insumos usados y tiempo, serán útiles para la gestión de las operaciones.</li>
</ul>

#### 1.2.2.3. Lean UX Hypothesis Statements

Hypothesis Statement 1

<p align="justify">

We believe we will achieve a 40% reduction in spraying time and cost if small and medium farmers (PyMAs) attain precise and efficient crop coverage with the autonomous drone spraying feature.

</p>

Hypothesis Statement 2

<p align="justify">

We believe we will achieve a faster response time to pest infestations if farmers and agricultural technical staff attain continuous, real-time visibility of field and drone status with the mission monitoring and control feature.

</p>

**Hypothesis Statement 3**

<p align="justify">

We believe we will achieve higher platform adoption and customer retention if farmers with low digital literacy attain an intuitive and easy-to-learn experience with the web/mobile monitoring platform.

</p>

**Hypothesis Statement 4**

<p align="justify">

We believe we will achieve increased adoption of premium features and improved operational decision-making if farmers and technical staff attain valuable, ready-to-use operational data with the automated spraying and usage report feature.

</p>

<p align="justify">

Creemos que integrar información meteorológica mediante una API externa ayudará a los usuarios a considerar las condiciones climáticas durante la planificación de una misión. Sabremos que esto es cierto cuando los usuarios puedan consultar dicha información antes de gestionar una operación.

</p>

Hypothesis Statement 4

<p align="justify">

Creemos que visualizar el estado y ubicación del dron durante una misión permitirá a los usuarios realizar un mejor seguimiento de la operación. Sabremos que esto es cierto cuando puedan identificar el estado y posición del dron durante una misión simulada.

</p>
#### 1.2.2.4. Lean UX Canvas

<div align="center">

<img width="1557" height="1010" alt="export-canva-48djfk42n3h4Hand56nD" src="https://github.com/user-attachments/assets/2d3277d5-22a1-40bb-a3c9-ad852362d1ef" />

</div>

Descripción:

<p align="justify">

El Lean UX Canvas (Iteración 1) resume el modelo de negocio de AgriDron Solutions. El <strong>Business Problem</strong> describe la necesidad de mejorar la forma en que los agricultores y el personal técnico gestionan las operaciones de fumigación. Las <strong>Solutions</strong> propuestas incluyen fumigación con drones, monitoreo en tiempo real y una app móvil/web. Los <strong>Business Outcomes</strong> esperados incluyen reducir el tiempo y costo de fumigación, disminuir el tiempo de respuesta ante infestaciones y aumentar la retención de clientes.

</p>

<p align="justify">

En cuanto a los <strong>Users & Customers</strong>, los principales segmentos son los pequeños y medianos agricultores (PyMAs) y el personal técnico. Sus <strong>User Outcomes & Benefits</strong> incluyen tener mayor control de sus campos, acceder a información de sus operaciones y reducir su exposición a productos químicos. Las <strong>Hypotheses</strong> buscan validar si los usuarios están dispuestos a pagar por el servicio y si las funciones de fumigación, monitoreo y reporte generan valor. El siguiente paso será validar la disposición de pago y el valor percibido mediante entrevistas y pruebas piloto.

</p>

### 1.3. Segmentos objetivo

#### 1.3.1. Pequeños y Medianos Agricultores (PyMAs)

<p align="justify">

Este es el segmento principal de AgriDron Solutions. Está conformado por productores agrícolas con extensiones de 5 a 50 hectáreas, que cultivan principalmente para el mercado local y regional. Pueden trabajar de forma independiente o agrupados en cooperativas y buscan reducir costos y proteger el rendimiento de sus cultivos.

</p>

<p align="justify">

<strong>Características cuantitativas:</strong> edad entre 28 y 60 años, extensión de cultivo de 5 a 50 hectáreas, nivel educativo variado desde educación básica hasta técnica, familiaridad tecnológica media-baja, con adopción creciente de smartphones.

</p>

<p align="justify">

<strong>Características cualitativas:</strong> su principal motivación es reducir costos y mejorar el rendimiento de sus cultivos. Sus principales problemas son las pérdidas por plagas, los costos de mano de obra y la falta de información para tomar decisiones.

</p>

<p align="justify">

<strong>Relación con la solución:</strong> este segmento utilizará la plataforma para gestionar fincas y parcelas, seleccionar áreas de fumigación en el mapa, crear misiones, consultar el clima y revisar reportes e historial de sus operaciones.

</p>

#### 1.3.2. Personal Técnico (Ingenieros Agrónomos y Técnicos de Campo)

<p align="justify">

Este segmento está conformado por ingenieros agrónomos, técnicos agrícolas y operadores de drones. Son usuarios de la plataforma que se encargan de revisar la información, planificar las operaciones y supervisar las misiones de fumigación.

</p>

<p align="justify">

<strong>Características cuantitativas:</strong> edad entre 22 y 45 años, formación técnica o universitaria en agronomía, ingeniería agrícola o carreras afines, experiencia de 1 a 15 años en campo, a cargo de la supervisión de múltiples parcelas o unidades productivas de forma simultánea.

</p>

<p align="justify">

<strong>Características cualitativas:</strong> cuentan con mayor familiaridad tecnológica que el agricultor promedio y valoran herramientas que les ayuden a ahorrar tiempo. Su principal motivación es contar con información precisa para planificar las operaciones. Su principal problema es la dificultad para supervisar varios campos al mismo tiempo.

</p>

<p align="justify">

<strong>Relación con la solución:</strong> este segmento utilizará la plataforma para revisar información de las operaciones, planificar y ejecutar misiones de fumigación mediante el software de control de drones y supervisar varias unidades productivas a la vez.

</p>

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

[PEGAR AQUÍ LA MATRIZ / TABLA DE ANÁLISIS COMPETITIVO.]

| Criterio | Competidor 1 | Competidor 2 | Competidor 3 | Nuestra solución |
| :--- | :--- | :--- | :--- | :--- |
| [CRITERIO] | [DATO] | [DATO] | [DATO] | [DATO] |
| [CRITERIO] | [DATO] | [DATO] | [DATO] | [DATO] |
| [CRITERIO] | [DATO] | [DATO] | [DATO] | [DATO] |

### 2.1.2. Estrategias y tácticas frente a competidores

<p align="justify">

[DESCRIBIR LAS ESTRATEGIAS Y TÁCTICAS QUE PERMITIRÁN DIFERENCIAR LA SOLUCIÓN.]

</p>

---

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Objetivo de la entrevista:**

[DESCRIBIR OBJETIVO.]

**Segmento entrevistado:**

[DESCRIBIR SEGMENTO.]

**Cantidad de entrevistados:**

[CANTIDAD]

**Preguntas generales**

1. [PREGUNTA]
2. [PREGUNTA]
3. [PREGUNTA]

**Preguntas específicas del segmento 1**

1. [PREGUNTA]
2. [PREGUNTA]
3. [PREGUNTA]

**Preguntas específicas del segmento 2**

1. [PREGUNTA]
2. [PREGUNTA]
3. [PREGUNTA]

### 2.2.2. Registro de entrevistas

[PARA CADA ENTREVISTA, COMPLETAR EL SIGUIENTE FORMATO.]

#### Entrevista [NÚMERO]

| Campo | Información |
| :--- | :--- |
| Entrevistado | [NOMBRE / IDENTIFICADOR] |
| Edad | [EDAD] |
| Segmento | [SEGMENTO] |
| Fecha | [FECHA] |
| Modalidad | [PRESENCIAL / VIRTUAL] |
| Lugar | [LUGAR] |

**Registro / respuestas:**

| N.º | Pregunta | Respuesta |
| :--- | :--- | :--- |
| 1 | [PREGUNTA] | [RESPUESTA] |
| 2 | [PREGUNTA] | [RESPUESTA] |
| 3 | [PREGUNTA] | [RESPUESTA] |

**Evidencia:**

![Evidencia de entrevista](assets/interviews/entrevista_01.png)

### 2.2.3. Análisis de entrevistas

<p align="justify">

[RESUMIR LOS HALLAZGOS PRINCIPALES DE LAS ENTREVISTAS.]

</p>

| Hallazgo | Evidencia / entrevista | Necesidad identificada | Implicación para la solución |
| :--- | :--- | :--- | :--- |
| [HALLAZGO] | [EVIDENCIA] | [NECESIDAD] | [IMPLICACIÓN] |
| [HALLAZGO] | [EVIDENCIA] | [NECESIDAD] | [IMPLICACIÓN] |

---

## 2.3. Needfinding

### 2.3.1. User Personas

#### Persona 1: [NOMBRE]

![User Persona 1](assets/needfinding/persona_01.png)

**Descripción:**

[DESCRIPCIÓN.]

**Necesidades:**

- [NECESIDAD 1]
- [NECESIDAD 2]

**Objetivos:**

- [OBJETIVO 1]
- [OBJETIVO 2]

**Frustraciones:**

- [FRUSTRACIÓN 1]
- [FRUSTRACIÓN 2]

#### Persona 2: [NOMBRE]

![User Persona 2](assets/needfinding/persona_02.png)

[REPETIR ESTRUCTURA.]

### 2.3.2. User Task Matrix

[PEGAR / CONSTRUIR AQUÍ LA MATRIZ DE TAREAS.]

| Tarea | Usuario | Frecuencia | Importancia | Dificultad | Problemas actuales |
| :--- | :--- | :--- | :--- | :--- | :--- |
| [TAREA] | [USUARIO] | [ALTA/MEDIA/BAJA] | [ALTA/MEDIA/BAJA] | [ALTA/MEDIA/BAJA] | [PROBLEMA] |
| [TAREA] | [USUARIO] | [ALTA/MEDIA/BAJA] | [ALTA/MEDIA/BAJA] | [ALTA/MEDIA/BAJA] | [PROBLEMA] |

### 2.3.3. User Journey Mapping

<div align="center">

![User Journey Mapping](assets/needfinding/user_journey_mapping.png)

</div>

**Descripción:**

<p align="justify">

[EXPLICAR EL JOURNEY MAP Y LOS PRINCIPALES PUNTOS DE DOLOR.]

</p>

### 2.3.4. Empathy Mapping

<div align="center">

![Empathy Mapping](assets/needfinding/empathy_mapping.png)

</div>

**Descripción:**

<p align="justify">

[EXPLICAR EL EMPATHY MAP.]

</p>

---

## 2.4. Big Picture EventStorming
asdasdasdasdasfsdsd

<div align="center">

![Big Picture EventStorming](assets/architecture/big_picture_eventstorming.png)

</div>

**Descripción:**

<p align="justify">

[EXPLICAR EL FLUJO GENERAL DEL DOMINIO, EVENTOS PRINCIPALES, ACTORES Y PROCESOS IDENTIFICADOS.]

</p>

---

## 2.5. Ubiquitous Language

| Término | Definición |
| :--- | :--- |
| [TÉRMINO] | [DEFINICIÓN DENTRO DEL DOMINIO] |
| [TÉRMINO] | [DEFINICIÓN DENTRO DEL DOMINIO] |
| [TÉRMINO] | [DEFINICIÓN DENTRO DEL DOMINIO] |

---

# Capítulo III: Requirements Specification

## 3.1. User Stories

> User Stories - Landing Page (Rol: Visitante / Visitor).

| ID     | Título                        | Descripción | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                      | Epic   |
|:-------|:------------------------------| :--- |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------|
| LP-001 | Visualizar propuesta de valor | Como visitante, quiero visualizar la propuesta de valor de AgriDron en la página principal, <br/>para entender rápidamente qué ofrece el servicio. | 1. Escenario 1: Visualización exitosa<br>Dado que el visitante ingresa al Landing Page, cuando la página carga completamente, entonces el sistema muestra el hero section con el título, subtítulo y un llamado a la acción (CTA) visible.                                                                                                                   | EP-001 |
| LP-002 | Conocer servicios ofrecidos   | Como visitante, quiero ver los servicios y características principales de AgriDron, para evaluar si la solución satisface mis necesidades. | 1. Escenario 1: Visualización de servicios<br>Dado que el visitante está en el Landing Page, cuando hace scroll hacia la sección "Servicios", entonces el sistema muestra al menos 3 tarjetas con iconos, títulos y descripciones breves de los servicios                                                                                                    | EP-002 |
| LP-003 | Ver planes y precios   | Como visitante, quiero conocer los planes de precios y suscripción, para tomar una decisión informada sobre la contratación del servicio. | 1. Escenario 1: Visualización de planes<br>Dado que el visitante está en el Landing Page, cuando hace scroll hacia la sección "Planes", entonces el sistema muestra al menos 2 opciones de planes con sus precios y características incluidas.                                                                                                               | EP-003 |
| LP-004 | Registrarse como nuevo usuario   | Como visitante, quiero registrarme en la plataforma proporcionando mis datos básicos, para acceder a las funcionalidades de la Web Application. | 1. Escenario 1: Registro exitoso<br>Dado que el visitante está en el Landing Page y hace clic en "Registrarse", cuando completa el formulario con nombre, email, contraseña y selecciona su rol (Agricultor/Operador/Supervisor), entonces el sistema crea la cuenta y redirige al Dashboard de la Web Application.<br/>2. Escenario 2: Email ya registrado<br>Dado que el visitante ingresa un email que ya existe en el sistema, cuando envía el formulario de registro, entonces el sistema muestra el mensaje "El correo electrónico ya está registrado" y no crea la cuenta. | EP-004 |
| LP-005 | Iniciar sesión en la plataforma   | Como visitante registrado, quiero iniciar sesión con mis credenciales, para acceder a la Web Application. | 1. Escenario 1:  Inicio de sesión exitoso<br>Dado que el visitante está en el Landing Page y hace clic en "Iniciar Sesión", cuando ingresa email y contraseña válidos, entonces el sistema autentica al usuario y redirige al Dashboard de la Web Application.<br/>2. Escenario 2: Credenciales inválidas<br>Dado que el visitante ingresa email o contraseña incorrectos, cuando envía el formulario de login, entonces el sistema muestra el mensaje "Credenciales inválidas" y no permite el acceso.                                                                                                    | EP-005 |
| LP-006 | Consultar términos y condiciones   | Como visitante, quiero acceder a los términos y condiciones de servicio, para conocer las políticas de uso y privacidad. | 1. Escenario 1: Visualización de términos<br>Dado que el visitante está en el Landing Page y hace clic en el enlace "Términos y Condiciones" en el footer, entonces el sistema navega a la página de términos y condiciones con el contenido completo.                                                                                                    | EP-006 |

> User Stories - Web Application (Roles: Agricultor, Operador, Supervisor)
> Rol: Agricultor

| ID     | Título                        | Descripción | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Epic   |
|:-------|:------------------------------| :--- |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------|
| WA-001 | Registrar una finca | Como agricultor, quiero registrar mis fincas en la plataforma, para gestionar mis parcelas de forma centralizada. | 1. Escenario 1: Registro exitoso<br>Dado que el agricultor está autenticado en el Dashboard, cuando accede a "Gestión de Fincas" y completa el formulario con nombre, ubicación (seleccionando en mapa), tamaño en hectáreas y tipo de cultivo, entonces el sistema guarda la finca y la muestra en el listado.<br/>2. Escenario 2: Nombre duplicado<br>Dado que el agricultor ingresa un nombre de finca que ya existe, cuando envía el formulario, entonces el sistema muestra el mensaje "Ya existe una finca con este nombre" y no la registra.                                        | EP-007 |
| WA-002 | Dibujar área de fumigación   | Como agricultor, quiero dibujar el área de fumigación sobre un mapa interactivo, para planificar misiones de manera precisa. | 1. Escenario 1: Dibujo exitoso<br>Dado que el agricultor está en la sección "Crear Misión", cuando selecciona "Dibujar Área" y traza un polígono cerrado sobre el mapa, entonces el sistema calcula el área en hectáreas y la muestra.<br/>2. Escenario 2: Área fuera de límites<br/>Dado que el agricultor dibuja un área fuera de los límites de su finca registrada, cuando intenta guardar la misión, entonces el sistema muestra el mensaje "El área seleccionada excede los límites de su finca" y no permite continuar.                                                             | EP-008 |
| WA-003 | Crear misión de fumigación   | Como agricultor, quiero crear una misión de fumigación seleccionando el área y el cultivo, para solicitar el servicio. | 1. Escenario 1: Creación exitosa<br>Dado que el agricultor ha dibujado un área válida, cuando selecciona el tipo de cultivo, ingresa observaciones y confirma la misión, entonces el sistema guarda la misión con estado "Pendiente" y genera una notificación para el Supervisor.<br/>2. Escenario 2: Datos incompletos<br/>Dado que el agricultor no ha dibujado un área, cuando intenta crear la misión, entonces el sistema muestra el mensaje "Debe seleccionar un área para la misión" y no permite continuar.                                                                       | EP-009 |
| WA-004 | Ver historial de misiones   | Como agricultor, quiero consultar el historial de misiones de fumigación de mis fincas, para dar seguimiento a las operaciones realizadas. | 1. Escenario 1: Visualización de historial<br>Dado que el agricultor está en el Dashboard, cuando accede a "Historial de Misiones", entonces el sistema muestra un listado con todas las misiones filtradas por finca, con fecha, estado, área y tipo de cultivo.<br/>2. Escenario 2: Filtrado por fecha<br>Dado que el agricultor necesita buscar misiones de un período específico, cuando selecciona un rango de fechas, entonces el sistema muestra solo las misiones dentro de ese rango.                                                                                             | EP-010 |
| WA-005 | Generar reporte de productividad   | Como agricultor, quiero generar reportes de productividad por hectárea, para justificar inversiones y tomar decisiones estratégicas. | 1. Escenario 1:  Generación exitosa<br>Dado que el agricultor está en la sección "Reportes", cuando selecciona una finca y un rango de fechas y hace clic en "Generar Reporte", entonces el sistema genera un reporte en PDF con área total fumigada, insumos utilizados, horas de operación, costo por hectárea y rendimiento estimado.<br/>2. Escenario 2: Sin datos<br>Dado que el agricultor selecciona un rango de fechas sin misiones registradas, cuando intenta generar el reporte, entonces el sistema muestra el mensaje "No hay datos disponibles para el período seleccionado".| EP-011 |

> Rol: Operador

| ID     | Título                        | Descripción | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Epic   |
|:-------|:------------------------------| :--- |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------|
| WA-006 | Consultar misiones asignadas | Como operador, quiero visualizar las misiones de fumigación que me han sido asignadas, para planificar mi jornada de trabajo. | 1. Escenario 1: Visualización de misiones<br>Dado que el operador está autenticado en el Dashboard, cuando accede a "Mis Misiones", entonces el sistema muestra un listado de las misiones asignadas con estado (Pendiente/En Progreso/Completada), fecha, finca y área.<br/>2. Escenario 2: Detalle de misión<br>Dado que el operador selecciona una misión específica, cuando hace clic en "Ver Detalle", entonces el sistema muestra la ubicación en el mapa, el área a fumigar, el tipo de cultivo y las observaciones.                                                                 | EP-012 |
| WA-007 | Actualizar estado de misión   | Como operador, quiero actualizar el estado de una misión (En Progreso / Completada), para mantener informado al agricultor y al supervisor. | 1. Escenario 1: Inicio de misión<br>Dado que el operador está en el detalle de una misión con estado "Pendiente", cuando hace clic en "Iniciar Misión", entonces el sistema cambia el estado a "En Progreso" y registra la hora de inicio.<br/>2. Escenario 2: Completar misión<br/>Dado que el operador está en el detalle de una misión con estado "En Progreso", cuando hace clic en "Completar Misión", entonces el sistema cambia el estado a "Completada", registra la hora de finalización y calcula el área efectivamente fumigada.                                                 | EP-013 |
| WA-008 | Registrar horas trabajadas   | Como operador, quiero registrar mis horas trabajadas con verificación de ubicación, para garantizar precisión en la información de mi jornada. | 1. Escenario 1: Registro automático<br>Dado que el operador llega a la finca registrada, cuando el GPS confirma que está dentro de la geocerca autorizada, entonces el sistema inicia automáticamente el registro de la jornada.<br/>2. Escenario 2: Fuera de zona<br/>Dado que el operador intenta registrar horas fuera de la geocerca de la finca, cuando intenta iniciar el registro, entonces el sistema muestra el mensaje "Ubicación no válida para registro automático" y solicita verificación manual al supervisor.                                                               | EP-014 |
| WA-009 | Registrar incidencias en campo   | Como operador, quiero registrar incidencias durante la operación (clima adverso, falla técnica, etc.), para documentar interrupciones y justificar reprogramaciones. | 1. Escenario 1: Registro de incidencia<br>Dado que el operador está en el detalle de una misión en progreso, cuando hace clic en "Reportar Incidencia" y completa el formulario con tipo (clima/equipo/otro), descripción y adjunta una foto, entonces el sistema guarda la incidencia y notifica al Supervisor.<br/>2. Escenario 2: Incidencia crítica<br>Dado que el operador reporta una incidencia de tipo "Falla crítica", cuando confirma el registro, entonces el sistema cambia automáticamente el estado de la misión a "Pausada" y envía una alerta prioritaria al Supervisor.    | EP-015 |

> Rol: Supervisor

| ID     | Título                        | Descripción | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Epic   |
|:-------|:------------------------------| :--- |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------|
| WA-010 | Asignar misiones a operadores | Como supervisor, quiero asignar misiones creadas por agricultores a operadores disponibles, para coordinar las operaciones de campo | 1. Escenario 1: Asignación exitosa<br>Dado que el supervisor está en el listado de misiones "Pendientes", cuando selecciona una misión, elige un operador disponible y confirma la asignación, entonces el sistema cambia el estado de la misión a "Asignada" y envía una notificación al operador.<br/>2. Escenario 2: Sin operadores disponibles<br>Dado que el supervisor intenta asignar una misión pero no hay operadores con disponibilidad, cuando confirma la asignación, entonces el sistema muestra el mensaje "No hay operadores disponibles para esta fecha" y sugiere reprogramar. | EP-012 |
| WA-011 | Monitorear múltiples drones   | Como supervisor, quiero ver el estado y ubicación de todos los drones activos en tiempo real, para optimizar la coordinación de misiones. | 1. Escenario 1: Supervisión en tiempo real<br>Dado que el supervisor está en el panel "Monitoreo en Tiempo Real", cuando accede a la vista de drones, entonces el sistema muestra todos los drones activos con posición GPS, nivel de batería, estado de misión (en vuelo/en carga/detenido) y progreso porcentual, actualizados cada 5 segundos.<br/>2. Escenario 2: Pérdida de conexión<br/>Dado que uno o más drones pierden señal, cuando el sistema detecta la pérdida, entonces muestra un ícono de alerta y el mensaje "Conexión perdida con Dron-X. Intentando reconexión...            | EP-013 |
| WA-012 | Consultar reportes de eficiencia   | Como supervisor, quiero consultar reportes de eficiencia operativa (tiempo/hectárea, costo/hectárea), para evaluar el desempeño y optimizar recursos. | 1. Escenario 1: Reporte de eficiencia<br>Dado que el supervisor está en la sección "Reportes de Eficiencia", cuando selecciona un rango de fechas y hace clic en "Generar", entonces el sistema calcula y muestra métricas como tiempo promedio por hectárea, costo por hectárea, eficiencia de insumos y horas-hombre invertidas.<br/>2. Escenario 2: Comparativa<br/>Dado que el supervisor necesita comparar el desempeño entre operadores, cuando selecciona "Comparar Operadores", entonces el sistema muestra una tabla comparativa con las métricas de cada uno.                         | EP-014 |
| WA-013 | Gestionar inventario de insumos   | Como supervisor, quiero gestionar el inventario de pesticidas y fertilizantes disponibles, para planificar compras y garantizar el abastecimiento. | 1. Escenario 1: Visualización de inventario<br>Dado que el supervisor está en la sección "Inventario", cuando accede al módulo, entonces el sistema muestra la lista de insumos con stock actual, umbral mínimo y estado de alerta.<br/>2. Escenario 2: Alerta de stock bajo<br>Dado que un insumo tiene stock por debajo del umbral mínimo, cuando el supervisor accede al inventario, entonces el sistema resalta el producto en rojo y muestra la alerta "Stock crítico - Realizar pedido".                                                                                                  | EP-015 |


---

## 3.2. Impact Mapping

<div align="center">

![Impact Mapping](assets/Chapter3/Impact_Mapping.png)

</div>

**Descripción:**

<p align="justify">

Diagrama que muestra la relación entre los actores clave (agricultor, operador y supervisor), 
los objetivos estratégicos del proyecto y las funcionalidades necesarias para lograrlos

</p>

---

## 3.3. Product Backlog

| ID     | Epic | User Story | Prioridad         | Story Points | Estado   |
|:-------| :--- | :--- |:------------------|:------------:|:---------|
| LP-001 | Landing Page | Como visitante, quiero visualizar la propuesta de valor de AgriDron en la página principal, para entender rápidamente qué ofrece el servicio. | ALTA              |      2       | To-Do    |
| LP-002 | Landing Page | Como visitante, quiero ver los servicios y características principales de AgriDron, para evaluar si la solución satisface mis necesidades. | ALTA              |      2       | To-Do    |
| LP-003 | Landing Page | Como visitante, quiero conocer los planes de precios y suscripción, para tomar una decisión informada sobre la contratación del servicio. | ALTA              |      3       | To-Do    |
| LP-004 | Landing Page | Como visitante, quiero registrarme en la plataforma proporcionando mis datos básicos, para acceder a las funcionalidades de la Web Application. | ALTA              |      5       | To-Do    |
| LP-005 | Landing Page | Como visitante registrado, quiero iniciar sesión con mis credenciales, para acceder a la Web Application. | ALTA              |      3       | To-Do    |
| LP-006 | Landing Page | Como visitante, quiero acceder a los términos y condiciones de servicio, para conocer las políticas de uso y privacidad. | BAJA              |      1       | To-Do    |
| LP-007 | Landing Page | Como visitante, quiero cambiar el idioma del sitio entre español e inglés, para navegar en mi idioma preferido. | MEDIA             |      5       | To-Do    |
| WA-008 | Web App - Agricultor | Como agricultor, quiero registrar mis fincas en la plataforma, para gestionar mis parcelas de forma centralizada. | ALTA              |      5       | To-Do    |
| WA-009 | Web App - Agricultor | Como agricultor, quiero dibujar el área de fumigación sobre un mapa interactivo, para planificar misiones de manera precisa. | ALTA              |      8       | To-Do    |
| WA-010 | Web App - Agricultor | Como agricultor, quiero crear una misión de fumigación seleccionando el área y el cultivo, para solicitar el servicio. | ALTA              |      5       | To-Do    |
| WA-011 | Web App - Agricultor | Como agricultor, quiero consultar el historial de misiones de fumigación de mis fincas, para dar seguimiento a las operaciones realizadas. | MEDIA             |      5       | To-Do    |
| WA-012 | Web App - Agricultor | Como agricultor, quiero generar reportes de productividad por hectárea, para justificar inversiones y tomar decisiones estratégicas. | MEDIA             |      8       | To-Do    |
| WA-013 | Web App - Operador | Como operador, quiero visualizar las misiones de fumigación que me han sido asignadas, para planificar mi jornada de trabajo. | ALTA              |      3       | To-Do    |
| WA-014 | Web App - Operador | Como operador, quiero actualizar el estado de una misión (En Progreso / Completada), para mantener informado al agricultor y al supervisor. | ALTA              |      5       | To-Do    |
| WA-015 | Web App - Operador | Como operador, quiero registrar mis horas trabajadas con verificación de ubicación, para garantizar precisión en la información de mi jornada. | MEDIA             |      8       | To-Do    |
| WA-016 | Web App - Operador | Como operador, quiero registrar incidencias durante la operación (clima adverso, falla técnica, etc.), para documentar interrupciones y justificar reprogramaciones. | MEDIA             |      5       | To-Do    |
| WA-017 | Web App - Supervisor | Como supervisor, quiero asignar misiones creadas por agricultores a operadores disponibles, para coordinar las operaciones de campo. | ALTA              |      5       | To-Do    |
| WA-018 | Web App - Supervisor | Como supervisor, quiero ver el estado y ubicación de todos los drones activos en tiempo real, para optimizar la coordinación de misiones. | ALTA              |      8       | To-Do    |
| WA-019 | Web App - Supervisor | Como supervisor, quiero consultar reportes de eficiencia operativa (tiempo/hectárea, costo/hectárea), para evaluar el desempeño y optimizar recursos. | MEDIA             |      8       | To-Do    |
| WA-020 | Web App - Supervisor | Como supervisor, quiero gestionar el inventario de pesticidas y fertilizantes disponibles, para planificar compras y garantizar el abastecimiento. | MEDIA       |      5       | To-Do     |


---

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

> Branding (Identidad de Marca)

| Elemento | Descripcion        | 
|:---------|:-------------------| 
| Nombre de la Startup   | AgriDron Solutions |
| Nombre del Producto   | AgriDron           | 
| Eslogan   | "Smart Farming, Precision Agriculture" / "Agricultura Inteligente, Precisión que Cosecha Resultados"       | 
| Concepto de Marca   | La marca combina la tecnología de los drones (componente tecnológico y de precisión) con los valores del campo y la agricultura (componente natural y humano). El nombre "AgriDron" fusiona "Agriculture" y "Drone", representando la convergencia entre el mundo agrícola tradicional y la innovación tecnológica        | 
| Arquetipo de Marca   | El Experto / El Creador — AgriDron se posiciona como un socio tecnológico confiable y especializado, que empodera a los agricultores con herramientas de precisión para optimizar sus cultivos .       | 
| Personalidad de Marca   | Profesional, confiable, innovador, cercano, accesible y transparente.       | 

> Valores Visuales

| Valor                  | Aplicacion                                                                                                                                                                                                                                                                                                         | 
|:-----------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| Precisión              | Líneas limpias, bordes definidos, grids estructurados.                                                                                                                                                                                                                                                                                                |
| Confianza              | Colores sobrios (verde oscuro, azul), tipografía legible y profesional.                                                                                                                                                                                                                                                                                                           | 
| Innovación             | Toques de color vibrante (teal, amarillo) para elementos interactivos (CTAs, iconos, estados activos)                                                                                                                                                                                                              | 
| Cercanía               | Uso de fotografía real de campos y cultivos (evitar imágenes genéricas de stock)  | 
| Sostenibilidad         | Paleta de colores inspirada en la naturaleza y la agricultura                                                                                                                   | 

> Typography (Tipografía)

| Role                  | Familia Tipográfica  | Uso                                                                         | 
|:----------------------|:---------------------|:----------------------------------------------------------------------------|  
| Brand                 | Inter (sans-serif)   | Títulos principales (Display, Headline), elementos de marca, hero sections. |
| Plain                 | Roboto (sans-serif)  | Cuerpo de texto, párrafos, etiquetas, botones, contenido general.           |
| Mono                  | Roboto Mono          | Código, datos técnicos, logs (aplicación interna).                          |

> Type Scale (Jerarquía Tipográfica)

| Style           | Size | Weight | Line Height | Uso                             |                                                                   
|:----------------|:-----|:-------|:------------|:--------------------------------|    
| Display Large   | 57px | 400    | 64px        | Hero text (Landing Page)        |
| Display Medium  | 45px | 400    | 52px        | Títulos principales de sección  |
| Display Small   | 36px | 400    | 44px        | Subtítulos de sección           |
| Headline Large  | 32px | 400    | 40px        | Títulos de página (Dashboard)   |
| Headline Medium | 28px | 400    | 36px        | Títulos de sección (Dashboard)  |
| Headline Small  | 24px | 400    | 32px        | Títulos de tarjetas             |
| Title Large     | 22px | 500    | 28px        | Títulos de App Bar              |
| Title Medium    | 16px | 500    | 24px        | Títulos de elementos de lista   |
| Title Smal      | 14px | 500    | 20px        | Tabs, navegación                |
| Body Large      | 16px | 400    | 24px        | Texto principal                 |
| Body Medium     | 14px | 400    | 20px        | Texto secundario, descripciones |
| Body Small      | 12px | 400    | 16px        | Captions, notas a pie           |
| Label Large     | 14px | 500    | 20px        | Texto de botones                |
| Label Medium    | 12px | 500    | 16px        | Etiquetas de navegación         |
| Label Small     | 11px | 500    | 16px        | Badges, contadores              |

> Colors (Paleta de Colores)

| Role              | Color         | Hex  | Uso  |                                                                   
|:------------------|:--------------|:-----|:-----|   
| Primary           | Forest Green  | 400  | 64px |
| Primary Light     | 45px          | 400  | 52px |
| Secondary         | 36px          | 400  | 44px |
| Tertiary / Accent | 32px          | 400  | 40px |
| Headline Medium   | 28px          | 400  | 36px |
| Surface           | 24px          | 400  | 32px |
| Background        | 22px          | 500  | 28px |
| Text Primary      | 16px          | 500  | 24px |
| Text Secondary    | 14px          | 500  | 20px |
| Error             | 16px          | 400  | 24px |
| Success           | 14px          | 400  | 20px |
| Warning           | 12px          | 400  | 16px |

[PEGAR AQUÍ LAS GENERAL STYLE GUIDELINES.]
---

## 4.2. Information Architecture

### 4.2.1. Organization Systems

> Jerarquía de Contenido

| Nivel                  | Landing Page                                     | Web Application                                                 |                                                                   
|:-----------------------|:-------------------------------------------------|:----------------------------------------------------------------|   
| Nivel 1 (Global)       | Header<br/>(Logo + Navegación principal)         | App Bar (Logo + Menú principal + Perfil de usuario)             |
| Nivel 2 (Secciones)    | Hero, Servicios, Beneficios, Planes, Testimonios | Dashboard, Misiones, Fincas, Monitoreo, Reportes, Configuración |
| Nivel 3 (Subsecciones) | Detalle de cada sección                          | Pantallas de detalle de cada módulo                             |
| Nivel 4 (Acciones)     | CTAs<br/>(Registro, Login, Ver Planes)           | Formularios, tablas, mapas, acciones específicas                |

> Esquemas de Organización por Contexto

| Contexto             | Esquema de Organización        | Descripción                                                                                                                       |                                                                   
|:---------------------|:-------------------------------|:----------------------------------------------------------------------------------------------------------------------------------|   
| Landing Page         | Secuencial (Step-by-Step)      | El contenido guía al visitante desde el descubrimiento hasta la conversión:<br/>Hero → Beneficios → Servicios → Planes → Registro |
| Dashboard (Web App)  | Jerárquica (Visual Hierarchy)  | Organización por importancia: KPIs principales arriba, gráficos y tablas debajo, accesos rápidos en el lateral                    |
| Módulo de Fincas     | Por Tópicos (Topical)          | Agrupación por fincas, cada finca contiene parcelas y sus detalles                                                                |
| Módulo de Misiones   | Cronológico (Chronological)    | Las misiones se organizan por fecha, desde la más reciente a la más antigua                                                       |
| Módulo de Operadores | Por Audiencia (Audience-based) | Los perfiles se organizan por rol (Operador, Supervisor) y por disponibilidad                                                     |
| Reportes             | Matricial (Matrix)             | Combinación de filtros: por finca, por fecha, por tipo de cultivo, por operador                                                   |

> Visual Hierarchy (Jerarquía Visual)

| Nivel        | Elementos                | Landing Page                                | Web Application                                                           |                                                                   
|:-------------|:-------------------------|:--------------------------------------------|:--------------------------------------------------------------------------|   
| Primario     | Contenido más importante | Hero section<br/>(propuesta de valor + CTA) | KPIs principales (misiones activas, hectáreas fumigadas, ahorro estimado) |
| Secundario   | Contenido de soporte     | Secciones de Servicios y Beneficios         | Tablas de misiones, gráficos de rendimiento                               |
| Terciario    | Detalles y opciones      | Testimonios, planes de precios              | Historial, configuraciones, detalles de misiones                          |
| Cuaternario  | Elementos globales       | Footer<br/>(enlaces legales, redes sociales)| App Bar, navegación lateral, pie de página                                |


### 4.2.2. Labeling Systems

> Tabla de Etiquetas por Contexto

| Contexto                | Etiqueta en Español | Etiqueta en Inglés | Descripción / Uso                           |                                                                   
|:------------------------|:--------------------|:-------------------|:--------------------------------------------|   
| Navegación Global       |                     |                    |                                             |
|                         | Inicio              | Home               | Página principal                            |
|                         | Misiones            | Missions           | Gestión de misiones de fumigación           |
|                         | Fincas              | Farms              | Gestión de fincas y parcelas                |
|                         | Monitoreo           | Monitoring         | Visualización de drones en tiempo real      |
|                         | Reportes            | Reports            | Generación y consulta de reportes           |
|                         | Configuración       | Settings           | Ajustes de cuenta y preferencias            |
|                         | Cerrar Sesión       | Logout             | Cerrar la sesión actual                     |
| Secciones del Dashboard |                     |                    |                                             |
|                         | Resumen             | Overview           | KPIs y métricas principales                 |
|                         | Mis Fincas          | My Farms           | Listado de fincas registradas               |
|                         | Mis Misiones        | My Missions        | Misiones del agricultor autenticado         |
|                         | Asignar Misiones    | Assign Missions    | Panel del supervisor para asignar           |
|                         | Misiones Asignadas  | Assigned Missions  | Misiones recibidas por el operador          |
|                         | Estado de Drones    | Drone Status       | Monitoreo de drones activos                 |
|                         | Historial           | History            | Historial de operaciones realizadas         |
| Acciones Comunes        |                     |                    |                                             |
|                         | Crear               | Create             | Crear un nuevo registro                     |
|                         | Editar              | Edit               | Modificar un registro existente             |
|                         | Eliminar            | Delete             | Eliminar un registro                        |
|                         | Guardar             | Save               | Guardar cambios                             |
|                         | Cancelar            | Cancel             | Cancelar la operación actual                |
|                         | Generar             | Generate           | Generar un reporte o documento              |
|                         | Descargar           | Download           | Descargar un archivo                        |
|                         | Asignar             | Assign             | Asignar un recurso o tarea                  |
|                         | Iniciar             | Start              | Iniciar una misión o proceso                |
|                         | Completar           | Complete           | Completar una misión                        |
|                         | Reprogramar         | Reschedule         | Reprogramar una misión                      |
|                         | Buscar              | Search             | Iniciar una búsqueda                        |
| Entidades del Dominio   |                     |                    |                                             |
|                         | Finca               | Farm               | Propiedad agrícola registrada               |
|                         | Parcela             | Parcel             | Subdivisión de una finca                    |
|                         | Misión              | Mission            | Operación de fumigación planificada         |
|                         | Dron                | Drone              | Unidad aérea para fumigación                |
|                         | Operador            | Operator           | Personal asignado a misiones                |
|                         | Supervisor          | Supervisor         | Coordinador de operaciones                  |
|                         | Insumo              | Input              | Pesticidas, fertilizantes y otros productos |
|                         | Reporte             | Report             | Documento con datos y análisis              |
|                         | Incidencia          | Incident           | Evento no planificado durante la operación  |
|                         | Cultivo             | Crop               | Tipo de planta cultivada                    |
| Atributos y Estados     |                     |                    |                                             |
|                         | Pendiente           | Pending            | Estado inicial de una misión                |
|                         | Asignada            | Assigned           | Misión asignada a un operador               |
|                         | En Progreso         | In Progress        | Misión en ejecución                         |
|                         | Completada          | Completed          | Misión finalizada exitosamente              |
|                         | Cancelada           | Cancelled          | Misión cancelada                            |
|                         | Pausada             | Paused             | Misión detenida temporalmente               |
|                         | Activo              | Active             | Dron o usuario en operación                 |
|                         | Inactivo            | Inactive           | Dron o usuario sin actividad                |
|                         | Disponible          | Available          | Operador o recurso disponible               |
|                         | Ocupado             | Busy               | Operador o recurso no disponible            |
|                         | Crítico             | Critical           | Alerta de alta prioridad                    |
| Mensajes de Feedback    |                     |                    |                                             |
|                         | Éxito               | Success            | Operación completada correctamente          |
|                         | Error               | Error              | Fallo en la operación                       |
|                         | Advertencia         | Warning            | Situación que requiere atención             |
|                         | Cargando...         | Loading...         | Procesamiento de datos en curso             |
|                         | Sin datos           | No data            | No hay información para mostrar             |
|                         | ¿Está seguro?       | Are you sure?      | Confirmación de acción destructiva          |


### 4.2.3. SEO Tags and Meta Tags

> Landing Page - SEO Tags y Meta Tags

| Tag                   | Valor                                                                                                                                                                          | Justificación                                                                                                                                                                |
|:----------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Title**             | `AgriDron Solutions - Agricultura de Precisión con Drones \| Smart Farming`                                                                                                    | El título incluye la marca, el servicio principal (agricultura de precisión con drones) y un keyword secundario (smart farming). Longitud: 60 caracteres.                    |
| **Description**       | `AgriDron Solutions ofrece fumigación autónoma con drones, monitoreo en tiempo real y reportes inteligentes para agricultores. Reduce costos y optimiza tus cosechas.`         | Describe el valor del servicio, incluye keywords principales (fumigación con drones, monitoreo en tiempo real, reportes) y el beneficio principal. Longitud: 158 caracteres. |
| **Keywords**          | `fumigación con drones, agricultura de precisión, monitoreo de cultivos, drones agrícolas, fumigación autónoma, AgriDron, agricultura inteligente`                             | Palabras clave relevantes para el sector agrícola y la tecnología de drones.                                                                                                 |
| **Author**            | `AgriDron Solutions Team`                                                                                                                                                      | Identifica al autor del contenido.                                                                                                                                           |
| **Robots**            | `index, follow`                                                                                                                                                                | Permite a los motores de búsqueda indexar y seguir enlaces.                                                                                                                  |
| **Canonical**         | `https://www.agridron.com/`                                                                                                                                                    | URL canónica de la página principal.                                                                                                                                         |
| **Open Graph (OG)**   |                                                                                                                                                                                |                                                                                                                                                                              |
| `og:title`            | `AgriDron Solutions - Agricultura de Precisión con Drones`                                                                                                                     | Título para compartir en redes sociales.                                                                                                                                     |
| `og:description`      | `Optimiza tus cultivos con fumigación autónoma, monitoreo en tiempo real y reportes inteligentes. AgriDron transforma la agricultura tradicional en agricultura de precisión.` | Descripción para compartir en redes sociales.                                                                                                                                |
| `og:type`             | `website`                                                                                                                                                                      | Tipo de contenido.                                                                                                                                                           |
| `og:url`              | `https://www.agridron.com/`                                                                                                                                                    | URL de la página.                                                                                                                                                            |
| `og:image`            | `https://www.agridron.com/assets/img/og-image.jpg`                                                                                                                             | Imagen representativa (1200x630px).                                                                                                                                          |
| **Twitter Card**      |                                                                                                                                                                                |                                                                                                                                                                              |
| `twitter:card`        | `summary_large_image`                                                                                                                                                          | Formato de tarjeta para Twitter.                                                                                                                                             |
| `twitter:title`       | `AgriDron Solutions - Agricultura de Precisión con Drones`                                                                                                                     | Título para Twitter.                                                                                                                                                         |
| `twitter:description` | `Optimiza tus cultivos con fumigación autónoma, monitoreo en tiempo real y reportes inteligentes con AgriDron.`                                                                | Descripción para Twitter.                                                                                                                                                    |
| `twitter:image`       | `https://www.agridron.com/assets/img/og-image.jpg`                                                                                                                             | Imagen para Twitter.                                                                                                                                                         |


> Landing Page - SEO Tags y Meta Tags

| Tag                         | Valor                                                                                                                           | Justificación                             |
|:----------------------------|:--------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------|
| **Title (Dashboard)**       | `AgriDron - Panel de Control \| Smart Farming`                                                                                  | Título del Dashboard (con autenticación). |
| **Description (Dashboard)** | `Gestiona tus fincas, misiones de fumigación y monitorea el rendimiento de tus cultivos desde el panel de control de AgriDron.` | Descripción del Dashboard.                |


### 4.2.4. Searching Systems

> Alcance de Búsqueda

| Contexto       | Elementos Buscables                                             | Descripción                                  |
|:---------------|:----------------------------------------------------------------|:---------------------------------------------|
| **Misiones**   | ID de misión, nombre de finca, fecha, estado, operador asignado | Búsqueda de misiones por múltiples criterios |
| **Fincas**     | Nombre de finca, ubicación, tipo de cultivo                     | Búsqueda de fincas registradas               |
| **Operadores** | Nombre, apellido, rol, disponibilidad                           | Búsqueda de personal                         |
| **Reportes**   | Fecha, finca, tipo de cultivo, operador                         | Búsqueda de reportes generados               |
| **Insumos**    | Nombre del producto, tipo, stock                                | Búsqueda de inventario                       |

> Tipos de Búsqueda

| Tipo                   | Descripción                                                           | Contexto de Uso                                 |
|:-----------------------|:----------------------------------------------------------------------|:------------------------------------------------|
| **Búsqueda Simple**    | Campo de texto único con autocompletado y sugerencias                 | Búsqueda rápida de fincas, misiones, operadores |
| **Búsqueda Avanzada**  | Múltiples filtros combinados (fecha, estado, tipo, etc.)              | Panel de Reportes, Historial de Misiones        |
| **Filtros de Listado** | Filtros predefinidos en la interfaz (por estado, por tipo, por fecha) | Listados de misiones, operadores, fincas        |

> Búsqueda por Contexto

| Contexto       | Tipo de Búsqueda           | Filtros Disponibles                       | Comportamiento                                                        |
|:---------------|:---------------------------|:------------------------------------------|:----------------------------------------------------------------------|
| **Misiones**   | Búsqueda Simple + Avanzada | Estado, Fecha, Finca, Operador, Cultivo   | Resultados en tabla paginada. Orden predeterminado: fecha descendente |
| **Fincas**     | Búsqueda Simple            | Nombre, Ubicación                         | Resultados en lista con vista de tarjetas.                            |
| **Operadores** | Búsqueda Simple + Filtros  | Rol (Operador/Supervisor), Disponibilidad | Resultados en tabla con paginación.                                   |
| **Historial**  | Búsqueda Avanzada          | Fecha (rango), Finca, Tipo de Operación   | Resultados en tabla con exportación a CSV/Excel.                      |

> Mensajes de Búsqueda

| Escenario                | Mensaje en Español                                                                               | Mensaje en Inglés                                                               |
|:-------------------------|:-------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------|
| **Sin resultados**       | "No se encontraron resultados para tu búsqueda. Prueba con otros términos o ajusta los filtros." | "No results found for your search. Try different terms or adjust your filters." |
| **Búsqueda en progreso** | "Buscando..."                                                                                    | "Searching..."                                                                  |
| **Error en la búsqueda** | "Ocurrió un error al realizar la búsqueda. Por favor, intenta nuevamente."                       | "An error occurred while searching. Please try again."                          |


### 4.2.5. Navigation Systems

> Landing Page - Estructura de Navegación

```
┌───────────────────────────────────────────────────────────────────────────────────┐
│  [Logo AgriDron]  │  Inicio │ Servicios │ Planes │ Contacto │ [Login] [Registro]  │
├───────────────────────────────────────────────────────────────────────────────────┤
│                                                                                   │
│                                  Hero Section                                     │
│                       (Propuesta de valor + CTA principal)                        │
│                                                                                   │
├───────────────────────────────────────────────────────────────────────────────────┤
│                             Sección de Servicios                                  │
│                           (3-4 tarjetas con iconos)                               │
├───────────────────────────────────────────────────────────────────────────────────┤
│                              Sección de Beneficios                                │
│                         (Lista de beneficios con iconos)                          │
├───────────────────────────────────────────────────────────────────────────────────┤
│                                 Sección de Planes                                 │
│                          (2-3 opciones de precios + CTA)                          │
├───────────────────────────────────────────────────────────────────────────────────┤
│                              Sección de Testimonios                               │
│                             (Frases de usuarios reales)                           │
├───────────────────────────────────────────────────────────────────────────────────┤
│                                       Footer                                      │
│              [Logo] │ Términos │ Privacidad │ Contacto │ Redes Sociales           │
└───────────────────────────────────────────────────────────────────────────────────┘
```

> Web Application - Estructura de Navegación

```
┌─────────────────────────────────────────────────────────────────┐
│  [Logo AgriDron]                 │  [Notificaciones] │ [Perfil] │
├──────────┬──────────────────────────────────────────────────────┤
│          │                                                      │
│ 📊       │              ÁREA DE CONTENIDO                       │
│ Dashboard│                                                      │
│          │            (Panel principal según                    │
│ 🏠       │             el módulo seleccionado)                  │
│ Fincas   │                                                      │
│          │                                                      │
│ ✈️       │                                                      │
│ Misiones │                                                      │
│          │                                                      │
│ 📡       │                                                      │
│ Monitoreo│                                                      │
│          │                                                      │
│ 📈       │                                                      │
│ Reportes │                                                      │
│          │                                                      │
│ 📦       │                                                      │
│Inventario│                                                      │
│          │                                                      │
│ 👥       │                                                      │
│ Personal │                                                      │
│          │                                                      │
│ ⚙️       │                                                      │
│ Config.  │                                                      │
│          │                                                      │
│ 🚪       │                                                      │
│ Cerrar   │                                                      │
│ Sesión   │                                                      │
├──────────┴──────────────────────────────────────────────────────┤
│  © 2026 AgriDron Solutions - Todos los derechos reservados      │
└─────────────────────────────────────────────────────────────────┘
```

> Tipos de Navegación

| Tipo de Navegación           | Descripción                                                 | Contexto de Uso                                            |
|:-----------------------------|:------------------------------------------------------------|:-----------------------------------------------------------|
| **Global (Principal)**       | Navegación lateral (sidebar) con acceso a todos los módulos | Web Application (todas las páginas)                        |
| **Secundaria (Tabs)**        | Pestañas dentro de un módulo para cambiar entre vistas      | Misiones: "Pendientes", "En Progreso", "Completadas"       |
| **Contextual (Breadcrumbs)** | Ruta de navegación que muestra la ubicación actual          | Reportes > Historial > Detalle de Misión                   |
| **De Acción (Botones)**      | Botones que realizan acciones específicas                   | Crear, Editar, Eliminar, Generar, Asignar                  |
| **De Paginación**            | Navegación entre páginas de listados largos                 | Tablas de misiones, historial, operadores                  |
| **De Enlaces Internos**      | Enlaces que permiten navegar entre páginas relacionadas     | Desde el detalle de una misión, enlace a la finca asociada |

> Patrones de Navegación por Rol

| Rol            | Módulos Principales                                              | Accesos Rápidos                                   |
|:---------------|:-----------------------------------------------------------------|:--------------------------------------------------|
| **Agricultor** | Dashboard, Fincas, Misiones, Reportes, Historial                 | Crear Misión, Ver Fincas, Generar Reporte         |
| **Operador**   | Dashboard, Mis Misiones, Incidencias, Horas Trabajadas           | Iniciar Misión, Reportar Incidencia               |
| **Supervisor** | Dashboard, Misiones, Operadores, Monitoreo, Reportes, Inventario | Asignar Misión, Monitorear Drones, Ver Eficiencia |
---

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

![Landing Page Wireframe](assets/chapter4/landing_wireframe.png)

**Descripción:**

El wireframe de la Landing Page en versión Desktop presenta la estructura y distribución de los principales elementos que conforman la página web de AgriDron Solutions, sin aplicar todavía los estilos visuales definitivos. Su objetivo es definir la jerarquía de información y organizar el recorrido que realizará el visitante.

### 4.3.2. Landing Page Mock-up

![Landing Page Mock-up](assets/chapter4/landing_mockup.png)

**Descripción:**

El mockup de la Landing Page en versión Desktop representa la propuesta visual de alta fidelidad de AgriDron Solutions. A partir de la estructura definida en el wireframe, se incorporan colores, tipografías, imágenes, iconografía, botones y demás elementos gráficos relacionados con la identidad de la plataforma.

---

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

![Web Applications Wireframes](assets/chapter4/Web_Applications_Wireframes.png)


### 4.4.2. Web Applications Wireflow Diagrams

![Web Applications Wireflow Diagrams](assets/chapter4/Web_Applications_Wireflow_Diagrams.png)


### 4.4.3. Web Applications Mock-ups

![Web Applications Mock-ups](assets/chapter4/Web_Applications_Mock-ups.png)

### 4.4.4. Web Applications User Flow Diagrams

![Web Applications User Flow Diagrams](assets/chapter4/Web_Applications_User_Flow_Diagrams.png)

---

## 4.5. Web Applications Prototyping

[PEGAR AQUÍ EL ENLACE / EVIDENCIA DEL PROTOTIPO.]

---

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming
El **Design-Level Event Storming** permite representar el flujo principal del dominio de AgriDron Solutions mediante comandos, eventos de dominio, actores, políticas y agregados. A partir de este análisis se identifican cuatro áreas principales del dominio y se particiona la solución en los siguientes **Bounded Contexts**:

1. **Field Management**
2. **Flight Operations**
3. **Weather Integration**
4. **Analytics & Reporting**

### Flujo principal del dominio

El flujo comienza cuando un agricultor solicita un servicio de fumigación y termina con el registro de los resultados y la generación de información histórica para consulta.

```mermaid
flowchart LR
    A["Agricultor / Cliente"] --> C1["Registrar parcela"]
    C1 --> E1["Parcela registrada"]
    E1 --> C2["Delimitar área de fumigación"]
    C2 --> E2["Área de fumigación delimitada"]
    E2 --> C3["Crear misión"]
    C3 --> E3["Misión creada"]
    E3 --> C4["Programar misión"]
    C4 --> E4["Misión programada"]
    E4 --> P1{"Política: verificar condiciones meteorológicas"}
    P1 --> C5["Consultar condiciones meteorológicas"]
    C5 --> E5["Condiciones meteorológicas obtenidas"]
    E5 --> P2{"Política: evaluar condiciones"}
    P2 -->|Condiciones favorables| E6["Misión autorizada"]
    P2 -->|Condiciones desfavorables| E7["Alerta meteorológica generada"]
    E6 --> C6["Iniciar operación"]
    C6 --> E8["Operación iniciada"]
    E8 --> C7["Monitorear operación"]
    C7 --> E9["Estado de operación actualizado"]
    E9 --> P3{"¿Ocurrió un incidente?"}
    P3 -->|Sí| C8["Registrar incidente"]
    C8 --> E10["Incidente registrado"]
    E10 --> C7
    P3 -->|No| C9["Finalizar operación"]
    C9 --> E11["Operación finalizada"]
    E11 --> C10["Registrar resultado"]
    C10 --> E12["Resultado de misión registrado"]
    E12 --> C11["Actualizar historial"]
    C11 --> E13["Historial actualizado"]
    E13 --> C12["Generar reporte"]
    C12 --> E14["Reporte generado"]
```

### Actores principales

| Actor | Responsabilidad |
|---|---|
| **Agricultor / Cliente** | Solicita servicios y consulta información de sus operaciones. |
| **Operador técnico** | Registra y planifica misiones, verifica condiciones, ejecuta y monitorea operaciones y registra resultados. |
| **Sistema meteorológico externo** | Proporciona información climática para apoyar la planificación. |

### Comandos

| Comando | Origen | Propósito |
|---|---|---|
| Registrar parcela | Operador | Crear información de una parcela agrícola. |
| Delimitar área de fumigación | Operador | Definir el área que será tratada. |
| Crear misión | Operador | Crear una operación de fumigación asociada a una parcela. |
| Programar misión | Operador | Definir fecha y hora planificadas. |
| Consultar condiciones meteorológicas | Sistema | Obtener información climática de la API externa. |
| Iniciar operación | Operador | Marcar el inicio de la misión. |
| Monitorear operación | Operador / Sistema | Actualizar estado y ubicación simulada del dron. |
| Registrar incidente | Operador | Registrar situaciones inesperadas. |
| Finalizar operación | Operador | Marcar la finalización de la misión. |
| Registrar resultado | Operador | Registrar hectáreas tratadas, volumen aplicado y observaciones. |
| Actualizar historial | Sistema | Incorporar la misión finalizada al historial. |
| Generar reporte | Usuario / Sistema | Generar información consolidada de la operación. |

### Eventos de dominio

| Evento | Descripción |
|---|---|
| **Parcela registrada** | Se creó una parcela con su información básica. |
| **Área de fumigación delimitada** | Se definió geográficamente el área que será tratada. |
| **Misión creada** | Se creó una nueva misión. |
| **Misión programada** | La misión tiene fecha y hora planificadas. |
| **Condiciones meteorológicas obtenidas** | El sistema recibió información climática externa. |
| **Misión autorizada** | Las condiciones disponibles permiten continuar con la planificación. |
| **Alerta meteorológica generada** | Las condiciones requieren advertencia, pausa o reprogramación. |
| **Operación iniciada** | Comenzó la ejecución de la misión. |
| **Estado de operación actualizado** | Se actualizó el estado o ubicación simulada del dron. |
| **Incidente registrado** | Se registró una situación inesperada. |
| **Operación finalizada** | Terminó la ejecución de la misión. |
| **Resultado de misión registrado** | Se registraron las métricas y observaciones finales. |
| **Historial actualizado** | La misión finalizada está disponible como antecedente. |
| **Reporte generado** | Se generó información consolidada. |

### Políticas y reglas de negocio

| Política | Regla |
|---|---|
| **Verificación meteorológica previa** | Antes de iniciar una misión se deben consultar las condiciones meteorológicas disponibles. |
| **Evaluación de condiciones** | Si las condiciones son desfavorables, se genera una alerta para apoyar la decisión de pausar o reprogramar. |
| **Registro de incidentes** | Una incidencia debe quedar registrada para mantener trazabilidad. |
| **Registro de resultados** | Una misión finalizada debe conservar información sobre el trabajo realizado. |
| **Actualización del historial** | Los resultados de misiones finalizadas deben estar disponibles para consultas posteriores. |

### Agregados principales

- **Farm / Parcel:** concentra información territorial y agrícola.
- **Mission:** concentra la información principal de una operación y su ciclo de vida.
- **Drone:** representa el recurso utilizado para ejecutar una misión.
- **Mission Report:** concentra los resultados registrados al finalizar una operación.

---

# 4.6.1.1. Bounded Contexts

La partición del dominio se realiza considerando las responsabilidades y conceptos principales de la solución.

## Bounded Context 1: Field Management

**Responsabilidad:** administrar la información de campos y parcelas utilizada para planificar servicios.

**Conceptos:** campo, parcela, cultivo, ubicación, área de fumigación y coordenadas.

**Operaciones:** registrar/actualizar parcela, visualizarla en mapa, delimitar área y asociar cultivo.

**Eventos:** `ParcelaRegistrada`, `AreaFumigacionDelimitada`, `InformacionCultivoRegistrada`.

## Bounded Context 2: Flight Operations

**Responsabilidad:** gestionar la planificación, ejecución y seguimiento de misiones.

**Conceptos:** misión, dron, programación, estado, operación, incidente y hectáreas tratadas.

**Operaciones:** crear/programar misión, iniciar operación, actualizar estado, registrar incidentes, finalizar operación y registrar resultados.

**Eventos:** `MisionCreada`, `MisionProgramada`, `OperacionIniciada`, `EstadoOperacionActualizado`, `IncidenteRegistrado`, `OperacionFinalizada`.

## Bounded Context 3: Weather Integration

**Responsabilidad:** encapsular la integración con la API meteorológica y proporcionar información climática para apoyar la planificación.

**Conceptos:** consulta meteorológica, condición, viento, temperatura, humedad, precipitación y alerta.

**Operaciones:** consultar condiciones, consultar pronóstico, evaluar condiciones y generar alertas.

**Eventos:** `CondicionesMeteorologicasObtenidas`, `CondicionesEvaluadas`, `AlertaMeteorologicaGenerada`.

## Bounded Context 4: Analytics & Reporting

**Responsabilidad:** conservar y presentar información histórica de las operaciones.

**Conceptos:** historial, resultado, reporte, estadística y métrica.

**Operaciones:** registrar resultados, consultar historial, consolidar métricas y generar reportes.

**Eventos:** `ResultadoMisionRegistrado`, `HistorialActualizado`, `ReporteGenerado`.

### Relación entre Bounded Contexts

```mermaid
flowchart LR
    FM["Field Management"]
    FO["Flight Operations"]
    WI["Weather Integration"]
    AR["Analytics & Reporting"]
    API["API Meteorológica Externa"]

    FM -->|"Información de parcela y área"| FO
    FO -->|"Solicitud de condiciones"| WI
    WI -->|"Condiciones y alertas"| FO
    FO -->|"Resultados de operación"| AR
    WI -->|"Consulta"| API
```

### Justificación

- **Field Management** mantiene la información territorial.
- **Flight Operations** gestiona el ciclo de vida de la misión.
- **Weather Integration** aísla la dependencia externa de información meteorológica.
- **Analytics & Reporting** transforma resultados en información histórica y reportes.

### 4.6.2. Software Architecture Context Diagram
El **System Context Diagram de C4** representa el sistema como una única unidad y muestra los usuarios y sistemas externos que interactúan directamente con él. En este nivel no se detallan tecnologías internas.

```mermaid
C4Context
    title System Context Diagram - AgriDron Solutions

    Person(farmer, "Agricultor / Cliente", "Solicita servicios de fumigación y consulta información de sus operaciones.")
    Person(operator, "Operador Técnico", "Gestiona parcelas, planifica misiones, monitorea operaciones y registra resultados.")

    System(agridron, "AgriDron Solutions", "Plataforma web para la planificación y monitoreo de operaciones de fumigación agrícola mediante drones.")

    System_Ext(weather, "API Meteorológica", "Servicio externo que proporciona información de condiciones meteorológicas.")

    Rel(farmer, agridron, "Solicita y consulta servicios")
    Rel(operator, agridron, "Gestiona parcelas, misiones y operaciones")
    Rel(agridron, weather, "Consulta condiciones meteorológicas")
```

### Descripción

**AgriDron Solutions** es el sistema principal en el alcance de la solución. El **Agricultor / Cliente** interactúa con la plataforma para solicitar y consultar información relacionada con sus servicios, mientras que el **Operador Técnico** la utiliza para gestionar parcelas, planificar misiones, monitorear operaciones y registrar resultados.

La plataforma interactúa con una **API Meteorológica externa** para obtener información utilizada en la evaluación de las condiciones de operación.

### 4.6.3. Software Architecture Container Diagrams
El **Container Diagram de C4** realiza un acercamiento al sistema y muestra sus principales aplicaciones, servicios y almacenes de datos, incluyendo las tecnologías utilizadas y sus relaciones.

Los contenedores definidos son:

1. **Landing Page**
2. **Frontend Angular**
3. **Backend Spring Boot**
4. **Base de Datos Relacional**
5. **API Meteorológica Externa**

```mermaid
C4Container
    title Container Diagram - AgriDron Solutions

    Person(farmer, "Agricultor / Cliente", "Consulta información de sus servicios y operaciones.")
    Person(operator, "Operador Técnico", "Gestiona parcelas, planifica y monitorea operaciones de fumigación.")

    System_Ext(weather, "API Meteorológica", "API externa para obtener condiciones meteorológicas.")

    System_Boundary(agridron, "AgriDron Solutions") {
        Container(landing, "Landing Page", "HTML / CSS / JavaScript", "Presenta la solución y permite acceder a la plataforma.")
        Container(frontend, "Frontend Angular", "Angular / TypeScript", "Interfaz web para gestionar parcelas, misiones, monitoreo, historial y reportes.")
        Container(backend, "Backend Spring Boot", "Java / Spring Boot", "Implementa la lógica de negocio y expone la API REST.")
        ContainerDb(database, "Base de Datos Relacional", "SQL", "Almacena usuarios, parcelas, misiones, drones, operaciones, incidentes y reportes.")
    }

    Rel(farmer, landing, "Consulta información")
    Rel(operator, landing, "Consulta información")
    Rel(farmer, frontend, "Consulta servicios")
    Rel(operator, frontend, "Gestiona operaciones")
    Rel(landing, frontend, "Redirige al acceso de la plataforma")
    Rel(frontend, backend, "Consume API REST", "HTTPS / JSON")
    Rel(backend, database, "Lee y almacena información", "SQL")
    Rel(backend, weather, "Consulta condiciones meteorológicas", "HTTPS / JSON")
```

### Descripción de los contenedores

| Contenedor | Tecnología | Responsabilidad |
|---|---|---|
| **Landing Page** | HTML / CSS / JavaScript | Presentar AgriDron Solutions y facilitar el acceso a la plataforma. |
| **Frontend Angular** | Angular / TypeScript | Proporcionar la interfaz para gestionar parcelas, misiones, monitoreo, historial y reportes. |
| **Backend Spring Boot** | Java / Spring Boot | Implementar la lógica de negocio, exponer servicios REST y coordinar datos y servicios externos. |
| **Base de Datos Relacional** | SQL | Persistir usuarios, parcelas, misiones, operaciones, incidentes y reportes. |
| **API Meteorológica** | Servicio externo | Proporcionar datos meteorológicos para apoyar la planificación. |

### Flujo de comunicación

1. El usuario accede a la **Landing Page**.
2. El usuario utiliza el **Frontend Angular** para gestionar o consultar información.
3. El **Frontend Angular** consume el **Backend Spring Boot** mediante API REST.
4. El **Backend Spring Boot** consulta y actualiza la **Base de Datos Relacional**.
5. El **Backend Spring Boot** consulta la **API Meteorológica** cuando se requiere información climática.
6. La información procesada se presenta mediante el **Frontend Angular**.

## Trazabilidad entre dominio y arquitectura

| Bounded Context | Responsabilidad | Soporte arquitectónico |
|---|---|---|
| **Field Management** | Campos, parcelas y áreas | Frontend + Backend + BD |
| **Flight Operations** | Misiones, drones, operaciones e incidentes | Frontend + Backend + BD |
| **Weather Integration** | Condiciones y alertas meteorológicas | Backend + API Meteorológica |
| **Analytics & Reporting** | Historial, métricas y reportes | Frontend + Backend + BD |

La correspondencia permite mantener trazabilidad entre el análisis de dominio realizado mediante Event Storming y la arquitectura propuesta para AgriDron Solutions.

### 4.6.4. Software Architecture Components Diagrams
Esta sección presenta el diseño interno de los principales componentes de software de **AgriDron Solutions**. Se mantiene la separación entre la aplicación web, los servicios REST y las integraciones externas, alineándolos con los Bounded Contexts definidos en la arquitectura.


## 4.6.4.1. RESTful API

La API RESTful implementada con Spring Boot concentra la lógica de aplicación y dominio. Se organiza en capas de presentación, aplicación, dominio e infraestructura.

```mermaid
flowchart LR
    subgraph API["RESTful API - Spring Boot"]
        subgraph Presentation["API / Presentation Layer"]
            FC["Field Controller"]
            MC["Mission Controller"]
            WC["Weather Controller"]
            RC["Report Controller"]
        end
        subgraph Application["Application Layer"]
            FS["Field Service"]
            MS["Mission Service"]
            WS["Weather Service"]
            RS["Report Service"]
        end
        subgraph Domain["Domain Layer"]
            FD["Field Management Domain"]
            MD["Flight Operations Domain"]
            WD["Weather Integration Domain"]
            RD["Analytics & Reporting Domain"]
        end
        subgraph Infrastructure["Infrastructure Layer"]
            FR["Field Repository"]
            MR["Mission Repository"]
            RR["Report Repository"]
            WA["Weather API Adapter"]
        end
    end
    DB[("Relational Database")]
    Weather["Weather API"]
    FC --> FS
    MC --> MS
    WC --> WS
    RC --> RS
    FS --> FD
    MS --> MD
    WS --> WD
    RS --> RD
    FS --> FR
    MS --> MR
    RS --> RR
    WS --> WA
    FR --> DB
    MR --> DB
    RR --> DB
    WA --> Weather
```

### Responsabilidades

| Capa | Responsabilidad |
|---|---|
| Presentation | Recibir solicitudes HTTP y devolver respuestas mediante endpoints REST. |
| Application | Coordinar casos de uso y orquestar operaciones del dominio. |
| Domain | Contener reglas y conceptos principales de cada Bounded Context. |
| Infrastructure | Implementar persistencia e integración con servicios externos. |

## 4.6.4.2. Web Application

La aplicación web utiliza Angular para proporcionar las funcionalidades de operadores y clientes.

```mermaid
flowchart LR
    subgraph Web["Web Application - Angular"]
        subgraph Field["Field Management"]
            Farms["Farm Management"]
            Parcels["Parcel Management"]
            Map["Interactive Map"]
        end
        subgraph Flight["Flight Operations"]
            Missions["Mission Management"]
            Schedule["Mission Calendar"]
            Monitor["Mission Monitoring"]
        end
        subgraph Weather["Weather Integration"]
            WeatherView["Weather View"]
            Alerts["Weather Alerts"]
        end
        subgraph Reports["Analytics & Reporting"]
            History["Mission History"]
            ReportsView["Reports"]
            Metrics["Operational Metrics"]
        end
        Shared["Shared Components / Authentication"]
        APIClient["REST API Client"]
    end
    API["RESTful API"]
    Farms --> APIClient
    Parcels --> APIClient
    Map --> APIClient
    Missions --> APIClient
    Schedule --> APIClient
    Monitor --> APIClient
    WeatherView --> APIClient
    Alerts --> APIClient
    History --> APIClient
    ReportsView --> APIClient
    Metrics --> APIClient
    Shared --> APIClient
    APIClient --> API
```

### Responsabilidades

- **Field Management:** administrar campos, parcelas y áreas de fumigación.
- **Flight Operations:** crear, programar y monitorear misiones.
- **Weather Integration:** mostrar condiciones y alertas meteorológicas.
- **Analytics & Reporting:** consultar historial y reportes.
- **Shared Components:** centralizar elementos reutilizables y autenticación.
- **REST API Client:** encapsular la comunicación con el Backend.

## 4.6.4.3. Weather Integration Component

La integración meteorológica se mantiene aislada para evitar acoplar directamente la lógica de negocio con la API externa.

```mermaid
flowchart LR
    Backend["Backend Spring Boot"]
    subgraph WeatherIntegration["Weather Integration"]
        WS["Weather Service"]
        WClient["Weather API Client"]
        Mapper["Weather Response Mapper"]
        Evaluator["Weather Condition Evaluator"]
        Alert["Weather Alert Generator"]
    end
    External["External Weather API"]
    Backend --> WS
    WS --> WClient
    WClient --> External
    External --> WClient
    WClient --> Mapper
    Mapper --> Evaluator
    Evaluator --> Alert
    Alert --> Backend
```

El componente permite cambiar o adaptar el proveedor meteorológico sin modificar directamente los componentes de **Flight Operations**.

---

## 4.7. Software Object-Oriented Design
El diseño orientado a objetos representa los principales elementos del dominio y sus relaciones. El Project Statement solicita que los Class Diagrams incluyan clases, interfaces, enumeraciones, atributos, métodos, visibilidad, relaciones y multiplicidades cuando correspondan.

### 4.7.1. Class Diagrams

### 4.7.1.1. Field Management

```mermaid
classDiagram
    class Farm {
        -Long id
        -String name
        -String location
        -String ownerName
        +register()
        +update()
        +getParcels()
    }
    class Parcel {
        -Long id
        -String name
        -String cropType
        -Double area
        -String geometry
        +defineArea()
        +updateCrop()
        +getGeometry()
    }
    class FumigationArea {
        -Long id
        -String geometry
        -Double area
        +calculateArea()
        +updateGeometry()
    }
    class Crop {
        -Long id
        -String name
        -String variety
        +getInformation()
    }
    Farm "1" *-- "1..*" Parcel : contains
    Parcel "1" *-- "0..*" FumigationArea : defines
    Parcel "1" --> "1" Crop : has
```

### 4.7.1.2. Flight Operations

```mermaid
classDiagram
    class Mission {
        -Long id
        -String code
        -LocalDate scheduledDate
        -MissionStatus status
        -Double plannedArea
        -Double treatedArea
        +create()
        +schedule()
        +start()
        +pause()
        +complete()
        +cancel()
    }
    class Drone {
        -Long id
        -String serialNumber
        -String model
        -Double capacity
        -DroneStatus status
        +assignToMission()
        +updateStatus()
        +getLocation()
    }
    class Incident {
        -Long id
        -String type
        -String description
        -LocalDateTime occurredAt
        +register()
        +update()
    }
    class OperationStatus {
        -Double latitude
        -Double longitude
        -String status
        -LocalDateTime timestamp
        +updateLocation()
    }
    class MissionStatus {
        <<enumeration>>
        PLANNED
        AUTHORIZED
        IN_PROGRESS
        PAUSED
        COMPLETED
        CANCELLED
    }
    class DroneStatus {
        <<enumeration>>
        AVAILABLE
        ASSIGNED
        IN_FLIGHT
        PAUSED
        MAINTENANCE
    }
    Mission "1" --> "1" Drone : uses
    Mission "1" *-- "0..*" Incident : records
    Mission "1" *-- "0..*" OperationStatus : tracks
    Mission --> MissionStatus : has
    Drone --> DroneStatus : has
```

### 4.7.1.3. Weather Integration

```mermaid
classDiagram
    class WeatherService {
        -WeatherApiClient apiClient
        +getCurrentConditions(latitude, longitude)
        +getForecast(latitude, longitude)
        +evaluateConditions(weather)
    }
    class WeatherApiClient {
        <<interface>>
        +getCurrentWeather(latitude, longitude)
        +getForecast(latitude, longitude)
    }
    class WeatherCondition {
        -Double temperature
        -Double humidity
        -Double windSpeed
        -Double precipitation
        -LocalDateTime observedAt
        +isSuitable()
    }
    class WeatherAlert {
        -Long id
        -String severity
        -String message
        -LocalDateTime createdAt
        +generate()
    }
    WeatherService --> WeatherApiClient : uses
    WeatherService --> WeatherCondition : evaluates
    WeatherService --> WeatherAlert : generates
```

### 4.7.1.4. Analytics & Reporting

```mermaid
classDiagram
    class MissionReport {
        -Long id
        -Double treatedArea
        -Double appliedVolume
        -String observations
        -LocalDateTime generatedAt
        +generate()
        +export()
    }
    class MissionHistory {
        -Long id
        -Long missionId
        -LocalDateTime completedAt
        -String finalStatus
        +register()
        +findByDate()
    }
    class OperationalMetric {
        -String name
        -Double value
        -String unit
        +calculate()
    }
    MissionReport "1" --> "1" MissionHistory : summarizes
    MissionReport "1" *-- "0..*" OperationalMetric : contains
```

### 4.7.1.5. Shared / Identity

```mermaid
classDiagram
    class User {
        -Long id
        -String name
        -String email
        -String passwordHash
        -UserRole role
        +authenticate()
        +updateProfile()
    }
    class UserRole {
        <<enumeration>>
        FARMER
        OPERATOR
        TECHNICIAN
    }
    class Farmer {
        +requestService()
        +viewReports()
    }
    class Operator {
        +createMission()
        +monitorMission()
        +registerResult()
    }
    User <|-- Farmer
    User <|-- Operator
    User --> UserRole : has
```

## 4.8. Database Design

### 4.8.1. Database Diagrams

![Database Diagram](assets/database/database_diagram.png)

**Descripción:**

[DESCRIPCIÓN.]

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

El **Software Configuration Management (SCM)** de AgriDron Solutions establece las herramientas, convenciones y procedimientos que permitirán mantener la consistencia del producto durante su ciclo de vida. Esta configuración cubre el entorno de desarrollo, la gestión del código fuente, las convenciones de programación y el despliegue de los productos de software.

De acuerdo con el Project Statement, esta sección debe establecer decisiones y convenciones para mantener la consistencia durante el ciclo de vida del producto. Además, se debe considerar el entorno utilizado para actividades de gestión del proyecto, requisitos, UX/UI, desarrollo, despliegue y documentación.

La propuesta de SCM para AgriDron Solutions se alinea con la arquitectura definida previamente: **Landing Page**, **Frontend Angular**, **Backend Spring Boot** y **base de datos relacional**, además de la integración con una API meteorológica externa.

### 5.1.1. Software Development Environment Configuration

## 5.1.1.1. Propósito

El entorno de desarrollo define las herramientas que utilizará el equipo para implementar, documentar, probar y desplegar AgriDron Solutions. Se busca que todos los integrantes trabajen con una configuración homogénea, reduciendo problemas de compatibilidad y facilitando la colaboración.

El Project Statement indica que esta sección debe especificar el nombre de cada producto de software, su propósito y la ruta de referencia o descarga correspondiente, considerando las actividades de Project Management, Requirements Management, UX/UI Design, Software Development, Software Deployment y Software Documentation.

## 5.1.1.2. Herramientas del proyecto

| Categoría | Herramienta / Tecnología | Propósito | Referencia |
|---|---|---|---|
| Control de versiones | Git | Control local de versiones del código fuente. | https://git-scm.com/ |
| Repositorios | GitHub | Hospedaje de repositorios y colaboración mediante branches y Pull Requests. | https://github.com/ |
| Gestión del proyecto | Trello / Jira / YouTrack | Organización del backlog, tareas y seguimiento del trabajo. | Según herramienta seleccionada |
| Editor / IDE Frontend | Visual Studio Code | Desarrollo de Landing Page y Frontend Angular/TypeScript. | https://code.visualstudio.com/ |
| IDE Backend | IntelliJ IDEA / Eclipse | Desarrollo del Backend Java/Spring Boot. | https://www.jetbrains.com/idea/ |
| Runtime Frontend | Node.js + npm | Instalación de dependencias y ejecución de herramientas Angular. | https://nodejs.org/ |
| Framework Frontend | Angular | Implementación de la aplicación web. | https://angular.dev/ |
| Lenguaje Frontend | TypeScript | Desarrollo de la lógica del Frontend Angular. | https://www.typescriptlang.org/ |
| Lenguaje Backend | Java | Implementación del Backend y lógica de negocio. | https://www.java.com/ |
| Framework Backend | Spring Boot | Implementación de servicios REST y lógica del Backend. | https://spring.io/projects/spring-boot |
| Build Backend | Maven | Gestión de dependencias y construcción del proyecto Spring Boot. | https://maven.apache.org/ |
| Base de datos | PostgreSQL / SQL | Persistencia de la información de la plataforma. | https://www.postgresql.org/ |
| API testing | Postman | Prueba de endpoints REST durante el desarrollo. | https://www.postman.com/ |
| Documentación API | Swagger / OpenAPI | Documentación y consulta de los servicios REST. | https://swagger.io/ |
| Diseño UI/UX | Figma | Diseño de wireframes, mock-ups y prototipos. | https://www.figma.com/ |
| Diagramación | Mermaid | Diagramas como código dentro del repositorio Markdown. | https://mermaid.js.org/ |
| Documentación | Markdown | Elaboración de documentación técnica dentro del repositorio. | https://www.markdownguide.org/ |

> **Nota:** Las herramientas de gestión de proyectos y los proveedores cloud deberán reemplazarse por los productos concretos que el equipo haya seleccionado en su implementación final. La tabla mantiene como propuesta las herramientas que no han sido fijadas previamente.

## 5.1.1.3. Configuración base

Todos los integrantes deberán mantener una configuración equivalente para evitar diferencias entre ambientes locales.

### Frontend

```text
Node.js
npm
Angular CLI
Angular
TypeScript
```

### Backend

```text
Java JDK
Maven
Spring Boot
IDE compatible con Java
```

### Base de datos

```text
PostgreSQL
Cliente gráfico de base de datos
```

### Control de versiones

```text
Git
GitHub
GitFlow
Conventional Commits
Semantic Versioning
```

## 5.1.1.4. Estructura de repositorios

Para mantener separadas las responsabilidades de los productos, se propone trabajar con repositorios independientes:

```text
AgriDron Solutions
│
├── agridron-landing
│   └── Landing Page
│
├── agridron-frontend
│   └── Frontend Angular
│
└── agridron-backend
    ├── Backend Spring Boot
    ├── Unit Tests
    └── Integration / Acceptance Tests
```

Esta organización sigue la indicación del Project Statement de considerar los productos **Landing Page, Web Services y Frontend Web Applications** y, en el caso de Web Services, incluir también los archivos de pruebas.


### 5.1.2. Source Code Management

## 5.1.2.1. Plataforma y repositorios

El control de versiones del proyecto se realizará mediante **Git gestionado desde GitHub**. El Project Statement establece explícitamente GitHub como plataforma de control de versiones y solicita aplicar **GitFlow Workflow, Conventional Commits y Semantic Versioning**.

Los repositorios considerados para AgriDron Solutions son:

| Producto | Repositorio | Contenido |
|---|---|---|
| Landing Page | `AgiDron-LandingPage-7760-G3` | HTML, CSS y JavaScript |
| Frontend Web Application | `AgiDron-FrontEnd-7760-G3` | Angular y TypeScript |
| Web Services | `AgiDron-BackEnd-7760-G3` | Java, Spring Boot, pruebas unitarias e integración/aceptación |

> Los nombres anteriores son una propuesta de nomenclatura. Si el equipo ya creó repositorios con nombres diferentes, deben sustituirse por los nombres reales y sus URLs reales antes de entregar el informe.

## 5.1.2.2. GitFlow Workflow

Se utilizará **GitFlow** como estrategia de organización de ramas.

```mermaid
gitGraph
    commit id: "Initial"
    branch develop
    checkout develop
    commit id: "Setup project"

    branch feature/field-management
    checkout feature/field-management
    commit id: "feat: add parcel management"
    checkout develop
    merge feature/field-management

    branch feature/flight-operations
    checkout feature/flight-operations
    commit id: "feat: add mission management"
    checkout develop
    merge feature/flight-operations

    branch release/1.0.0
    checkout release/1.0.0
    commit id: "chore: prepare release"
    checkout main
    merge release/1.0.0
    checkout develop
    merge release/1.0.0
```

### Ramas principales

| Branch | Propósito |
|---|---|
| `main` | Contiene versiones estables listas para entrega o producción. |
| `develop` | Rama de integración de funcionalidades terminadas. |
| `feature/*` | Desarrollo aislado de una funcionalidad específica. |
| `release/*` | Preparación de una nueva versión estable. |
| `hotfix/*` | Corrección urgente de errores encontrados en producción. |

## 5.1.2.3. Convención para Feature Branches

Cada funcionalidad debe desarrollarse en una rama independiente.

Formato:

```text
feature/<descripcion>
```

Ejemplos:

```text
feature/field-management
feature/parcel-registration
feature/mission-planning
feature/weather-integration
feature/mission-monitoring
feature/mission-reports
```

Se utilizarán nombres en **inglés**, en minúsculas y separados mediante guiones.

## 5.1.2.4. Convención para Release Branches

Formato:

```text
release/<major>.<minor>.<patch>
```

Ejemplos:

```text
release/1.0.0
release/1.1.0
release/1.1.1
```

Las release branches permiten realizar ajustes finales antes de integrar una versión estable a `main`.

## 5.1.2.5. Convención para Hotfix Branches

Formato:

```text
hotfix/<descripcion>
```

Ejemplos:

```text
hotfix/weather-api-error
hotfix/mission-status-fix
hotfix/login-validation
```

Los hotfixes estarán destinados exclusivamente a correcciones urgentes de versiones publicadas.

## 5.1.2.6. Pull Requests

Las modificaciones realizadas en `feature/*`, `release/*` y `hotfix/*` deberán integrarse mediante Pull Requests.

Flujo recomendado:

```text
feature/*
    ↓
Pull Request
    ↓
Code Review
    ↓
Tests
    ↓
Merge
    ↓
develop
```

Para una versión estable:

```text
develop
    ↓
release/x.y.z
    ↓
Validation
    ↓
main
    ↓
Tag vX.Y.Z
```

Se recomienda que ningún integrante trabaje directamente sobre `main` para funcionalidades nuevas.

## 5.1.2.7. Conventional Commits

Los mensajes de commit seguirán la especificación de **Conventional Commits**.

Formato:

```text
<type>[optional scope]: <description>
```

Ejemplos:

```text
feat(field): add parcel registration
feat(mission): add mission planning
fix(weather): handle unavailable API response
docs(api): update endpoint documentation
test(mission): add mission service tests
refactor(report): simplify report generation
chore(deps): update project dependencies
```

Tipos principales:

| Tipo | Uso |
|---|---|
| `feat` | Nueva funcionalidad. |
| `fix` | Corrección de un error. |
| `docs` | Cambios en documentación. |
| `test` | Creación o modificación de pruebas. |
| `refactor` | Reestructuración sin cambiar el comportamiento funcional. |
| `style` | Cambios de formato que no modifican la lógica. |
| `chore` | Tareas de mantenimiento o configuración. |

Conventional Commits relaciona `feat` con incrementos **MINOR**, `fix` con incrementos **PATCH** y los cambios incompatibles con incrementos **MAJOR**, facilitando su integración con Semantic Versioning.

## 5.1.2.8. Semantic Versioning

Las versiones del producto seguirán el formato:

```text
MAJOR.MINOR.PATCH
```

Ejemplo:

```text
1.0.0
```

Reglas:

- **MAJOR:** cambios incompatibles con versiones anteriores.
- **MINOR:** nuevas funcionalidades compatibles.
- **PATCH:** correcciones compatibles.

Ejemplos:

```text
1.0.0 → primera versión estable
1.1.0 → incorporación del módulo de monitoreo
1.1.1 → corrección de un error
2.0.0 → cambio incompatible de la API
```

Las versiones estables serán identificadas mediante tags de Git:

```text
v1.0.0
v1.1.0
v1.1.1
```

### 5.1.3. Source Code Style Guide & Conventions

## 5.1.3.1. Principios generales

El Project Statement establece que para los lenguajes utilizados en la solución debe aplicarse nomenclatura en **inglés**. Para AgriDron Solutions se aplicará esta regla a HTML, CSS, JavaScript, TypeScript y Java.

Principios:

1. Utilizar nombres descriptivos.
2. Mantener una nomenclatura consistente.
3. Evitar abreviaturas innecesarias.
4. Mantener métodos y clases con responsabilidades específicas.
5. Evitar duplicación de código.
6. Mantener funciones pequeñas y legibles.
7. Documentar únicamente la lógica que requiera contexto adicional.
8. Mantener las pruebas junto con el código correspondiente.
9. No incluir credenciales ni secretos dentro del código fuente.

## 5.1.3.2. HTML

Convenciones:

- Utilizar HTML5 semántico.
- Utilizar elementos semánticos como `header`, `nav`, `main`, `section` y `footer`.
- Utilizar atributos `aria-*` cuando sean necesarios para accesibilidad.
- Utilizar nombres descriptivos para clases e identificadores.
- Mantener los atributos en minúsculas.

Ejemplo:

```html
<section class="mission-summary" aria-labelledby="mission-title">
    <h2 id="mission-title">Mission Summary</h2>
</section>
```

## 5.1.3.3. CSS

Convenciones:

- Utilizar nombres de clases en inglés.
- Utilizar `kebab-case` para clases CSS.
- Evitar estilos inline cuando no sean necesarios.
- Agrupar reglas relacionadas.
- Evitar selectores excesivamente específicos.

Ejemplo:

```css
.mission-card {
    display: flex;
    gap: 1rem;
}

.mission-card__status {
    font-weight: 600;
}
```

## 5.1.3.4. JavaScript

Convenciones:

- Variables y funciones: `camelCase`.
- Constantes: `UPPER_SNAKE_CASE` cuando representen valores constantes globales.
- Clases: `PascalCase`.
- Utilizar `const` por defecto y `let` cuando sea necesario.
- Evitar variables globales.

Ejemplo:

```javascript
const DEFAULT_MISSION_STATUS = "PENDING";

function createMission(missionData) {
    // implementation
}
```

## 5.1.3.5. TypeScript / Angular

Convenciones:

| Elemento | Convención | Ejemplo |
|---|---|---|
| Clase | PascalCase | `MissionService` |
| Interface | PascalCase | `Mission` |
| Variable | camelCase | `missionStatus` |
| Método | camelCase | `createMission()` |
| Constante | UPPER_SNAKE_CASE | `API_BASE_URL` |
| Archivo | kebab-case | `mission.service.ts` |
| Componente | kebab-case | `mission-list` |

Ejemplo:

```typescript
export interface Mission {
    id: number;
    parcelId: number;
    scheduledDate: string;
    status: MissionStatus;
}

export class MissionService {
    createMission(mission: Mission): void {
        // implementation
    }
}
```

## 5.1.3.6. Java / Spring Boot

Convenciones:

| Elemento | Convención | Ejemplo |
|---|---|---|
| Class | PascalCase | `MissionService` |
| Method | camelCase | `createMission()` |
| Variable | camelCase | `missionStatus` |
| Constant | UPPER_SNAKE_CASE | `MAX_MISSION_DURATION` |
| Package | lowercase | `com.agridron.mission` |
| DTO | PascalCase + DTO | `MissionResponseDTO` |
| Entity | PascalCase | `Mission` |

La estructura del backend seguirá una separación lógica entre:

```text
controller/
service/
domain/
repository/
dto/
config/
exception/
```

Ejemplo:

```java
@RestController
@RequestMapping("/api/missions")
public class MissionController {

    @GetMapping("/{id}")
    public MissionResponseDTO getMission(@PathVariable Long id) {
        return missionService.getMission(id);
    }
}
```

## 5.1.3.7. API REST

Los endpoints utilizarán nombres de recursos en plural y en inglés.

Ejemplos:

```text
GET    /api/farms
GET    /api/parcels
POST   /api/parcels
GET    /api/missions
POST   /api/missions
PUT    /api/missions/{id}
DELETE /api/missions/{id}
GET    /api/weather
GET    /api/reports
```

Se utilizarán los verbos HTTP según la operación:

| Verbo | Uso |
|---|---|
| GET | Consultar recursos. |
| POST | Crear recursos. |
| PUT | Actualizar un recurso. |
| PATCH | Actualizar parcialmente un recurso. |
| DELETE | Eliminar un recurso. |

## 5.1.3.8. Documentación y lenguaje

El idioma por defecto definido para los mensajes, interfaz de usuario e interfaz de documentación de los productos de la solución es **inglés**.

Por lo tanto:

- Variables: inglés.
- Clases: inglés.
- Métodos: inglés.
- Endpoints: inglés.
- Mensajes de API: inglés.
- Documentación técnica: inglés.
- Textos visibles para el usuario: inglés, salvo que una decisión posterior de UX establezca otro idioma.

### 5.1.4. Software Deployment Configuration

## 5.1.4.1. Objetivo

El despliegue permitirá publicar los productos de AgriDron Solutions en plataformas cloud y automatizar progresivamente el proceso de entrega.

El Project Statement establece que esta configuración debe contemplar la creación de cuentas, configuración de recursos en proveedores cloud y configuración de proyectos de desarrollo para integración o automatización del deployment. El proceso debe considerar los productos **Landing Page, Web Applications y Web Services**.

## 5.1.4.2. Arquitectura de despliegue

Se propone separar los componentes desplegables de acuerdo con la arquitectura del sistema:

```mermaid
flowchart TB
    User["User"]
    GitHub["GitHub Repository"]

    subgraph Cloud["Cloud Environment"]
        Landing["Landing Page"]
        Frontend["Angular Frontend"]
        Backend["Spring Boot REST API"]
        Database[("Relational Database")]
    end

    Weather["External Weather API"]

    User --> Landing
    User --> Frontend
    Frontend --> Backend
    Backend --> Database
    Backend --> Weather

    GitHub -->|"CI/CD"| Landing
    GitHub -->|"CI/CD"| Frontend
    GitHub -->|"CI/CD"| Backend
```

## 5.1.4.3. Ambientes

Se utilizarán tres ambientes conceptuales:

| Ambiente | Propósito |
|---|---|
| Development | Desarrollo local y validaciones iniciales. |
| Staging | Integración y validación antes de producción. |
| Production | Versión disponible para los usuarios. |

Flujo:

```text
feature/*
    ↓
Development
    ↓
develop
    ↓
Staging
    ↓
release/*
    ↓
main
    ↓
Production
```

## 5.1.4.4. Integración continua

El repositorio podrá utilizar **GitHub Actions** para automatizar las tareas de integración y despliegue.

Pipeline conceptual:

```mermaid
flowchart LR
    Commit["Push / Pull Request"]
    Checkout["Checkout"]
    Build["Build"]
    Test["Automated Tests"]
    Package["Package"]
    DeployStaging["Deploy Staging"]
    Validate["Validation"]
    DeployProd["Deploy Production"]

    Commit --> Checkout
    Checkout --> Build
    Build --> Test
    Test --> Package
    Package --> DeployStaging
    DeployStaging --> Validate
    Validate --> DeployProd
```

### Backend

```text
Checkout
↓
Install dependencies
↓
Run unit tests
↓
Run integration tests
↓
Build Spring Boot application
↓
Package application
↓
Deploy
```

### Frontend

```text
Checkout
↓
Install npm dependencies
↓
Run lint
↓
Run tests
↓
Build Angular application
↓
Deploy
```

### Landing Page

```text
Checkout
↓
Validate files
↓
Build / prepare static assets
↓
Deploy
```

## 5.1.4.5. Variables y secretos

Las credenciales, API keys, tokens y contraseñas no deberán almacenarse directamente en el repositorio.

Se utilizarán variables de entorno y secretos administrados por la plataforma de CI/CD.

Ejemplos:

```text
DATABASE_URL
DATABASE_USERNAME
DATABASE_PASSWORD
WEATHER_API_KEY
JWT_SECRET
```

Los valores reales no se incluirán en archivos versionados.

GitHub permite asociar secretos y variables a ambientes de despliegue. Además, los ambientes pueden restringir qué branches o tags tienen autorización para realizar deployments y pueden aplicar reglas de protección.

## 5.1.4.6. Configuración de base de datos

La base de datos relacional se desplegará como un servicio administrado o recurso equivalente dentro del proveedor cloud seleccionado.

La configuración deberá considerar:

- Nombre de base de datos.
- Usuario de aplicación.
- Contraseña almacenada como secreto.
- Host.
- Puerto.
- SSL/TLS cuando sea requerido.
- Variables de conexión.
- Backups.
- Restricción de acceso desde servicios autorizados.

El Backend consumirá la configuración mediante variables de entorno, por ejemplo:

```text
DB_HOST
DB_PORT
DB_NAME
DB_USER
DB_PASSWORD
```

## 5.1.4.7. Configuración de la API meteorológica

La API meteorológica será consumida exclusivamente desde el Backend.

```text
Frontend
   ↓
Backend
   ↓
Weather API
```

La clave de acceso de la API meteorológica deberá almacenarse como secreto:

```text
WEATHER_API_KEY
```

El Frontend no deberá contener directamente la clave privada del proveedor meteorológico.

## 5.1.4.8. Estrategia de deployment

La estrategia propuesta es:

1. Los desarrolladores trabajan en `feature/*`.
2. Se crea un Pull Request hacia `develop`.
3. Se ejecutan las pruebas automáticas.
4. La funcionalidad aprobada se integra en `develop`.
5. Una `release/*` prepara la versión.
6. La versión se valida en staging.
7. Se integra en `main`.
8. Se crea el tag correspondiente a Semantic Versioning.
9. El pipeline despliega la versión en production.

```mermaid
flowchart TD
    A["feature/*"] --> B["Pull Request"]
    B --> C{"Tests pass?"}
    C -->|"No"| A
    C -->|"Yes"| D["develop"]
    D --> E["release/x.y.z"]
    E --> F["Staging"]
    F --> G{"Validation approved?"}
    G -->|"No"| E
    G -->|"Yes"| H["main"]
    H --> I["Tag vX.Y.Z"]
    I --> J["Production"]
```

## 5.1.4.9. Trazabilidad del deployment

Cada versión desplegada deberá poder relacionarse con:

```text
Git Commit
    ↓
Pull Request
    ↓
Branch
    ↓
Release
    ↓
Semantic Version
    ↓
Deployment
```

Esto permite identificar qué cambios forman parte de una versión determinada y facilita la recuperación ante errores.

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

**Objetivo del Sprint:**

[OBJETIVO.]

**Fecha de inicio:** [FECHA]

**Fecha de finalización:** [FECHA]

**Meta del Sprint:**

[DESCRIPCIÓN.]

#### 5.2.1.2. Aspect Leaders and Collaborators

| Aspecto | Líder | Colaboradores |
| :--- | :--- | :--- |
| [ASPECTO] | [NOMBRE] | [NOMBRES] |
| [ASPECTO] | [NOMBRE] | [NOMBRES] |

#### 5.2.1.3. Sprint Backlog 1

| ID | User Story | Tarea | Responsable | Estado |
| :--- | :--- | :--- | :--- | :--- |
| US-001 | [USER STORY] | [TAREA] | [NOMBRE] | [ESTADO] |
| US-002 | [USER STORY] | [TAREA] | [NOMBRE] | [ESTADO] |

#### 5.2.1.4. Development Evidence for Sprint Review

[PEGAR AQUÍ CAPTURAS / EVIDENCIAS DEL DESARROLLO.]

![Evidencia de desarrollo](assets/evidences/sprint1_development.png)

#### 5.2.1.5. Execution Evidence for Sprint Review

[PEGAR AQUÍ CAPTURAS / EVIDENCIAS DE EJECUCIÓN.]

![Evidencia de ejecución](assets/evidences/sprint1_execution.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

[PEGAR AQUÍ LA DOCUMENTACIÓN / EVIDENCIA DE SERVICIOS.]

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

[PEGAR AQUÍ LA EVIDENCIA DEL DESPLIEGUE.]

#### 5.2.1.8. Team Collaboration Insights during Sprint

[DESCRIBIR LA COLABORACIÓN DURANTE EL SPRINT.]

![Evidencia de colaboración del Sprint](assets/evidences/sprint1_collaboration.png)

---

## 5.3. Validation Interviews

### 5.3.1. Interview Design

[DESCRIBIR EL DISEÑO DE LAS ENTREVISTAS DE VALIDACIÓN.]

### 5.3.2. Interview Registry

[REGISTRAR LAS ENTREVISTAS DE VALIDACIÓN.]

### 5.3.3. Heuristic Evaluations

[PEGAR AQUÍ LOS RESULTADOS DE LAS EVALUACIONES HEURÍSTICAS.]

---

## 5.4. Video About-the-Product

**Enlace al video:**

[PEGAR AQUÍ EL ENLACE AL VIDEO]

**Descripción:**

[DESCRIBIR BREVEMENTE EL CONTENIDO DEL VIDEO.]

---

# Conclusiones

## Conclusión 1

[PEGAR AQUÍ LA CONCLUSIÓN.]

## Conclusión 2

[PEGAR AQUÍ LA CONCLUSIÓN.]

## Recomendaciones

[PEGAR AQUÍ LAS RECOMENDACIONES.]

---

# Bibliografía

> Registrar las fuentes utilizadas siguiendo el formato APA 7.

1. [REFERENCIA APA 7]
2. [REFERENCIA APA 7]
3. [REFERENCIA APA 7]

---

# Anexos

## Anexo A: Evidencias adicionales

[PEGAR AQUÍ EVIDENCIAS ADICIONALES.]

## Anexo B: Videos de Exposiciones

**Video de exposición:** [ENLACE]

## Anexo C: Otros

[AGREGAR OTROS ANEXOS SI CORRESPONDE.]



