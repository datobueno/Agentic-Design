# Curso Agentic Product Design  (UI/UX)

**Formato:** 10 sesiones de 1 h 30 min.

## Introducción

El módulo aborda el diseño de producto digital (UI/UX) con apoyo de agentes generativos, a través del desarrollo de un producto o servicio a elección del alumnado. Cada estudiante definirá la intención de su producto, establecerá un sistema de diseño, diseñará el recorrido principal en Figma y lo llevará a una implementación funcional.

***El programa hace un uso extensivo de herramientas de IA. Se recomienda disponer de credenciales de pago a un modelo como ChatGPT, Claude o Gemini y a Figma Professional o Education. Servicios adicionales de pago recomendables, pero no obligatorios, Mobbin y Refero Plus.***

## Objetivos

- Definir la intención del producto, sus usuarios, el problema y las hipótesis de partida.
- Organizar el conocimiento del proyecto para que el equipo y los agentes puedan consultar y reutilizar el contexto.
- Establecer estilos, variables, componentes y patrones coherentes en un sistema de diseño.
- Definir las entidades del producto y los datos/contenido que mostrará la interfaz.
- Aprender a diseñar y revisar en Figma mediante el uso de agentes.
- Implementar el recorrido con agentes de programación y conectarlo a una fuente de datos.

## Metodología

El enfoque de las sesiones es el de un taller proyectual. Partiremos de un proyectos de interés para el alumnado. Cada estudiante trabajará sobre un producto, servicio o experiencia visual de otra asignatura, o seleccionará un proyecto nuevo. En cada sesión se compartirán avances y se invitará al alumnado a aportar feedback constructivo. 

## 1er Bloque: Estrategia (2 clases)

### 1ª sesión: Contexto estratégico I: Intención y público del producto

**Previo a la sesión:** El alumno tendrá que venir con una idea de producto y experiencia que servirá como hilo conductor de todo el curso. Ideas sencillas que puedan desarrollarse en lenguajes HTML web. Pasarelas de pago y autenticaciones quedan fuera del encaje del curso.

- Configurar el espacio de trabajo en Obsidian o en el IDE elegido y preparar dónde guardar el contexto del proyecto.
- Partir de una intuición para definir la intención del producto con las 5W.
- Redactará una protopersona con las hipótesis de partida y se mejorará a través de skills.
- Revisar si el contexto explica con claridad a quién se dirige el producto, qué problema pretende resolver y por qué merece la pena abordarlo.

**Resultado de la sesión:** espacio de trabajo con las 5W y una primera protopersona.

### 2ª sesión: Contexto estratégico para agentes II: Competidores, problemas y Jobs to Be Done

- Uso del MCP Firecrawl para realizar un análisis competitivo simple y extraer oportunidades de mejora de nuestro producto.
- Formular enunciados de problema y Jobs to Be Done (JTBD) con ayuda de skills
- Elegir el JTBD que guiará el recorrido principal.

**Resultado de la sesión:** contexto estratégico consultable por el agente, con competidores, problemas y un JTBD prioritario.

## 2º Bloque: Arquitectura (3 clases)

### 3ª sesión: Creación del sistema de diseño I: Estilos y variables

**Previo a la sesión:** El alumno tendrá que traer una recopilación de capturas de interfaces que sirvan de referencia brand

- Explorar referencias visuales con Mobbin o Refero mediante MCP y seleccionar criterios de interfaz aplicables al producto.
- Definir en Figma los estilos y variables básicos de color, tipografía y espaciado a partir de esos criterios.
- Probar las variables en una muestra de interfaz y revisar su coherencia y nomenclatura.

**Resultado de la sesión:** base visual en Figma con estilos y variables listos para aplicar a los componentes.

### 4ª sesión: Creación del sistema de diseño II: Componentes y patrones de interfaz

**Previo a la sesión:** El alumno tendrá que traer una recopilación de capturas de interfaces que sirvan de referencia arquitectura visual

- Conectar el agente al archivo mediante Figma MCP y elegir en shadcn/ui los componentes comunes que requiere el recorrido.
- Aplicar los estilos y variables de la sesión anterior a los componentes en Figma y componer un patrón de interfaz para el flujo principal.
- Documentar el uso de los componentes y comprobar que el agente puede localizar el patrón e interpretar sus reglas.

**Resultado de la sesión:** sistema de diseño básico y documentado, con componentes y un patrón reutilizable por el equipo y los agentes.

### 5ª sesión: Entidades de producto

- Revisar el JTBD y el recorrido principal para identificar la información que necesita el producto.
- Identificar las entidades y diseñarlas mediante skills para posteriormente editarlas a mano.
- Comprobar que cumplen con las necesidades del JTDB

**Resultado de la sesión:** primeros elementos visuales complejos del producto que servirán como contexto para que el agente aprenda los patrones de diseño que deberá seguir.

## 3er Bloque: Formalización (3 clases)

### 6ª sesión: Diseñar en Figma I: Composición del recorrido principal

- Revisar el recorrido, los patrones y el modelo de datos. Si se necesita explorar una solución visual, utilizar Mobbin, Refero o Google Stitch para contrastar propuestas.
- Componer las pantallas principales en Figma con ayuda de Figma AI y Figma MCP, aplicando el sistema de diseño e incorporando contenidos y campos del modelo de datos.
- Conectar las pantallas en un prototipo y recorrer el flujo para revisar su continuidad.

**Resultado de la sesión:** prototipo en Figma con las pantallas del recorrido principal enlazadas.

### 7ª sesión: Diseñar en Figma II: Estados y recuperación

- Identificar dónde se necesitan estados de carga, vacío, validación, error y recuperación.
- Diseñar en Figma los estados pertinentes con los componentes y patrones del sistema. Definir cómo continúa el usuario después de un error.
- Recorrer el prototipo con los datos de ejemplo y revisar que los mensajes, las acciones y las transiciones se entiendan.

**Resultado de la sesión:** recorrido principal en Figma con los estados necesarios para llevarlo a código.

### 8ª sesión: Diseñar en Figma III: Preparar el prototipo para la implementación

- Revisar cómo se adapta el diseño a distintos anchos de pantalla.
- Comprobar el contraste, las zonas táctiles y el foco de teclado.
- Recorrer el prototipo y comprobar que las pantallas y los estados estén bien enlazados.
- Añadir notas de implementación en Figma sobre cómo se adapta el diseño y cómo funcionan las interacciones.

**Resultado de la sesión:** prototipo revisado y anotado para su implementación.

## 4º Bloque: Implementación (2 clases)

### 9ª sesión: Conectar con el código I:  Publicar entidades y componentes en Storybook

- Usar **Figma MCP** para implementar los componentes en y entidades en Storybook
- Probar el comportamiento de las entidades en Storybook.
- Ajustar lo que haga falta, volver a probarlo y guardar los cambios con **Git** y **GitHub**.

**Resultado de la sesión:** Componentes probados con datos de ejemplo y listos para usarse en las pantallas.

### 10ª sesión: Conectar con el código II: Implementar recorrido

- Utilizar los diseños de Figma y las notas de implementación para pasar a código las pantallas.
- Crear datos de ejemplo o reales, mediante una API o una hoja de cálculo. Se podrá usar Supabase si se require de una base de datos
- Publicar en **Vercel** o **GitHub Pages**

**Resultado de la sesión:** El recorrido principal de nuestro producto funcional, publicado y accesible por cualquiera.
