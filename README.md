Sistema de Gestión de Inventarios y Ventas

Este repositorio contiene el código fuente del sistema de Gestión de Inventarios y Ventas desarrollado para la empresa NIVA EIRL. Este sistema está diseñado para mejorar la eficiencia en los procesos de inventario y ventas, optimizando la operación diaria mediante un conjunto de funcionalidades intuitivas y fáciles de usar.

Características Principales

Gestión de Productos:

Creación, edición y deshabilitación de productos.

Control de existencias por almacén.

Control de Almacenes:

Administración de entradas, salidas y traslado de mercadería.

Kardex físico para el seguimiento de movimientos de inventario.

Módulo de Ventas:

Registro de ventas con actualización automática del stock.

Generación de reportes en formato PDF.

Módulo de Caja:

Registro y control del movimiento de dinero.

Usuarios y Proveedores:

Administración de usuarios con roles y credenciales.

Registro de proveedores con información de contacto detallada.

Tecnologías Utilizadas

Backend:

Java con Spring Boot (Thymeleaf, JPA, Hibernate).

Base de Datos:

PostgreSQL.

Frontend:

Thymeleaf.

Requisitos del Sistema

Hardware:

Procesador Intel Core i5 (10ª generación o superior).

16 GB de RAM.

Conexión Ethernet para entornos locales.

Tarjeta gráfica NVIDIA GeForce 750 (o equivalente).

Software:

Java 17 o superior.

PostgreSQL 14.

Maven para la gestión de dependencias.

Configuración del Proyecto

Clonar este repositorio:

git clone https://github.com/usuario/nombre-del-repositorio.git

Configurar la base de datos:

Crear una base de datos PostgreSQL llamada niva_eirl.

Configurar las credenciales en el archivo application.properties.

Compilar y ejecutar el proyecto:

mvn clean install
mvn spring-boot:run

Acceder a la aplicación en el navegador:

http://localhost:8080

Documentación

Diagramas UML:

Diagrama de clases, casos de uso, secuencia y actividad.

Manual del usuario y manual técnico.

Reportes en formato PDF.

La documentación completa está disponible en el directorio docs/ del repositorio.

Enlace al Repositorio

Puedes acceder al código fuente en GitHub mediante el siguiente enlace:
Repositorio del Proyecto en GitHub

Contribuciones

Si deseas contribuir a este proyecto:

Haz un fork del repositorio.

Crea una rama para tus cambios:

git checkout -b feature/nueva-funcionalidad

Realiza tus cambios y haz un commit:

git commit -m "Descripción de los cambios"

Envía un pull request.

Contacto

Para consultas o soporte, por favor contacta al desarrollador principal:

Nombre: [Tu Nombre]

Email: [tuemail@dominio.com]

Teléfono: [+51 123 456 789]

Nota: Este sistema está diseñado para ser usado localmente y no requiere conexión a internet para su operación.
