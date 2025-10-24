# Historias de usuario

## ÉPICA 1: Definición y preparación del proyecto

### Sprint 1

* **HU-001**: Como equipo de desarrollo, quiero definir claramente la idea del sistema de notas, para tener un objetivo compartido y alineado con las necesidades del usuario final.
* **HU-002**: Como Product Owner, quiero identificar las épicas e historias de usuario del proyecto, para organizar el backlog y priorizar el trabajo en sprints.

### Sprint 2

* **HU-003**: Como arquitecto del sistema, quiero diseñar la arquitectura de software (frontend, backend y base de datos), para asegurar la escalabilidad y mantenibilidad del sistema.
* **HU-004**: Como arquitecto del sistema, quiero crear los diagramas de casos de uso, de clases, de secuencia y de componentes, para documentar y comunicar el diseño del sistema.
* **HU-005**: Como equipo de desarrollo, quiero crear un repositorio central en GitHub, para versionar el código y facilitar la colaboración.

### Sprint 3

* **HU-006**: Como desarrollador frontend, quiero crear el proyecto base en Vue con Vuetify y configurar buenas prácticas (eslint, prettier, estructura de carpetas), para garantizar escalabilidad y consistencia del código.
* **HU-007**: Como desarrollador backend, quiero configurar el proyecto con Java y Springboot, para implementar la lógica de negocio y las API.
* **HU-008**: Como equipo de desarrollo, quiero definir e implementar la base de datos inicial, para almacenar los datos de las entidades necesarias para el funcionamiento del sistema.

### Sprint 5

* **HU-C01**: Como miembro del equipo de desarrollo, quiero traducir al inglés todos los diagramas creados para el proyecto, para que la documentación sea comprensible para usuarios, evaluadores o colaboradores internacionales.

### Sprint 6

* **HU-009**: Como diseñador UX/UI, quiero elaborar mockups de las pantallas principales del sistema, para visualizar la interfaz antes de implementarla y validar con los usuarios que cumple sus necesidades.

### Sprint 11

* **HU-010**: Como analista de sistemas, quiero crear un diagrama BPMN que represente el flujo de procesos del sistema, para documentar de visualmente las interacciones entre los actores, los módulos y los procesos principales del sistema.

## ÉPICA 2: Base del Sistema

### Sprint 6

* **HU-101**: Como desarrollador frontend, quiero configurar el router y definir rutas privadas y públicas, para asegurar que solo usuarios autenticados accedan a las vistas internas.
* **HU-102**: Como usuario, quiero ver una pantalla de inicio de sesión con campos de usuario y contraseña, validaciones de campos vacíos y botón de recordar sesión, para ingresar al sistema correctamente.
* **HU-103**: Como usuario, quiero recuperar mi contraseña a través de un correo electrónico de restablecimiento, para poder acceder si la olvido.
* **HU-104**: Como usuario, quiero registrarme en el sistema proporcionando mis datos básicos, para crear mi cuenta de acceso.
* **HU-105**: Como usuario, quiero recibir mensajes claros de error (credenciales inválidas, usuario no encontrado, etc.), para comprender la causa del fallo en el login.
* **HU-106**: Como usuario, quiero acceder a un panel principal después de iniciar sesión, con menús visibles según mi rol (estudiante, docente, administrador), para ver solo las funcionalidades disponibles.
* **HU-107**: Como usuario, quiero cerrar sesión desde el panel, para garantizar la seguridad de mi cuenta.

### Sprint 7

* **HU-C02**: Como usuario del sistema, quiero poder navegar entre las diferentes vistas del frontend (login, panel principal, carga de archivos, reportes), para acceder fácilmente a todas las funcionalidades del sistema desde una misma interfaz.

## ÉPICA 3: Gestión de Entidades

### Sprint 5

* **HU-202**: Como desarrollador backend, quiero configurar el backend del módulo Student con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-203**: Como desarrollador backend, quiero desarrollar las funciones de CRUD para el módulo Student, para poder estructurar la información requerida en la base de datos y poder realizar el manejo de datos por parte del módulo.
* **HU-204**: Como equipo de desarrollo, quiero desplegar la versión básica del módulo Student en un entorno local de pruebas con Postman, para verificar el funcionamiento de manejo de datos del módulo.

### Sprint 6

* **HU-205**: Como administrador, quiero registrar estudiantes manualmente usando un formulario validado, para crear nuevos registros.
* **HU-206**: Como administrador, quiero ver una tabla con estudiantes, incluyendo filtros y búsqueda, para consultar rápidamente su información.
* **HU-207**: Como administrador, quiero editar los datos de un estudiante, para mantenerlos actualizados.
* **HU-208**: Como administrador, quiero eliminar un estudiante y confirmar la acción, para evitar borrados accidentales.
* **HU-209**: Como estudiante, quiero acceder a mi perfil y visualizar mis datos personales y académicos, para confirmar que mi información está almacenada correctamente.
* **HU-211**: Como desarrollador backend, quiero configurar el backend del módulo Teacher con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-212**: Como desarrollador backend, quiero desarrollar las funciones de CRUD para el módulo Teacher, para poder estructurar la información requerida en la base de datos y poder realizar el manejo de datos por parte del módulo.
* **HU-213**: Como equipo de desarrollo, quiero desplegar la versión básica del módulo Teacher en un entorno local de pruebas con Postman, para verificar el funcionamiento de manejo de datos del módulo.

### Sprint 7

* **HU-C03**: Como arquitecto de software, quiero conectar los módulos creados con el frontend, para que puedan comunicarse con los demás servicios y funcionen de manera integrada dentro de la arquitectura distribuida.
* **HU-C04:** Como usuario del sistema, quiero visualizar los datos de los estudiantes mediante paginación, para poder navegar fácilmente por grandes volúmenes de datos sin afectar el rendimiento de la interfaz.
* **HU-C05**: Como usuario del sistema, quiero visualizar los datos de los docentes mediante paginación, para poder navegar fácilmente por grandes volúmenes de datos sin afectar el rendimiento de la interfaz.
* **HU-C06**: Como usuario del sistema, quiero visualizar los datos de las universidades mediante paginación, para poder navegar fácilmente por grandes volúmenes de datos sin afectar el rendimiento de la interfaz.
* **HU-C07**: Como arquitecto de software, quiero integrar SonarQube en el módulo Student, para analizar la calidad del código, identificar vulnerabilidades y mantener estándares de desarrollo consistentes en todos los módulos del sistema.
* **HU-C08**: Como arquitecto de software, quiero integrar SonarQube en el módulo Teacher, para analizar la calidad del código, identificar vulnerabilidades y mantener estándares de desarrollo consistentes en todos los módulos del sistema.
* **HU-C09**: Como arquitecto de software, quiero integrar SonarQube en el módulo University, para analizar la calidad del código, identificar vulnerabilidades y mantener estándares de desarrollo consistentes en todos los módulos del sistema.
* **HU-214**: Como administrador, quiero registrar docentes manualmente usando un formulario validado, para crear nuevos registros.
* **HU-215**: Como administrador, quiero ver una tabla con docentes, incluyendo filtros y búsqueda, para consultar rápidamente su información.
* **HU-216**: Como administrador, quiero editar los datos de un docente, para mantenerlos actualizados.
* **HU-217**: Como administrador, quiero eliminar un docente y confirmar la acción, para evitar borrados accidentales.
* **HU-219**: Como desarrollador backend, quiero configurar el backend del módulo University con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-220**: Como desarrollador backend, quiero desarrollar las funciones de CRUD para el módulo University, para poder estructurar la información requerida en la base de datos y poder realizar el manejo de datos por parte del módulo.
* **HU-221**: Como equipo de desarrollo, quiero desplegar la versión básica del módulo University en un entorno local de pruebas con Postman, para verificar el funcionamiento de manejo de datos del módulo.

### Sprint 8

* **HU-C10**: Como desarrollador backend, quiero corregir la clase de prueba para el módulo Student, completando su implementación para asegurar que el archivo tenga una finalidad clara dentro del proyecto.
* **HU-C11**: Como desarrollador backend, quiero corregir la clase de prueba para el módulo Teacher, completando su implementación para asegurar que el archivo tenga una finalidad clara dentro del proyecto.
* **HU-C12**: Como desarrollador backend, quiero corregir la clase de prueba para el módulo University, completando su implementación para asegurar que el archivo tenga una finalidad clara dentro del proyecto.
* **HU-C13**: Como arquitecto de software, quiero aumentar la cobertura de código del módulo Student medida por SonarQube, para garantizar que las pruebas validen la mayor parte del sistema y asegurar la calidad y mantenibilidad del proyecto.
* **HU-C14**: Como arquitecto de software, quiero aumentar la cobertura de código del módulo Teacher medida por SonarQube, para garantizar que las pruebas validen la mayor parte del sistema y asegurar la calidad y mantenibilidad del proyecto.
* **HU-C15**: Como arquitecto de software, quiero aumentar la cobertura de código del módulo University medida por SonarQube, para garantizar que las pruebas validen la mayor parte del sistema y asegurar la calidad y mantenibilidad del proyecto.
* **HU-222**: Como administrador, quiero registrar universidades manualmente con atributos académicos (cortes, notas mínimas, etc.), para que queden parametrizadas.
* **HU-223**: Como administrador, quiero ver una tabla con universidades, incluyendo filtros y búsqueda, para consultar rápidamente su información.
* **HU-224**: Como administrador, quiero editar los datos de una universidad, para mantenerlos actualizados.
* **HU-225**: Como administrador, quiero eliminar una universidad y confirmar la acción, para evitar borrados accidentales.

### Sprint 9

* **HU-226**: Como desarrollador backend, quiero configurar el backend del módulo Eureka con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-227**: Como arquitecto de software, quiero realizar la configuración básica el módulo Eureka, para definir las características del servicio y hacer que los otros servicios se registren en el módulo.
* **HU-228**: Como arquitecto de software, quiero configurar el módulo Eureka con los módulos de gestión de datos, para que pueda comunicarse con los demás servicios y funcione de manera integrada dentro de la arquitectura distribuida.
* **HU-229**: Como desarrollador backend, quiero configurar el backend del módulo Gateway con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-230**: Como arquitecto de software, quiero realizar la configuración básica el módulo Gateway, para definir las características del servicio y hacer que los otros servicios se registren en el módulo.
* **HU-231**: Como desarrollador frontend, quiero conectar el frontend con el módulo Gateway, para que todas las solicitudes del usuario se redirijan correctamente hacia los microservicios a través de un único punto de acceso seguro y controlado.

## ÉPICA 4: Autenticación

### Sprint 9

* **HU-301**: Como desarrollador backend, quiero configurar el backend del módulo Student con Java y Springboot, para poder implementar las funcionalidades específicas para el módulo.
* **HU-302**: Como desarrollador backend, quiero desarrollar las funciones de CRUD para el módulo AuthService, para poder estructurar la información requerida en la base de datos y poder realizar el manejo de datos por parte del módulo.
* **HU-303**: Como desarrollador backend, quiero implementar los métodos específicos del módulo AuthService, para manejar la autenticación y sesión de los usuarios dentro del sistema.

### Sprint 10

* **HU-304**: Como arquitecto de software, quiero configurar la gestión de seguridad en el módulo AuthService mediante SecurityConfig y JWT, para garantizar que solo los usuarios autenticados y autorizados puedan acceder a los recursos del sistema.
* **HU-305**: Como arquitecto del sistema, quiero establecer la configuración con respecto al módulo Gateway para que redirija las peticiones al AuthService y valide los tokens de autenticación, para centralizar el control de acceso en el sistema.
* **HU-306**: Como desarrollador backend, quiero implementar un mecanismo de autorización basado en roles, para controlar el acceso a los recursos según el tipo de usuario dentro del sistema.
* **HU-307**: Como usuario, quiero que la vista de inicio de sesión esté conectada con el AuthService, para poder ingresar correctamente al sistema con mis credenciales y mantener mi sesión activa.
* **HU-308**: Como usuario, quiero que la vista de recuperación de contraseña se conecte con el AuthService, para poder restablecer mi contraseña mediante el correo electrónico registrado.
* **HU-309**: Como nuevo usuario, quiero que la vista de registro esté conectada con el AuthService, para poder crear una cuenta válida y acceder al sistema.

## ÉPICA 5: Carga de Archivos

### Sprint 11

* **HU-401**: Como docente, quiero descargar una plantilla de Excel para estudiantes, con estructura validada, para garantizar un formato estándar.
* **HU-402**: Como docente, quiero cargar un archivo Excel con estudiantes y que el sistema ejecute un POST hacia el backend, para registrar automáticamente los datos.
* **HU-403**: Como docente, quiero recibir un mensaje de error si el archivo de estudiantes no cumple con el formato esperado, para corregirlo.
* **HU-404**: Como docente, quiero cargar un archivo Excel con calificaciones, para que el sistema lo procese y almacene los datos en una base estructurada.
* **HU-405**: Como sistema, quiero validar que el archivo Excel tenga encabezados correctos (materia, estudiante, nota), para asegurar la integridad de los datos.
* **HU-406**: Como docente, quiero cargar un archivo PDF con calificaciones, para que el sistema pueda interpretar y extraer los datos relevantes.
* **HU-407**: Como sistema, quiero convertir automáticamente las tablas de calificaciones en PDF a un formato estructurado, para facilitar el análisis posterior.
* **HU-408**: Como sistema, quiero validar que los archivos subidos tengan el formato correcto (Excel o PDF), para evitar errores de procesamiento.
* **HU-409**: Como docente, quiero recibir un mensaje de error claro cuando suba un archivo no válido, para entender qué debo corregir.
* **HU-410**: Como sistema, quiero identificar automáticamente materias, estudiantes y cortes dentro de los archivos subidos, para organizar los datos sin intervención manual.
* **HU-411**: Como docente, quiero revisar una vista previa de los datos procesados, para confirmar que la información fue interpretada correctamente.
* **HU-412**: Como administrador, quiero que los datos extraídos se almacenen en una base de datos relacional, para poder consultarlos posteriormente.
* **HU-413**: Como sistema, quiero detectar errores en los documentos (datos faltantes o inconsistentes), para informar al usuario de problemas en la carga.
* **HU-414**: Como usuario, quiero que se guarde un historial de archivos subidos, para rastrear las cargas anteriores.

## ÉPICA 6: Análisis y Estadísticas

### Sprint 12

* **HU-501**: Como estudiante, quiero consultar mi promedio académico general, para conocer mi rendimiento.
* **HU-502**: Como estudiante, quiero consultar mis notas y compararlas con el promedio del grupo, para conocer mi posición académica.
* **HU-503**: Como estudiante, quiero ver un gráfico de mi progreso académico por semestre, para identificar mejoras o retrocesos.
* **HU-504**: Como docente, quiero ver estadísticas de notas por materia, para identificar el rendimiento global de los estudiantes.
* **HU-505**: Como docente, quiero ver estadísticas de notas por estudiante, para evaluar el progreso individual.
* **HU-506**: Como docente, quiero ver estadísticas de distribución de notas (promedio, mínimo, máximo, desviación estándar), para analizar tendencias.
* **HU-507**: Como docente, quiero filtrar estadísticas por fecha (cortes), para hacer un análisis temporal.
* **HU-508**: Como docente, quiero generar estadísticas de notas por corte, para analizar cómo evoluciona el rendimiento en el semestre.
* **HU-509**: Como docente, quiero identificar estudiantes en riesgo (bajo promedio), para tomar decisiones preventivas.
* **HU-510**: Como docente, quiero ver gráficos de barras por materia, para visualizar los promedios de manera clara.
* **HU-511**: Como docente, quiero ver gráficos circulares por grupo, para observar la distribución de calificaciones.
* **HU-512**: Como docente, quiero alternar entre diferentes tipos de gráficos (líneas, barras, circulares), para personalizar la visualización.
* **HU-513**: Como docente, quiero generar reportes comparativos entre cortes de un mismo estudiante, para ver cómo evoluciona su desempeño.
* **HU-514**: Como sistema, quiero calcular automáticamente promedios generales por semestre, para consolidar los datos en un solo valor.

### Sprint 13

* **HU-515**: Como coordinador, quiero ver estadísticas comparativas entre grupos, para identificar diferencias de desempeño académico.
* **HU-516**: Como sistema, quiero generar automáticamente un listado de estudiantes con notas menores a un umbral definido, para facilitar la detección de bajo rendimiento.
* **HU-517**: Como coordinador, quiero generar estadísticas globales de un programa académico, para tener una visión consolidada del rendimiento.
* **HU-518**: Como sistema, quiero permitir exportar estadísticas en formato CSV, para que puedan ser reutilizadas en otros sistemas.
* **HU-519**: Como coordinador, quiero filtrar estadísticas por materia específica, para analizar casos particulares.
* **HU-520**: Como coordinador, quiero ver reportes de rendimiento histórico (varios semestres), para analizar tendencias a largo plazo.
* **HU-521**: Como administrador, quiero generar reportes en PDF que incluyan tablas y gráficos de las estadísticas, para presentarlos en reuniones académicas.
* **HU-522**: Como usuario, quiero personalizar los reportes seleccionando qué materias, grupos o estudiantes incluir, para obtener información relevante.
* **HU-523**: Como usuario, quiero agregar un logo institucional en mis reportes, para darle un formato oficial.
* **HU-524**: Como coordinador, quiero descargar reportes consolidados por facultad o programa, para tener una visión estratégica de los resultados.
* **HU-525**: Como coordinador, quiero programar la generación automática de reportes semanales, para no tener que solicitarlos manualmente.
* **HU-526**: Como administrador, quiero ver métricas globales (número de estudiantes, docentes y universidades activas), para conocer el estado del sistema.
* **HU-527**: Como administrador, quiero ver gráficos de distribución (ejemplo: estudiantes por universidad o programa), para identificar patrones.

## OTROS

### Sprint 10

* **HU-C16**: Como arquitecto del sistema, quiero implementar el despliegue en Docker de cada módulo en entornos aislados, para garantizar independencia, estabilidad y control durante las pruebas e integraciones del sistema distribuido.
