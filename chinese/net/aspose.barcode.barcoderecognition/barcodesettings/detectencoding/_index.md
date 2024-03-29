---
title: DetectEncoding
second_title: Aspose.BarCode for .NET API 参考
description: 强制引擎检测 Unicode 代码集的代码文本编码的标志默认值为真
type: docs
weight: 30
url: /zh/net/aspose.barcode.barcoderecognition/barcodesettings/detectencoding/
---
## BarcodeSettings.DetectEncoding property

强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为真。

```csharp
public bool DetectEncoding { get; set; }
```

### 适当的价值

强制引擎检测 Unicode 代码集的代码文本编码的标志

### 例子

此示例显示如何在启用 DetectEncoding 的情况下动态检测文本编码

```csharp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
    {
        generator.Parameters.Barcode.QR.CodeTextEncoding = Encoding.UTF8;
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //检测 Unicode 代码集的编码是否启用
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //检测编码被禁用
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.Parameters.Barcode.QR.CodeTextEncoding = System.Text.Encoding.UTF8
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    '检测启用了 Unicode 代码集的编码
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    '检测编码被禁用
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```

### 也可以看看

* class [BarcodeSettings](../../barcodesettings)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodesettings)
* 部件 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
