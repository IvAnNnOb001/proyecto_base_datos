# Proyecto Base de Datos

Este proyecto contiene el diseño, creación y manejo de una base de datos para un sistema de gestión de información.

## Objetivos
1. Diseñar la estructura de la base de datos.
2. Implementar consultas y operaciones CRUD.
3. Garantizar la integridad y seguridad de los datos.

## Tecnologías utilizadas
- MySQL
- PHP
- HTML/CSS

> "Una base de datos bien diseñada es el corazón de un sistema eficiente."

[Documentación oficial de MySQL](https://dev.mysql.com/doc/)

![Base de Datos](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Database-icon.svg/640px-Database-icon.svg.png)

```sql
-- Ejemplo de creación de tabla
CREATE TABLE usuarios (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nombre VARCHAR(50) NOT NULL,
    email VARCHAR(100) UNIQUE NOT NULL
);
```
