---
title: "method"
linktitle: "set_QualitySettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: " method. QualitySettings 允许手动配置识别质量和速度。您可以通过内置预设快速设置 QualitySettings：HighPerformance、NormalQuality、HighQuality、MaxBarCodes，或者手动配置各个选项。QualitySettings 的默认值在 C++ 中为 NormalQuality。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/set_qualitysettings/
---
## BarCodeReader::set_QualitySettings method


[QualitySettings](../../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../../qualitysettings/) is NormalQuality.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_QualitySettings(System::SharedPtr<Aspose::BarCode::BarCodeRecognition::QualitySettings> value)
```

## 备注


[QualitySettings](../../qualitysettings/) to configure recognition quality and speed. 

此示例展示了如何将 [QualitySettings](../../qualitysettings/) 与 [BarCodeReader](../) 一起使用。
```cpp
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

## 另见

* Class [QualitySettings](../../qualitysettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
