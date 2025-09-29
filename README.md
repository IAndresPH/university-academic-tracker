# university-academic-tracker

Repositorio base de documentación para el proyecto de **Sistemas Distribuidos**.
Este espacio centraliza la **visión general del sistema**, su **arquitectura distribuida**, la **organización de la documentación** y los **enlaces a los repositorios de código**.

> Importante: este repositorio **no contiene implementación**, solo documentación, diagramas y referencias para guiar el desarrollo.

---

## Objetivo del proyecto

Desarrollar una plataforma académica que permita a estudiantes universitarios gestionar sus calificaciones, porcentajes por corte, metas académicas y actividades de cada asignatura.

El sistema busca ofrecer:

* Organización de la información académica.
* Alertas preventivas.
* Reportes automáticos.
* Control del rendimiento académico en tiempo real.

---

## Arquitectura distribuida

La solución seguirá un modelo basado en **microservicios**, lo que permitirá:

* Escalabilidad.
* Modularidad.
* Mantenimiento sencillo.

Los diagramas de arquitectura se encuentran en la carpeta [`docs/diagrams/`](./docs/diagrams/).

---

## Estructura de este repositorio

```plaintext
/
├─ docs/                     → Documentación técnica
│  ├─ vision.md              → Visión general y alcance
│  ├─ architecture.md        → Detalle de la arquitectura
│  ├─ user-stories.md        → Historias de usuario (HU-#)
│  ├─ diagrams/              → Diagramas del sistema
│
├─ repos/                    → Referencias a repositorios de código
├─ reports/                  → Entregables por corte (corte1/, corte2/, corte3/)
│
├─ README.md                 → Documentación principal (este archivo)
├─ LICENSE                   → Licencia del proyecto
```

---

## Metodología de trabajo

El proyecto se desarrolla bajo la metodología **Scrum**, organizada en **épicas** y **sprints semanales**.
Cada sprint dura **una semana**, lo que permite entregas incrementales y continuas.

* Las **épicas** definen los objetivos principales de cada corte académico.
* No siempre hay una correspondencia exacta de **una épica por corte**: pueden existir **épicas adicionales** o de **corrección** según las necesidades del proyecto.
* Las **historias de usuario (HU)** dividen esas épicas en funcionalidades más pequeñas y manejables.
* Cada HU se documenta en este repositorio y se gestiona en **Jira**, asegurando trazabilidad entre planificación y documentación.

---

## Convención de Historias de Usuario (HU-#)

* Épica 1 (Definición y preparación del proyecto) → HU-0## y HU-C01
* Épica 2 (Base del Sistema) → HU-1##
* Épica 3 (Gestión de Entidades) → HU-2##
* Épica 4 (Análisis y Estadísticas) → HU-3##
* Épica 5 (Carga de Archivos) → HU-4##
* Épica 6 (Módulo AuthService) → HU-5##
* Épica 7 (Módulo API Gateway) → HU-6##
* Épica 8 (Módulo Eureka) → HU-7##

Cada HU tendrá:

* ID.
* Descripción.
* Criterios de aceptación.
* Enlace a su issue en Jira.

---

## Gestión del backlog

El seguimiento de épicas e historias de usuario se realiza en **Jira**, mediante un tablero Scrum.

El tablero permite:

* Organizar épicas e historias de usuario.
* Dar seguimiento a cada sprint semanal.
* Visualizar estado (pendiente, en progreso, terminado).
* Priorizar de acuerdo con necesidades.

**Enlace al tablero de Jira:**
[Tablero Scrum – Jira](https://juanferperez0421.atlassian.net/jira/software/projects/SCRUM/boards/1?atlOrigin=eyJpIjoiNTJhZjdiZDQwMzAwNDVlN2I1MThiNmU3MzNjYjYzMjIiLCJwIjoiaiJ9)

---

## Repositorios relacionados

| Microservicio            | Repositorio                                                                        | Estado     | Descripción                                           |
| ------------------------ | ---------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------- |
| **Eureka Server**        | enlace                                                                             | Pendiente  | Registro y descubrimiento de microservicios           |
| **API Gateway**          | enlace                                                                             | Pendiente  | Enrutamiento centralizado, seguridad y políticas      |
| **Auth Service**         | enlace                                                                             | Pendiente  | Autenticación y autorización con JWT/OAuth2           |
| **Student Service**      | [student-service](https://github.com/IAndresPH/student-service.git)                | En proceso | Gestión de estudiantes, materias y calificaciones     |
| **University Service**   | [university-service](https://github.com/JuanPerez012/university-service.git)       | En proceso | Administración de universidades, programas y periodos |
| **Teacher Service**      | [teacher-service](https://github.com/JuanPerez012/teacher-service.git)             | En proceso | Gestión de docentes y asignaturas                     |
| **Notification Service** | enlace                                                                             | Pendiente  | Envío de recordatorios y alertas (correo/push)        |
| **Report Service**       | enlace                                                                             | Pendiente  | Generación de reportes PDF/Excel                      |
| **Config Server**        | enlace                                                                             | Pendiente  | Configuración centralizada                            |
| **Frontend Web**         | [university-academic-frontend](https://github.com/IAndresPH/university-academic-frontend.git)| En proceso  | Interfaz gráfica del sistema                          |
