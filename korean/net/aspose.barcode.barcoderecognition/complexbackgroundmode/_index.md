---
title: "열거형 ComplexBackgroundMode"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.ComplexBackgroundMode 열거형. 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다."
type: docs
weight: 200
url: /ko/net/aspose.barcode.barcoderecognition/complexbackgroundmode/
---
## ComplexBackgroundMode enumeration

컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다.

```csharp
public enum ComplexBackgroundMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 현재는 Disabled와 동일합니다. 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다. |
| Disabled | `1` | 컬러 이미지에서 컬러 바코드의 추가 인식을 비활성화합니다. |
| Enabled | `2` | 컬러 이미지에서 컬러 바코드의 추가 인식을 활성화합니다. |

## 예제

이 샘플은 ComplexBackground 모드를 사용하는 방법을 보여줍니다

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.ComplexBackground = ComplexBackgroundMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


