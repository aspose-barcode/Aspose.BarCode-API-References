---
title: "विधि"
linktitle: "set_QualitySettings"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "मेथड। QualitySettings आपको पहचान की गुणवत्ता और गति को मैन्युअली कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes द्वारा जल्दी से QualitySettings सेट कर सकते हैं या आप अलग विकल्पों को मैन्युअली कॉन्फ़िगर कर सकते हैं। C++ में QualitySettings का डिफ़ॉल्ट मान NormalQuality है।"
type: docs
weight: 800
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/set_qualitysettings/
---
## BarCodeReader::set_QualitySettings method


[QualitySettings](../../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../../qualitysettings/) is NormalQuality.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_QualitySettings(System::SharedPtr<Aspose::BarCode::BarCodeRecognition::QualitySettings> value)
```

## टिप्पणियाँ


[QualitySettings](../../qualitysettings/) to configure recognition quality and speed. 

यह उदाहरण दिखाता है कि [QualitySettings](../../qualitysettings/) को [BarCodeReader](../) के साथ कैसे उपयोग करें।
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //उच्च प्रदर्शन मोड सेट करें
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //डिफ़ॉल्ट रूप से सामान्य गुणवत्ता मोड सेट है
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //उच्च प्रदर्शन मोड सेट करें
   reader.QualitySettings = QualitySettings.HighPerformance;
   //अलग विकल्प सेट करें
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

## और देखें

* Class [QualitySettings](../../qualitysettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
