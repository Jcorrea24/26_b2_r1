# Actividad 1 - Backend 2 (Miércoles)
**Nombre Completo:** [Julio Eduardo Correa Caraballo]
**Institución:** Cesde

---

## 1. Instancia de Base de Datos

* **Enlace a la instancia:**  
https://console.prisma.io/cmlirilzx00674tfld13f12gl/cmlmyyese08lfw8efpamujybq/cmlmyyese08ldw8eftl1jn1v3/studio

* **Configuración en Prisma.io:**

![Configuración de Base de Datos en Prisma](./screenshots/prisma-config.jpg)

* **Cadena de Conexión:**
`postgres://[usuario]:[PASSWORD_OCULTA]@db.prisma.io:5432/postgres?sslmode=require`

*(Nota: URL y host visibles, contraseña oculta por seguridad)*

---

## 2. Conexión desde Spring Boot
A continuación, se muestra el log de la consola donde se evidencia que la aplicación inició correctamente y estableció conexión con PostgreSQL en Prisma.io:

![Log de Spring Boot - Conexión Exitosa](./screenshots/spring-boot-log.jpg)



## 3. Pruebas de la API (CRUD)

### [POST] Crear Registro
*Captura de la solicitud (Request) y la respuesta (Response) en Postman/Insomnia:*

![POST - Crear Estudiante](./screenshots/post-create.jpg)



### [GET] Obtener Todos (All)

![GET - Obtener todos los estudiantes](./screenshots/get-all.jpg)
 
### [GET] Obtener por ID

![GET - Obtener por ID](./screenshots/get-by-id.jpg)
 

### [GET] Obtener por Email

![GET - Obtener por Email](./screenshots/get-by-email.jpg)
 
### [PUT] Actualizar Registro

![PUT - Actualizar estudiante](./screenshots/put-update.jpg)
 
### [DELETE] Eliminar Registro

![DELETE - Eliminar estudiante](./screenshots/delete-request.jpg)

![DELETE - Respuesta exitosa](./screenshots/delete-response.jpg)

---

## 4. Pruebas Internas del Proyecto
Resultado de la ejecución del comando `mvnw.cmd test`:

![Resultado de pruebas unitarias](./screenshots/maven-tests.jpg)

> **Estado final:** Todas las pruebas pasaron exitosamente.

---
*Este repositorio es un fork del proyecto original para la asignatura de Backend 2.*
