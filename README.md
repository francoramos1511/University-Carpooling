# Informe Académico - Mini proyecto ISA1

Este informe presenta los resultados finales del desarrollo de la aplicación de carpooling universitario solicitada por el cliente. A través de este proyecto, se adoptaron prácticas de ingeniería de software ágil que optimizaron la entrega de valor y permitieron adaptarse a las necesidades cambiantes del cliente.

# Índice

- [Integrantes del equipo](#integrantes-del-equipo)
  - [Roles y responsabilidades](#roles-y-responsabilidades)
- [Objetivo del proyecto](#objetivo-del-proyecto)
- [Metodología de desarrollo](#metodología-de-desarrollo)
  - [Marco de Trabajo](#marco-de-trabajo)
  - [Artefactos de Gestión](#artefactos-de-gestión)
  - [Técnicas utilizadas](#técnicas-utilizadas)
- [Iteraciones y esfuerzo](#iteraciones-y-esfuerzo)
- [Resultados de cada iteración](#resultados-de-cada-iteración)
  - [Iteración 1](#iteración-1)
  - [Iteración 2](#iteración-2)
  - [Iteración 3](#iteración-3)
  - [Iteración 4](#iteración-4)
- [Tiempo dedicado en el proyecto ](#tiempo-dedicado-en-el-proyecto)
- [Resultados y reflexiones del proyecto](#resultados-y-reflexiones-del-proyecto)
  - [Prototipos](#prototipos)
  - [Video Demo](#video-demo)
  - [Principales Aprendizajes](#principales-aprendizajes)
  - [Reflexión Grupal](#reflexión-grupal)
  - [Reflexión Individual](#reflexión-individual)

## Integrantes del equipo

- Agustín Peraza - 313678
- Santiago Meizoso - 273286
- Franco Ramos - 230508

### Roles y responsabilidades

**Product Owner:** Franco Ramos  
**Scrum Master:** Agustín Peraza  
**Developer:** Santiago Meizoso 

Todos los integrantes del equipo actuamos como Development Team, participando activamente en el desarrollo de los prototipos y la documentación del proyecto. Con el fin de repartirnos el trabajo entre todos y no sobrecargar un rol en específico.

## Objetivo del proyecto

El objetivo de este proyecto fue aprender prácticas de gestión ágil mediante su aplicación en el prototipado de un MVP (Minimum Viable Product) de una aplicación de carpooling universitario. El proyecto nos permitió experimentar con el marco SCRUM en un contexto real, enfrentando desafíos de priorización, gestión del tiempo y validación con usuarios.

## Metodología de desarrollo

Para el desarrollo del proyecto utilizamos el marco de trabajo **SCRUM** para organizar al equipo, priorizar tareas y maximizar el valor entregado en cada iteración. 

### Marco de trabajo

El marco de trabajo utilizado fue **SCRUM**, utilizando sus ceremonias para organizarnos y mejorar en cada iteración. Estos son:

#### Sprint Planning
Realizamos al inicio de cada iteración para:
- Definir el objetivo del sprint
- Seleccionar historias de usuario del Product Backlog
- Estimar esfuerzo usando Planning Poker
- Crear el Sprint Backlog con tareas específicas
- Duración: 30 - 45 minutos.

#### Daily Scrum
Reuniones breves (15 min) realizadas principalmente por Discord/WhatsApp donde cada integrante respondía:
- ¿Qué hice desde la última daily?
- ¿Qué haré hoy?
- ¿Tengo algún impedimento?

Frecuencia: 2-3 veces por semana (adaptado a disponibilidad)

#### Sprint Review
Al final de las iteraciones 2 y 3 presentamos los prototipos desarrollados a:
- Compañeros de clase (usuarios potenciales)
- Sponsors del proyecto (iteración 3)
Con el fin de conseguir feedback para poder ajustar la planificaion y los prototipos en una etapa temprana en caso de ser necesario.

#### Sprint Retrospective
Al final de cada sprint analizamos:
- ¿Qué salió bien?
- ¿Qué no salió bien?
- ¿Qué acciones de mejora implementaremos?

### Artefactos de Gestión

####  Backlog del Producto
Se organizó y priorizó siempre en función del valor que aportaba a los usuarios, enfocándonos en las funcionalidades más importantes primero.

#### Increment
Al final de cada sprint generamos un entregable en forma de:
- Prototipos validados en Figma
- Documentación actualizada en este repositorio.

#### Definition of Done

Se considera completada una historia de usuario cuando se cumplen los siguientes criterios:
- Se integró la historia al código y pasó las pruebas unitarias. 
- Fue validada por el Product Owner.
- Se encuentra lista para ser desplegada.   

Es importante tener en cuenta que no se trata solo de haber pasado a código las historias listas, sino también validar, probar, documentar y garantizar que aporte valor real al cliente.

#### Definition of Ready

Una historia de usuario se considera lista para su desarrollo cuando:
- Se definió de manera clara y concisa, es decir, todos los miembros del equipo la entienden.
- Se definió el criterio de aceptación. (Enunciado que define las condiciones para que sea considerada completa)
- Debe aportar valor para el cliente, que sea relevante.
- Debe poder completarse de forma independiente a las demas historias de usuario.
- Debe ser realizable durante una iteracion. De no serlo debe ser dividida.
- Debe estar priorizada.

### Técnicas Utilizadas

#### Estimation Poker
Se hicieron estimaciones colaborativas, alineando al equipo y logrando acuerdos rápidos sobre el esfuerzo requerido en cada tarea.

#### Validación con Usuarios
Integrando el feedback directo en las mejoras iterativas para alcanzar las expectativas de los usuarios.

## Iteraciones y esfuerzo

La ejecución del proyecto consistió en 4 iteraciones de dos semanas de duración cada una, con un esfuerzo esperado de **5 horas-persona/semana**.

**Total de horas planificadas:** 4 sprints × 2 semanas × 3 personas × 5 horas = 120 horas

Las siguientes carpetas contienen la entrega de cada iteración:

- [Iteración 1](./iteración-1/README.md) - Identificación y definición del problema
- [Iteración 2](./iteración-2/README.md) - Primeros prototipos y validación inicial
- [Iteración 3](./iteración-3/README.md) - Refinamiento y validación con sponsors
- [Iteración 4](./iteración-4/README.md) - Cierre y documentación final

## Resultados de cada iteración

### Iteración 1

**Duración:** 22/9 - 11/10

Antes de comenzar a trabajar, definimos el rol de cada integrante del equipo para asegurar una buena organización y coordinación del proyecto.

En la primera iteración nos enfocamos en varios objetivos clave:

- Crear y priorizar de las historias de usuario del product backlog, estimando tanto su complejidad como su valor para el proyecto. [Backlog](./iteración-1/productBacklog/userstory.png)

- Analizar los competidores, lo que nos permitió identificar buenas prácticas del mercado y detectar oportunidades de diferenciación para nuestra solución. [Estudio de Competidores](./iteración-1/competidores.md)

- Identificar posibles interesados (stakeholders) vinculados al proyecto. [Interesados](./iteración-1/interesados.md)

- Definir inicialmente posibles requerimientos funcionales y no funcionales, estableciendo las bases para el alcance y la funcionalidad del sistema. [Funcionalidades](./iteración-1/funcionalidades.md)

### Iteración 2

**Duración:** 13/10 - 25/10

En la segunda iteración, nos enfocamos principalmente en implementar los primeros prototipos de la app e intentar validarlos inicialmente con algunos usuarios. Las actividades que realizamos incluyeron:

**Desarrollo de prototipos**: Creamos las pantallas básicas que representan las funcionalidades principales del sistema. [Prototipos](./iteración-2/figma)

**Pruebas de usabilidad**: Hicimos pruebas con usuarios para obtener feedback temprano y evaluar la experiencia de uso. [Validación con usuarios](./iteración-2/README.md#validacion-con-usuarios)

**Ajustes basados en el feedback**: Realizamos las modificaciones sobre los prototipos en función de las observaciones y comentarios recibidos.

### Iteración 3

**Duración:** 27/10 - 8/11

En la tercera iteración, avanzamos con la implementación y el refinamiento de los prototipos, incorporando las funcionalidades adicionales sugeridas durante la reunión con los sponsors, optimizando la experiencia del usuario. Las actividades principales incluyeron:

**Finalización del MVP**: Integramos las nuevas funcionalidades definidas en conjunto con los sponsors y concretamos las características esenciales para que el producto cumpliera con los requisitos mínimos establecidos. [Prototipos](./iteración-3/figma)

**Validación final con usuarios**: Realizamos pruebas de usabilidad adicionales para evaluar las mejoras implementadas, detectando posibles ajustes y asegurando que la experiencia final resultara fluida e intuitiva. [Validación con usuarios](./iteración-3/README.md#inspección-y-adaptación-del-producto)

### Iteración 4

**Duración:** 10/11 - 22/11

En la última iteración, como finalizamos el MVP del sistema de carpooling universitario, nos enfocamos en redactar el informe final para la entrega del proyecto.

## Tiempo dedicado en el proyecto 

Para saber cuanto tiempo le dedicamos a cada parte del proyecto utilizamos **Toggl Track**. Es una herramienta muy fácil de usar que nos permitió registrar las horas invertidas en cada tarea, hacer un buen seguimiento del trabajo y finalmente visualizar gráficos con nuestros resultados.

**Total de horas trabajadas:** 

**Distribución por persona:**
- Agustín: [X] horas
- Santiago: [Y] horas
- Franco: [Z] horas

**Imágenes de toggl finales**
- [Agustín](imagenes/toggle/toggleAgustin.png)
- [Santiago](imagenes/toggle/toggleSantiago.png)
- [Franco](imagenes/toggle/toggleFranco.png)

### Conclusiones

-  La actividad que más tiempo consumió fue el prototipado.
- La iteración con mayor carga de trabajo fue la 2.
- El tiempo real invertido fue menor a lo planificado

## Resultados y reflexiones del proyecto

### Prototipos

El uso de **Figma** nos permitió crear prototipos interactivos que facilitaron la validación rápida de ideas y el ajuste continuo en base al feedback de los stakeholders.

[Enlace a los prototipos en Figma](https://www.figma.com/design/OGWqjIFF6Q7cqERJLukGV0/Prototipos?node-id=0-1&m=dev&t=z13POlvW3Ch6GRjO-1)

### Video Demo

_[Debe existir un video (de 6 minutos máximo) demostrando el flujo principal de los prototipos, explicando el problema que se quiere resolver y el valor entregado por el producto ideado. El video deberá ser publicado y enlazado en el informe académico para su correcta visualización.]_

A continuación, un video demostrativo que presenta el flujo principal del prototipo, explicando el problema que se busca resolver y el valor entregado por el MVP al cliente.

[![Video de Demostración](video-thumbnail.png)](**Agregar link al video**)

### Principales Aprendizajes

- **Importancia del Feedback**: Involucrar a los usuarios permitió asegurar que el producto respondiera realmente a sus necesidades y expectativas.
- **Iteración Continua en Scrum**: Gracias al enfoque iterativo de Scrum, pudimos ajustar el rumbo en cada sprint, aprendiendo de los resultados y mejorando el producto de forma constante.
- **Prototipado**: El uso de herramientas como Figma facilitó la creación y mejora continua de prototipos de manera rápida y visual.
- **Gestión del Backlog**: Se priorizaron historias de alto valor, lo que permitió enfocar el esfuerzo del equipo en entregas que generaran impacto para el cliente.
- **Roles**: La definición clara de las responsabilidades favoreció la comunicación fluida y una mayor eficiencia del trabajo del equipo.
- **Toggl**: Herramienta práctica y fácil de usar para registrar y visualizar las horas trabajadas por cada integrante del equipo, ayudando a mejorar la organización y el seguimiento del tiempo.

### Reflexión Grupal
Se logró el objetivo de realizar un MVP trabajando con sobre el marco ágil de trabajo SCRUM. Respetamos en su mayoría las ceremonias y los tiempos de entrega. Hubo buena comunicación y disposición por parte de todos los integrantes del equipo. 

### Reflexión Individual

#### Franco Ramos

Me quedo muy conforme con resultado final del proyecto. Nos logramos organizar de buena manera y no tuvimos mayores problemas. Se trabajo tanto individual como grupalmente y se lograron hacer todas las cosas propuestas en tiempo y forma. 

Como persona soy muy organizada en trabajos grupales, me gusta liderar y mantener el orden de las cosas, por lo tanto, creo haber sido un buen Product Owner.

Logre entender la metodología SCRUM y aprendi muchas herramientas para aplicar a nivel laboral a futuro.

#### Agustín Peraza
Me gustó cómo pudimos organizarnos y trabajar en equipo para llegar a un resultado con el que estemos todos conformes. 

Como Scrum Master, lo más valioso fue comprender la importancia del rol de facilitador. En mi experiencia laboral he trabajado con Scrum Masters, pero nunca había estado en esa posición. Traté de facilitar la generación de las user stories para que fueran claras y todos pudiéramos trabajar en conjunto.

Hay lugar a mejora en cuanto a la aplicación de Scrum, ya que deberíamos haber hecho más dailies formales, especialmente en las iteraciones 2 y 3 donde generalmente nos arreglábamos por mensaje. Por otro lado, las retrospectivas generaron cambios concretos y valiosos.

En términos generales, estoy conforme con el resultado y considero que las herramientas utilizadas son útiles para nuestro desarrollo profesional.

#### Santiago Meizoso

Aprendi las herramientas del curso y pude ponerlas en practica, valoro el trabajo del grupo que siempre estuvo dispuesto a reunirse y trabajar durante el transcurso del obligatorio.  
Si bien la aplicacion de Scrum pudo ser mejor, creo que cumplimos satisfactoriamente con lo pedido en el obligatorio y personalmente me sirvió para entender como se trabaja con esa metodología.  
No conocia Figma, con los prototipos fui entendiendolo cada vez más y seguramente lo use a futuro para realizar demos rapidamente. 
Por todo lo anteriormente mencionado concluyo que este trabajo me sirvió para aprender herramientas sumamente utiles para mi carrera.  