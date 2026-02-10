# Vista de Despliegue

El sistema ERP se desplegará en una arquitectura cliente-servidor.

Los usuarios accederán al sistema mediante un navegador web desde sus equipos, conectándose a la aplicación web a través de Internet o una red interna.

La aplicación estará compuesta por los siguientes elementos:

- Servidor de Aplicaciones: alojará la API monolítica desarrollada en Java con Spring Boot, encargada de manejar la lógica de negocio.
- Servidor Web: servirá la aplicación frontend tipo SPA desarrollada en React.
- Servidor de Base de Datos: contendrá la base de datos PostgreSQL donde se almacenará la información del sistema.

La comunicación entre el frontend y el backend se realizará mediante HTTPS, y la API se conectará a la base de datos utilizando JDBC.

Esta arquitectura permite un despliegue sencillo, escalable y fácil de mantener.
