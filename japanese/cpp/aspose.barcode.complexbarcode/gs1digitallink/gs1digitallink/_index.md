---
title: "constructor"
linktitle: "GS1DigitalLink"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "コンストラクタ。指定された URI ステムで空の GS1 デジタルリンクを初期化します。C++ でプライマリキー候補がちょうど1つ存在する場合、プライマリキーは自動的に選択されます。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.complexbarcode/gs1digitallink/gs1digitallink/
---
## GS1DigitalLink::GS1DigitalLink(System::String) constructor


指定された URI ステムで空の GS1 デジタルリンクを初期化します。プライマリキーは、プライマリキー候補が正確に1つ存在する場合に自動的に選択されます。

```cpp
Aspose::BarCode::ComplexBarcode::GS1DigitalLink::GS1DigitalLink(System::String uriStem)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriStem | System::String | プライマリキーの前にある絶対的な HTTP または HTTPS URI プレフィックス。 |

## 関連項目

* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::GS1DigitalLink(System::String, System::String) constructor


指定された URI ステムとプライマリキーで空の GS1 デジタルリンクを初期化します。

```cpp
Aspose::BarCode::ComplexBarcode::GS1DigitalLink::GS1DigitalLink(System::String uriStem, System::String primaryApplicationIdentifier)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriStem | System::String | プライマリキーの前にある絶対的な HTTP または HTTPS URI プレフィックス。 |
| primaryApplicationIdentifier | System::String | プライマリキー AI、または自動選択の場合は null。 |

## 関連項目

* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
