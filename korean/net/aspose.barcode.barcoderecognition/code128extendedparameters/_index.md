---
title: "Class Code128ExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.Code128ExtendedParameters 클래스. 인식된 Code128 바코드의 특수 데이터를 저장합니다"
type: docs
weight: 180
url: /ko/net/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class

Code128 인식 바코드의 특수 데이터를 저장합니다.

인식된 바코드의 영역 및 바코드 각도를 나타냅니다.

```csharp
public sealed class Code128ExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Code128DataPortions](../../aspose.barcode.barcoderecognition/code128extendedparameters/code128dataportions/) { get; } | 인식된 Code128 바코드의 [`Code128DataPortion`](../code128dataportion/) 배열을 가져옵니다 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/code128extendedparameters/equals/)(object) | 이 인스턴스가 지정된 `Code128ExtendedParameters` 값과 동일한지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/code128extendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/code128extendedparameters/tostring/)() | 이 `Code128ExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_equality/) | 첫 번째 `Code128ExtendedParameters` 값이 두 번째와 동일한지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/code128extendedparameters/op_inequality/) | 첫 번째 `Code128ExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 code128 원시 값을 가져오는 방법을 보여줍니다

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


