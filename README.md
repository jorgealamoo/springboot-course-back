# Spring Boot CRUD (Backend del proyecto con Angular)  
(Basado en el proyecto original de [Sotobotero](https://sotobotero.com))  
[![Powered by @sotobotero](https://img.shields.io/badge/Powered%20by-%40sotobotero-blue?style=flat-square&logo=twitter)](https://twitter.com/sotobotero)  
[![Sotobotero.com](https://img.shields.io/badge/Powered%20by-sotobotero.com-blue?style=flat-square&logo=twitter)](https://sotobotero.com/)

## 🌟 Descripción

Este repositorio contiene **el backend desarrollado en Spring Boot** de un proyecto CRUD integrado con un **frontend en Angular**.  
Es una **versión personalizada y mejorada** del proyecto original de [Sotobotero](https://sotobotero.com), adaptada para mi aprendizaje en el desarrollo fullstack con **Spring Boot + Angular**.

> 🧠 *El propósito principal de este proyecto es practicar el diseño de APIs REST, la conexión con bases de datos y la integración con un cliente Angular.*

---

## 🚀 Mejoras y Cambios Realizados

- Actualización de dependencias y estructura de paquetes.  
- Ajustes en controladores, servicios y entidades.  
- Configuración mejorada de CORS para conectar con el frontend Angular.  
- Limpieza y reorganización de código para mayor claridad.  
- Adaptación del README y documentación.  

---

## 🧩 Relación con el Frontend

Este backend está diseñado para trabajar junto con el frontend Angular disponible en el siguiente repositorio:  
👉 [**Angular CRUD Frontend (Proyecto asociado)**]([https://github.com/tu-usuario/tu-repo-frontend](https://github.com/jorgealamoo/springboot-course-front))

---

## 🛠️ Requisitos

1. **Java 17** o superior.  
2. **Maven** (incluido wrapper `mvnw`).  
3. (Opcional) **Base de datos MySQL o H2** configurada en `application.properties`.  

---

## ⚙️ Instalación y Ejecución

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/tu-repo-backend.git
   ```
2. Entrar en la carpeta del proyecto:  
   ```bash
   cd tu-repo-backend
   ```
3. Compilar el proyecto:  
   ```bash
   ./mvnw package
   ```
4. Ejecutar la aplicación:  
   ```bash
   java -jar target/customer-back-0.0.1-SNAPSHOT.jar
   ```
5. Abrir en el navegador:  
   [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

---

## 🌐 Endpoints Principales

- `GET /api/customers` → Lista de clientes  
- `POST /api/customers` → Crear un nuevo cliente  
- `PUT /api/customers/{id}` → Actualizar cliente  
- `DELETE /api/customers/{id}` → Eliminar cliente  

---

## 🔗 Integración con Angular

Por defecto, este backend está configurado para aceptar peticiones desde `http://localhost:4200`.  
Asegúrate de tener el frontend ejecutándose con el comando:

```bash
ng serve
```

Y el backend activo en el puerto **8080** para una correcta comunicación entre ambos.

---

## 📄 Licencia

Este proyecto se distribuye bajo la licencia [MIT](https://github.com/sotobotero/CodeHub/blob/develop/LICENSE).  
Créditos al autor original: [Sotobotero](https://sotobotero.com).  
Modificaciones y mejoras: *jorgealamoo* ✨
