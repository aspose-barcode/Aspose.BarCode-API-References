---
title: "클래스 QRExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.QRExtendedParameters 클래스. 인식된 바코드의 QR Structured Append 정보를 저장합니다"
type: docs
weight: 350
url: /ko/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

인식된 바코드의 QR Structured Append 정보를 저장합니다.

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | 인식된 바코드의 Reed-Solomon 오류 정정 수준. 낮은 수준부터 높은 수준까지: LevelL, LevelM, LevelQ, LevelH. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | 인식된 MicroQR 코드의 버전. M1부터 M4까지. |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | 인식된 RectMicroQR 코드의 버전. R7x43부터 R17x139까지. |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | QR Structured Append 모드 바코드의 인덱스를 가져옵니다. 인덱스는 0부터 시작합니다. 기본값은 -1입니다. |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | QR Structured Append 모드 바코드 수량을 가져옵니다. 기본값은 -1입니다. |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | QR Structured Append 모드 패리티 데이터를 가져옵니다. 기본값은 -1입니다. |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | 인식된 QR 코드의 버전. Version1부터 Version40까지. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | 이 인스턴스가 지정된 `QRExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | 이 `QRExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | 첫 번째 `QRExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | 첫 번째 `QRExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 QR Structured Append 데이터를 가져오는 방법을 보여줍니다.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


