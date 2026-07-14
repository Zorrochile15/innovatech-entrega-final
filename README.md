# Evaluación Final - Innovatech Chile (Arquitectura de Microservicios)

Este es el repositorio central de infraestructura para el proyecto Innovatech. 

## Repositorios del Código Fuente
El código de los microservicios, junto con sus respectivos historiales de Git y pipelines de CI/CD en GitHub Actions, se encuentran en los siguientes repositorios:
* [Frontend - Innovatech](https://github.com/Zorrochile15/innovatech-frontend)
* [Backend Ventas - Innovatech](https://github.com/Zorrochile15/innovatech-backend-ventas)
* [Backend Despachos - Innovatech](https://github.com/Zorrochile15/innovatech-backend-despachos)

## Entorno de Desarrollo Local
Para levantar el entorno completo de forma local, debe clonar los 3 repositorios mencionados en la misma carpeta raíz que este archivo y ejecutar:
`docker-compose up --build -d`

## Despliegue Cloud (AWS ECS Fargate)
El sistema completo se encuentra automatizado con Integración y Entrega Continua (CI/CD) y desplegado en AWS.
