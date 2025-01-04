# Configuración

## 1 Crear red y conectar los contenedores a la misma

### (Ejecutar los siguientes comandos en una nueva terminal con los contenedores anteriores corriendo)

`$ docker network create mysql-local_default` (Puede ser cualquier nombre)

`$ docker network connect mysql-local_default <id_contenedor>` (Ejecutar tanto para MySQL como para MariaDB)

`$ docker-compose up`
