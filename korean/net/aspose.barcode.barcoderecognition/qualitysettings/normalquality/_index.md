---
title: "QualitySettings.NormalQuality"
second_title: "Aspose.BarCode for .NET API 참조"
description: "QualitySettings 속성. NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다."
type: docs
weight: 40
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/normalquality/
---
## QualitySettings.NormalQuality property

NormalQuality 인식 품질 프리셋. 대부분의 바코드에 적합합니다.

```csharp
public static QualitySettings NormalQuality { get; }
```

### Property Value

NormalQuality 인식 품질 프리셋.

## 예제

이 샘플은 NormalQuality 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.NormalQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


