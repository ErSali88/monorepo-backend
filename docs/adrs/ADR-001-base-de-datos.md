# ADR-001: Base de datos del proyecto

## Contexto

El proyecto es un e-commerce de móviles que necesita almacenar información sobre usuarios, productos, categorías, carritos y pedidos.

Necesitamos una base de datos que permita almacenar estos datos y que se integre correctamente con el backend desarrollado con Node y Express.

## Decisión

Utilizaremos MongoDB como base de datos principal del proyecto, gestionada mediante Docker.

## Consecuencias

### Positivas

* Flexibilidad para añadir nuevos campos a los productos y usuarios.
* Buena integración con Node.js y Express.
* Facilita el trabajo con datos en formato de documentos.

### Negativas

* Las consultas con muchas relaciones pueden ser menos adecuadas que en una base de datos relacional.
* Es necesario diseñar correctamente las relaciones entre los documentos.
