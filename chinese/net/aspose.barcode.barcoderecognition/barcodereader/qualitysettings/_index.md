---
title: "BarCodeReader.QualitySettings"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 属性。QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设 HighPerformance、NormalQuality、HighQuality、MaxBarCodes 快速设置 QualitySettings，或手动配置各个选项。QualitySettings 的默认值为 NormalQuality。"
type: docs
weight: 70
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或者手动配置各个选项。QualitySettings 的默认值为 NormalQuality。

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

用于配置识别质量和速度的 QualitySettings。

## 示例

此示例展示了如何将 QualitySettings 与 BarCodeReader 一起使用

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //设置高性能模式
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //默认设置为普通质量模式
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //设置高性能模式
   reader.QualitySettings = QualitySettings.HighPerformance;
   //设置单独的选项
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'set high performance mode
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    'normal quality mode is set by default
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
   'set high performance mode
   reader.QualitySettings = QualitySettings.HighPerformance
   'set separate options
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### 另见

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


