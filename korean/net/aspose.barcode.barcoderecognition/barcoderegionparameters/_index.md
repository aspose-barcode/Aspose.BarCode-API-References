---
title: "클래스 BarCodeRegionParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters 클래스. 인식된 바코드 영역 및 바코드 각도를 나타냅니다."
type: docs
weight: 90
url: /ko/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

인식된 바코드의 영역 및 바코드 각도를 나타냅니다.

```csharp
public sealed class BarCodeRegionParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | 바코드의 각도(0-360)를 가져옵니다. |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | 바코드 영역을 둘러싼 Points 배열을 가져옵니다. |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | 바코드 영역을 둘러싼 [`Quadrangle`](../quadrangle/)을 가져옵니다. |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | 바코드 영역을 둘러싼 Rectangle을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | 이 인스턴스가 지정된 `BarCodeRegionParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | 이 `BarCodeRegionParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | 첫 번째 `BarCodeRegionParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | 첫 번째 `BarCodeRegionParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 바코드 각도와 둘러싼 사각형 값을 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


