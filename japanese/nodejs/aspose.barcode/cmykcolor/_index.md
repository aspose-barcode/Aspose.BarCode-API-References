---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "CMYK カラーのクラス。"
type: docs
weight: 180
url: /ja/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

CMYK カラー用のクラスです。null インスタンスは CMYK が使用されていないことを意味し、デフォルトの RGB カラーが使用されます。

```js
new CMYKColor(c, m, y, k)
```

CMYK 値から CMYKColor クラスの新しいインスタンスを初期化します。CMYK 値は 0〜100 の範囲であることが期待されます。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | 数値 | – シアン値 [0, 100] |
| m | 数値 | – マゼンタ値 [0, 100] |
| y | 数値 | – イエロー値 [0, 100] |
| k | 数値 | – ブラック値 [0, 100] |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | 形式 "C_M_Y_K" の CMYK 文字列を解析し、CMYKColor インスタンスに変換します。 |
| [formatCMYK()](#formatcmyk) | この CMYKColor を文字列 "C_M_Y_K" にフォーマットし、各内部コンポーネント (0–1) を 100 倍して丸めます。 |
| [toString()](#tostring) | オプション: 人間が読みやすい表現。 |

### parseCMYK(str) (static) {#parsecmyk}

形式 "C_M_Y_K" の CMYK 文字列を解析し、CMYKColor インスタンスに変換します。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | 文字列 | – "30_100_0_30" のような文字列 |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

この CMYKColor を文字列 "C_M_Y_K" にフォーマットし、各内部コンポーネント (0–1) を 100 倍して丸めます。

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

オプション: 人間が読みやすい表現。
