<h1 align="center">Sistema ForoHub</h1>
<p align="center">ForoHub es una solución tecnológica construida con Spring Boot, diseñada para habilitar la creación, administración y participación en foros educativos. El proyecto incorpora un sistema confiable y seguro que facilita la gestión de usuarios, la organización de temas, la estructuración de cursos y la interacción a través de respuestas.</p>


---
## **Características**
- **Gestión de Usuarios**: Autenticación y autorización con JWT.
- **Gestión de Foros**: Creación y visualización de temas y respuestas.
- **Gestión de Cursos**: Asociación de cursos con temas y categorías.
- **Documentación de la API**: Generada con Swagger.
- **Seguridad**: Implementación de roles y permisos con Spring Security.

---


## **Tecnologías Utilizadas**
- **Lenguaje**: Java 17
- **Framework Principal**: Spring Boot
- **Seguridad**: Spring Security, JWT
- **Acceso a Datos**: Spring Data JPA, Hibernate
- **Base de Datos**: MySQL
- **Documentación**: SpringDoc OpenAPI (Swagger)

---

## **Configuración e Instalación**

### **Pasos**
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/castleortiz1/Challenge-ForoHub-AluraLatam
   cd forohub
   ```
2. Configurar la base de datos:
   - Crear una base de datos en MySQL.
   - Actualizar las credenciales en el archivo `application.properties`:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/forohub
     spring.datasource.username=tu_usuario
     spring.datasource.password=tu_contraseña
     ```
3. Compilar y ejecutar la aplicación:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
---
### **Autor**
LÓPEZ CLAUDIA ROCIO

  ## **¡Gracias por su tiempo!** 
