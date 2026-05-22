# Bitácora

Registro de sesiones del semillero.
## Sesión 5 2026-05-20

- **Visión Estratégica (Próximo Semestre)**
  - Propuesta del Profe Edison para estructurar el Semillero como un grupo exclusivo por invitación.
  - Debate sobre la gestión del tiempo y la viabilidad de extender la duración de las sesiones más allá de una hora (planteado por Santiago).
  - Enfoque en rutas en aprendizaje a través de los cursos oficiales de Claude.
- **Discusión Técnica y Referencias**
  - Análisis del consumo de tokens y el futuro de la infraestructura de IA basado en el ensayo [Situational Awareness](https://situational-awareness.ai/).
  - Introducción a la metodología *Spec-Driven Development* (SDD) mediante el repositorio curado [Awesome Spec-Driven Development](https://github.com/Engineering4AI/awesome-spec-driven-development).
  - Exploración de [agents.md](https://agents.md/) como una fuente de referencia clave para consultar otros ejemplos prácticos de flujos de trabajo (*workflows*) de agentes estructurados en Markdown.
  - Revisión del framework [BMAD Method](https://github.com/bmad-code-org/BMAD-METHOD?tab=readme-ov-file#readme), enfocado en la orquestación de agentes para la creación de agencias de desarrollo autónomas.
  - Estudio de caso práctico del repositorio de **Gotalab**, analizando el flujo de trabajo para desglosar features (*Break down a large initiative*) en su guía de documentación técnica [spec-driven.md](https://github.com/gotalab/cc-sdd/blob/main/docs/guides/spec-driven.md).
- **Líneas de Investigación Propuestas**
  - **Optimización Sintáctica:** Análisis comparativo de eficiencia en consumo de tokens y precisión estructural entre formatos YAML y Markdown (`.md`).
  - **Agentes de Validación:** Estudiar la necesidad de "Agentes Supervisores" en circuitos cerrados de retroalimentación para auditar la precisión del código en SDD. Podemos vernos en casos donde un agente complique el trabajo, antes de hacerlo bien.
  - **Taxonomía de Agentes (Vibecoding Core):** Delimitación conceptual y operativa entre un *skill*, un *MCP (Model Context Protocol)* y un *Role*.
- **Filosofía y Cultura**
  - Reflexión sobre [The Way of Code](https://wayofcode.com/) (inspirado en Rick Rubin), adoptando el rol del programador actual como un productor creativo y editor de contexto. Esta discusión siembra la semilla para el futuro **Manifiesto de Vibecoding UdeA**.
- **Tareas y Siguientes Pasos**
  [ ] Definir criterios de selección para el formato por invitación.
  [ ] Evaluar el nuevo horario para las sesiones prácticas.
  [ ] Diseñar el entorno de pruebas para experimentar con las líneas de investigación planteadas.

## Sesión 4: 2026-05-13

- Hablamos sobre google dev exper talk, agentic flutter y angular. Aula 21 - 326 ingeniera 20 junio 10 am a 2 pm

> Enviar logo universidad para que ellos compartan comunicaciones y mandar correo oficial a facultades. 

- Sandusky expone su flujo de trabajo creando el curso de programacion creativa : artilugiotaller.com

## Sesión 3: 2026-05-06

- Merge del PR de Dani donde explica el flujo de trabajo para la creación de material de estudio.

- Santiago presenta su flujo de trabajo para creacion de prototipos

- Primer caso, Lorenz AI en clude design, articulando Google Stich, Gemini y Claude Design

- Caso: Sistema de control de redes contra incendios, articulando Figma, Gemini y Claude Design.

- Idea: Taller sobre economia de tokens

- Se presenta Erix y GDC Colombia, vistazo a como funciona GDC

- Nos presenta las proximas actividades de GDC Colombia.

- Hablamos sobre las posibilidades para realizar un evento de "Build with AI" en la universidad.

- Quedamos pendientes de coordinar fecha y logística para el evento de "Expert talks" en la universidad para no cruzar con examenes finales.

- Erix nos habla sobre como se usa la IA en Mercado Libre desde su experiencia persona: Usan SDD; Skills, MCP, todo con Claude Code exclusivamente. La IA es requisito dentro de la compañía. Orquestan equipos de agentes para desarrollar segun responsabilidades.

- Meli usa diferentes plantilla de SDD.

    - La primera desarrolla planes donde el agente hace preguntas al product owner.
    - La segunda plantilla detalla las espeficaciones de tecnologia.
    - La tercera plantilla incluye los detalles de la especificacion para cada feature. 
    - Para aceptar el codigo, usan skills en claude para diferentes plataformas, para android por ejemplo un skill que presenta los criterios de aceptacion adaptados a android. Asegurando buenas practicas, uso del framework, seguridad, etc.

- Pendiente: Coordinar taller de google dev experts sobre creacion de agentes con gemini.

## Sesión 2: 2026-04-29

- Andrés Presenta brevemente el programa de google dev community : https://developers.google.com/community/build-with-ai y sugire la posibildiad de organizar una meetup en la universidad.

- Daniel nos muestra su flujo de trabajo creando clases: Numeros transfinitios con Latex y ondas gravitatorias con Jupyter + python. Importante: documentar sus prompts en la carpeta de repo. Uso de copilot desde github directamente en el navegador. Otras herramientas usadas Prism. Importante: La universidad ofrece copilot junto a github education.

- Edison comenta la idea de un orquestador de modelos que separe labores entre diferentes modelos.

- Daniel dice que le gustarpia crear flujos de trabajo mas elaborados y que no sea simplemente enviar prompts.

## Sesión 1: 2026-04-22

- Introducción al programa.
- Presentación de asistentes.
- Acuerdo de flujo de trabajo: Trunk-based en GitHub con PR's.
- Propuesta de trabajo: Estructura de carpetas individuales en `proyectos/`.