# Alcance del Proyecto – University Academic Tracker

## Objetivo General
Diseñar e implementar una plataforma académica distribuida que permita a los estudiantes universitarios gestionar calificaciones, porcentajes por corte y metas académicas de manera sencilla.  
Adicionalmente, y de forma **opcional** (dependiendo del tiempo disponible durante el semestre), se podrán incluir funcionalidades complementarias como reportes básicos en PDF y alertas de actividades.

---

## Alcance Funcional
El sistema se centrará en un conjunto reducido y alcanzable de funcionalidades principales:

1. **Gestión de calificaciones**
   - Registro de materias.
   - Registro de notas por actividad dentro de cada materia.
   - Configuración dinámica de porcentajes de corte (adaptable a distintas universidades).
   - Cálculo automático de la nota necesaria para alcanzar una meta en cada corte.
   - Promedio final por materia y promedio general del semestre.

2. **Organización académica (básico)**
   - Registro de actividades por materia (exámenes, entregas).
   - Visualización organizada por cortes.

3. **Autenticación y administración**
   - Registro y autenticación de usuarios mediante credenciales seguras.
   - Roles básicos: estudiante y docente.  
   *(La administración avanzada de instituciones y universidades se documentará, pero puede no quedar implementada en su totalidad dentro del semestre).*

4. **Funcionalidades opcionales (dependiendo del tiempo disponible)**
   - **Reportes en PDF** con calificaciones y promedios.  
   - **Alertas o recordatorios** antes de actividades relevantes.

---

## Alcance No Funcional
Se contemplarán únicamente los aspectos mínimos no funcionales necesarios para cumplir con el semestre:

- **Disponibilidad:** acceso mediante navegador web (la aplicación móvil se dejará como una propuesta futura, no implementada).  
- **Escalabilidad:** el diseño contemplará microservicios, pero solo se implementarán los servicios principales listados en los entregables.  
- **Seguridad:** autenticación básica mediante JWT. No se cubrirán autorizaciones avanzadas ni federación de identidades.  
- **Usabilidad:** interfaz sencilla que permita registrar y consultar información sin complejidad. No se implementarán diseños avanzados ni personalización por usuario.  
- **Portabilidad:** el sistema será accesible desde navegador en escritorio; soporte móvil será limitado al acceso vía navegador, no como app nativa.

---

## Exclusiones
Para acotar el proyecto al tiempo disponible (12 semanas), se deja constancia de que **no se desarrollarán** las siguientes características:

- Integración con plataformas externas (ej. Moodle, Blackboard, Google Classroom).  
- Soporte multilenguaje (solo disponible en español).  
- Funcionalidades de analítica avanzada o predicción de rendimiento académico.  
- Aplicación móvil nativa (iOS).  
- Panel de administración completo para instituciones y universidades (solo se documentará su diseño).  
- Gestión avanzada de docentes (informes, horarios, carga académica).  
- Gestión avanzada de notificaciones (push en dispositivos móviles, integraciones con correo masivo).  
- Reportes gráficos avanzados o dashboards interactivos.  
- Escenarios de alta concurrencia o despliegue en producción a gran escala (se trabajará en un entorno académico controlado).  

---

## Entregables
- Documentación de arquitectura distribuida y diagramas de diseño.  
- Épicas e historias de usuario clasificadas por cortes académicos.  
- Implementación de los microservicios principales:  
  - Auth  
  - Student  
  - University  
  - Teacher  
  - Gateway  
  - Eureka  
  - Frontend Web  
- Documentación final consolidada.  
- Funcionalidades opcionales (si el tiempo lo permite): reportes básicos en PDF y alertas simples.  

---

## Usuarios objetivo
- **Estudiantes universitarios** que deseen organizar y controlar su rendimiento académico.  
- **Docentes** interesados en gestionar materias y actividades de forma sencilla.  
- **Instituciones educativas** como potenciales usuarios futuros, considerando este proyecto como una base de investigación académica.