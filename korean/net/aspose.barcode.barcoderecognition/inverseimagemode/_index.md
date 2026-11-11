---
title: "Enum InverseImageMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.InverseImageMode enum. 색상 밝기가 반전된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드"
type: docs
weight: 270
url: /ko/net/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enumeration

색상 반전(휘도)된 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다.

```csharp
public enum InverseImageMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | QR 코드 제외 모든 바코드 유형에 대해 반전 이미지에서 바코드의 추가 인식을 비활성화합니다. |
| Disabled | `1` | 반전 이미지에서 바코드의 추가 인식을 비활성화합니다. |
| Enabled | `2` | 반전 이미지에서 바코드의 추가 인식을 활성화합니다 |

## 예제

이 샘플은 InverseImage 모드를 사용하는 방법을 보여줍니다

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


