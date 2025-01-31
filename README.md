# Task Manager App 🚀

Aplicación web sencilla para gestionar tus tareas diarias. Desarrollada con Spring Boot, te permite crear, ver, editar y eliminar tareas.

---

## 🛠️ Tecnologías utilizadas

- **Spring Boot**: Framework principal para construir la aplicación.
- **Spring MVC**: Para manejar las solicitudes HTTP y la lógica de la interfaz web.
- **Spring Data JPA**: Para interactuar con la base de datos de manera sencilla.
- **H2 Database**: Base de datos en memoria para desarrollo rápido.
- **Thymeleaf**: Motor de plantillas para renderizar las vistas HTML.
- **HTML/CSS**: Para la estructura y el diseño de la interfaz de usuario.
- **Maven/Gradle**: Gestión de dependencias y construcción del proyecto.

---

## 🚀 ¿Qué hace esta aplicación?

El **Task Manager App** te permite:
- **Crear tareas**: Agrega nuevas tareas con un título, descripción y fecha de vencimiento.
- **Ver tareas**: Visualiza todas tus tareas en una lista ordenada.
- **Eliminar tareas**: Elimina tareas que ya no necesitas.
- **Interfaz sencilla**: Diseño limpio y fácil de usar.

---

## 🛠️ Requisitos previos

Antes de ejecutar la aplicación, asegúrate de tener instalado:
- **Java 17 o superior**: [Descargar Java](https://www.oracle.com/java/technologies/javase-downloads.html)
- **Maven o Gradle**: [Descargar Maven](https://maven.apache.org/download.cgi) | [Descargar Gradle](https://gradle.org/install/)
- **Un IDE** (opcional pero recomendado): IntelliJ IDEA, Eclipse o VS Code.

---

## 🧩 Estructura del proyecto
```plaintext
task-manager-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── taskmanager/
│   │   │               ├── controller/       # Controladores
│   │   │               ├── model/            # Entidades
│   │   │               ├── repository/       # Repositorios
│   │   │               ├── service/          # Lógica de negocio
│   │   │               └── TaskManagerApplication.java  # Clase principal
│   │   └── resources/
│   │       ├── static/                       # Archivos estáticos (CSS, JS)
│   │       ├── templates/                    # Plantillas Thymeleaf
│   │       └── application.properties        # Configuración de la aplicación
│   └── test/                                 # Pruebas unitarias
├── pom.xml                                   # Configuración de Maven
└── README.md                                 # Este archivo
```
---

## 🖼️ Capturas de pantalla





