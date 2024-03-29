---
title: BarCodeRegionParameters
second_title: Aspose.BarCode for.NETAPIリファレンス
description: 認識されたバーコードの領域とバーコードの角度を表します
type: docs
weight: 80
url: /ja/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

認識されたバーコードの領域とバーコードの角度を表します

```csharp
public sealed class BarCodeRegionParameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | バーコードの角度を取得します (0 ～ 360)。 |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | 取得Points 配列境界バーコード領域 |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | 取得[`Quadrangle`](../quadrangle/)境界バーコード領域 |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | 取得Rectangle境界バーコード領域 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | このインスタンスが指定された値と等しいかどうかを示す値を返します`BarCodeRegionParameters`値. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | これの人間が読める文字列表現を返します`BarCodeRegionParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | 最初かどうかを示す値を返します。`BarCodeRegionParameters`値は秒に等しい. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | 最初の`BarCodeRegionParameters`値が秒と異なります. |

### 例

このサンプルは、バーコードの角度と境界四角形の値を取得する方法を示しています

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### 関連項目

* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
