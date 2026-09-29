# ADR-002: Estructura inicial del proyecto

## Contexto

El proyecto de e-commerce está formado por diferentes partes, como el frontend y el backend.

Necesitamos organizar el código de forma clara para facilitar el desarrollo, el mantenimiento y el trabajo en equipo.

## Decisión

Utilizaremos una estructura con el frontend y el backend organizados dentro del mismo repositorio.

El backend contendrá la API desarrollada con Node.js y Express, mientras que el frontend contendrá la aplicación web del e-commerce.

Además, la documentación del proyecto se almacenará dentro de la carpeta `docs/`.

## Consecuencias

### Positivas

* Todo el proyecto queda organizado en un mismo repositorio.
* Facilita la gestión del proyecto.
* La documentación queda centralizada.
* Facilita el trabajo colaborativo.

### Negativas

* El repositorio puede crecer de tamaño al contener frontend, backend y documentación.
* Es necesario mantener una estructura de carpetas clara.
