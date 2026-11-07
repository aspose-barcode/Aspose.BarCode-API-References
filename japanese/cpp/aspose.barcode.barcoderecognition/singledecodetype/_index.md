---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType クラス"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType クラス。シングルデコードタイプ。C++ でインスタンスを取得するには decode type を参照してください。"
type: docs
weight: 3200
url: /ja/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


単一デコードタイプです。インスタンスを取得するには decode type を参照してください。

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | このインスタンスが指定されたリストに含まれているかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | このインスタンスが指定された [SingleDecodeType](./) の値と等しいかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | 指定された [MultiDecodeType](../multidecodetype/) コレクションがこのデコードタイプのみを含むかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | このインスタンスが指定された [SingleDecodeType](./) の値と等しいかどうかを示す値を返します。 |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | このインスタンスが指定された [BaseDecodeType](../basedecodetype/) の値と等しいかどうかを示す値を返します。 |
| [get_TypeIndex](./get_typeindex/)() const | デコードタイプのインデックスを取得します |
| [get_TypeName](./get_typename/)() const | デコードタイプの名前を取得します |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| [GetString](./getstring/)() | [SingleDecodeType](./) のインスタンスを同等の文字列表現に変換します。文字列形式は "Index:-1; Name:None" です。 |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | [SingleDecodeType](./) のインスタンスを同等の文字列表現に変換します。文字列形式は "Index:-1; Name:None" です。 |
| static [Parse](./parse/)(System::String) | [SingleDecodeType](./) の名前の文字列表現をインスタンスに変換します。 |
| [ToString](./tostring/)() const override | 指定された [SingleDecodeType](./) の名前を文字列として返します。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | [SingleDecodeType](./) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | [BaseDecodeType](../basedecodetype/) の文字列表現を具体的な型を判定した上でインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## 備考


このサンプルはシングルデコードタイプのインスタンスを取得する方法を示しています。
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## 関連項目

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
