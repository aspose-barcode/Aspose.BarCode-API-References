---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType クラス"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType クラス。C++ における複合デコード型です。"
type: docs
weight: 2600
url: /ja/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


複合デコードタイプです。

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](../singledecodetype/) をもう一つ [MultiDecodeType](./) に追加します。 |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | これがバーコードタイプのすべてのタイプを含んでいるか確認します。 |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | いずれかのタイプを含んでいるか |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | このインスタンスが指定された [MultiDecodeType](./) の値と等しいかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | このデコードタイプコレクションが指定された [SingleDecodeType](../singledecodetype/) の値のみを含むかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [MultiDecodeType](./) の値と等しいかどうかを示す値を返します。 |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | このインスタンスが指定された [BaseDecodeType](../basedecodetype/) の値と等しいかどうかを示す値を返します。 |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | [MultiDecodeType](./) から [SingleDecodeType](../singledecodetype/) を除外し、新しい [MultiDecodeType](./) インスタンスを返します。 |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | 単一タイプの数を返します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetSingleTypes](./getsingletypes/)() | 単一タイプのリストを表します。 |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | [MultiDecodeType](./) クラスの新しいインスタンスを初期化します。 |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | [MultiDecodeType](./) クラスの新しいインスタンスを初期化します。 |
| [ToString](./tostring/)() const override | [MultiDecodeType](./) を文字列として表すオーバーライドされたメソッドです。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](./) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 文字列表現の [SingleDecodeType](../singledecodetype/) をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) の文字列表現を具体的な型を判定した上でインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## 備考


このサンプルは、[SingleDecodeType](../singledecodetype/) と MultiDecode タイプを組み合わせた複合 MultiDecode タイプの作成方法を示しています。
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## 関連項目

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
