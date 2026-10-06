<!-- ELUCENIA technical documentation · indice-de-bishop · it · no clinical/professional/rights approval -->

# Indice di Bishop

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/indice-de-bishop)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Dilatazione

`dil`

- `0` — Chiuso
- `1` — 1 a 2 cm
- `2` — 3 a 4 cm
- `3` — ≥ 5 cm

### Appianamento cervicale

`apag`

- `0` — 0 a 30%
- `1` — 40 a 50%
- `2` — 60 a 70%
- `3` — ≥ 80%

### Livello della parte presentata (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 o 0
- `3` — +1 o +2

### Consistenza cervicale

`cons`

- `0` — Dura
- `1` — Media
- `2` — Morbida

### Posizione cervicale

`pos`

- `0` — Posteriore
- `1` — Intermedia
- `2` — Anteriore

## Edizione del metodo

Bishop 1964: 5 componenti 0–13; appianamento percentuale, non versione lunghezza cervicale

## Formula documentata

Somma di 5 item vaginali: dilatazione (0–3), appianamento (0–3), stazione (0–3), consistenza (0–2), posizione cervicale (0–2). Totale 0–13.

## Limiti e popolazione

Il Bishop classico descrive la maturazione cervicale mediante cinque componenti dell’esame e non autorizza da solo l’induzione del parto. L’articolo del 1964 studiava un contesto storico di pluripare a partire da 36 settimane; ciò non costituisce un’indicazione attuale all’induzione elettiva a quell’età gestazionale. L’orientamento istituzionale ACOG consultato richiede di valutare indicazioni e controindicazioni ostetriche e di non effettuare induzione elettiva prima di 39 settimane. Questa versione usa l’appianamento cervicale in percentuale, non una versione modificata basata sulla lunghezza cervicale.

## Riferimenti

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Cervice sfavorevole (≤ 6): indicare la preparazione cervicale prima dell’ossitocina

Metodi di preparazione: misoprostolo, catetere di Foley o dinoprostone, secondo il protocollo del servizio e la cicatrice uterina.


### 2

Cervice intermedia (7 a 8)

La probabilità di parto vaginale dopo induzione è inferiore rispetto a quella con cervice favorevole; individualizzare la preparazione cervicale.


### 3

Cervice favorevole (> 8): probabilità di parto vaginale simile a quella del travaglio spontaneo

Può essere indotta con ossitocina e/o amniotomia.


### 4

Cervice favorevole (> 8): probabilità di parto vaginale simile a quella del travaglio spontaneo

Può essere indotta con ossitocina e/o amniotomia.

