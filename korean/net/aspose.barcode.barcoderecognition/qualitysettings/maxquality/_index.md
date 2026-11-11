---
title: "QualitySettings.MaxQuality"
second_title: "Aspose.BarCode for .NET API 참조"
description: "QualitySettings 속성. MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다."
type: docs
weight: 30
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/maxquality/
---
## QualitySettings.MaxQuality property

MaxQuality 인식 품질 프리셋. 이 프리셋은 잘못된 바코드까지 모든 가능한 바코드를 인식하도록 개발되었습니다.

```csharp
public static QualitySettings MaxQuality { get; }
```

### Property Value

MaxQuality 인식 품질 프리셋.

## 예제

이 샘플은 MaxQuality 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.MaxQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


