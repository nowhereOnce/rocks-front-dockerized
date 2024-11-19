# Rock Samples API

Este proyecto es un backend desarrollado con FastAPI que se conecta a una base de datos PostgreSQL. Su propósito es servir como una API capaz de realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre datos relacionados con geología, específicamente muestras de rocas, ubicaciones y tipos de rocas.

## Prerequisitos

- Docker
- Docker Compose

## Cómo ejecutar el servicio

Para ejecutar todo el servicio, simplemente usa el siguiente comando:

```sh
docker-compose up --build
```

Base de datos PostgreSQL:

- Puerto: 5433 (mapeado al puerto 5432 del contenedor)
- Servicio: db

API de FastAPI:
- Puerto: 8000 (mapeado al puerto 8000 del contenedor)
- Servicio: web

Servidor Nginx:
- Puerto: 8003 (mapeado al puerto 80 del contenedor)
- Servicio: nginx

## Documentación de FastAPI

Para poder acceder a la documentación ingresar a `localhost:8000/docs`.