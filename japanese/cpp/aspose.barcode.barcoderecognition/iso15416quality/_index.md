---
title: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality クラス"
linktitle: "Iso15416Quality"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::Iso15416Quality クラス。C++ で 1 次元バーコードの ISO/IEC 15416 標準に従って計算されたバーコード品質グレードを格納します。"
type: docs
weight: 2200
url: /ja/cpp/aspose.barcode.barcoderecognition/iso15416quality/
---
## Iso15416Quality class


ISO/IEC 15416 標準に基づいて計算された 1D バーコードのバーコード品質等級を保存します。

```cpp
class Iso15416Quality : public System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Decodability](./get_decodability/)() const | バーとスペース幅の精度に基づくデコード可能性グレードを取得します。 |
| [get_Decode](./get_decode/)() const | リファレンスデコードアルゴリズムを使用してバーコードをデコードできるかどうかを示すデコードグレードを取得します。 |
| [get_Defects](./get_defects/)() const | バーとスペース内の反射率の不規則性に基づく欠陥グレードを取得します。 |
| [get_DetailedGrades](./get_detailedgrades/)() const | シンボロジー固有のチェックを含む追加の品質グレードを取得します。 |
| [get_Grade](./get_grade/)() const | ISO/IEC 15416 に基づく全体的なバーコード品質グレードを取得します。 |
| [get_MinimumEdgeContrast](./get_minimumedgecontrast/)() const | 隣接するバーとスペース間の最小の反射率差に基づく最小エッジコントラストグレードを取得します。 |
| [get_MinimumReflectance](./get_minimumreflectance/)() const | 最も暗いバーの反射率に基づく最小反射率グレードを取得します。 |
| [get_Modulation](./get_modulation/)() const | バーコード全体のエッジコントラストの均一性に基づく変調グレードを取得します。 |
| [get_SymbolContrast](./get_symbolcontrast/)() const | 最大と最小の反射率の差に基づいてシンボルのコントラスト等級を取得します。 |
## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
