---
title: "BarCodeReader.QualitySettings"
second_title: "Aspose.BarCode for .NET API 참조"
description: "BarCodeReader 속성. QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있다. HighPerformance, NormalQuality, HighQuality, MaxBarCodes와 같은 내장 프리셋으로 QualitySettings를 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있다. QualitySettings의 기본값은 NormalQuality이다."
type: docs
weight: 70
url: /ko/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings는 인식 품질과 속도를 수동으로 구성할 수 있게 합니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 QualitySettings를 설정하거나 별도의 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

```csharp
public QualitySettings QualitySettings { get; set; }
```

### Property Value

인식 품질과 속도를 구성하기 위한 QualitySettings.

## 예제

이 샘플은 BarCodeReader와 함께 QualitySettings를 사용하는 방법을 보여줍니다

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //고성능 모드 설정
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //기본적으로 일반 품질 모드가 설정됩니다.
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
   //고성능 모드 설정
   reader.QualitySettings = QualitySettings.HighPerformance;
   //개별 옵션 설정
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

### 또 보기

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


