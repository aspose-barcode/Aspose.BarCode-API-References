---
title: "BarCodeReader.BarCodeReadType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 属性。获取或设置用于识别的条形码解码类型。必须在调用 ReadBarCodes 之前设置。"
type: docs
weight: 30
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/barcodereadtype/
---
## BarCodeReader.BarCodeReadType property

获取或设置用于识别的条形码解码类型。必须在调用 [`ReadBarCodes`](../readbarcodes/) 之前设置。

```csharp
public BaseDecodeType BarCodeReadType { get; set; }
```

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.BarCodeReadType = new MultiDecodeType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString());
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.BarCodeReadType = New MultiDecodeType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
    Console.WriteLine("BarCodeReadType: " + reader.BarCodeReadType.ToString())
End Using
```

### 另见

* class [BaseDecodeType](../../basedecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


