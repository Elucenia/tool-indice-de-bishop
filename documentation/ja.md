<!-- ELUCENIA technical documentation · indice-de-bishop · ja · no clinical/professional/rights approval -->

# Bishopスコア

[条件・出典・許諾](https://elucenia.org/ja/tools/indice-de-bishop)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 開大

`dil`

- `0` — 閉鎖
- `1` — 1 ～ 2 cm
- `2` — 3 ～ 4 cm
- `3` — ≥ 5 cm

### 子宮頸管の展退

`apag`

- `0` — 0 ～ 30%
- `1` — 40 ～ 50%
- `2` — 60 ～ 70%
- `3` — ≥ 80%

### 児頭下降度（De Lee）

`alt`

- `0` — −3
- `1` — −2
- `2` — −1または0
- `3` — +1または+2

### 子宮頸部の硬さ

`cons`

- `0` — 硬い
- `1` — 中等度
- `2` — 軟らかい

### 子宮頸部の位置

`pos`

- `0` — 後方
- `1` — 中間
- `2` — 前方

## 方法の版

Bishop 1964：5項目0–13；展退率、頸管長版ではない

## 記載された計算式

内診5項目合計：開大（0–3）、展退（0–3）、下降度（0–3）、硬度（0–2）、頸管位置（0–2）。計0–13。

## 限界・対象集団

古典的Bishopは五つの診察項目で子宮頸管の成熟度を示し、それだけで分娩誘発を認めるものではありません。1964年の論文は妊娠36週以降の経産婦という歴史的背景を対象にしており、その妊娠週数での現在の選択的分娩誘発の適応を意味しません。参照したACOGの機関情報は、産科の適応・禁忌を評価し、39週未満では選択的誘発を行わないことを求めています。この版は頸管展退を百分率で用い、頸管長を用いる修正版ではありません。

## 参考文献

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
