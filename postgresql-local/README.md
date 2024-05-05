
# PostgreSQL pgadmin con docker

Configuraciones para tener PostgreSQL y pgadmin (web) desde un docekr con un docker-compose

Crear .env con el contenido de .env.example y tus variables personalizadas

## Variables de entorno

##### LOCAL_PATH_POSTGRES_VOLUME=./postgresqldata
#####
path a la carpeta de volume local donde quieres almacenar los datos de la base de datos (defaukt: ./postgresqldata)

##### LOCAL_PATH_PG_ADMIN_VOLUME=./pgadmindata 
#####
path a la carpeta de volume local donde quieres almacenar los datos de pgadmin (default: ./pgadmindata)

##### POSTGRES_USER= 
#####
usuario de la base de datos

##### POSTGRES_PASSWORD= 
#####
password del usuario

##### POSTGRES_DB= 
#####
base de datos (opcional)

##### PGADMIN_DEFAULT_EMAIL=superman@google.com
#####
usuario de pg admin (default: superman@google.com)

##### PGADMIN_DEFAULT_PASSWORD=123546
#####
password del usuario pg admin (default: 123546)

##

## Linux

##### Darle permisos al volume de pg admin en linux
#####
ejecutar: sudo chown -R 5050:5050 pgadmindata
