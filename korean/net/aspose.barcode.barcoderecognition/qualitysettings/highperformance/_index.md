---
title: "QualitySettings.HighPerformance"
second_title: "Aspose.BarCode for .NET API 참조"
description: "QualitySettings 속성. HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식한다."
type: docs
weight: 10
url: /ko/net/aspose.barcode.barcoderecognition/qualitysettings/highperformance/
---
## QualitySettings.HighPerformance property

HighPerformance 인식 품질 프리셋. 이 모드에서는 고품질 바코드를 잘 인식합니다.

```csharp
public static QualitySettings HighPerformance { get; }
```

### Property Value

HighPerformance 인식 품질 프리셋.

## 예제

이 샘플은 HighPerformance 모드를 사용하는 방법을 보여준다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* class [QualitySettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


