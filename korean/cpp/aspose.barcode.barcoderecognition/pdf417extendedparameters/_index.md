---
title: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters 클래스"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::BarCodeRecognition::Pdf417ExtendedParameters 클래스. C++에서 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다."
type: docs
weight: 2800
url: /ko/cpp/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class


인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다.

```cpp
class Pdf417ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | 908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩된 MicroPdf417 바코드를 나타내는 플래그입니다. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** 모든 매개변수가 기본값만 가지고 있는지 확인합니다. |
| [get_IsLinked](./get_islinked/)() const | 바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그입니다. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | Macro PDF417 수신자 이름 (옵션). |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | Macro PDF417 체크섬 (옵션). |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417에서만 사용할 수 있는 바코드의 파일 ID를 가져옵니다. |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | Macro PDF417 파일 이름 (옵션). |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | Macro PDF417 파일 크기 (옵션). |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417에서만 사용할 수 있는 바코드의 세그먼트 ID를 가져옵니다. |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | Macro PDF417 바코드 세그먼트 수를 가져옵니다. 기본값은 -1입니다. |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | Macro PDF417 발신자 이름 (옵션). |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | 세그먼트가 Macro PDF417 파일의 마지막 세그먼트인지 여부를 나타냅니다. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | Macro PDF417 타임스탬프 (옵션). |
| [GetHashCode](./gethashcode/)() const override | 이 인스턴스의 해시 코드를 반환합니다. |
| [ToString](./tostring/)() const override | 이 [Pdf417ExtendedParameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 Macro Pdf417 메타데이터를 가져오는 방법을 보여줍니다.
```cpp
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

## 또 보기

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
