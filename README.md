## FORO HUB - API REST

Es proyecto de preguntas y respuestas desarrollada como parte del desafío final del programa Oracle Next Education, ofrecido por Alura LATAM. El desafío consistió en la creación de una API REST que permite a los usuarios realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre temas y preguntas. La plataforma implementa un sistema de autenticación y autorización para restringir el acceso a la información, y utiliza una base de datos para la persistencia de los datos, todo siguiendo las mejores prácticas del modelo REST.

## 🔧 Tecnologías Utilizadas
- **Lenguaje de programación:** Java 17 ☕
- **Framework:** Spring Boot 3 🌱
- **Base de Datos:** MySQL 8.0 🐬
- **Seguridad:** JSON Web Tokens (JWT) 🔐
- **Gestor de Dependencias:** Maven 4.0.0 📦
- **Dependencias:** Spring Boot DevTools, Spring Web, Spring Data JPA, Spring Security, MySQL Driver, Validation, Lombok, Flyway Migration, Auth0, SpringDocs

## 📂 Funcionalidades

- Autenticación y autorización: Los usuarios se registran, inician sesión y reciben tokens JWT para acceder a los recursos protegidos de la plataforma.

- Gestión de tópicos y respuestas: Los usuarios pueden crear, leer, actualizar y eliminar tópicos, así como responder a preguntas.

- Visualización de tópicos y respuestas: Los usuarios pueden acceder a tópicos y respuestas mediante su ID específico o por las rutas /topicos y /respuestas.

- Reglas de negocio: Se valida que los campos no estén vacíos ni en blanco, que no haya títulos o mensajes duplicados y que cada usuario pueda crear un máximo de 10 tópicos.
