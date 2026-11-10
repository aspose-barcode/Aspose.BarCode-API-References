---
title: "BarCodeReader.SetBarCodeReadType"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 方法。设置用于识别的 SingleDecodeType 类型数组。必须在调用 ReadBarCodes 方法之前调用。"
type: docs
weight: 130
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader.SetBarCodeReadType method

设置用于识别的 [`SingleDecodeType`](../../singledecodetype/) 类型数组。必须在调用 ReadBarCodes() 方法之前调用。

```csharp
public void SetBarCodeReadType(params SingleDecodeType[] barcodeTypes)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| barcodeTypes | SingleDecodeType[] | 要读取的 [`SingleDecodeType`](../../singledecodetype/) 类型数组。 |

## 示例

此示例展示了如何检测 Code39 和 Code128 条形码。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [SingleDecodeType](../../singledecodetype/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


