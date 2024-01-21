# AOS_Especificacion_Recambios
Especificación OpenAPI para la gestión del inventario completo de **recambios** de un taller de mecánica rápida para la asignatura de Arquitecturas Orientadas a Servicios.

## Endpoints
- `/recambios`
- `/recambios/{Numero_Serie}`

## Características
- Interfaz gráfica con SwaggerUI
- Mocks de la API con Stoplight Prism
- Redirección de peticiones con Caddy

## Requisitos para el despliegue
- Docker

## Instrucciones de despliegue
1. Clonar el repositorio
2. Ir a la raíz del repositorio local
3. Ejecutar el comando `docker compose up`

## URLs
### Interfaz gráfica de la especificación
http://127.0.0.1:8000/
### Ejemplo de petición
http://127.0.0.1/api/v1/recambios