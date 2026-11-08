---
title: "metod"
linktitle: "get_QualitySettings"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.barcoderecognition/barcodereader/get_qualitysettings/
---
## BarCodeReader::get_QualitySettings method


[QualitySettings](../../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../../qualitysettings/) is NormalQuality.

```cpp
System::SharedPtr<Aspose::BarCode::BarCodeRecognition::QualitySettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_QualitySettings()
```

## Anmärkningar


[QualitySettings](../../qualitysettings/) to configure recognition quality and speed. 

Detta exempel visar hur man använder [QualitySettings](../../qualitysettings/) med [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //sätt högprestandaläge
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //normalkvalitetsläge är förinställt som standard
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //sätt högprestandaläge
   reader.QualitySettings = QualitySettings.HighPerformance;
   //sätt separata alternativ
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

## Se även

* Class [QualitySettings](../../qualitysettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
