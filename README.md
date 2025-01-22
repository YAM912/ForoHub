# ForoHub - API REST con Spring Boot

ForoHub es una API REST desarrollada con Spring Boot que implementa las funcionalidades básicas de un foro de discusión y permite a los usuarios crear, leer, actualizar y eliminar tópicos de discusión.

## 🛠️ Tecnologías Utilizadas
- Java 17
- Spring Boot 3.2.2
- Spring Data JPA
- MySQL
- Maven
- Lombok
- Spring Validation
- JUnit 5

## Requisitos
- JDK 17 o superior
- Maven 3.6.3 o superior
- MySQL 8.0 o superior

## 📌 Endpoints API

### Tópicos
- **GET** `/topicos` - Listar todos los tópicos
- **GET** `/topicos/{id}` - Obtener un tópico específico
- **POST** `/topicos` - Crear un nuevo tópico
- **PUT** `/topicos/{id}` - Actualizar un tópico existente
- **DELETE** `/topicos/{id}` - Eliminar un tópico


## 📋 Reglas de Negocio
- Todos los campos son obligatorios
- No se permiten tópicos duplicados (mismo título y mensaje)
- Cada tópico tiene un estado que indica su situación actual
- Se registra automáticamente la fecha de creación
