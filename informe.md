## 1. Título
**Despliegue de contenedores MySQL y phpMyAdmin conectados mediante red personalizada en Docker**
## 2. Tiempo de duración
**Tiempo estimado: 120 minutos**
## 3. Fundamentos

### ¿Qué es MySQL?
MySQL es un sistema de gestión de bases de datos relacional de código abierto, ampliamente utilizado para el almacenamiento y manejo de información estructurada en aplicaciones web.

### ¿Qué es phpMyAdmin?
phpMyAdmin es una herramienta gratuita basada en web que permite administrar bases de datos MySQL o MariaDB utilizando una interfaz gráfica amigable, sin necesidad de trabajar directamente desde la terminal.

### ¿Qué es una red personalizada en Docker?
Una red personalizada en Docker permite que los contenedores se comuniquen usando nombres de host (los nombres de los contenedores) en lugar de direcciones IP, proporcionando una mejor organización, seguridad y facilidad de conexión entre servicios relacionados.

## 4. Conocimientos previos
- Uso básico de Docker (comandos: `docker run`, `docker network create`, etc.).
- Conceptos de redes en Docker.
- Gestión básica de bases de datos MySQL.
- Acceso a servicios web mediante navegador.

## 5. Objetivos a alcanzar
- Crear y configurar un contenedor para MySQL.
- Crear y configurar un contenedor para phpMyAdmin.
- Crear una red personalizada para interconectar los contenedores.
- Establecer comunicación entre phpMyAdmin y MySQL.
- Crear una base de datos de prueba usando la interfaz gráfica de phpMyAdmin.

## 6. Equipo necesario
- Computador con Windows, Linux o MacOS.
- Docker instalado y funcionando.
- Navegador web actualizado (Chrome, Firefox, Edge).
- Editor de texto (opcional).

## 7. Material de apoyo
- Documentación oficial de [Docker](https://docs.docker.com)
- Documentación de [phpMyAdmin](https://docs.phpmyadmin.net/)
- Documentación oficial de [MySQL](https://dev.mysql.com/doc/)

## 8. Procedimiento

![img01](https://github.com/Edissonfierro/contenedoresmysqlyphomyadmin/blob/main/1.jpg)
![img01](https://github.com/Edissonfierro/contenedoresmysqlyphomyadmin/blob/main/2.jpg)
![img01](https://github.com/Edissonfierro/contenedoresmysqlyphomyadmin/blob/main/3.jpg)
![img01](https://github.com/Edissonfierro/contenedoresmysqlyphomyadmin/blob/main/4.jpg)

## 9. Resultados esperados
Acceso exitoso a la interfaz de phpMyAdmin desde el navegador (localhost:8080).

Conexión establecida entre phpMyAdmin y MySQL mediante la red personalizada red_mysql_phpmyadmin.

Base de datos creada correctamente usando phpMyAdmin.

Ambos contenedores visibles corriendo en Docker.

## 9. blibrliografia
Docker. (n.d.). Docker networking overview. Docker. Recuperado el 25 de abril de 2025, de https://docs.docker.com/network/

phpMyAdmin. (n.d.). phpMyAdmin Documentation. Recuperado el 25 de abril de 2025, de https://docs.phpmyadmin.net/

MySQL. (n.d.). MySQL 8.0 Reference Manual. Recuperado el 25 de abril de 2025, de https://dev.mysql.com/doc/
