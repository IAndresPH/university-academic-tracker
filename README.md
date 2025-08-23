# university-academic-tracker – Arquitectura

Este apartado corresponde a la documentación de la **arquitectura distribuida** del proyecto **University Academic Tracker**.  
El objetivo es describir la estructura técnica del sistema, los servicios que lo conforman y los lineamientos tecnológicos que se utilizarán durante el desarrollo.

---

## Enfoque arquitectónico

El sistema se construirá bajo una **arquitectura distribuida basada en microservicios** para garantizar escalabilidad, modularidad y facilidad de mantenimiento.  
Se utilizará un único **frontend web** para la interfaz de usuario, que consumirá los servicios a través de un **API Gateway**.

---

## Servicios principales

- **Auth Service**  
  Responsable de la autenticación y autorización de usuarios.  
  - Tecnología: Spring Boot, Java 21, Maven  
  - Seguridad: JWT  
  - Comunicación: Eureka Client  

- **Student Service**  
  Gestión de estudiantes, materias, actividades y calificaciones.  
  - Tecnología: Spring Boot, Java 21, Maven  
  - Comunicación: Eureka Client  

- **University Service**  
  Administración de universidades, programas académicos y periodos.  
  - Tecnología: Spring Boot, Java 21, Maven  
  - Comunicación: Eureka Client  

- **Teacher Service**  
  Gestión de docentes y asignaturas.  
  - Tecnología: Spring Boot, Java 21, Maven  
  - Comunicación: Eureka Client  

- **Gateway Service**  
  Punto de entrada único para el frontend y enrutador hacia los microservicios.  
  - Tecnología: Spring Cloud Gateway  
  - Comunicación: Eureka Client  

- **Eureka Server**  
  Registro y descubrimiento de servicios en la arquitectura distribuida.  
  - Tecnología: Spring Cloud Netflix Eureka Server  

- **Frontend Web**  
  Interfaz de usuario centralizada, conectada al Gateway.  
  - Tecnología: a definir (ej. Angular, React, Vue).  

---

## Tecnologías principales

- **Lenguaje**: Java 21  
- **Framework**: Spring Boot  
- **Gestión de dependencias**: Maven  
- **Seguridad**: JWT (Auth Service)  
- **Service Discovery**: Eureka (Server & Clients)  
- **Arquitectura**: Microservicios con comunicación vía Gateway  

---

## Documentación adicional

Los diagramas que representan esta arquitectura se encuentran en la carpeta:  
[`docs/architecture/diagrams/`](diagrams/)  

Los registros de decisiones arquitectónicas estarán en:  
[`docs/architecture/decisions/`](decisions/)  