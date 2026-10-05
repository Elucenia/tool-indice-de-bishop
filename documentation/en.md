<!-- ELUCENIA technical documentation · indice-de-bishop · en · no clinical/professional/rights approval -->

# Bishop score

[conditions, sources and permissions](https://elucenia.org/en/tools/indice-de-bishop)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Dilation

`dil`

- `0` — Closed
- `1` — 1 to 2 cm
- `2` — 3 to 4 cm
- `3` — ≥ 5 cm

### Cervical effacement

`apag`

- `0` — 0 to 30%
- `1` — 40 to 50%
- `2` — 60 to 70%
- `3` — ≥ 80%

### Fetal station (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 or 0
- `3` — +1 or +2

### Cervical consistency

`cons`

- `0` — Firm
- `1` — Mean
- `2` — Soft

### Cervical position

`pos`

- `0` — Posterior
- `1` — Intermediate
- `2` — Anterior

## Method edition

Bishop 1964: 5 components 0–13; percentage effacement, not cervical-length version

## Documented formula

Sum of 5 vaginal-examination items: dilatation (0–3), effacement (0–3), station (0–3), consistency (0–2) and cervical position (0–2). Total 0–13.

## Limits and population

Classic Bishop describes cervical readiness using five examination components and does not by itself authorize labor induction. The 1964 paper studied a historical multiparous population from 36 weeks; this is not a current indication for elective induction at that gestational age. The consulted ACOG institutional guidance requires assessment of obstetric indications and contraindications and no elective induction before 39 weeks. This version uses cervical effacement as a percentage, not a modified version based on cervical length.

## References

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
