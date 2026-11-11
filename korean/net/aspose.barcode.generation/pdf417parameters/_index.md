---
title: "Pdf417Parameters 클래스"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Generation.Pdf417Parameters 클래스. PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드인 Pdf417MacroFileID와 Pdf417MacroSegmentID가 필요합니다. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417는 MacroPDF417 모드와 동일하게 두 개의 필드인 Pdf417MacroFileID와 Pdf417MacroSegmentID가 필요합니다. 다른 모든 필드는 선택 사항입니다."
type: docs
weight: 1570
url: /ko/net/aspose.barcode.generation/pdf417parameters/
---
## Pdf417Parameters class

PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417( MacroPDF417 모드와 동일)도 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다.

```csharp
public class Pdf417Parameters
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/pdf417parameters/aspectratio/) { get; set; } | 2D 바코드 모듈의 높이/너비 비율. |
| [Columns](../../aspose.barcode.generation/pdf417parameters/columns/) { get; set; } | 열 수. |
| [ECIEncoding](../../aspose.barcode.generation/pdf417parameters/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. |
| [EncodeMode](../../aspose.barcode.generation/pdf417parameters/encodemode/) { get; set; } | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/pdf417parameters/errorlevel/) { get; set; } | BarCode의 오류 정정 수준에 대한 Pdf417 심볼 유형을 가져오거나 설정합니다. level0부터 level8까지이며, level0은 오류 정정 정보가 없음을, level8은 최상의 오류 정정으로 더 큰 이미지가 됨을 의미합니다. |
| [IsCode128Emulation](../../aspose.barcode.generation/pdf417parameters/iscode128emulation/) { get; set; } | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128로 해석될 수 있음을 나타냅니다. |
| [IsLinked](../../aspose.barcode.generation/pdf417parameters/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결된 모드를 정의합니다. GS1MicroPdf417 기호는 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417 및 Pdf417 기호는 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. |
| [IsReaderInitialization](../../aspose.barcode.generation/pdf417parameters/isreaderinitialization/) { get; set; } | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [MacroCharacters](../../aspose.barcode.generation/pdf417parameters/macrocharacters/) { get; set; } | Macro Characters 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417에서만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.generation/pdf417parameters/macropdf417addressee/) { get; set; } | MacroPdf417 바코드 수신자 이름 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름 (선택 필드) |
| [MacroPdf417Checksum](../../aspose.barcode.generation/pdf417parameters/macropdf417checksum/) { get; set; } | MacroPdf417 바코드 체크섬 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬 (선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다. |
| [MacroPdf417ECIEncoding](../../aspose.barcode.generation/pdf417parameters/macropdf417eciencoding/) { get; set; } | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [MacroPdf417FileID](../../aspose.barcode.generation/pdf417parameters/macropdf417fileid/) { get; set; } | MacroPdf417 바코드의 파일 ID(필수 필드). Structured Append 모드의 MicroPDF417 바코드 파일 ID(필수 필드). |
| [MacroPdf417FileName](../../aspose.barcode.generation/pdf417parameters/macropdf417filename/) { get; set; } | MacroPdf417 바코드 파일 이름 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름 (선택 필드) |
| [MacroPdf417FileSize](../../aspose.barcode.generation/pdf417parameters/macropdf417filesize/) { get; set; } | MacroPdf417 파일 크기 (선택 필드). MicroPDF417 파일 크기 (구조화된 추가 모드용 선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 단위 크기를 포함합니다. |
| [MacroPdf417SegmentID](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentid/) { get; set; } | MacroPdf417 바코드의 세그먼트 ID(필수 필드)이며, 0부터 MacroSegmentsCount - 1까지입니다. Structured Append 모드의 MicroPDF417 바코드 세그먼트 ID(필수 필드). |
| [MacroPdf417SegmentsCount](../../aspose.barcode.generation/pdf417parameters/macropdf417segmentscount/) { get; set; } | MacroPdf417 바코드 세그먼트 수(선택 필드). Structured Append 모드의 MicroPDF417 바코드 세그먼트 수(선택 필드). |
| [MacroPdf417Sender](../../aspose.barcode.generation/pdf417parameters/macropdf417sender/) { get; set; } | MacroPdf417 바코드 발신자 이름 (선택 필드). MicroPDF417 바코드 발신자 이름 (구조화된 추가 모드용 선택 필드) |
| [MacroPdf417Terminator](../../aspose.barcode.generation/pdf417parameters/macropdf417terminator/) { get; set; } | 인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가할지 여부를 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다. |
| [MacroPdf417TimeStamp](../../aspose.barcode.generation/pdf417parameters/macropdf417timestamp/) { get; set; } | MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조화된 추가 모드용 선택 필드) |
| [Rows](../../aspose.barcode.generation/pdf417parameters/rows/) { get; set; } | 행 수. |
| [Truncate](../../aspose.barcode.generation/pdf417parameters/truncate/) { get; set; } | BarCode의 Pdf417 심볼 유형이 축소(공간 절약)되는지 여부. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/pdf417parameters/tostring/)() | `Pdf417Parameters`의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

## 예제

이 샘플은 GS1MicroPdf417에서 UCC/EAN-128 비연결 모드를 인코딩하는 방법을 보여줍니다.

```csharp
[C#]
//AI 01(GTIN)과 함께 GS1 UCC/EAN-128 비연결 모드 905를 인코딩합니다.
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

### 또 보기

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


