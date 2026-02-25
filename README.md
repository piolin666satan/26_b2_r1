# Actividad: Configuración y Pruebas de Proyecto Spring Boot con Base de Datos en la Nube

**Nombre del Estudiante:** [Santiago Sanchez Rojas.]  
**Institución:** CESDE  
**Materia:** Backend 2  

---

## 1. Configuración de Base de Datos (Prisma.io)
Se ha configurado una instancia de PostgreSQL en la nube utilizando Prisma.io.

* **Enlace a la instancia:**
* **Captura de configuración:** ![Configuración Prisma](./Evidencias/Captura%20de%20pantalla%202026-02-24%20122343.png)

---

## 2. Conexión y Ejecución del Proyecto
La aplicación Spring Boot se conecta exitosamente a la base de datos remota.

* **Log de la consola al iniciar:** ![Log Spring Boot](./Evidencias/Captura%20de%20pantalla%202026-02-24%20111247.png)

---

## 3. Pruebas de la API RESTful (CRUD)
A continuación, se presentan las evidencias de las operaciones realizadas en la ruta base `/api/students` usando Postman.

### A. POST - Crear Estudiantes
Se crearon al menos 3 estudiantes diferentes.  
![POST Evidence](./Evidencias/Captura%20de%20pantalla%202026-02-24%20111201.png)

### B. GET ALL - Listar Estudiantes
Obtención de la lista completa de registros.  
![GET ALL Evidence](./Evidencias/Captura%20de%20pantalla%202026-02-24%20111701.png)

### C. GET by Email
Búsqueda de un estudiante específico por su correo electrónico.  
![GET Email Evidence](./Evidencias/Captura%20de%20pantalla%202026-02-24%20111701.png)

### D. PUT - Actualizar Estudiante
Actualización de la información de un registro existente.  
![PUT Evidence](./Evidencias/Captura%20de%20pantalla%202026-02-24%20173303.png)

### E. DELETE - Eliminar Estudiante
Eliminación de un registro de la base de datos.  
![DELETE Evidence](./Evidencias/Captura.PNG)

---

## 4. Ejecución de Pruebas Internas
Resultado de la ejecución del comando `mvn test`, demostrando que todas las pruebas unitarias e integración pasaron exitosamente.

![Resultado Pruebas](./Evidencias/Captura%20de%20pantalla%202026-02-24%20174459.png)

---

## 5. Gestión de Credenciales
Se confirma que el archivo `.env` fue configurado localmente basándose en `.env.example` y que este **no** ha sido subido al repositorio de GitHub, cumpliendo con las normas de seguridad.
