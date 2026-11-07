---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile クラス"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdJurisdSubfile クラス. C++ における USA DL の管轄特有フィールド用クラス。"
type: docs
weight: 3100
url: /ja/cpp/aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
## USADriveIdJurisdSubfile class


USA DLの管轄別フィールド用クラスです。

```cpp
class USADriveIdJurisdSubfile : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [AddOrReplace](./addorreplace/)(System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | ElementID が既に存在する場合、**DataElement** を新規追加または置き換えます。 |
| [AddOrReplace](./addorreplace/)(System::String, System::String) | 指定された識別子と値で新しい **DataElement** を追加し、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。 |
| [Clear](./clear/)() | すべてのデータ要素をクリアします |
| [FindDataElement](./finddataelement/)(System::String, bool) | 3文字の ID でデータ要素を検索します |
| [get_Count](./get_count/)() | データ要素の数を返します |
| [idx_get](./idx_get/)(System::String) | 3文字の要素 ID によるインデックス付け |
| [idx_get](./idx_get/)(int32_t) | インデックス番号によるインデックス付け |
| [idx_set](./idx_set/)(System::String, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 3文字の要素 ID によるインデックス付け |
| [idx_set](./idx_set/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | インデックス番号によるインデックス付け |
| [Insert](./insert/)(int32_t, System::SharedPtr\<USADriveIdJurisdSubfile::DataElement\>) | 指定されたインデックスに **DataElement** を挿入します。同じ ElementID の **DataElement** が既に存在する場合は置き換えられます。 |
| [RemoveAt](./removeat/)(int32_t) | インデックス位置の要素を削除しようとします |
| [RemoveAt](./removeat/)(System::String) | 3文字の ID を持つ要素を削除しようとします |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/)() |  |
## 関連項目

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
