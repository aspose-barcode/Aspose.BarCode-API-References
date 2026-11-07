---
title: "メソッド"
linktitle: "挿入"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. 指定された DataElement を指定されたインデックスに挿入します。同じ ElementID を持つ DataElement が既に存在する場合、C++ で置き換えられます。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/insert/
---
## USADriveIdJurisdSubfile::Insert method


指定されたインデックスに **DataElement** を挿入します。同じ ElementID の **DataElement** が既に存在する場合は置き換えられます。

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::Insert(int32_t index, System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| インデックス | int32_t | 要素を挿入すべきゼロベースのインデックス。 |
| ノード | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | 対象位置に挿入または置き換える **DataElement** インスタンスです。 |

### ReturnValue

既存のエントリを置き換えるために挿入または使用された **DataElement** です。

## 関連項目

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
