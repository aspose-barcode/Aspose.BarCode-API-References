---
title: "BarCodeReader.Timeout"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 属性。获取或设置识别过程的超时时间（毫秒）"
type: docs
weight: 80
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/timeout/
---
## BarCodeReader.Timeout property

获取或设置识别过程的超时时间（毫秒）。

```csharp
public int Timeout { get; set; }
```

### Property Value

超时。

## 示例

此示例展示了如何在大图像上避免识别挂起和超时。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### 另见

* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


