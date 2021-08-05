# Introduccion
Master en Desarrollo de Software
Asignatura: “Ingeniería WEB”
(Ingeniería Web. Una visión general IW)

Módulo 1. Ejercicio 2: Implementación de un ejemplo funcional de uso de tecnologías web.

## Descripción

Este codigo es el DockerCompose que se descarga los 3 modulos: BD-Mongo, Backend y Frontend de DockerHub y los compone y ejecuta.

Ademas incluse un modulo seed para rellenar con 3 datos la base de datos y tener datos iniciales. Es un docker que se inicia al inicio, popula la BD mongo y se apaga.

Para levantar el docker-compose, simplemente:

`docker-compose -f "docker-compose.yml" up -d --build`

Si todo ha ido correcto, una vez levantado se debe poder acceder a traves de un navegador web a:

`http://localhost:3000/aplicaciones/`