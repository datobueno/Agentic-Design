# Módulo Agentic Product Design  (UI/UX)

**Formato:** 13 sesiones, 34 horas

## Introducción

El módulo aborda el diseño de UI/UX con apoyo de agentes generativos, a través del desarrollo de un producto o experiencia interactiva a elección del alumno.

La duración es de trece sesiones, en las que se impartirán los conocimientos básicos para el desarrollo del bloque y de las tareas prácticas. Se resolverán todas aquellas dudas que lxs alumnxs vayan exponiendo. 

El alumnado trabajará sobre un proyecto propio organizado en cinco bloques:

- **Estrategia:** aprenderemos a trabajar con agentes para que nos apoye en la definición de la intención del producto a partir de una visión inicial. Construiremos un contexto compartido para que diseñador y agente puedan consultar problemas e hipótesis de diseño.
- **Arquitectura:** estableceremos criterios atómicos de diseño para automatizar y delegar tareas en agentes de forma consistente con el sistema de diseño. Definiremos las entidades y relaciones necesarias para estructurar la información del producto.
- **Formalización:** colaboraremos con agentes para diseñar interfaces y convertir procesos de diseño en instrucciones reutilizables.
- **Investigación:** utilizaremos el contexto de la estrategia para que los agentes puedan generar nuevos supuestos, formular preguntas y preparar estrategias de investigación.
- **Implementación:** conectaremos las interfaces, los datos y los flujos mediante agentes de programación.

**Trabajo final:** El alumando dispone de 10 horas OnLive tutorizadas para desarrollar su proyecto final. Se recomienda usar las sesiones teóricas para ir avanzando.

***IMPORTANTE: Este programa usa de forma extensiva diferentes modelos de inteligencia artificial para alcanzar sus objetivos. Se recomienda atender las clases con suscripciones de pago de los modelos que los asistentes quieran utilizar. (ChatGPT / Claude / Gemini y Figma). El alumnado puede decidir adquirir licencias de Mobbin o Refero para acceder al MCP de diseño, con el fin de agilziar su proceso creativo.***

## Objetivos

- Definir la estrategia del producto: concretar su intención, usuarios, problema, alcance y resultados esperados.
- Organizar el contexto para agentes: estructurar conocimiento, evidencias, supuestos e incógnitas que permitan orientar su trabajo.
- Explorar oportunidades de diseño: utilizar herramientas generativas así como agentes para crear nuevos diseños.
- Formalizar criterios y procesos: documentar estilos, componentes y patrones, y crear skills que permitan delegar tareas on demand.
- Preparar investigación con usuarios: identificar preguntas y seleccionar métodos, utilizando IA para elaborar entrevistas y pruebas de usabilidad.
- Conectar datos, diseño y código: definir entidades y relaciones, diseñar pantallas y estados en Figma y desarrollar un recorrido funcional conectado con datos.

## Metodología

- El módulo es un taller proyectual a partir de proyectos reales de interés para el alumnado.
- Cada estudiante trabajará sobre un producto, servicio o experiencia visual de otra asignatura, o seleccionará un proyecto nuevo. 
- Cada sesión incluirá una base teórica, ampliable con otros conocimientos según las necesidades del alumnado.
- Se compartirán regularmente avances, resultados y métodos relevantes para el aprendizaje del grupo.
- Se invitará al alumnado a aportar opiniones y feedback constructivo sobre los trabajos de sus compañeros.

## Contenidos

**Estrategia (Sesiones 1 y 2)**

- Intención y motivación para agentes
- Product discovery agéntico

**Arquitectura (Sesiones 3 y 4)**

- Sistema de diseño
- Modelo de datos y entidades de diseño

**Formalización (Sesiones 5 y 6)**

- Diseño de flujos en Figma
- Skills auténticos de diseño

**UX Research (Sesión 7)**

- Research asistido por agentes

**Building (Sesión 8)**

- Conectar la experiencia con el código

**Trabajo final (Sesiones 9 a 13)**

## 1er Bloque: Estrategia (2 clases)

### 1ª sesión: Contexto estratégico

**Previo a la sesión:** el alumnado deberá acudir a al primera sesión con una idea de proyecto. Esta idea servirá como hilo conductor de todo el curso. No hace falta que esté desarrollada. 

En la primera sesión formará, a tarvés de un trabajo manual, crearemos un contexto del que los agentes se beneficiarán en las sesiones posteriores. El alumnado partirá desde una intuición para definir la intención de un producto. Organizará en Obsidian, o en su IDE de confianza, el contexto que los agentes utilizarán para entender la motivación, la intención y las hipótesis de negocio que hay detrás.

- Configurará su espacio de trabajo en un IDE (Cursor, Visual Studio, Antigravity, etc...)
- Se realizará una introducción a las funcionalidades básicas de los IDEs.
- Definirá la intención de un producto mediante el marco de las 5W y la protopersona a la que va dirigida.
- Identificará competidores directos e indirectos
- Formulará problemas y Jobs to Be Done mediante skills.

**Resultado de la sesión:** Un espacio de producto que dará al agente el espacio contextual, organizado y curado para poder entender nuestra intención y recomendar avances.

### Sesion 2: Product Discovery agéntico

Utilizar el contexto estratégico como materia prima para que diseñador y agentes colaboren en El alumnado retomará el primer JTBD para identificar qué problemas merece la pena abordar, contrastar sus supuestos con productos de referencia y priorizar oportunidades de diseño.

- Analizará funcionalidades de competidores y referencias mediante scrapping agéntico con Firecrawl.
- Construirá un Opportunity Solution Tree que los agentes usarán para identificar y priorizar oportunidades.

**Resultado de la sesión:** Un primer JTBD y sus enunciados de problema refinados, una protopersona revisada, un análisis funcional de referencias y un árbol de oportunidades que orienta la fase de arquitectura visual.

## 2º Bloque: Arquitectura (2 clases)

### 3ª sesión: Creación del sistemas de diseño

Estructurar las decisiones de UI de manera que puedan ser comprendidas y utilizadas tanto por diseñadores como por agentes generativos.

- Utilizará MCPs de referecncias visuals como Mobbin, Refero 
- Usará la librería Shadcn como base de componentes comunes
- Utilizará el MCP de FIgma para conectar el agente con el diseño
- Definirá estilos y variables en Figma 
- Establecerá patrones de interfaz

**Resultado de la sesión:** sistema de diseño simple, documentado, creado y reinterpretable por agentes.

### 4ª sesión: Entidades y modelo de datos

Transformar el recorrido de usuario en flujo interactivo con las entidades básicas ya diseñadas e implementadas.

- Identificará las entidades necesarias a partir de los JTDB  proyecto.
- Construirá un diccionario de datos: campos, tipos, identificadores, obligatoriedad, valores permitidos y procedencia
- Creará valores de ejemplo.

**Resultado de la sesión:** modelo de información que populará el producto.

## 3er Bloque: Formalización (2 clases)

### 5ª sesión: Views en Figma

Convertir el comportamiento y la arquitectura definidos previamente en una interfaz consistente, utilizando Figma AI y Figma MCP.

- Compondrá las pantallas del recorrido principal utilizando los patrones definidos.
- Incorporará contenidos y campos correspondientes al modelo de datos.
- Diseñará los estados de carga, vacío, validación, error y recuperación pertinentes para cada experiencia.
- Utilizará referencias visuales y herramientas de exploración creativa como Mobbin, Refero,  Google Stitch o similares si fuera necesario.

**Resultado de la sesión:** recorrido principal formalizado en Figma mediante un sistema de diseño.

### 6ª sesión: Creación de skills de diseño

Transformar procedimientos habituales de UI/UX en instrucciones reutilizables que permitan a los agentes ejecutar tareas siguiendo los criterios del diseñador.

- Distinguirá entre contexto, instrucciones, skills, referencias, assets y scripts en una misma skill.
- Estructurará procedimientos ejecutables por agentes.
- Evaluará y adaptará skills existentes.
- Aprenderá donde encontrar skills prefabricadas y modifcarlas para sus usos específicos.
- Seguirá diseñando interfaces esta vez con la involucración de skills.

**Resultado de la sesión:** conjunto inicial de skills que permite delegar operaciones de diseño manteniendo criterios y procesos definidos por el diseñador.

## 4º Bloque: Investigación (1 clase)

### 7ª sesión: UX Research agéntico

Convertir los supuestos e incógnitas en un plan de investigación, utilizando agentes para analizar contexto y preparar métodos sin sustituir la investigación con usuarios reales.

- Identificará actores y fuentes relevantes para la investigación.
- Formulará y priorizará preguntas de investigación.
- Seleccionará métodos de UX Research adecuados.
- Aplicará cambios derivados de la invetsigación agéntica.

**Resultado de la sesión:** un protocolo de investigación conectado con las decisiones y preguntas surgidas durante el diseño del producto.

## 5º Bloque: Implementación (1 clase)

### 8ª sesión: Conectar la experiencia con el código

Transformar el diseño en una implementación funcional utilizando agentes de programación y el contexto generado durante las sesiones anteriores.

- Traducirá componentes y patrones de Figma a código.
- Utilizará Storybook para visualizar componentes, variantes y estados.
- Integrará APIs, bases de datos, hojas de cálculo u otras fuentes estructuradas.
- Versionará y supervisará cambios mediante Git y GitHub.
- Usará Vercel o Github.io para publicar su producto

**Resultado de la sesión:** recorrido funcional implementado y conectado con datos reales o representativos manteniendo.

## 6º Bloque: Trabajo Final (5 clases)

### 9ª a 13ª sesión: Trabajo Final

Estas sesiones estarán destinadas integramente a la tutoría y feedback del trabajo final.