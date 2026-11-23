# Diccionario de datos

<!-- LAB 03: una sección por cada tabla de la base de datos, con TODAS sus
     columnas. El ejemplo es genérico: sustituidlo por vuestras tablas. -->

## Tabla `usuario`

Guarda las personas registradas en la aplicación.

| Columna | Tipo | Nulo | Clave | Restricciones | Descripción |
| --- | --- | --- | --- | --- | --- |
| id_usuario | INT | No | PK | AUTO_INCREMENT | Identificador único |
| nombre | VARCHAR(100) | No | | | Nombre completo |
| email | VARCHAR(150) | No | | UNIQUE | Correo; no puede repetirse |
| fecha_alta | DATE | No | | DEFAULT (CURRENT_DATE) | Fecha de registro |

## Tabla `reserva`

<Qué guarda esta tabla.>

| Columna | Tipo | Nulo | Clave | Restricciones | Descripción |
| --- | --- | --- | --- | --- | --- |
| id_reserva | INT | No | PK | AUTO_INCREMENT | Identificador único |
| fecha | DATE | No | | | <...> |
| id_usuario | INT | No | FK → usuario.id_usuario | ON DELETE RESTRICT | Usuario que hace la reserva |

## Tabla `<...>`

| Columna | Tipo | Nulo | Clave | Restricciones | Descripción |
| --- | --- | --- | --- | --- | --- |
| | | | | | |
