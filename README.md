# 🏥 Ecosistema de Microservicios - Sistema de Gestión Médica

¡Bienvenido al repositorio central y portal de arquitectura! 

Este repositorio sirve como **Organizacion para los Microservicios hechos** para una plataforma integral de gestión clínica y administrativa desarrollada.

---

## 📋 Descripción del Sistema

La plataforma está diseñada para descentralizar los procesos médicos y administrativos de un centro de salud. Se divide en servicios independientes y desacoplados que gestionan el flujo completo del usuario: desde la administración de pacientes y su historial clínico hasta la emisión de previsiones y facturación.


## 🧩 Index de Microservicios y Repositorios

A continuación se detallan los repositorios independientes que componen el código fuente del sistema:

| Servicio | Descripción | Tecnologías | Enlace al Código |
| :--- | :--- | :--- | :--- |
| 🛡️ **API Gateway** | Punto de entrada único (Entry Point). Maneja el enrutamiento de peticiones, balanceo de carga y seguridad. | Java, Spring Cloud Gateway | [📂 Ver Repositorio](https://github.com/MatiasBeas/api-gateway.git) |
| 🔍 **Eureka Server** | Servidor de descubrimiento (Service Discovery) para el registro dinámico de instancias en la red. | Java, Netflix Eureka | [📂 Ver Repositorio](https://github.com/MatiasBeas/eureka-server) |
| 👤 **Paciente** | Servicio CRUD para el registro, consulta y actualización de datos demográficos de los pacientes. | Java, Spring Boot, JPA | [📂 Ver Repositorio](https://github.com/MatiasBeas/Paciente) |
| 🩺 **Historial Médico** | Gestión centralizada de fichas médicas, diagnósticos, recetas y antecedentes del paciente. | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Historial_Medico) |
| 🏥 **Previsión** | Validación y consulta de previsión de salud (Isapre / Fonasa) para atención médica. | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Prevision) |
| 🧾 **Facturación** | Módulo encargado del procesamiento de pagos, cálculo de prestaciones y emisión de facturas. | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Factura) |

---

## 🛠️ Stack Tecnológico

* **Lenguaje Principal:** Java (JDK 17)
* **Framework Backend:** Spring Boot
* **Arquitectura Distribuida:** Spring Cloud (Eureka Server, API Gateway)
* **Persistencia de Datos:** Spring Data JPA / Hibernate
* **Herramientas de Construcción:** Maven / Gradle

---

## 🚀 Cómo ejecutar la infraestructura completa localmente

1. **Clonar los servicios principales:**
   Asegúrate de clonar e iniciar primero los servicios base de infraestructura:
   ```bash
   git clone [https://github.com/MatiasBeas/eureka-server.git](https://github.com/MatiasBeas/eureka-server.git)
   git clone [https://github.com/MatiasBeas/api-gateway.git](https://github.com/MatiasBeas/api-gateway.git)
