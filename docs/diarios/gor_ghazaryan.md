# Diario de Trabajo Individual
**Gor Ghazaryan**  
*2DAMB* · Rol H.A.D.A.: **Analista**

---

## Índice de Meses
* [Septiembre 2026](#septiembre-2026)
* [Octubre 2026](#octubre-2026)
* [Noviembre 2026](#noviembre-2026)
* [Leyenda](#leyenda)

---

## Septiembre 2026

| Fecha | Sesión | Tareas Realizadas | Tiempo | Problemas Encontrados | Soluciones Aplicadas | Reflexión/Aprendizaje |
| :---: | :---: | :--- | :---: | :--- | :--- | :--- |
| 17/09 | :books: S1 | Test de roles H.A.D.A. para formar los equipos. | 25 min | - | - | Me tocó el rol de **Analista**: revisar y corregir más que construir. |
| 24/09 | :books: S2 | *Iniciándose con Git*: comandos básicos (`init`, `add`, `commit`, `status`, `log`). | 3 h | Muchos comandos nuevos de golpe. | Practicar cada comando en repositorios de prueba. | La base de todo lo demás; hay que tenerla clara. |
| 29/09 | :dart: S3 | *Git con GitHub*: clonar `proyecto-colaborativo`, crear `marco.md` en mi rama, fusionar con `main` y añadir la línea sobre Pull Requests. | 2 h | Primer contacto con ramas y merges de otros compañeros. | Hacer `pull` antes de fusionar mi rama. | Trabajar varios en el mismo repositorio obliga a actualizar siempre antes de subir. |

<br>

### Resumen del mes:
* **Total de horas:** 5 h 25 min
* **Principales logros:** Primeros commits y primera fusión de rama en el repositorio del equipo.
* **Área de mejora:** Soltura con los comandos de Git sin tener que consultarlos.
* **Próximos objetivos:** Trabajar con ramas y Pull Requests desde VS Code.

[Volver al índice](#índice-de-meses)

---

## Octubre 2026

| Fecha | Sesión | Tareas Realizadas | Tiempo | Problemas Encontrados | Soluciones Aplicadas | Reflexión/Aprendizaje |
| :---: | :---: | :--- | :---: | :--- | :--- | :--- |
| 08/10 | :books: S4 | *Git, GitHub y VS Code*: trabajo en ramas (`Izan`, `marco`) en `proyecto-colaborativo`, sección de hobbies en `marco.md` y merges. | 3 h | Varios merges entre ramas de compañeros a la vez. | Integrar la rama de `main` en la mía antes de subir. | VS Code agiliza mucho el ciclo `pull` → `commit` → `push`. |
| 13/10 | :dart: S5 | HADA Task Tracker (C#): creación de la clase `TaskItem` y esqueleto de `TaskManager`. Pull Request #2 fusionada en `main`. | 2 h | - | - | Separar las clases permite repartir el trabajo sin pisarse. |
| 22/10 | :warning: S6 | HADA: limpieza del repositorio (borrado de `bin/`, `obj/` y `Program` vacío) y diario de retrospectiva HADA. | 3 h | Se habían subido ficheros compilados por no tener un buen `.gitignore`. | Borrarlos del repositorio y usar el `.gitignore` del equipo. | El `.gitignore` tiene que estar en `main` antes de empezar a programar. |
| 25/10 | :bug: S7 | HADA: corrección de errores, integración de todas las funciones y testeo final. Capturas de funcionamiento para la entrega. | ~2 h | El programa no compilaba al juntar las partes. | Corregir los errores tras la integración y probar todas las opciones del menú. | Las estimaciones fueron cortas; las partes largas mejor entre dos personas. |
| 29/10 | :fire: S8 | **Comunify** – `PROYECTO.md`: apartado **Riesgos y mitigación** (12 riesgos técnicos y de equipo). | 3 h | No tenía claro qué apartado me tocaba. | Revisar el reparto en el chat del grupo y el documento: era el único apartado vacío y encaja con el rol de Analista. Redacción con apoyo de IA. | Apuntar la tarea en cuanto se reparte y no dejarla para el último día. |

<br>

### Resumen del mes:
* **Total de horas:** 13 h
* **Principales logros:**
  * Clase `TaskItem` del HADA Task Tracker integrada en `main` mediante Pull Request.
  * Apartado de riesgos del documento del proyecto Comunify.
* **Área de mejora:** Organización: empezar antes las tareas del grupo y confirmar el reparto.
* **Próximos objetivos:** Aprender Scrum y gestionar las tareas del proyecto con GitHub Projects.

[Volver al índice](#índice-de-meses)

---

## Noviembre 2026

| Fecha | Sesión | Tareas Realizadas | Tiempo | Problemas Encontrados | Soluciones Aplicadas | Reflexión/Aprendizaje |
| :---: | :---: | :--- | :---: | :--- | :--- | :--- |
| 05/11 | :books: S9 | Tutorial de Scrum y test de Scrum. | ~1 h | Muchos términos nuevos (Product Backlog, DoD, Velocity…). | Repasar el tutorial antes del test. | Scrum organiza el trabajo en sprints cortos con entregas revisables. |
| Nov. | :dart: S10 | *Hackathon Express de Redes Sociales* (campaña para una protectora con Scrum): títulos de Adoptar perro, Colaborador y Veterinario, y anuncio completo de Voluntariado. | ~2 h | Mantener el mismo estilo que los anuncios ya hechos por el equipo. | Usar las imágenes del equipo como referencia de formato y paleta. | Un buen gancho y una llamada a la acción clara pesan más que el texto largo. |
| Nov. | :dart: S11 | Actividad Scrum en clase con folio y pósits (backlog, sprints e incrementos). | ~2 h | - | - | Ver el tablero en físico ayuda a entender cómo se mueven las tareas. |
| 10/11 | :books: S12 | Práctica Scrum con GitHub Projects en mi organización: tipo de issue `User Story` y proyecto *SungJinBot* con la plantilla *Team planning*. | 2 h | Confundía **User Story** con **Task**. | Repasar la teoría: la US es lo que quiere el usuario («Como… quiero… para…»); la Task, el trabajo del equipo. | GitHub Projects permite llevar el tablero de Scrum junto al código. |
| 19/11 | :dart: S13 | **Comunify – Sprint 1 (Prototipado UI/UX)**: tarea 1.3, prompt de la pantalla **Chats** de la app móvil (issue #26). Dos pantallas: lista de los 4 canales fijos (Presidente, Bloque, Comunidad, Avisos) y conversación. | ~1 h | La issue no tenía descripción y no estaba claro qué incluir. | Basarme en el caso de uso *Sistema de Chats* de `PROYECTO.md` y en el boceto del equipo. | Partir del boceto común hace que todas las pantallas encajen. |

<br>

### Resumen del mes (parcial):
* **Total de horas:** ~8 h
* **Principales logros:**
  * Base de Scrum: roles, backlog, User Stories y sprints.
  * Prompt de la pantalla de Chats para el Sprint 1 de Comunify.
* **Área de mejora:** Diferenciar bien User Story y Task al planificar.
* **Próximos objetivos:** Sprint 2: modelo de dominio en C# y mocks.

[Volver al índice](#índice-de-meses)

---

## Leyenda

:fire: Muy productiva · :warning: Bloqueos · :dart: Objetivo concreto · :bug: Debugging · :books: Aprendizaje
