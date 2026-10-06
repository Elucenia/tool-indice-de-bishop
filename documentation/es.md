<!-- ELUCENIA technical documentation · indice-de-bishop · es · no clinical/professional/rights approval -->

# Índice de Bishop

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/indice-de-bishop)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Dilatación

`dil`

- `0` — Cerrado
- `1` — 1 a 2 cm
- `2` — 3 a 4 cm
- `3` — ≥ 5 cm

### Borramiento cervical

`apag`

- `0` — 0 a 30%
- `1` — 40 a 50%
- `2` — 60 a 70%
- `3` — ≥ 80%

### Estación fetal (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 o 0
- `3` — +1 o +2

### Consistencia cervical

`cons`

- `0` — Firme
- `1` — Media
- `2` — Blanda

### Posición cervical

`pos`

- `0` — Posterior
- `1` — Intermedia
- `2` — Anterior

## Edición del método

Bishop 1964: 5 componentes 0–13; borramiento porcentual, no versión longitud cervical

## Fórmula documentada

Suma de 5 ítems del tacto: dilatación (0–3), borramiento (0–3), estación (0–3), consistencia (0–2) y posición cervical (0–2). Total 0–13.

## Límites y población

El Bishop clásico describe la preparación cervical mediante cinco componentes del examen y no autoriza por sí solo la inducción del parto. El artículo de 1964 estudió una población histórica de multíparas a partir de 36 semanas; esto no constituye una indicación actual de inducción electiva a esa edad gestacional. La orientación institucional ACOG consultada exige evaluar indicaciones y contraindicaciones obstétricas y no realizar inducción electiva antes de 39 semanas. Esta versión usa borramiento cervical en porcentaje, no una versión modificada basada en la longitud cervical.

## Referencias

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Cuello uterino desfavorable (≤ 6): indicar preparación cervical antes de la oxitocina

Métodos de preparación: misoprostol, sonda de Foley o dinoprostona, según el protocolo del servicio y la cicatriz uterina.


### 2

Cuello uterino intermedio (7 a 8)

La probabilidad de parto vaginal después de la inducción es menor que con un cuello favorable; individualizar la preparación cervical.


### 3

Cuello uterino favorable (> 8): probabilidad de parto vaginal similar a la del trabajo de parto espontáneo

Se puede inducir con oxitocina y/o amniotomía.


### 4

Cuello uterino favorable (> 8): probabilidad de parto vaginal similar a la del trabajo de parto espontáneo

Se puede inducir con oxitocina y/o amniotomía.

