---
title: "DataBarExtendedParameters 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters 클래스. 인식된 바코드의 DataBar 추가 정보를 저장합니다."
type: docs
weight: 210
url: /ko/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

인식된 바코드의 DataBar 추가 정보를 저장합니다.

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | DataBar 2D 복합 구성 요소 플래그를 가져옵니다. 기본값은 false입니다. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | 이 인스턴스가 지정된 `DataBarExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | 이 `DataBarExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | 첫 번째 `DataBarExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | 첫 번째 `DataBarExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 DataBar 추가 정보를 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


