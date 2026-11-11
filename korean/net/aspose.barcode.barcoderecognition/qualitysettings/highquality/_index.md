---
title: "QualitySettings.HighQuality"
second_title: "Aspose.BarCode for .NET API 참조"
description: "QualitySettings 속성. HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 손상된 바코드를 높은 정확도로 감지할 수 있습니다."
type: docs
weight: 20
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/highquality/
---
## QualitySettings.HighQuality property

HighQuality 인식 품질 프리셋. 이 프리셋은 저품질 바코드를 위해 개발되었습니다. 심하게 손상된 바코드도 감지할 수 있습니다.

```csharp
public static QualitySettings HighQuality { get; }
```

### Property Value

HighQuality 인식 품질 프리셋.

## 예제

이 샘플은 HighQuality 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


