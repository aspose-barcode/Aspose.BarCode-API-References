---
title: "metode"
linktitle: "get_QualitySettings"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "metode. QualitySettings memungkinkan mengonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality di C++."
type: docs
weight: 700
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/get_qualitysettings/
---
## BarCodeReader::get_QualitySettings method


[QualitySettings](../../qualitysettings/) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](../../qualitysettings/) by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of [QualitySettings](../../qualitysettings/) is NormalQuality.

```cpp
System::SharedPtr<Aspose::BarCode::BarCodeRecognition::QualitySettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_QualitySettings()
```

## Catatan


[QualitySettings](../../qualitysettings/) to configure recognition quality and speed. 

Contoh ini menunjukkan cara menggunakan [QualitySettings](../../qualitysettings/) dengan [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //atur mode kinerja tinggi
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //mode kualitas normal diatur secara default
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //atur mode kinerja tinggi
   reader.QualitySettings = QualitySettings.HighPerformance;
   //atur opsi terpisah
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

## Lihat Juga

* Class [QualitySettings](../../qualitysettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
