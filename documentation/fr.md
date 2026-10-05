<!-- ELUCENIA technical documentation · indice-de-bishop · fr · no clinical/professional/rights approval -->

# Score de Bishop

[conditions, sources et autorisations](https://elucenia.org/fr/outils/indice-de-bishop)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Dilatation

`dil`

- `0` — Fermé
- `1` — 1 à 2 cm
- `2` — 3 à 4 cm
- `3` — ≥ 5 cm

### Effacement cervical

`apag`

- `0` — 0 à 30%
- `1` — 40 à 50%
- `2` — 60 à 70%
- `3` — ≥ 80%

### Hauteur de la présentation (De Lee)

`alt`

- `0` — −3
- `1` — −2
- `2` — −1 ou 0
- `3` — +1 ou +2

### Consistance du col

`cons`

- `0` — Ferme
- `1` — Moyenne
- `2` — Souple

### Position du col

`pos`

- `0` — Postérieur
- `1` — Intermédiaire
- `2` — Antérieur

## Édition de la méthode

Bishop 1964 : 5 composantes 0–13 ; effacement en %, pas version longueur cervicale

## Formule documentée

Somme de 5 items au toucher : dilatation (0–3), effacement (0–3), hauteur (0–3), consistance (0–2), position du col (0–2). Total 0–13.

## Limites et population

Le Bishop classique décrit la maturation cervicale à l’aide de cinq composantes de l’examen et n’autorise pas à lui seul le déclenchement du travail. L’article de 1964 portait sur une population historique de multipares à partir de 36 semaines ; cela ne constitue pas une indication actuelle de déclenchement électif à ce terme. L’orientation institutionnelle ACOG consultée exige d’évaluer les indications et contre-indications obstétricales et de ne pas pratiquer de déclenchement électif avant 39 semaines. Cette version utilise l’effacement cervical en pourcentage, et non une version modifiée fondée sur la longueur du col.

## Références

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
