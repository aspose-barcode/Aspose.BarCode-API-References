---
title: "Aspose::BarCode::Generation::Pdf417Parameters 클래스"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for C++ API 레퍼런스"
description: "Aspose::BarCode::Generation::Pdf417Parameters 클래스. PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417( MacroPDF417 모드와 동일)도 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 C++에서 선택 사항입니다."
type: docs
weight: 4000
url: /ko/cpp/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class


PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417(또는 MacroPDF417 모드와 동일)도 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다.

```cpp
class Pdf417Parameters : public System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [get_Columns](./get_columns/)() const | 열 수. |
| [get_ECIEncoding](./get_eciencoding/)() const | Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. |
| [get_EncodeMode](./get_encodemode/)() const | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | [BarCode](../../aspose.barcode/)의 오류 정정 수준이 level0부터 level8까지인 Pdf417 심볼 유형을 가져옵니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 가장 높은 오류 정정을 의미하며, 이는 더 큰 이미지를 의미합니다. |
| [get_IsCode128Emulation](./get_iscode128emulation/)() const | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128로 해석될 수 있음을 나타냅니다. |
| [get_IsLinked](./get_islinked/)() const | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417 및 Pdf417 심볼은 918 연결 플래그를 인코딩하여 EAN.UCC가 아닌 연관된 선형 구성 요소와 연결합니다. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Characters 05 및 06 값은 특수 모드에서 보다 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: [MacroCharacters.None](../barcodeclassifications/). |
| [get_MacroPdf417Addressee](./get_macropdf417addressee/)() const | MacroPdf417 바코드 수신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름(선택 필드) |
| [get_MacroPdf417Checksum](./get_macropdf417checksum/)() const | MacroPdf417 바코드 체크섬(선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬(선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다. |
| [get_MacroPdf417ECIEncoding](./get_macropdf417eciencoding/)() const | Extended Channel Interpretation Identifiers. Macro PDF417 텍스트 필드에 적용됩니다. |
| [get_MacroPdf417FileID](./get_macropdf417fileid/)() const | MacroPdf417 바코드 파일 ID(필수 필드). Structured Append 모드용 MicroPDF417 바코드 파일 ID(필수 필드) |
| [get_MacroPdf417FileName](./get_macropdf417filename/)() const | MacroPdf417 바코드 파일 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름(선택 필드) |
| [get_MacroPdf417FileSize](./get_macropdf417filesize/)() const | MacroPdf417 파일 크기(선택 필드). Structured Append 모드용 MicroPDF417 파일 크기(선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 단위 크기를 포함합니다. |
| [get_MacroPdf417SegmentID](./get_macropdf417segmentid/)() const | MacroPdf417 바코드 세그먼트 ID(필수 필드)로, 0부터 MacroSegmentsCount - 1까지입니다. Structured Append 모드용 MicroPDF417 바코드 세그먼트 ID(필수 필드) |
| [get_MacroPdf417SegmentsCount](./get_macropdf417segmentscount/)() const | MacroPdf417 바코드 세그먼트 수(선택 필드). Structured Append 모드용 MicroPDF417 바코드 세그먼트 수(선택 필드) |
| [get_MacroPdf417Sender](./get_macropdf417sender/)() const | MacroPdf417 바코드 발신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 발신자 이름(선택 필드) |
| [get_MacroPdf417Terminator](./get_macropdf417terminator/)() const | 인코더에게 매크로 PDF417 종결자 (코드워드 922)를 세그먼트에 추가할지 여부를 알려주는 데 사용됩니다. 매크로 PDF417에만 적용됩니다. |
| [get_MacroPdf417TimeStamp](./get_macropdf417timestamp/)() const | MacroPdf417 바코드 타임스탬프(선택 필드). Structured Append 모드용 MicroPDF417 바코드 타임스탬프(선택 필드) |
| [get_Rows](./get_rows/)() const | 행 수. |
| [get_Truncate](./get_truncate/)() const | [BarCode](../../aspose.barcode/)의 Pdf417 심볼 유형이 축소(공간 절약)되는지 여부. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다. |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) 모듈의 높이/너비 비율. |
| [set_Columns](./set_columns/)(int32_t) | 열 수. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. |
| [set_EncodeMode](./set_encodemode/)(Pdf417EncodeMode) | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(Pdf417ErrorLevel) | [BarCode](../../aspose.barcode/)의 Pdf417 심볼 유형 오류 정정 수준을 level0부터 level8까지 설정합니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정으로 더 큰 이미지가 됩니다. |
| [set_IsCode128Emulation](./set_iscode128emulation/)(bool) | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128로 해석될 수 있음을 나타냅니다. |
| [set_IsLinked](./set_islinked/)(bool) | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417 및 Pdf417 심볼은 918 연결 플래그를 인코딩하여 EAN.UCC가 아닌 연관된 선형 구성 요소와 연결합니다. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Characters 05 및 06 값은 특수 모드에서 보다 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: [MacroCharacters.None](../barcodeclassifications/). |
| [set_MacroPdf417Addressee](./set_macropdf417addressee/)(System::String) | MacroPdf417 바코드 수신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름(선택 필드) |
| [set_MacroPdf417Checksum](./set_macropdf417checksum/)(int32_t) | MacroPdf417 바코드 체크섬(선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬(선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다. |
| [set_MacroPdf417ECIEncoding](./set_macropdf417eciencoding/)(ECIEncodings) | Extended Channel Interpretation Identifiers. Macro PDF417 텍스트 필드에 적용됩니다. |
| [set_MacroPdf417FileID](./set_macropdf417fileid/)(int32_t) | MacroPdf417 바코드 파일 ID(필수 필드). Structured Append 모드용 MicroPDF417 바코드 파일 ID(필수 필드) |
| [set_MacroPdf417FileName](./set_macropdf417filename/)(System::String) | MacroPdf417 바코드 파일 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름(선택 필드) |
| [set_MacroPdf417FileSize](./set_macropdf417filesize/)(int32_t) | MacroPdf417 파일 크기(선택 필드). Structured Append 모드용 MicroPDF417 파일 크기(선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 단위 크기를 포함합니다. |
| [set_MacroPdf417SegmentID](./set_macropdf417segmentid/)(int32_t) | MacroPdf417 바코드 세그먼트 ID(필수 필드)로, 0부터 MacroSegmentsCount - 1까지입니다. Structured Append 모드용 MicroPDF417 바코드 세그먼트 ID(필수 필드) |
| [set_MacroPdf417SegmentsCount](./set_macropdf417segmentscount/)(int32_t) | MacroPdf417 바코드 세그먼트 수(선택 필드). Structured Append 모드용 MicroPDF417 바코드 세그먼트 수(선택 필드) |
| [set_MacroPdf417Sender](./set_macropdf417sender/)(System::String) | MacroPdf417 바코드 발신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 발신자 이름(선택 필드) |
| [set_MacroPdf417Terminator](./set_macropdf417terminator/)(Pdf417MacroTerminator) | 인코더에게 매크로 PDF417 종결자 (코드워드 922)를 세그먼트에 추가할지 여부를 알려주는 데 사용됩니다. 매크로 PDF417에만 적용됩니다. |
| [set_MacroPdf417TimeStamp](./set_macropdf417timestamp/)(System::DateTime) | MacroPdf417 바코드 타임스탬프(선택 필드). Structured Append 모드용 MicroPDF417 바코드 타임스탬프(선택 필드) |
| [set_Rows](./set_rows/)(int32_t) | 행 수. |
| [set_Truncate](./set_truncate/)(bool) | [BarCode](../../aspose.barcode/)의 Pdf417 심볼 유형이 축소(공간 절약)되는지 여부. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다. |
| [ToString](./tostring/)() const override | 이 [Pdf417Parameters](./)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
## 비고


이 샘플은 GS1MicroPdf417에서 UCC/EAN-128 비연결 모드를 인코딩하는 방법을 보여줍니다.
```cpp
[C#]
//AI 01 (GTIN)을 사용하여 GS1 UCC/EAN-128 비연결 모드 905를 인코딩합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(01)12345678901231");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//임의의 AI와 함께 GS1 UCC/EAN-128 비연결 모드 903, 904를 인코딩합니다.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(241)123456789012345(241)ABCD123456789012345");
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## 또 보기

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
