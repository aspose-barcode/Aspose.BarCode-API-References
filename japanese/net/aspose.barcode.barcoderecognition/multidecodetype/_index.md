---
title: "クラス MultiDecodeType"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType クラス。複合デコードタイプ"
type: docs
weight: 320
url: /ja/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

複合デコードタイプです。

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | `MultiDecodeType` クラスの新しいインスタンスを初期化します。 |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | `MultiDecodeType` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | 単一タイプの数を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | MultiDecodeType にもう1つの [`SingleDecodeType`](../singledecodetype/) を追加します。 |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | これがすべてのバーコードタイプを含んでいるか確認します。 |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | いずれかのタイプが含まれているか |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | このインスタンスが指定された [`BaseDecodeType`](../basedecodetype/) の値と等しいかどうかを示す値を返します。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | このインスタンスが指定された `MultiDecodeType` の値と等しいかどうかを示す値を返します。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | このインスタンスが指定された `MultiDecodeType` の値と等しいかどうかを示す値を返します。 |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | このデコードタイプコレクションが指定された [`SingleDecodeType`](../singledecodetype/) の値のみを含むかどうかを示す値を返します。 |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | `MultiDecodeType` から [`SingleDecodeType`](../singledecodetype/) を除外し、新しい MultiDecodeType インスタンスを返します。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | このインスタンスのハッシュコードを返します。 |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | 単一タイプのリストを表します。 |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | MultiDecodeType を文字列として表すオーバーライドされたメソッドです。 |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | MultiDecodeType の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。 |

## 例

このサンプルは、SingleDecodeType と MultiDecode タイプを組み合わせた複合 MultiDecode タイプの作成方法を示しています。

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### 関連項目

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


