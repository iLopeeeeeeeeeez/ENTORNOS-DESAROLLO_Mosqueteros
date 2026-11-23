# Documentación de Programación

<!-- LAB 02: sustituid lo que está entre < > y borrad estos comentarios. -->

## Clases principales

| Clase | Paquete | Responsabilidad |
| --- | --- | --- |
| <UsuarioService> | <com.reto.servicio> | <Alta, búsqueda y baja de usuarios> |
| <...> | <...> | <...> |

## Cómo generar el Javadoc

1. En Eclipse: *Project → Generate Javadoc…*
2. Javadoc command: `<ruta-del-JDK>/bin/javadoc`
3. Visibilidad: *Protected*.
4. Destination: `docs/programacion/javadoc`
5. *Extra Javadoc options*: `-encoding UTF-8 -charset UTF-8 -docencoding UTF-8`
6. Abrir `docs/programacion/javadoc/index.html` en el navegador.

Alternativa desde terminal, en la raíz del repositorio:

```bash
javadoc -d docs/programacion/javadoc -sourcepath programacion/src -subpackages <paquete-raiz> -encoding UTF-8 -charset UTF-8 -docencoding UTF-8
```

## Tareas pendientes en el código

Los TODO se ven en la vista *Tasks* de Eclipse (*Window → Show View → Tasks*). La lista consolidada y clasificada está en [pendientes.md](../pendientes.md).
