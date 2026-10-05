<!-- ELUCENIA technical documentation · indice-de-bishop · pt-BR · no clinical/professional/rights approval -->

# Índice de Bishop

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/indice-de-bishop)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Dilatação

`dil`

- `0` — Fechado
- `1` — 1 a 2 cm
- `2` — 3 a 4 cm
- `3` — ≥ 5 cm

### Apagamento

`apag`

- `0` — 0 a 30%
- `1` — 40 a 50%
- `2` — 60 a 70%
- `3` — ≥ 80%

### Altura da apresentação (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 ou 0
- `3` — +1 ou +2

### Consistência do colo

`cons`

- `0` — Firme
- `1` — Média
- `2` — Amolecida

### Posição do colo

`pos`

- `0` — Posterior
- `1` — Intermediária
- `2` — Anterior

## Edição do método

Bishop 1964:5 componentes 0–13; apagamento percentual, sem versão comprimento cervical

## Fórmula documentada

Soma de 5 itens do toque vaginal: dilatação (0 a 3), apagamento (0 a 3), altura da apresentação (0 a 3), consistência (0 a 2) e posição do colo (0 a 2). Total de 0 a 13.

## Limites e população

O Bishop clássico descreve preparo cervical pelos cinco componentes do exame e não autoriza, sozinho, indução do parto. O artigo de 1964 estudou contexto histórico de multíparas a partir de 36 semanas; isso não constitui indicação atual de indução eletiva nessa idade. A orientação institucional ACOG consultada exige avaliar indicações e contraindicações obstétricas e não realizar indução eletiva antes de 39 semanas. Esta versão usa apagamento cervical em porcentagem, não uma versão modificada baseada no comprimento cervical.

## Referências

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
