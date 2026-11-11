---
title: "클래스 OneDExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.OneDExtendedParameters 클래스. 별도의 코드텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다."
type: docs
weight: 330
url: /ko/net/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class

분리된 코드 텍스트와 체크섬과 같은 1D 인식 바코드의 특수 데이터를 저장합니다.

```csharp
public sealed class OneDExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CheckSum](../../aspose.barcode.barcoderecognition/onedextendedparameters/checksum/) { get; } | 1D 바코드의 체크섬을 가져옵니다. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [Value](../../aspose.barcode.barcoderecognition/onedextendedparameters/value/) { get; } | 체크섬 없이 1D 바코드의 코드텍스트를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/onedextendedparameters/equals/)(object) | 이 인스턴스가 지정된 `OneDExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/onedextendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/onedextendedparameters/tostring/)() | 이 `OneDExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_equality/) | 첫 번째 `OneDExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/onedextendedparameters/op_inequality/) | 첫 번째 `OneDExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 1D 바코드 값과 체크섬을 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


