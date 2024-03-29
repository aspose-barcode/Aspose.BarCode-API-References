---
title: OneDExtendedParameters
second_title: Aspose.BarCode for.NETAPIリファレンス
description: 別のコードテキストやチェックサムなど1D 認識バーコードの特別なデータを格納します
type: docs
weight: 230
url: /ja/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

別のコードテキストやチェックサムなど、1D 認識バーコードの特別なデータを格納します

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | 1D バーコードのチェックサムを取得します。 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | すべてのパラメータがデフォルト値のみを持つかどうかをテストします |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | チェックサムなしで 1D バーコードのコードテキストを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | このインスタンスが指定された値と等しいかどうかを示す値を返します`OneDExtendedParameters`値. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | このインスタンスのハッシュ コードを返します。 |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | これの人間が読める文字列表現を返します`OneDExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | 最初かどうかを示す値を返します。`OneDExtendedParameters`値は秒に等しい. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | 最初の`OneDExtendedParameters`値が秒と異なります. |

### 例

このサンプルは、1D バーコード値とチェックサムを取得する方法を示しています

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### 関連項目

* class [BaseExtendedParameters](../baseextendedparameters/)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
