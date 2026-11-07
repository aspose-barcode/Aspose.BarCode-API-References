---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType クラス"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType クラス。C++ における MultiDecodeType と SingleDecodeType の基底クラスです。"
type: docs
weight: 900
url: /ja/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


[MultiDecodeType](../multidecodetype/) と [SingleDecodeType](../singledecodetype/) の基底クラスです。

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | 指定されたデコードタイプのいずれかが含まれているかどうかを判定します。 |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | このインスタンスが指定された [SingleDecodeType](../singledecodetype/) の値と等しいかどうかを示す値を返します。 |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | このインスタンスが指定された [MultiDecodeType](../multidecodetype/) の値と等しいかどうかを示す値を返します。 |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | このインスタンスが指定された [BaseDecodeType](./) の値と等しいかどうかを示す値を返します。 |
| [GetHashCode](./gethashcode/)() const override | このインスタンスのハッシュコードを返します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | 文字列表現の [SingleDecodeType](../singledecodetype/) をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | [MultiDecodeType](../multidecodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | 具体的な型を判定した上で、文字列表現の [BaseDecodeType](./) をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |
## 備考


このサンプルは、[BaseDecodeType](./) を [SingleDecodeType](../singledecodetype/) および [MultiDecodeType](../multidecodetype/) と共に使用する方法を示しています。
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## 関連項目

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
