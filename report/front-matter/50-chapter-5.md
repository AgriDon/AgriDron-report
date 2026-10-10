# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

Para tener consistencia y seguimiento del desarrollo de la plataforma, se definió un conjunto de herramientas y estrategias de trabajo. Esta sección cubre la configuración del entorno de desarrollo, la gestión del código fuente y el despliegue, alineados con las buenas prácticas de ingeniería de software y con los marcos de trabajo ágiles.

### 5.1.1. Software Development Environment Configuration

Con el fin de facilitar la colaboración del equipo en las distintas etapas del ciclo de vida de AgriDron Solutions, se configuró un entorno de desarrollo unificado. Este entorno incluye herramientas estandarizadas para gestión de proyectos, diseño UX/UI, modelado de dominio, codificación, documentación y simulación de APIs, despliegue y control de versiones. La selección responde a criterios de integración con tecnologías open-source (Vue 3 y C# con .NET), soporte para datos geoespaciales y climáticos, y cumplimiento de estándares de la industria.

| Categoría | Herramienta | Propósito | Tipo de acceso / Enlace |
|:--|:--|:--|:--|
| **Project Management** | Jira / Trello | Gestión del backlog, trazabilidad de historias de usuario, y tablero de tareas de cada Sprint bajo Scrum. | [Jira](https://agridron.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog) / [Trello](https://trello.com/invite/b/6aac1a270d8f45bc33ecd592/ATTIbc784176eb8dc497a26da32a3c554ea69211FF0D/agridron) |
| **Requirements Management** | UXPressia | Elaboración de User Personas, Journey Maps, Empathy Maps e Impact Mapping. | [UXPressia](https://uxpressia.com) |
| **Product UX/UI Design** | Figma | Wireframes, wireflows, mock-ups de alta fidelidad y prototipos interactivos. | [Figma](https://www.figma.com) |
| **Modelado de Software** | Structurizr / Miro | Diagramas de arquitectura (C4 Model) y sesiones de EventStorming. | [Structurizr](https://structurizr.com) / [Miro](https://miro.com) |
| **Frontend Development** | WebStorm | Desarrollo de la Web Application en Vue 3 (HTML5, CSS3 y JavaScript). | [WebStorm](https://www.jetbrains.com/webstorm/) |
| **Backend Development** | JetBrains Rider | Desarrollo del RESTful API en C# (.NET) siguiendo Domain-Driven Design. | [JetBrains Rider](https://www.jetbrains.com/rider/) |
| **API Mocking & Documentation** | Apidog | Simulación de endpoints (mock API) y documentación con OpenAPI. | [Apidog](https://apidog.com) |
| **Deployment** | GitHub Pages / Firebase Hosting | Publicación de la Landing Page y de la Web Application. | [GitHub Pages](https://pages.github.com) / [Firebase](https://firebase.google.com/products/hosting) |
| **Version Control** | GitHub | Alojamiento de repositorios y control de versiones mediante GitFlow y Conventional Commits. | [GitHub](https://github.com) |
| **Software Documentation** | Markdown | Redacción del informe del proyecto en formato Docs-as-Code. | Compatible con GitHub |

### 5.1.2. Source Code Management

#### 5.1.2.1. Plataforma y repositorios

El control de versiones del proyecto se realiza en GitHub, dentro de la organización pública AgriDon. Los repositorios son los siguientes:

<div align="center">

| Producto digital | URL del repositorio |
|:--|:--|
| Project Report | https://github.com/AgriDon/AgriDron-report |
| Landing Page | https://github.com/AgriDon/Agridron-LandingPage |
| Frontend Web Application | https://github.com/AgriDon/Agridron-Fronted |
| API simulado (mock) | https://github.com/AgriDon/agridron-mock-api |
| Web Services (Backend API) | https://github.com/AgriDon/Agridron-backend |

</div>

**Modelo de ramificación (GitFlow Workflow)**

Se adopta GitFlow para mantener una separación clara entre el código en desarrollo, las entregas parciales y las versiones estables:

- `main`: contiene el código estable, que es el que se publica.
- `develop`: rama de integración del trabajo en progreso.
- `feature/*`: ramas para cada funcionalidad o bounded context.
  - Convención: `feature/<nombre-descriptivo>`
  - Ejemplos: `feature/fieldManagement`, `feature/reportingContext`, `feature/dashboard-and-settings`
- `release/*`: estabilización y preparación de versiones.
  - Convención: `release/X.Y.Z`
  - Ejemplo: `release/1.0.0`
- `hotfix/*`: correcciones urgentes aplicadas sobre `main`.
  - Convención: `hotfix/X.Y.Z`
  - Ejemplo: `hotfix/1.0.1`

**Versionado semántico**

Las versiones siguen la nomenclatura MAJOR.MINOR.PATCH (Semantic Versioning 2.0.0):

- **MAJOR:** cambios incompatibles en el API o reestructuraciones profundas.
- **MINOR:** nuevas funcionalidades retrocompatibles.
- **PATCH:** correcciones de errores retrocompatibles.
- **Ejemplos:** v1.0.0 (primera versión de la Landing Page), v1.1.0 (primera versión de la Web Application), v1.1.1 (corrección en el visor de mapa).

**Convenciones para commits**

Los mensajes de commit siguen la estructura de Conventional Commits `<type>[optional scope]: <description>`:

- **feat:** nueva funcionalidad.
- **fix:** corrección de un error.
- **docs:** cambios solo en la documentación.
- **style:** formato de código sin cambios de lógica.
- **refactor:** cambios de código que no corrigen errores ni agregan funcionalidades.
- **test:** incorporación o ajuste de pruebas.
- **chore:** tareas de compilación, configuración o dependencias.

Ejemplos de commits del proyecto:

```
feat(reporting): implement analytics and reporting bounded context
fix(flightOperations): resolve i18n translation keys and status badge styles in missions
docs(api): add OpenAPI specification for mock endpoints
```

### 5.1.3. Source Code Style Guide & Conventions

Para velar por la legibilidad, mantenibilidad y calidad del código, el equipo adopta guías de estilo oficiales. Todos los identificadores, variables, nombres de métodos y comentarios del código se redactan en inglés.

**Backend: C# con .NET**

Para el RESTful API se toma como base la guía C# Coding Conventions y las Microsoft ASP.NET Core Coding Guidelines, con una estructura de capas basada en Domain-Driven Design:

- **Estructura de capas:**
  - **Domain:** entidades, agregados, value objects y contratos de repositorios.
  - **Application:** casos de uso, servicios de aplicación, handlers de comandos y consultas, y DTOs.
  - **Infrastructure:** implementación de repositorios (Entity Framework Core), persistencia y clientes HTTP para servicios externos (clima).
  - **API:** controladores RESTful (`[ApiController]`), middlewares de manejo de excepciones y documentación OpenAPI con Swagger.
- **Nomenclatura:**
  - Clases, interfaces, enumeraciones y métodos en PascalCase: `FarmService`, `IParcelRepository`, `MissionStatus`, `CalculateTreatedArea()`.
  - Parámetros y variables locales en camelCase: `plotCoordinates`, `droneId`.
  - Interfaces con prefijo `I`. Constantes en PascalCase.
- **Documentación y anotaciones:**
  - Comentarios XML (`/// <summary>`) en métodos y endpoints públicos.
  - Controladores con atributos de enrutamiento y validaciones (`[HttpGet]`, `[HttpPost]`, `[FromBody]`, `[Required]`).

**Frontend: Vue 3 (JavaScript, HTML5 y CSS3)**

La Web Application y la Landing Page siguen la Vue Style Guide, la Google JavaScript Style Guide, las MDN JavaScript guidelines y la Google HTML/CSS Style Guide:

- **Estructura modular:**
  - Código organizado por bounded contexts (`fieldManagement`, `flightOperations`, `weatherIntegration`, `reporting`) y una capa `shared` para componentes y vistas comunes.
  - Single File Components (`.vue`) que agrupan `<template>`, `<script>` y `<style scoped>`.
- **Nomenclatura:**
  - Archivos de componentes y vistas en kebab-case: `farm-management-view.vue`, `map-polygon-editor.vue`.
  - Nombres de componentes en PascalCase: `FarmManagementView`, `MapPolygonEditor`.
  - Variables, funciones y props en camelCase: `selectedParcelId`, `fetchWeatherForecast()`.
- **HTML y accesibilidad:**
  - Elementos semánticos de HTML5 (`<main>`, `<header>`, `<section>`, `<article>`, `<nav>`).
  - Atributos `alt` en imágenes y atributos `aria-*` para accesibilidad.
- **CSS con nomenclatura BEM (Block Element Modifier):**
  - Clases en kebab-case para evitar colisiones de estilos:
    - Bloque: `.mission-card`
    - Elemento: `.mission-card__status-badge`
    - Modificador: `.mission-card__status-badge--in-progress`
  - Estilos encapsulados con `<style scoped>` en cada componente Vue.

### 5.1.4. Software Deployment Configuration

La configuración de despliegue de AgriDron Solutions establece los procesos, herramientas y entornos para publicar los productos digitales: Landing Page, Web Application y Web Services.

**Despliegue de la Landing Page**

- Tecnología: HTML5, CSS3 y JavaScript, con diseño responsive.
- Repositorio: https://github.com/AgriDon/Agridron-LandingPage
- Plataforma: GitHub Pages.
- Procedimiento:
  - La rama `main` es la fuente de publicación, tomando el directorio raíz (`/`).
  - Los cambios aprobados en `develop` se integran a `main` mediante Pull Requests revisados por el equipo.
  - GitHub Pages actualiza el sitio tras cada integración en `main`.
- URL: https://agridon.github.io/Agridron-LandingPage/

**Despliegue de la Web Application**

- Tecnología: Vue 3 con Vite (JavaScript, HTML5 y CSS3).
- Repositorio: https://github.com/AgriDon/Agridron-Fronted
- Plataforma: Firebase Hosting.
- Procedimiento:
  - Se genera el build de producción con `npm run build`, que produce los archivos estáticos en la carpeta `dist`.
  - Se publica con Firebase CLI mediante `firebase deploy --only hosting`.
  - Firebase Hosting se configura como single-page app, de modo que todas las rutas se redirijan a `index.html`.
  - Las variables de entorno del cliente (como la URL base del API) se definen en archivos `.env`.
  - La automatización del despliegue con GitHub Actions está planificada para los siguientes Sprints.
- URL: https://agridronapp.web.app

**API simulado (mock)**

- Herramienta: Apidog (servicio de mock).
- Repositorio: https://github.com/AgriDon/agridron-mock-api
- La especificación OpenAPI se versiona en el repositorio y la Web Application consume la URL del mock mientras el RESTful API se implementa.

**Despliegue del Backend (Web Services)** *(planificado)*

- Tecnología: C# con .NET (RESTful API).
- Repositorio: https://github.com/AgriDon/Agridron-backend
- Plataforma prevista: Render.
- Las variables sensibles (cadenas de conexión, claves JWT y credenciales del servicio de clima) se gestionarán en la configuración de la plataforma, y el servicio expondrá una URL con HTTPS y CORS restringido a la Web Application.

**Consideraciones generales**

- **Separación de entornos:** los entornos de desarrollo y producción se mantienen aislados mediante archivos de configuración (`appsettings.Development.json` y `appsettings.Production.json` en el backend, y archivos `.env` en el frontend).
- **Pruebas de humo:** después de cada despliegue se verifica manualmente la carga de la aplicación, la navegación entre vistas y el consumo de los endpoints.

## 5.2. Landing Page, Services & Applications Implementation

![Team Members](../images/chapter5/landingPage/teamMembers.png)

*Figura: Team Members de la Landing Page con información sobre el equipo de trabajo.*

![Footer](../images/chapter5/landingPage/footer.png)

*Figura: Footer de la Landing Page con información de contacto y redes sociales.*

**Aquí está el enlace a la página desplegada:** https://agridon.github.io/Agridron-LandingPage/

**Enlace del video de ejecucion en youtube:**  https://youtu.be/R6O4g6COh6o

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Como la Landing Page es una página estática, no fue necesario durante el Sprint el uso de
servicios externos ni conexiones a API's, por lo cual no hay generación ni evidencia de documentación técnica relacionada.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

La evidencia del despliegue de la Landing Page durante el Sprint se mostrará a continuación, el despliegue se realizará en GitHub Pages.

![settings github](../images/chapter5/github/settings.png)

*Nos dirigimos a la seccion de deploy, y selecionamos la rama main:*
*Luego de unos minutos, el deploy se realizara correctamente:*

![deploy github](../images/chapter5/github/deploy.png)

#### 5.2.1.8. Team Collaboration Insights during Sprint

Se anexa evidencia de la participación activa del equipo en el desarrollo de la Landing Page.
Durante el Sprint 1, el equipo utilizó una metodología colaborativa mediante Pull Requests y
revisiones de código, asegurando que cada sección cumpliera con los estándares de calidad definidos.
El gráfico de contribuciones muestra una distribución equitativa de tareas entre maquetación, estilos, lógica de i18n y despliegue.

![deploy github](../images/chapter5/github/TeamCollaboration.png)

*Reporte de contribuciones y commits del equipo Agridron en el repositorio de la Landing Page*

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

En el Sprint 2, el equipo se enfocó en el diseño, desarrollo y despliegue de la primera versión de la Web Application de AgriDron Solutions, desarrollada con Vue y PrimeVue bajo el lenguaje de diseño Material Design, y en la actualización de la Landing Page para que sus llamadas a la acción (CTA) redirijan a la vista correspondiente de la Web Application según el segmento.

| Campo | Detalle |
|:--|:--|
| **Sprint #** | Sprint 2 |
| **Fecha** | 26/09/2026 – 09/10/2026 |
| **Hora** | 16:00 hrs |
| **Lugar** | Virtual (Discord / Microsoft Teams) |
| **Preparado por** | Damacen Galindo, Italo Gianfranco; Vasquez Roncal, Alexander Felipe |
| **Asistentes** | Damacen Galindo, Italo Gianfranco; Nicho Huillcañahui, Edwin Noe; Vasquez Roncal, Alexander Felipe; Choquehuanca Vasquez, Alejandro Samir; Jara Espinoza, Miguel Angel |
| **Sprint 1 Review Summary** | La Landing Page quedó desplegada en GitHub Pages con las secciones planificadas (hero, características, planes y precios, preguntas frecuentes, navegación, equipo, galería, métricas de impacto y footer), diseño responsive, soporte multiidioma (ES/EN) y configuración de SEO y accesibilidad. [COMPLETAR: feedback del docente recibido en AV1] |
| **Sprint 1 Retrospective Summary** | Aciertos: uso de ramas feature y Pull Requests hacia `develop` y `main`, y reparto de aspectos entre líderes y colaboradores. Oportunidades de mejora: aplicar Conventional Commits de forma consistente en todos los mensajes y mejorar la estimación de tareas. |
| **Sprint 2 Goal** | Nuestro enfoque está en que agricultores y operadores técnicos puedan acceder a la Web Application desde la Landing Page, gestionar sus fincas y parcelas, y dar seguimiento a las misiones de fumigación, la flota de drones y los reportes. Creemos que esto genera confianza y reduce la coordinación informal por WhatsApp o llamadas. Se confirmará cuando un usuario de prueba pueda recorrer, sin ayuda del equipo, la Landing Page y la Web Application desplegada. |
| **Sprint 2 Velocity** | Límite de 35 SP \| Sumatoria de Story Points: 30 SP |

---

#### 5.2.2.2. Aspect Leaders and Collaborators

Para el Sprint 2 se definieron aspectos asociados a la Web Application y a la actualización de la Landing Page. Cada aspecto tiene un líder (L) responsable de su calidad y colaboradores (C) que apoyan su ejecución. Esta distribución se relaciona con la asignación de tareas del Sprint Backlog 2.

| Team Member | GitHub Username | Authentication & Routing | Field Management (Map) | Mission Request & Weather | Landing Page Update & CTAs | i18n & Accessibility | Deployment |
|:--|:--|:-:|:-:|:-:|:-:|:-:|:-:|
| **Damacen Galindo, Italo Gianfranco** | italodamacen | L | C | C | C | - | C |
| **Nicho Huillcañahui, Edwin Noe** | edwinnicho | C | L | C | - | C | L |
| **Jara Espinoza, Miguel Angel** | MiguelJara | C | C | L | C | C | C |
| **Choquehuanca Vasquez, Alejandro Samir** | SamirChoquehuanca | C | C | C | C | L | - |
| **Vasquez Roncal, Alexander Felipe** | alexandervasquez | - | C | C | L | C | C |

---
#### 5.2.2.3. Sprint Backlog 2

El Sprint Backlog 2 descompone las historias de usuario seleccionadas en tareas técnicas estimadas en horas.
El objetivo principal del sprint es entregar la primera versión desplegada de la Web Application, integrada con la Landing Page.

![Board del Sprint 2](../../assets/chapter5/sprint2/trello.png)

*Figura: Board del Sprint 2 en Trello.*

**URL público del board:** https://trello.com/invite/b/6aac1a270d8f45bc33ecd592/ATTIbc784176eb8dc497a26da32a3c554ea69211FF0D/agridron


| Sprint # | Sprint 2 |
|:--|:--|

| Story Id | Story Title | Task Id | Task Title | Task Description | Estimation (Hours) | Assigned To | Status (To-do / InProcess / ToReview / Done) |
|:--|:--|:--|:--|:--|:-:|:--|:--|
| LP-006 | Registrarse como nuevo usuario | T01 | Crear vista de registro | Construir el formulario de registro con PrimeVue y validaciones de campos. | [6] | [ ] | [Done] |
| LP-006 | Registrarse como nuevo usuario | T02 | Conectar registro con el servicio de autenticación | Enviar los datos del formulario al servicio [local/mock/API] y manejar respuestas de éxito y error. | [5] | [ ] | [Done] |
| LP-007 | Iniciar sesión en la plataforma | T03 | Crear vista de inicio de sesión | Construir el formulario de acceso con mensajes de error accesibles. | [4] | [ ] | [Done] |
| LP-007 | Iniciar sesión en la plataforma | T04 | Configurar rutas protegidas por rol | Configurar Vue Router con guardas de navegación para agricultor, operador y supervisor. | [5] | [ ] | [Done] |
| WA-001 | Registrar finca y parcelas en mapa interactivo | T05 | Integrar biblioteca de mapas | Incorporar la biblioteca de mapas ([Leaflet / otra]) con capa satelital. | [6] | [ ] | [Done] |
| WA-001 | Registrar finca y parcelas en mapa interactivo | T06 | Implementar dibujo de polígonos de parcelas | Permitir delimitar parcelas sobre el mapa y calcular el área en hectáreas. | [10] | [ ] | [Done] |
| WA-001 | Registrar finca y parcelas en mapa interactivo | T07 | Crear formulario y listado de fincas | Registrar nombre, ubicación y cultivo, y listar las fincas del usuario. | [6] | [ ] | [Done] |
| WA-002 | Solicitar misión con validación de riesgos | T08 | Crear formulario de solicitud de misión | Seleccionar parcela, cultivo y fecha para solicitar el servicio. | [6] | [ ] | [Done] |
| WA-002 | Solicitar misión con validación de riesgos | T09 | Mostrar validación de riesgo climático | Presentar la condición del clima antes de confirmar la solicitud. | [4] | [ ] | [Done] |
| TU-003 | Integración con Weather API | T10 | Consumir servicio externo de clima | Implementar el cliente del servicio externo ([nombre de la API]) y manejar errores de conexión. | [6] | [ ] | [Done] |
| WA-003 | Consultar historial y estados | T11 | Crear vista de historial de misiones | Listar misiones con su estado y filtros básicos. | [5] | [ ] | [Done] |
| WA-005 | Gestionar agenda de órdenes | T12 | Crear vista de agenda del operador | Mostrar las órdenes asignadas en calendario junto con la parcela. | [6] | [ ] | [Done] |
| — | Tarea general (Landing Page) | T13 | Actualizar CTAs por segmento | Redirigir cada CTA de la Landing Page a la vista correspondiente de la Web Application. | [4] | [ ] | [Done] |
| — | Tarea general (i18n y a11y) | T14 | Implementar i18n y atributos ARIA en la Web Application | Soportar inglés (en_US, por defecto) y español latinoamericano (es_419), y configurar ARIA. | [8] | [ ] | [Done] |
| — | Tarea general (Despliegue) | T15 | Desplegar la Web Application | Configurar el despliegue desde el repositorio y publicar la primera versión. | [5] | [ ] | [Done] |
 
---

#### 5.2.2.4. Development Evidence for Sprint Review

Durante el Sprint 2 el equipo avanzó en la implementación de la Web Application y en la actualización de la Landing Page de AgriDron Solutions. En la Web Application (Vue 3 con Vite) se estructuró el proyecto, se implementaron los bounded contexts Field Management, Weather Integration, Flight Operations y Analytics & Reporting, y se construyeron las vistas del dashboard y de configuración alineadas con los mock-ups. En paralelo se refactorizó la organización del código para seguir las convenciones de Domain-Driven Design. En la Landing Page se mejoró el diseño responsive y se incorporó el selector de idioma (i18n).

El trabajo se organizó con GitFlow: cada bounded context o funcionalidad se desarrolló en su rama `feature/*` y se integró en `develop` mediante Pull Requests o merges. Las tablas siguientes listan los commits del Sprint 2 por repositorio.

##### Repositorio: Web Application

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|:--|:--|:--|:--|:--|:-:|
| AgriDon/Agridron-Fronted | develop | f426ac7 | initialize project structure with Vue 3, Vite, and basic layout components | Inicialización del proyecto con Vue 3 y Vite, y componentes base del layout. | 03/10/2026 |
| AgriDon/Agridron-Fronted | develop | eea89a3 | refactor: remove TypeScript support and update script setup in Vue components | Se elimina TypeScript y se actualiza el uso de script setup en los componentes Vue para trabajar con JavaScript. | 03/10/2026 |
| AgriDon/Agridron-Fronted | feature/fieldManagement | 914f310 | docs: resolver conflicto en README.md al fusionar develop | Resolución del conflicto en el README al integrar develop en la rama de la funcionalidad. | 06/10/2026 |
| AgriDon/Agridron-Fronted | feature/fieldManagement | e6070f3 | bounded contex 2 field management | Implementación del bounded context Field Management (fincas y parcelas). | 06/10/2026 |
| AgriDon/Agridron-Fronted | develop | 9faa7f4 | Merge pull request #1 from AgriDon/feature/fieldManagement | Integración de Field Management en develop mediante Pull Request #1. | 06/10/2026 |
| AgriDon/Agridron-Fronted | feature/weatherIntegration | 1dde398 | feat(weatherIntegration): migrate weatherIntegration bounded context from Angular to Vue | Migración del bounded context Weather Integration a Vue. | 07/10/2026 |
| AgriDon/Agridron-Fronted | feature/flightOperations | 401c3b2 | add: flightOpe | Primera versión del bounded context Flight Operations. | 07/10/2026 |
| AgriDon/Agridron-Fronted | feature/flightOperations | 2fea35d | add: comments | Comentarios de documentación en el código de Flight Operations. | 07/10/2026 |
| AgriDon/Agridron-Fronted | feature/fieldManagement | 4a18e03 | Merge remote-tracking branch 'origin/feature/flightOperations' into feature/fieldManagement | Integración de Flight Operations en la rama de Field Management. | 07/10/2026 |
| AgriDon/Agridron-Fronted | feature/fieldManagement | 18f17f6 | se agregaron bounded contex feature/weatherIntegration and feature/flightOperations | Se incorporan los bounded contexts Weather Integration y Flight Operations a la rama de Field Management. | 07/10/2026 |
| AgriDon/Agridron-Fronted | develop | e989dff | Merge pull request #2 from AgriDon/feature/fieldManagement | Integración de los tres bounded contexts en develop mediante Pull Request #2. | 07/10/2026 |
| AgriDon/Agridron-Fronted | develop | e0f9ad0 | feat(db): add new crop treatment entry and update server script | Nuevo registro de tratamiento de cultivo en los datos de prueba y actualización del script del servidor. | 08/10/2026 |
| AgriDon/Agridron-Fronted | develop | 6145836 | fix(flightOperations): resolve i18n translation keys and status badge styles in missions | Corrección de claves de traducción y estilos de las etiquetas de estado en misiones. | 08/10/2026 |
| AgriDon/Agridron-Fronted | develop | 11208cd | refactor(architecture): align fieldManagement, flightOperations, and weather integration with DDD principles | Reorganización de los tres bounded contexts según las convenciones de DDD. | 08/10/2026 |
| AgriDon/Agridron-Fronted | develop | aa3efae | fix(primevue): bypass license verification and suppress invalid license watermark | [Completar con el detalle real del cambio.] | 08/10/2026 |
| AgriDon/Agridron-Fronted | feature/reportingContext | f91dea6 | feat(reporting): implement analytics and reporting bounded context (BC5) | Implementación del bounded context Analytics & Reporting. | 08/10/2026 |
| AgriDon/Agridron-Fronted | develop | 9235c48 | Merge branch 'feature/reportingContext' into develop | Integración de Analytics & Reporting en develop. | 08/10/2026 |
| AgriDon/Agridron-Fronted | develop | 3c8b7dc | feat(flightOperations): integrate drone fleet management from FlightOperations branch | Integración de la gestión de la flota de drones en Flight Operations. | 09/10/2026 |
| AgriDon/Agridron-Fronted | develop | f007a56 | refactor(flightOperations): align architecture with DDD conventions | Reorganización de Flight Operations según las convenciones de DDD. | 09/10/2026 |
| AgriDon/Agridron-Fronted | feature/dashboard-and-settings | be3e9fb | refactor(shared): move layout component to shared presentation layer | El componente de layout pasa a la capa de presentación compartida. | 09/10/2026 |
| AgriDon/Agridron-Fronted | feature/dashboard-and-settings | ea80eb2 | feat(shared): implement dashboard home and settings views matching mockups | Vistas de inicio (dashboard) y configuración según los mock-ups del capítulo IV. | 09/10/2026 |
| AgriDon/Agridron-Fronted | feature/dashboard-and-settings | b5a66f0 | fix(ui): improve home KPI image reliability and synchronize user profile with layout header | Mejora de la carga de imágenes de los KPI y sincronización del perfil de usuario con la cabecera del layout. | 09/10/2026 |
| AgriDon/Agridron-Fronted | develop | 8430748 | Merge branch 'feature/dashboard-and-settings' into develop | Integración del dashboard y configuración en develop. | 09/10/2026 |

##### Repositorio: Landing Page

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|:--|:--|:--|:--|:--|:-:|
| AgriDon/Agridron-LandingPage | develop | f9a0fe6 | add: Improvements to responsive desing | Mejoras del diseño responsive para dispositivos móviles y de escritorio. | 07/10/2026 |
| AgriDon/Agridron-LandingPage | main | 4ec863a | Merge pull request #2 from AgriDon/develop | Publicación de las mejoras responsive mediante Pull Request #2. | 07/10/2026 |
| AgriDon/Agridron-LandingPage | develop | b5d4852 | add: translator | Selector de idioma para la internacionalización (inglés y español). | 07/10/2026 |
| AgriDon/Agridron-LandingPage | main | a703f2a | Merge pull request #3 from AgriDon/develop | Publicación del selector de idioma mediante Pull Request #3. | 07/10/2026 |

*Nota: los commits del 18/09/2026 de ambos repositorios (Initial commit y primera versión de la Landing Page) pertenecen al Sprint 1 y se presentan en la sección 5.2.1.4.*
 
---

#### 5.2.2.5. Execution Evidence for Sprint Review

En el Sprint 2 se logró la primera versión funcional de la Web Application de AgriDron Solutions, desarrollada con Vue 3 y PrimeVue, junto con la actualización de la Landing Page. La Web Application integra los bounded contexts Field Management, Weather Integration, Flight Operations y Analytics & Reporting, además de un layout compartido con las vistas de inicio (dashboard) y configuración, construidas según los mock-ups definidos en el capítulo IV. La interfaz se adapta a distintos tamaños de pantalla y soporta cambio de idioma entre inglés y español.

Se utilizó un API simulado (mock) para validar los flujos de gestión de fincas y parcelas, misiones, flota de drones y analítica sin depender del RESTful API en desarrollo. A continuación se presentan las principales vistas implementadas durante el Sprint, junto con una explicación de lo que permite hacer cada una.

##### Landing Page

![Landing Page en escritorio](../../assets/chapter5/sprint2/landingPage.png)

*Figura: Landing Page en su versión de escritorio.*

![Landing Page en móvil](../../assets/chapter5/sprint2/landingPageMovile.png)

*Figura: Landing Page en su versión móvil.*

En este Sprint se mejoró el diseño de la Landing Page para que las secciones se reorganicen correctamente en pantallas pequeñas, manteniendo la legibilidad y el tamaño adecuado de los elementos interactivos.

![Selector de idioma de la Landing Page](../../assets/chapter5/sprint2/idioma.png)

*Figura: Selector de idioma (inglés / español) y botón de demostración en la Landing Page.*

Se incorporó el selector de idioma, que permite al visitante alternar entre inglés (idioma por defecto) y español latinoamericano, como parte del enfoque de internacionalización del producto. Además, un botón permite acceder a una demostración del sistema.

##### Web Application

![Vista de inicio](../../assets/chapter5/sprint2/home.png)

*Figura: Vista de inicio (dashboard) con indicadores clave (KPI).*

La vista de inicio presenta un resumen de la operación mediante indicadores clave (KPI), de modo que el usuario identifique rápidamente el estado general de sus fincas y misiones al ingresar. El perfil del usuario se muestra sincronizado con la cabecera del layout.

![Gestión de fincas y parcelas](../../assets/chapter5/sprint2/fieldManagement.png)

*Figura: Vista de gestión de fincas y parcelas (Field Management).*

Esta vista permite registrar y consultar las fincas y parcelas del agricultor, que son la base para solicitar misiones de fumigación.

![Listado de misiones con etiquetas de estado](../../assets/chapter5/sprint2/missionList.png)

*Figura: Listado de misiones con etiquetas de estado (Flight Operations).*

El listado de misiones muestra cada misión con una etiqueta de estado, lo que facilita el seguimiento de las operaciones. Los textos de la vista se traducen según el idioma seleccionado.

![Gestión de la flota de drones](../../assets/chapter5/sprint2/droneFleet.png)

*Figura: Vista de gestión de la flota de drones.*

Esta vista permite consultar los drones disponibles y su estado, información que apoya la asignación de misiones a los operadores.

![Analítica y reportes](../../assets/chapter5/sprint2/analytics.png)

*Figura: Vista de analítica y reportes (Analytics & Reporting).*

La vista de analítica consolida información histórica de las operaciones y de los tratamientos aplicados, y apoya la toma de decisiones del agricultor y del supervisor.

##### Enlaces

**Web Application desplegada:** https://agridronapp.web.app

**Landing Page desplegada:** https://agridon.github.io/Agridron-LandingPage/

**Video de ejecución:** [COMPLETAR: URL del video (YouTube o Microsoft Stream) y duración]

---

    "location": "Cañete",
    "temperature": 24.5,
    "humidity": 68,
    "windSpeed": 12.3,
    "precipitation": 0,
    "observedAt": "2026-10-02T08:00:00",
    "alerts": []
}
]
```
 
`GET /drones` devuelve la flota de drones con su estado, nivel de batería y fechas de mantenimiento:
 
```json
[
  {
    "id": 1,
    "serialNumber": "AGRI-DRN-001-A",
    "model": "DJI Agras T40",
    "capacity": 40,
    "status": "AVAILABLE",
    "batteryLevel": 80,
    "nozzleId": 1,
    "lastMaintenanceDate": "2026-08-10",
    "nextMaintenanceDate": "2026-11-10"
  }
]
```

![Vista de analítica y reportes](../../assets/chapter5/sprint2/apidog-endpoints.png)

Figura: Lista de endpoints documentados en Apidog.

![Documentación de endpoints en Apidog mission](../../assets/chapter5/sprint2/apidog-missions.png)

Figura: Prueba del endpoint GET /missions con datos de muestra en Apidog.

![Documentación de endpoints en Apidog clima](../../assets/chapter5/sprint2/apidog-clima.png)

Figura: Prueba del endpoint GET /weather con datos de muestra en Apidog.

Repositorio de Web Services: https://github.com/AgriDon/agridron-mock-api/tree/develop

Commits relacionados con documentación: 5125fde

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 2 se realizaron actividades de despliegue para los tres productos de la solución. Se publicó la primera versión de la Web Application en Firebase Hosting, se volvió a desplegar la Landing Page con las mejoras de diseño responsive y el selector de idioma, y se dejó disponible el API simulado que consume la Web Application mientras el RESTful API en ASP.NET Core se encuentra en desarrollo.

| Producto | Plataforma | URL desplegada | Repositorio |
|:--|:--|:--|:--|
| Landing Page | GitHub Pages | https://agridon.github.io/Agridron-LandingPage/ | https://github.com/AgriDon/Agridron-LandingPage |
| Web Application | Firebase Hosting | https://agridronapp.web.app | https://github.com/AgriDon/Agridron-Fronted |
| API simulado (mock) | Apidog | https://mock.apidog.com/m1/1395107-1402934-default | https://github.com/AgriDon/agridron-mock-api |

##### Landing Page

La Landing Page se publica desde la rama `main` de su repositorio con GitHub Pages. En este Sprint, las mejoras de diseño responsive y el selector de idioma se integraron en `develop` y se publicaron mediante los Pull Requests #2 y #3 hacia `main` (07/10/2026), lo que activó un nuevo despliegue.

![Despliegue de la Landing Page en GitHub Pages](../../assets/chapter5/sprint2/deploy-landing.png)

*Figura: Despliegue de la Landing Page en GitHub Pages.*

##### Web Application

La Web Application se desplegó en Firebase Hosting, que sirve la aplicación compilada de Vue como un sitio estático con HTTPS. Pasos realizados:

1. **Creación del proyecto en Firebase.** Desde la consola de Firebase se creó el proyecto AgridronApp y se habilitó el servicio Firebase Hosting.

   ![Creación del proyecto](../../assets/chapter5/sprint2/deploy-webapp-1.png)

   *Figura: Creación del proyecto en la consola de Firebase.*

2. **Instalación de Firebase CLI e inicio de sesión.** Se instaló la herramienta con `npm install -g firebase-tools` y se inició sesión con `firebase login`.

   ![Instalación e inicio de sesión](../../assets/chapter5/sprint2/deploy-webapp-2.png)

   *Figura: Instalación de Firebase CLI e inicio de sesión.*

3. **Inicialización de Hosting.** Dentro del repositorio `Agridron-Fronted` se ejecutó `firebase init hosting`. Se seleccionó el proyecto creado, se indicó `dist` como directorio público y se configuró la aplicación como single-page app, de modo que todas las rutas se redirijan a `index.html` y la navegación entre vistas funcione al recargar la página.

   ![Inicialización de Hosting](../../assets/chapter5/sprint2/deploy-webapp-3.png)

   *Figura: Inicialización de Firebase Hosting en el repositorio.*

4. **Build y despliegue.** Se generó el build de producción con `npm run build` y se publicó con `firebase deploy --only hosting`, que devolvió la URL de Hosting. Se verificó que la aplicación cargara en esa URL, incluyendo la navegación entre vistas.

   ![Despliegue exitoso](../../assets/chapter5/sprint2/deploy-webapp-4.png)

   *Figura: Despliegue completado y aplicación disponible en Firebase Hosting.*

##### API simulado

Los endpoints simulados se publican mediante el servicio de mock de Apidog, cuya URL base es https://mock.apidog.com/m1/1395107-1402934-default. La Web Application consume esa URL, y la especificación OpenAPI se versiona en el repositorio `agridron-mock-api`.

![Configuración del API simulado](../../assets/chapter5/sprint2/deploy-mock.png)

*Figura: Configuración del API simulado en Apidog.*

##### Integración con el flujo de trabajo

El despliegue de la Landing Page es automático: cada integración en `main` actualiza GitHub Pages. La Web Application se publica con Firebase CLI después de integrar los cambios en el repositorio; la automatización de este paso con GitHub Actions está planificada para los siguientes Sprints. [COMPLETAR: confirmar la rama desde la que se despliega la Web Application]

---

#### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, el equipo desarrolló las actividades de implementación en tres repositorios de la organización AgriDron en GitHub: la Web Application (`Agridron-Fronted`), la Landing Page (`Agridron-LandingPage`) y el API simulado (`agridron-mock-api`). El trabajo se organizó con GitFlow: cada bounded context o funcionalidad se desarrolló en una rama `feature/*` y se integró en `develop` mediante Pull Requests o merges, y las versiones estables de la Landing Page se publicaron desde `main`. Se adoptó Conventional Commits; algunos mensajes de este Sprint no siguen la convención, por lo que se reforzará su aplicación en el siguiente Sprint.

##### Contribución por integrante

| Integrante | Repositorio | Aporte principal en el Sprint 2 | Commits |
|:--|:--|:--|:-:|
| Damacen Galindo, Italo Gianfranco | https://github.com/AgriDon/Agridron-Fronted/tree/develop | bounded context Flight Operations | 937C310 |
| Nicho Huillcañahui, Edwin Noe | https://github.com/AgriDon/Agridron-LandingPage/tree/develop | despliegue en Firebase Hosting y configuración del proyecto | 977K250 |
| Jara Espinoza, Miguel Angel | https://github.com/AgriDon/agridron-mock-api/tree/develop | especificación OpenAPI y API simulado | 837A410 |
| Choquehuanca Vasquez, Alejandro Samir | https://github.com/AgriDon/Agridron-Fronted/tree/develop | internacionalización y accesibilidad | 867K750 |
| Vasquez Roncal, Alexander Felipe | https://github.com/AgriDon/Agridron-LandingPage/tree/develop | Landing Page responsive y vistas de dashboard | 356C250 |

##### Web Application

![Insights de la Web Application - Sprint 2](../../assets/chapter5/sprint2/insights-webapp.png)

*Figura: Contribuciones de los integrantes en el repositorio de la Web Application durante el Sprint 2.*

##### Landing Page

![Insights de la Landing Page - Sprint 2](../../assets/chapter5/sprint2/insights-landing.png)

*Figura: Contribuciones de los integrantes en el repositorio de la Landing Page durante el Sprint 2.*

##### API simulado

![Insights del API simulado - Sprint 2](../../assets/chapter5/sprint2/insights-mock-api.png)

*Figura: Contribuciones de los integrantes en el repositorio del API simulado durante el Sprint 2.*