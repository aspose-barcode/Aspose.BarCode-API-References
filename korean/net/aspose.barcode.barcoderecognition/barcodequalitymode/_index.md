---
title: "BarcodeQualityMode 열거형"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.BarcodeQualityMode 열거형. 선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요하여 인식 속도가 느려집니다."
type: docs
weight: 110
url: /ko/net/aspose.barcode.barcoderecognition/barcodequalitymode/
---
## BarcodeQualityMode enumeration

선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 더 많은 복잡한 메서드가 필요하여 인식 속도가 느려집니다.

```csharp
public enum BarcodeQualityMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| High | `0` | 고품질 바코드에 대한 인식 메서드를 활성화합니다. |
| Normal | `1` | 일반(보통) 품질 바코드에 대한 인식 메서드를 활성화합니다. |
| Low | `2` | 저품질 바코드에 대한 인식 메서드를 활성화합니다. |

## 예제

이 샘플은 BarcodeQuality 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


