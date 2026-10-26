# Diario de Trabajo Individual
**Maryna Prykhodko**  
*2DAMB*

---

## Índice de Meses
* [Octubre 2026](#octubre-2026)
* [Noviembre 2026](#noviembre-2026)

---

## Octubre 2026

| Fecha | Sesión | Tareas Realizadas | Tiempo | Problemas Encontrados | Soluciones Aplicadas | Reflexión/Aprendizaje |
| :---: | :---: | :--- | :---: | :--- | :--- | :--- |
| 15/10 | S1 | Clonación del repositorio base, configuración inicial del entorno de desarrollo C# y análisis de requisitos. | 1.5 h | No se encontraba el repositorio inicial por falta de permisos en la organización. | El gestor del equipo otorgó acceso de colaborador y se configuraron credenciales. | Importancia de comprobar los accesos antes de arrancar el sprint para no demorar el inicio. |
| 20/10 | S2 | T2: Implementación del menú de consola interactivo y flujo de añadir tarea (`TaskItem`). | 2.5 h | Incompatibilidad de tipos al usar expresión `switch` para métodos `void` y errores con `int.Parse`. | Sustitución por `switch` tradicional con sentencias `case` y lectura segura mediante `int.TryParse`. | Es fundamental separar la lectura y validación de consola de la lógica de negocio. |
| 23/10 | S3 | T3 y T5: Soporte en la lógica de listar tareas y marcar tareas como completadas. | 2.0 h | Pérdida de estado en memoria por instanciar la lista dentro del método en lugar de a nivel de clase. | Refactorización de la colección `ListaTareas` como variable estática de clase. | Prestar atención al alcance (*scope*) y ciclo de vida de los datos en memoria. |
| 25/10 | S4 | Integración en Git, subida de rama remota, resolución de conflictos y apertura de Pull Request. | 3.0 h | Error `fatal: not a git repository`, ausencia de `.gitignore` en `main` que subió `bin/obj` y conflictos al fusionar. | Creación y posicionamiento en la ruta correcta, preparación del `.gitignore` y resolución manual de conflictos en VS Code antes del merge. | La integración continua y el `.gitignore` son críticos; resolver problemas de Git llevó más tiempo que programar en C#. |

<br>

### Resumen del mes (parcial):
* **Total de horas:** 9 h
* **Principales logros:**
  * Implementación completa del menú por consola y el registro de nuevas tareas en C#.
  * Superación de incidencias de Git, subida exitosa de rama y apertura de Pull Request revisada.
* **Área de mejora:** Dominio avanzado de Git/GitHub (manejo preventivo de ramas, comandos locales y `.gitignore`).
* **Próximos objetivos:** Modularizar la aplicación separando servicios de presentación y preparar la persistencia JSON/SQL.

[Volver al índice](#índice-de-meses)

---

## Noviembre 2026

| Fecha | Sesión | Tareas Realizadas | Tiempo | Problemas Encontrados | Soluciones Aplicadas | Reflexión/Aprendizaje |
| :---: | :---: | :--- | :---: | :--- | :--- | :--- |
| *Pendiente* | S5 | Próximas tareas del Sprint 2 | - | - | - | - |

<br>

### Resumen del mes:
* **Total de horas:** *Pendiente*
* **Principales logros:** *Pendiente*
* **Área de mejora:** *Pendiente*
* **Próximos objetivos:** *Pendiente*

[Volver al índice](#índice-de-meses)