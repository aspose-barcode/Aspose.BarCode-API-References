---
title: "클래스 Pdf417ParametersUI"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.Windows.Forms.Pdf417ParametersUI 클래스. Pdf417Parameters 클래스에 대한 UI 래퍼"
type: docs
weight: 1860
url: /ko/net/aspose.barcode.windows.forms/pdf417parametersui/
---
## Pdf417ParametersUI class

[`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/) 클래스에 대한 UI 래퍼.

```csharp
public class Pdf417ParametersUI
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AspectRatio](../../aspose.barcode.windows.forms/pdf417parametersui/aspectratio/) { get; set; } | 2D 바코드 모듈의 높이/너비 비율. |
| [Columns](../../aspose.barcode.windows.forms/pdf417parametersui/columns/) { get; set; } | 열 수. |
| [ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/eciencoding/) { get; set; } | Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다. |
| [EncodeMode](../../aspose.barcode.windows.forms/pdf417parametersui/encodemode/) { get; set; } | BarCode의 인코드 모드에 대한 Pdf417 심볼 유형. 기본값: Pdf417EncodeMode.Auto. |
| [ErrorLevel](../../aspose.barcode.windows.forms/pdf417parametersui/errorlevel/) { get; set; } | BarCode의 오류 정정 수준에 대한 Pdf417 심볼 유형을 가져오거나 설정합니다. level0부터 level8까지이며, level0은 오류 정정 정보가 없음을, level8은 최상의 오류 정정으로 더 큰 이미지가 됨을 의미합니다. |
| [IsCode128Emulation](../../aspose.barcode.windows.forms/pdf417parametersui/iscode128emulation/) { get; set; } | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128로 해석될 수 있음을 나타냅니다. |
| [IsLinked](../../aspose.barcode.windows.forms/pdf417parametersui/islinked/) { get; set; } | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결된 모드를 정의합니다. GS1MicroPdf417 기호는 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417 및 Pdf417 기호는 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. |
| [IsReaderInitialization](../../aspose.barcode.windows.forms/pdf417parametersui/isreaderinitialization/) { get; set; } | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [MacroCharacters](../../aspose.barcode.windows.forms/pdf417parametersui/macrocharacters/) { get; set; } | Macro Characters 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417에서만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None. |
| [MacroPdf417Addressee](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417addressee/) { get; set; } | MacroPdf417 바코드 수신자 이름 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름 (선택 필드) |
| [MacroPdf417Checksum](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417checksum/) { get; set; } | MacroPdf417 바코드 체크섬 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬 (선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다. |
| [MacroPdf417ECIEncoding](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417eciencoding/) { get; set; } | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [MacroPdf417FileID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417fileid/) { get; set; } | Macro Pdf417 바코드의 파일 ID를 가져오거나 설정합니다. MacroPdf417에 사용됩니다. |
| [MacroPdf417FileName](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filename/) { get; set; } | MacroPdf417 바코드 파일 이름 (선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름 (선택 필드) |
| [MacroPdf417FileSize](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417filesize/) { get; set; } | MacroPdf417 파일 크기 (선택 필드). MicroPDF417 파일 크기 (구조화된 추가 모드용 선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 단위 크기를 포함합니다. |
| [MacroPdf417SegmentID](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentid/) { get; set; } | Macro Pdf417 바코드의 세그먼트 ID를 가져오거나 설정합니다. 이 값은 0부터 시작하여 MacroSegmentsCount - 1까지입니다. |
| [MacroPdf417SegmentsCount](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417segmentscount/) { get; set; } | Macro Pdf417 바코드 세그먼트 수를 가져오거나 설정합니다. |
| [MacroPdf417Sender](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417sender/) { get; set; } | MacroPdf417 바코드 발신자 이름 (선택 필드). MicroPDF417 바코드 발신자 이름 (구조화된 추가 모드용 선택 필드) |
| [MacroPdf417Terminator](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417terminator/) { get; set; } | 인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가할지 여부를 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다. |
| [MacroPdf417TimeStamp](../../aspose.barcode.windows.forms/pdf417parametersui/macropdf417timestamp/) { get; set; } | MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조화된 추가 모드용 선택 필드) |
| [Rows](../../aspose.barcode.windows.forms/pdf417parametersui/rows/) { get; set; } | 행 수. |
| [Truncate](../../aspose.barcode.windows.forms/pdf417parametersui/truncate/) { get; set; } | 바코드의 Pdf417 기호 유형이 공간을 줄이기 위해 잘려 있는지 여부. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/pdf417parametersui/tostring/)() | 이 [`Pdf417Parameters`](../../aspose.barcode.generation/pdf417parameters/)의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### 또 보기

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


