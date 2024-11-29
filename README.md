# Proyecto Final Servidor1 , Javier Ortega Reina
Autor: Javier Ortega Reina
Este proyecto consiste en el desarrollo de una API REST destinada a gestionar datos de proyectos, desarrolladores y tecnologías. Fue implementada en Java con el framework Spring Boot, 
siguiendo el modelo de arquitectura MVC (Modelo-Vista-Controlador). 
Además, el control de versiones se realizó utilizando Git.

## Índice
- [Introducción](#Introducción)
- [Tecnologías](#Tecnologías)
- [Instalación y Configuración](#Instalación-y-Configuración)
- [Enlace a figma](#Figma)
- [Conclusión](#Conclusión)
- [Contribuciones](#Contribuciones)
- [Licensias](#Licensias)
- [Contacto](#Contacto)


---

## Introducción
Esta API proporciona las siguientes funcionalidades:
Gestión eficiente de proyectos, desarrolladores y tecnologías almacenados en una base de datos.
Operaciones CRUD completas: Crear, Leer, Actualizar y Eliminar datos.
Búsqueda de proyectos por nombre o por tecnología asociada.
Cambio de estado de los proyectos mediante un flujo organizado: Development ➔ Testing ➔ Production.
Integración de paginación en las consultas y manejo centralizado de errores.
Este proyecto fue desarrollado como parte de una evaluación en el módulo de desarrollo de servidores, cumpliendo con criterios técnicos avanzados y buenas prácticas de programación.



Este proyecto fue desarrollado como parte de la evaluación de un módulo de servidor y cumple con criterios como paginación en las consultas y manejo de errores con `ResponseEntity`.

---

## Tecnologías

Para ejecutar este proyecto, se requiere el uso de las siguientes herramientas:
Java 17: Lenguaje principal del desarrollo.
Spring Boot: Framework para la creación de la API.
Maven: Herramienta para la gestión de dependencias.
MySQL: Base de datos para almacenar la información.
Postman o Thunder Client: Para pruebas de endpoints.
Git: Control de versiones para el desarrollo colaborativo.



---


## Instalación y Configuración

Generación del Proyecto:
Crea el proyecto inicial utilizando Spring Initializr y configura las dependencias necesarias (Spring Web, Spring Data JPA, MySQL Driver).
Diseño del Modelo de Datos:
Define las entidades de la base de datos y sus relaciones mediante anotaciones de JPA.
Implementación de Controladores y Servicios:
Desarrolla los controladores para manejar las solicitudes HTTP.
Implementa la lógica del negocio a través de servicios especializados.
Gestión de Estados:
Configura la lógica para actualizar el estado de los proyectos (Development, Testing, Production).
Configuración de la Base de Datos:
Conecta la aplicación con MySQL mediante el archivo application.properties o application.yml.
Pruebas Locales:
Ejecuta y prueba los endpoints utilizando herramientas como Postman.
Control de Versiones:
Inicializa un repositorio Git y realiza commits para seguir la evolución del proyecto.



## Conclusión
Este proyecto demuestra una implementación robusta y escalable de una API REST con Spring Boot, incorporando características avanzadas como:
Paginación para optimizar consultas con gran cantidad de datos.
Manejo de errores mediante ResponseEntity para una experiencia de usuario más consistente.
Validaciones de entrada y documentación de la API con herramientas como Swagger.
En general, la solución presentada no solo cumple con los requisitos técnicos del módulo, sino que también refleja buenas prácticas de desarrollo y un diseño eficiente de la arquitectura.


---

## Contribuciones

Este proyecto está abierto a contribuciones de la comunidad. Cualquier desarrollador interesado puede participar realizando:
Mejoras en la funcionalidad existente.
Optimización del rendimiento.
Corrección de errores.
Incorporación de nuevas características.
Se recomienda enviar pull requests siguiendo las guías de estilo establecidas y documentando adecuadamente los cambios realizados.
---

## Licensias
El código está protegido bajo la licencia Apache 2.0, lo que permite:
Uso, modificación y distribución del código de manera libre.
Obligación de atribución al autor original.
Esta licencia garantiza un equilibrio entre la libertad de uso y la protección de los derechos del autor.
---

## Contacto
Nombre: Javier Ortega Reina
Localidad: Montellanoa(Sevilla)
Correo : javier.polo@a.vedrunasevillasj.es




