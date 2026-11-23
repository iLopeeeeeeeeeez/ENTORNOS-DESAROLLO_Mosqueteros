# Trazabilidad de una funcionalidad

<!-- LAB 05: elegid una funcionalidad completa del RETO y usad nombres reales
     que existan en el código, la base de datos y la web. El ejemplo es orientativo. -->

**Funcionalidad:** <registro de un nuevo usuario>

| Capa | Elemento | Detalle |
| --- | --- | --- |
| Web | `<registro.html>` | <Formulario con nombre, email y contraseña> |
| Java | `<UsuarioService.registrar(Usuario)>` | <Valida los datos y llama a UsuarioDAO.insertar> |
| BBDD | tabla `<usuario>` | <Columnas nombre, email (UNIQUE), fecha_alta> |

## Recorrido

<En 3-4 frases: qué pasa desde que la persona usa la web hasta que el dato queda guardado, y qué ocurre si algo falla. Ejemplo: el formulario envía los datos, la clase los valida y los inserta; si el email ya existe, la restricción UNIQUE lo impide y se muestra un error.>
