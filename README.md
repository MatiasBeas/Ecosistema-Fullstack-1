# 🏥 Ecosistema de Microservicios - Sistema de Gestión Médica

¡Bienvenido al repositorio central y portal de arquitectura! 

Este repositorio sirve como **Organización para los Microservicios hechos** para una plataforma integral de gestión clínica y administrativa desarrollada. 10 Microservicios en total. Desarrollo en grupo. 

---

## 📋 Descripción del Sistema

La plataforma está diseñada para descentralizar los procesos médicos y administrativos de un centro de salud. Se divide en servicios independientes y desacoplados que gestionan el flujo completo del usuario: desde la administración de pacientes y su historial clínico hasta la emisión de previsiones y facturación.


## 🧩 Index de Microservicios y Repositorios

A continuación se detallan los repositorios independientes que componen el código fuente del sistema:

| Servicio | Tecnologías | Enlace al Código |
| :--- | :--- | :--- | :--- |
| 🛡️ **API Gateway** | Java, Spring Cloud Gateway | [📂 Ver Repositorio](https://github.com/MatiasBeas/api-gateway.git) |
| 🔍 **Eureka Server** | Java, Netflix Eureka | [📂 Ver Repositorio](https://github.com/MatiasBeas/eureka-server.git) |
| 🐳 **Docker** | YML |  [📂 Ver Repositorio](https://github.com/MatiasBeas/Docker.git) |

Ecosistema de Microservicios - Matías Beas
| 👤 **Paciente** | Java, Spring Boot, JPA | [📂 Ver Repositorio](https://github.com/MatiasBeas/Paciente.git) |
| 🩺 **Historial Médico** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Historial_Medico.git) |
| 🏥 **Previsión** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Prevision.git) |
| 🧾 **Facturación** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Factura.git) |

Ecosistema de Microservicios - Josué Parra
| 🧪 **Exámenes** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Examenes.git) |
| 📝 **Receta Médica** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Receta-Medica.git) |
| 🏥 **Hospitalización** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Hospitalizacion) |

Ecosistema de Microservicios - Valentina Castro
| 📅 **Cita Médica** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Cita_Medica) |
| 🛏️ **Habitación** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Habitacion) |
| 👨‍⚕️ **Staff Médico** | Java, Spring Boot | [📂 Ver Repositorio](https://github.com/MatiasBeas/Staff) |

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
