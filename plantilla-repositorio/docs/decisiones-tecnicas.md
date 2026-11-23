# Decisiones técnicas

<!-- LAB 05: tres decisiones, mejor de módulos distintos. Cada una con al menos
     una alternativa real descartada. El ejemplo DT-01 es orientativo: sustituidlo. -->

## DT-01. Tabla intermedia para usuarios y actividades

- **Módulo:** Bases de Datos
- **Fecha:** <2026-11-xx>
- **Contexto:** un usuario puede apuntarse a varias actividades y cada actividad tiene varios usuarios.
- **Alternativas consideradas:**
  1. Guardar la lista de actividades en una columna de texto de `usuario`. Descartada: no permite claves foráneas ni consultar por actividad.
  2. Tabla intermedia `inscripcion(id_usuario, id_actividad, fecha)`.
- **Decisión:** opción 2.
- **Consecuencias:** la clase `InscripcionDAO` gestiona la tabla; la web necesita una página de inscripciones.

## DT-02. <Título de la decisión>

- **Módulo:** <Programación / Bases de Datos / Lenguajes de Marcas>
- **Fecha:** <...>
- **Contexto:** <qué problema había que resolver>
- **Alternativas consideradas:**
  1. <alternativa descartada y por qué>
  2. <alternativa elegida>
- **Decisión:** <...>
- **Consecuencias:** <qué implica para el resto del proyecto>

## DT-03. <Título de la decisión>

- **Módulo:** <...>
- **Fecha:** <...>
- **Contexto:** <...>
- **Alternativas consideradas:**
  1. <...>
  2. <...>
- **Decisión:** <...>
- **Consecuencias:** <...>
