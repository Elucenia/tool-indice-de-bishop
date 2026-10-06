<!-- ELUCENIA technical documentation · indice-de-bishop · zh · no clinical/professional/rights approval -->

# Bishop 评分

[条件、来源与许可](https://elucenia.org/zh/tools/indice-de-bishop)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 扩张

`dil`

- `0` — 闭合
- `1` — 1 至 2 cm
- `2` — 3 至 4 cm
- `3` — ≥ 5 cm

### 宫颈消退

`apag`

- `0` — 0 至 30%
- `1` — 40 至 50%
- `2` — 60 至 70%
- `3` — ≥ 80%

### 胎先露位置（De Lee）

`alt`

- `0` — −3
- `1` — −2
- `2` — −1或0
- `3` — +1或+2

### 宫颈质地

`cons`

- `0` — 硬
- `1` — 中等
- `2` — 软

### 宫颈位置

`pos`

- `0` — 后位
- `1` — 中间位
- `2` — 前位

## 方法版本

Bishop 1964：5项0–13；百分比消退，非宫颈长度版

## 已记录的公式

阴道检查5项之和：扩张（0–3）、消退（0–3）、先露高低（0–3）、质地（0–2）、宫颈位置（0–2）。总分0–13。

## 限制与适用人群

经典Bishop通过五项检查要素描述宫颈成熟度，不能单独作为引产授权依据。1964年的文章研究的是从孕36周起的历史经产妇人群，这不构成目前在该孕周择期引产的指征。所查阅的ACOG机构指导要求评估产科指征与禁忌证，不在39周前进行择期引产。本版本使用百分比表示宫颈消退程度，而非基于宫颈长度的改良版本。

## 参考文献

- [Bishop EH. Pelvic scoring for elective induction. Obstet Gynecol, 1964.](https://pubmed.ncbi.nlm.nih.gov/14199536/)

- [American College of Obstetricians and Gynecologists. ACOG Practice Bulletin No. 107: Induction of Labor. Obstet Gynecol, 2009.](https://doi.org/10.1097/AOG.0b013e3181b48ef5)

- [Bishop1964](https://epp.evidencio.com/uploads/files/models/files/1293/0bf17b-Bishop%20EH%2C%201964.pdf)

- [ACOG patient FAQ,current retrieval2026-10-04](https://www.acog.org/womens-health/faqs/labor-induction)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

宫颈条件不佳（≤ 6）：在使用催产素前进行宫颈准备

准备方法：米索前列醇、Foley导管或地诺前列酮，依据科室方案和子宫瘢痕。


### 2

宫颈中等（7到8）

引产后阴道分娩的可能性低于宫颈条件良好者；应个体化进行宫颈准备。


### 3

宫颈条件良好（> 8）：阴道分娩的可能性与自然临产相似

可使用催产素和/或人工破膜进行引产。


### 4

宫颈条件良好（> 8）：阴道分娩的可能性与自然临产相似

可使用催产素和/或人工破膜进行引产。

