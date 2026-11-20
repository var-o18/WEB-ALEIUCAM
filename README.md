# WEB-ALEIUCAM

Plataforma de estudio con preguntas tipo test para la asignatura **Aspectos Legales y Éticos de la Informática** (UCAM).

## Contenido

- **Primer Parcial:** 303 preguntas sin duplicados (simulacros de examen, compendio por marcos y deontología y legislación).
- **Segundo Parcial:** próximamente.

## Modos de estudio

- **Práctica guiada:** corrección inmediata, filtros por bloque, apartado y tema.
- **Simulacro de examen:** 40 o 20 preguntas con temporizador y baremo oficial (30/40 = 5,0).
- **Repaso de fallos:** la pregunta sale del repaso al acertarla dos veces seguidas.
- **Banco de preguntas:** buscador con todas las respuestas correctas.

## Uso

Abre `index.html` en el navegador. El progreso se guarda en el propio navegador.

## Añadir preguntas

Las preguntas están en `preguntas.js`. Para el Segundo Parcial, añade objetos a `parcial2` con este formato:

```js
{ id: "P2-1", bloque: "examenes", grupo: "Examen 1", tema: "T5",
  q: "Enunciado", opts: ["A", "B", "C", "D"], ans: 0, exp: "Explicación opcional" }
```

`ans` es la posición de la respuesta correcta empezando en 0 (0 = a, 1 = b, 2 = c, 3 = d).
