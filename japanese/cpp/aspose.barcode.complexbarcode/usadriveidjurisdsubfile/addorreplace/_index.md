---
title: "メソッド"
linktitle: "AddOrReplace"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。DataElement を新規追加し、ElementID が既に存在する場合は置き換えます（C++）。"
type: docs
weight: 800
url: /ja/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/addorreplace/
---
## USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) method


ElementID が既に存在する場合、**DataElement** を新規追加または置き換えます。

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::SharedPtr<USADriveIdJurisdSubfile::DataElement> node)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ノード | System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\> | **DataElement** を追加 |

### ReturnValue

追加/置換されたデータ要素

## 関連項目

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
## USADriveIdJurisdSubfile::AddOrReplace(System::String, System::String) method


指定された識別子と値で新しい **DataElement** を追加し、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。

```cpp
System::SharedPtr<USADriveIdJurisdSubfile::DataElement> Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile::AddOrReplace(System::String id, System::String value)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ID | System::String | 管轄関連データ要素を一意に指定する 3 文字の識別子。 |
| 値 | System::String | データ要素に割り当てられたテキスト値。要素が既に存在する場合、この値は既存のものを上書きします。 |

### ReturnValue

コレクションに追加された、またはその場で更新された **DataElement** インスタンス。

## 関連項目

* Class [USADriveIdJurisdSubfile](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
