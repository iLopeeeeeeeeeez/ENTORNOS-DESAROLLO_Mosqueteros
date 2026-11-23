# Estilos de la web

<!-- LAB 04: sustituid lo que está entre < > y los ejemplos, y borrad estos comentarios. -->

## Archivos CSS y orden de carga

1. `<css/estilos.css>`: <variables, estilos base y componentes comunes>
2. `<css/...>`: <...>

## Variables

| Variable | Valor | Uso |
| --- | --- | --- |
| `--color-principal` | `<#1e5aa8>` | <Botones, enlaces, cabecera> |
| `--color-texto` | `<#222222>` | <Texto general> |

## Clases reutilizables

| Clase | Dónde se usa | Qué hace |
| --- | --- | --- |
| `.menu-principal` | <Todas las páginas> | <Menú horizontal; en columna en móvil> |

## Diseño adaptable

| Media query | Qué cambia |
| --- | --- |
| `max-width: 600px` | <Menú en columna> |

## Cómo modificar los estilos sin romper la web

<Pasos concretos. Ejemplo: para cambiar el color principal, editar solo --color-principal en :root; no escribir colores sueltos en otras reglas.>
