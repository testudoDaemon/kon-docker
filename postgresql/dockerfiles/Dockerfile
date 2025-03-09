# version que se usara de la imagen
FROM postgres:17

# Script para hacer una tabla e insertar
COPY ../scripts/01_tablas.sql /docker-entrypoint-initdb.d/

# var de entorno
ENV POSTGRES_USER=root
ENV POSTGRES_PASSWORD=Morenopassword
ENV POSTGRES_BD=moreno

EXPOSE 5432
