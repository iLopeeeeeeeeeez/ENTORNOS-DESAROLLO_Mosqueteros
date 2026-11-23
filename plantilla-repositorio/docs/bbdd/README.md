# Documentación de la base de datos

<!-- LAB 03: sustituid lo que está entre < > y borrad estos comentarios.
     Añadid el diagrama exportado como modelo-er.png en esta carpeta. -->

- [Diagrama E-R](modelo-er.png)
- [Modelo relacional](modelo-relacional.md)
- [Diccionario de datos](diccionario-datos.md)
- [Scripts SQL](../../bbdd/sql/)

## Cómo reconstruir la base de datos

Requisitos: <MySQL 8 o MariaDB 10>, usuario con permiso para crear bases de datos.

Desde la raíz del repositorio:

1. Crear la base de datos vacía:

   ```bash
   mysql -u root -p -e "CREATE DATABASE <nombre_bd>;"
   ```

2. Crear las tablas:

   ```bash
   mysql -u root -p <nombre_bd> < bbdd/sql/01-esquema.sql
   ```

3. Cargar los datos de prueba:

   ```bash
   mysql -u root -p <nombre_bd> < bbdd/sql/02-datos-prueba.sql
   ```

4. Comprobar:

   ```bash
   mysql -u root -p <nombre_bd> -e "SHOW TABLES;"
   ```

   Deben aparecer las tablas: <usuario, reserva, ...>

## Probado por

| Fecha | Quién | Resultado |
| --- | --- | --- |
| <2026-11-xx> | <Nombre> | <Reconstruida sin errores / problemas encontrados> |
