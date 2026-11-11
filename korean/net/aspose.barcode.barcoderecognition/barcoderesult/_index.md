---
title: "BarCodeResult 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult 클래스. SingleDecodeType 타입, 문자열 codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다."
type: docs
weight: 100
url: /ko/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

[`SingleDecodeType`](../singledecodetype/) 타입, String codetext, [`BarCodeRegionParameters`](../barcoderegionparameters/) 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다.

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | `BarCodeResult` 클래스의 복사본을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | 인코딩된 코드 바이트를 가져옵니다. |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | 코드 텍스트를 가져옵니다. |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | 바코드 유형을 가져옵니다. |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | 바코드 유형의 이름을 가져옵니다. |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | 인식된 바코드의 신뢰도 수준을 가져옵니다. |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | 인식된 바코드의 확장 매개변수를 가져옵니다. |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | 인식된 바코드에 대한 ISO/IEC 심볼 품질 평가 결과를 가져옵니다. |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | 읽기 품질을 가져옵니다. 1D 및 우편 바코드에 적용됩니다. |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | 바코드 영역을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | `BarCodeResult` 클래스의 복사본을 생성합니다. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | 이 인스턴스가 지정된 `BarCodeResult` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | 이 인스턴스가 지정된 `BarCodeResult` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | 인코딩된 코드 텍스트를 가져옵니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | 이 `BarCodeResult`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | 첫 번째 `BarCodeResult` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | 첫 번째 `BarCodeResult` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 BarCodeResult를 얻는 방법을 보여줍니다.

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
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### 또 보기

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


