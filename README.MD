# Mosulo 8 laboratorio 4 USIP

Este es el docker compose que ejecuta backend y frontend de la aplicacion de heroes APP
Los repositorios de las aplicaciones son:

# PASO 1: CLonarse los repos y construir las imagenes de backend y frontend

FRONTEND: https://github.com/manuel-munoz-guti/projecto-vue.git
BACKEND: https://github.com/manuel-munoz-guti/backend-vue.git
DOCKER COMPOSE: https://github.com/manuel-munoz-guti/laboratorio4.git

# PASO 2
Crear las imagenes de docker del backend y del frontend con el comando 

 `docker build -t diplomado/heroes-app .` para el frontend
 `docker build -t jsonserver .` para el backend

# PASO 3
 `docker compose up`


El orden es primero ejecutar los serivicios de bases de datos, luego el backend y al final el frontend