# university-academic-tracker

Repositorio base de documentación para el proyecto de **Sistemas Distribuidos**.
Este espacio centraliza la visión general del sistema, su arquitectura distribuida, la organización de la documentación y los enlaces a los repositorios de código.

> Importante: este repositorio **no contiene implementación**, solo documentación, diagramas y referencias para guiar el desarrollo.

---

## Objetivo del proyecto

Desarrollar una plataforma académica que permita a estudiantes universitarios gestionar sus calificaciones, porcentajes por corte, metas académicas y actividades de cada asignatura.
El sistema busca ofrecer **organización, alertas preventivas y reportes automáticos**, contribuyendo a un mayor control del rendimiento académico en tiempo real.

---

## Arquitectura distribuida

La solución seguirá un modelo basado en **microservicios**, lo que permitirá escalabilidad, modularidad y un mantenimiento más sencillo.

**Componentes principales:**

* **Eureka Server**: registro y descubrimiento de microservicios.
* **API Gateway**: enrutamiento centralizado, seguridad y políticas.
* **Auth Service**: autenticación y autorización (JWT/OAuth2).
* **Student Service**: gestión de estudiantes, materias y calificaciones.
* **University Service**: administración de universidades, programas y periodos.
* **Teacher Service**: gestión de docentes y asignaturas.
* **Notification Service** (opcional): envío de recordatorios y alertas (correo/push).
* **Report Service** (opcional): generación de reportes PDF/Excel.
* **Config Server** (opcional recomendado): configuración centralizada.
* **Frontend Web**: un único repositorio para la interfaz gráfica (sin microfrontends).

---

## Estructura de este repositorio

```plaintext
/
├─ docs/                     → Documentación técnica
│  ├─ vision.md              → Visión general y alcance
│  ├─ architecture.md        → Detalle de la arquitectura
│  ├─ diagrams/              → Diagramas del sistema
│  ├─ epics/                 → Épicas por corte
│  ├─ user-stories/          → Historias de usuario (HU-#)
│  └─ references.md          → Bibliografía y referencias
│
├─ repos/                    → Referencias a repositorios de código
├─ reports/                  → Entregables por corte
│
├─ README.md                 → Documentación principal (este archivo)
├─ LICENSE                   → Licencia del proyecto
```

**Convención de Historias de Usuario (HU-#):**

* Corte 1 → HU-001 en adelante
* Corte 2 → HU-101 en adelante
* Corte 3 → HU-201 en adelante

---

## Gestión del backlog

El seguimiento de épicas e historias de usuario se realizará en **Jira**, mediante un tablero de tipo *Scrum*.
Este tablero permitirá:

* Organizar el backlog en épicas e historias de usuario.
* Dar seguimiento a las tareas de cada corte.
* Visualizar el estado (pendiente, en progreso, terminado).
* Priorizar de acuerdo con las necesidades del proyecto.

Cada historia de usuario documentada en este repositorio (`docs/user-stories/`) tendrá su respectivo **ID HU-#** y estará enlazada con su issue en Jira.

**Enlace al tablero de Jira:** https://juanferperez0421.atlassian.net/jira/software/projects/SCRUM/boards/1?atlOrigin=eyJpIjoiNTJhZjdiZDQwMzAwNDVlN2I1MThiNmU3MzNjYjYzMjIiLCJwIjoiaiJ9

---

## Repositorios relacionados

* **Eureka Server**: enlace
* **API Gateway**: enlace
* **Auth Service**: enlace
* **Student Service**: enlace
* **University Service**: enlace
* **Teacher Service**: enlace
* **Notification Service** (opcional): enlace
* **Report Service** (opcional): enlace
* **Frontend Web**: enlace

---

## Participantes

* **Camilo Andrés Chavarro Guenis**
* **Huber Andrés Parra Molina**
* **Juan Fernando Pérez Olaya**

**Universidad Corhuila – 2025-B**
