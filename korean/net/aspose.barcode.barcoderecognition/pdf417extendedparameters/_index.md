---
title: "클래스 Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.BarCodeRecognition.Pdf417ExtendedParameters 클래스. 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다."
type: docs
weight: 340
url: /ko/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다.

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsCode128Emulation](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/iscode128emulation/) { get; } | 908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩된 MicroPdf417 바코드를 나타내는 플래그입니다. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [IsLinked](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/islinked/) { get; } | 바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그입니다. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/isreaderinitialization/) { get; } | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | Macro PDF417 수신자 이름(선택 사항). |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | Macro PDF417 체크섬(선택 사항). |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | 바코드의 파일 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다. |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | Macro PDF417 파일 이름 (옵션). |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | Macro PDF417 파일 크기 (옵션). |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | 바코드의 세그먼트 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | macro pdf417 바코드 세그먼트 수를 가져옵니다. 기본값은 -1입니다. |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | Macro PDF417 발신자 이름 (옵션). |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | 세그먼트가 Macro PDF417 파일의 마지막 세그먼트인지 여부를 나타냅니다. |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | Macro PDF417 타임스탬프 (옵션). |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | 이 인스턴스가 지정된 `Pdf417ExtendedParameters` 값과 같은지 여부를 나타내는 값을 반환합니다. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | 이 인스턴스의 해시 코드를 반환합니다. |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | 이 `Pdf417ExtendedParameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | 첫 번째 `Pdf417ExtendedParameters` 값이 두 번째와 같은지 여부를 나타내는 값을 반환합니다. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | 첫 번째 `Pdf417ExtendedParameters` 값이 두 번째와 다른지 여부를 나타내는 값을 반환합니다. |

## 예제

이 샘플은 Macro Pdf417 메타데이터를 가져오는 방법을 보여줍니다

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

### 또 보기

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


