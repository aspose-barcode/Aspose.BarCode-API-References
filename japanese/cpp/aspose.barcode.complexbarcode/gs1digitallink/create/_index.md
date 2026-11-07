---
title: "メソッド"
linktitle: "Create"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド. C++ で GS1 codetext からすべての要素をコピーし、唯一利用可能なプライマリキーを選択して GS1 Digital Link を作成します。"
type: docs
weight: 2100
url: /ja/cpp/aspose.barcode.complexbarcode/gs1digitallink/create/
---
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>) method


GS1 コードテキストからすべての要素をコピーし、唯一利用可能なプライマリキーを選択して GS1 Digital Link を作成します。

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriStem | System::String | プライマリキーの前にある絶対的な HTTP または HTTPS URI プレフィックス。 |
| codetext | System::SharedPtr\<GS1Codetext\> | 要素がコピーされる GS1 codetext。 |

### ReturnValue

コピーされた要素を含むGS1デジタルリンクです。

## 関連項目

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## GS1DigitalLink::Create(System::String, System::SharedPtr\<GS1Codetext\>, System::String) method


GS1 コードテキストからすべての要素をコピーし、指定されたプライマリキーを使用して GS1 Digital Link を作成します。

```cpp
static System::SharedPtr<GS1DigitalLink> Aspose::BarCode::ComplexBarcode::GS1DigitalLink::Create(System::String uriStem, System::SharedPtr<GS1Codetext> codetext, System::String primaryApplicationIdentifier)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| uriStem | System::String | プライマリキーの前にある絶対的な HTTP または HTTPS URI プレフィックス。 |
| codetext | System::SharedPtr\<GS1Codetext\> | 要素がコピーされる GS1 codetext。 |
| primaryApplicationIdentifier | System::String | 主キー AI。 |

### ReturnValue

コピーされた要素を含むGS1デジタルリンクです。

## 関連項目

* Class [GS1DigitalLink](../)
* Class [GS1Codetext](../../gs1codetext/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
