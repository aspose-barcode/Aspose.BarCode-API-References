---
title: "method"
linktitle: "get_QualitySettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodereader/get_qualitysettings/
---
## BarCodeReader::get_QualitySettings method


[QualitySettings](../../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../../qualitysettings/) is NormalQuality.

```cpp
System::SharedPtr<Aspose::BarCode::BarCodeRecognition::QualitySettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_QualitySettings()
```

## Примечания


[QualitySettings](../../qualitysettings/) to configure recognition quality and speed. 

Этот пример показывает, как использовать [QualitySettings](../../qualitysettings/) с [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //установить режим высокой производительности
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //режим обычного качества установлен по умолчанию
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //установить режим высокой производительности
   reader.QualitySettings = QualitySettings.HighPerformance;
   //установить отдельные параметры
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

## См. также

* Class [QualitySettings](../../qualitysettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
