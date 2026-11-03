# 🏥 Ecosistema de Microservicios — Sistema de Gestión Médica

<p align="center">
  <strong>MEDICAL MANAGEMENT SYSTEM</strong>
  <br/>
  Arquitectura distribuida · Desarrollo colaborativo · Backend
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

---

## 📌 Descripción del proyecto

Bienvenido al repositorio central del **Sistema de Gestión Médica**, una plataforma desarrollada mediante una arquitectura de microservicios para gestionar procesos clínicos y administrativos de un centro de salud.

El sistema está compuesto por servicios independientes y desacoplados que permiten distribuir las responsabilidades de la aplicación, facilitando su mantenimiento, escalabilidad y comunicación.

Este repositorio funciona como índice central y punto de acceso a los diferentes componentes que conforman el ecosistema.

## 🏗️ Arquitectura del sistema

La solución utiliza una arquitectura distribuida basada en los siguientes componentes:

| Componente | Responsabilidad |
|---|---|
| API Gateway | Centraliza el acceso y enrutamiento de solicitudes. |
| Eureka Server | Permite el registro y descubrimiento de servicios. |
| Docker | Contiene recursos de configuración para la ejecución del ecosistema. |
| Microservicios | Gestionan las distintas funcionalidades del sistema médico. |

## 🧩 Índice de microservicios

A continuación se presentan los repositorios que conforman el proyecto.

### ⚙️ Infraestructura y comunicación

| Componente | Tecnologías | Repositorio |
|---|---|---|
| 🛡️ API Gateway | Java, Spring Cloud Gateway | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/api-gateway.git) |
| 🔍 Eureka Server | Java, Netflix Eureka | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/eureka-server.git) |
| 🐳 Docker | Docker, YAML | 📂[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Docker.git) |

---

### 👨‍💻 Microservicios — Matías Beas

| Servicio | Tecnologías | Repositorio |
|---|---|---|
| 👤 Paciente | Java, Spring Boot, JPA | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Paciente.git) |
| 🩺 Historial Médico | Java, Spring Boot | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Historial_Medico.git) |
| 🏥 Previsión | Java, Spring Boot | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Prevision.git) |
| 🧾 Facturación | Java, Spring Boot | 📂[[Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Factura.git) |

---

### 👨‍💻 Microservicios — Josué Parra

| Servicio | Tecnologías | Repositorio |
|---|---|---|
| 🧪 Exámenes | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Examenes.git) |
| 📝 Receta Médica | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Receta-Medica.git) |
| 🏥 Hospitalización | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Hospitalizacion.git) |

---

### 👩‍💻 Microservicios — Valentina Castro

| Servicio | Tecnologías | Repositorio |
|---|---|---|
| 📅 Cita Médica | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/CitaMedica.git) |
| 🛏️ Habitación | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Habitacion.git) |
| 👨‍⚕️ Staff Médico | Java, Spring Boot | [Ver repositorio](https://github.com/MatiasBeas-Microservicios-FullStack/Staff.git) |

---

## 🛠️ Stack tecnológico

| Categoría | Tecnología |
|---|---|
| Lenguaje principal | Java (JDK 17) |
| Framework backend | Spring Boot |
| Arquitectura distribuida | Spring Cloud |
| Descubrimiento de servicios | Netflix Eureka |
| Enrutamiento | Spring Cloud Gateway |
| Persistencia | Spring Data JPA / Hibernate |
| Construcción | Maven / Gradle |
| Contenerización | Docker |

## 🎯 Objetivos del proyecto

- Implementar una arquitectura basada en microservicios.
- Separar las responsabilidades de los módulos clínicos y administrativos.
- Facilitar la comunicación entre servicios independientes.
- Centralizar el acceso mediante API Gateway.
- Implementar descubrimiento de servicios mediante Eureka.
- Promover el desarrollo colaborativo y modular.

---

<p align="center">
  <strong>🏥 Sistema de Gestión Médica</strong>
  <br/>
  <sub>Microservices Architecture · Collaborative Software Development</sub>
  <br/><br/>
  <a href="https://github.com/MatiasBeas-GestionMedica">MatiasBeas-GestionMedica</a>
</p>
