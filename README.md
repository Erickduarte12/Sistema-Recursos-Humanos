# Sistema de Recursos Humanos

Este repositorio contiene una aplicación de sistema de recursos humanos desarrollada con React en el frontend y Spring Boot en el backend. La aplicación permite agregar, eliminar y actualizar los datos de los empleados. Además, utiliza Bootstrap para el diseño de la interfaz de usuario.

## Características

- **Agregar Empleados**: Permite agregar nuevos empleados con sus detalles.
- **Eliminar Empleados**: Permite eliminar empleados existentes del sistema.
- **Actualizar Empleados**: Permite actualizar la información de los empleados.
- **Interfaz de Usuario**: Diseñada con Bootstrap para una apariencia moderna y responsiva.

## Tecnologías Utilizadas

- **Frontend**: React, Bootstrap
- **Backend**: Spring Boot
- **Base de Datos**: MySql Workbench

## Prerrequisitos

Antes de comenzar, asegúrate de tener instalados los siguientes programas:

- [Node.js](https://nodejs.org/) (versión 18.12.0 o superior)
- [Maven](https://maven.apache.org/) (versión 3.9.7 o superior)
- [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (JDK 11 o superior)
- Una base de datos (MySQL)

## Instalación y Configuración

### Configuración del Backend (Spring Boot)

1. Clona el repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    cd tu-repositorio/backend
    ```

2. Configura la conexión a la base de datos en el archivo `application.properties`:

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/tu-base-de-datos
    spring.datasource.username=tu-usuario
    spring.datasource.password=tu-contraseña

    spring.jpa.hibernate.ddl-auto=update
    ```

3. Compila y ejecuta la aplicación Spring Boot:

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

### Configuración del Frontend (React)

1. Navega al directorio del frontend:

    ```bash
    cd ../frontend
    ```

2. Instala las dependencias necesarias:

    ```bash
    npm install axios, react
    ```

3. Ejecuta la aplicación React:

    ```bash
    npm start
    ```

    La aplicación estará disponible en `http://localhost:3000`.

## Uso

1. Navega a `http://localhost:3000` en tu navegador web.
2. Utiliza la interfaz para agregar, eliminar y actualizar la información de los empleados.

## Contribución

¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama con tu característica o corrección de errores (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -m 'Agrega una nueva característica'`).
4. Sube tus cambios (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarme a [erickdamianduarte@gamil.com](erickdamianduarte@gamil.com).****
