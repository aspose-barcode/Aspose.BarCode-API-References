---
title: "Pdf417Parameters"
linktitle: "Pdf417Parameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "PDF417 매개변수."
type: docs
weight: 770
url: /ko/nodejs/aspose.barcode/pdf417parameters/
---

## Pdf417Parameters class

PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417( MacroPDF417 모드와 동일)에서는 두 개의 필드가 필요합니다: Pdf917MacroFileID 및 Pdf917MacroSegmentID. 다른 모든 필드는 선택 사항입니다. 이 샘플은 GS1MicroPdf417에서 UCC/EAN-128 비연결 모드를 인코딩하는 방법을 보여줍니다.

```js
new Pdf417Parameters()
```

**Example:**

```js
# Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log( result.getCodeText());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [getColumns()](#getcolumns) | 열 개수. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [getEncodeMode()](#getencodemode) | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [getErrorLevel()](#geterrorlevel) | BarCode의 오류 정정 수준에 대한 Pdf417 심볼 유형을 가져옵니다. 수준은 level0부터 level8까지이며, level0은 오류 정정이 없음을 의미합니다. |
| [getMacroCharacters()](#getmacrocharacters) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05와 06 값을 사용합니다. Micro와만 사용할 수 있습니다. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | MacroPdf417 바코드 수신자 이름 (선택 필드). MicroPDF417 바코드 수신자 이름 (구조화된 A용 선택 필드 |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | MacroPdf417 바코드 체크섬 (선택 필드). MicroPDF417 바코드 체크섬 (구조화된 추가 모드용 선택 필드) |
| [getMacroPdf417ECIEncoding()](#getmacropdf417eciencoding) | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | MacroPdf417 바코드 파일 ID (필수 필드). MicroPDF417 바코드 파일 ID (구조화된 추가 모드용 필수 필드 |
| [getMacroPdf417FileName()](#getmacropdf417filename) | MacroPdf417 바코드 파일 이름 (선택 필드). MicroPDF417 바코드 파일 이름 (구조화된 추가 모드용 선택 필드 |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | MacroPdf417 파일 크기 (선택 필드). MicroPDF417 파일 크기 (구조화된 추가 모드용 선택 필드) 파일 크기 |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | MacroPdf417 바코드 세그먼트 ID (필수 필드), 0부터 MacroSegmentsCount - 1까지 시작합니다. MicroPDF417 바코드의 |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | MacroPdf417 바코드 세그먼트 수 (선택 필드). MicroPDF417 바코드 세그먼트 수 (구조화된 A용 선택 필드 |
| [getMacroPdf417Sender()](#getmacropdf417sender) | MacroPdf417 바코드 발신자 이름 (선택 필드). MicroPDF417 바코드 발신자 이름 (구조화된 추가용 선택 필드 |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | 인코더에 매크로 PDF417 종결자(codeword 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PD에만 적용됩니다. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조화된 추가 모드용 선택 필드 |
| [getPdf417CompactionMode()](#getpdf417compactionmode) | BarCode의 압축 모드에 대한 Pdf417 심볼 유형. 기본값: Pdf417CompactionMode.AUTO. |
| [getPdf417ECIEncoding()](#getpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [getPdf417EncodeMode()](#getpdf417encodemode) | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [getPdf417ErrorLevel()](#getpdf417errorlevel) ~~(deprecated)~~ | BarCode의 오류 정정 수준에 대한 Pdf417 심볼 유형을 가져옵니다. 수준은 level0부터 level8까지이며, level0은 오류 정정이 없음을 의미합니다. |
| [getPdf417MacroAddressee()](#getpdf417macroaddressee) ~~(deprecated)~~ | 매크로 Pdf417 바코드 수신자 이름을 가져옵니다. |
| [getPdf417MacroChecksum()](#getpdf417macrochecksum) ~~(deprecated)~~ | 매크로 Pdf417 바코드 체크섬을 가져옵니다. |
| [getPdf417MacroECIEncoding()](#getpdf417macroeciencoding) ~~(deprecated)~~ | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [getPdf417MacroFileID()](#getpdf417macrofileid) ~~(deprecated)~~ | 매크로 Pdf417 바코드의 파일 ID를 가져옵니다. MacroPdf417에 사용됩니다. |
| [getPdf417MacroFileName()](#getpdf417macrofilename) ~~(deprecated)~~ | 매크로 Pdf417 바코드 파일 이름을 가져옵니다. |
| [getPdf417MacroFileSize()](#getpdf417macrofilesize) ~~(deprecated)~~ | 매크로 Pdf417 파일 크기를 가져옵니다. |
| [getPdf417MacroSegmentID()](#getpdf417macrosegmentid) ~~(deprecated)~~ | 매크로 Pdf417 바코드의 세그먼트 ID를 가져옵니다. 0부터 MacroSegmentsCount - 1까지 시작합니다. |
| [getPdf417MacroSegmentsCount()](#getpdf417macrosegmentscount) ~~(deprecated)~~ | 매크로 Pdf417 바코드 세그먼트 수를 가져옵니다. |
| [getPdf417MacroSender()](#getpdf417macrosender) ~~(deprecated)~~ | 매크로 Pdf417 바코드 발신자 이름을 가져옵니다. |
| [getPdf417MacroTerminator()](#getpdf417macroterminator) ~~(deprecated)~~ | 인코더에 매크로 PDF417 종결자(codeword 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PD에만 적용됩니다. |
| [getPdf417MacroTimeStamp()](#getpdf417macrotimestamp) ~~(deprecated)~~ | 매크로 Pdf417 바코드 타임스탬프를 가져옵니다. |
| [getPdf417Truncate()](#getpdf417truncate) ~~(deprecated)~~ | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). |
| [getRows()](#getrows) | 행 개수. |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [getTruncate()](#gettruncate) | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). CompactPDF417이라고도 합니다. 오른쪽 행 표시 |
| [isCode128Emulation()](#iscode128emulation) | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치에서 FNC1을 인코딩할 수 있는 모드 908 및 |
| [isLinked()](#islinked) | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907을 인코딩합니다. |
| [isReaderInitialization()](#isreaderinitialization) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setAspectRatio()](#setaspectratio) | 2D 바코드 모듈의 높이/너비 비율. |
| [setCode128Emulation()](#setcode128emulation) | MicroPdf417와만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치에서 FNC1을 인코딩할 수 있는 모드 908 및 |
| [setColumns()](#setcolumns) | 열 개수. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [setEncodeMode()](#setencodemode) | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [setErrorLevel(value)](#seterrorlevel) | Pdf417 심볼 유형의 BarCode 오류 정정 수준을 level0부터 level8까지 설정합니다. level0은 오류 정정이 없음을 의미합니다. |
| [setLinked()](#setlinked) | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907을 인코딩합니다. |
| [setMacroCharacters()](#setmacrocharacters) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05와 06 값을 사용합니다. Micro와만 사용할 수 있습니다. |
| [setMacroPdf417Addressee()](#setmacropdf417addressee) | MacroPdf417 바코드 수신자 이름 (선택 필드). MicroPDF417 바코드 수신자 이름 (구조화된 A용 선택 필드 |
| [setMacroPdf417Checksum()](#setmacropdf417checksum) | MacroPdf417 바코드 체크섬 (선택 필드). MicroPDF417 바코드 체크섬 (구조화된 추가 모드용 선택 필드) |
| [setMacroPdf417ECIEncoding()](#setmacropdf417eciencoding) | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [setMacroPdf417FileID()](#setmacropdf417fileid) | MacroPdf417 바코드 파일 ID (필수 필드). MicroPDF417 바코드 파일 ID (구조화된 추가 모드용 필수 필드 |
| [setMacroPdf417FileName()](#setmacropdf417filename) | MacroPdf417 바코드 파일 이름 (선택 필드). MicroPDF417 바코드 파일 이름 (구조화된 추가 모드용 선택 필드 |
| [setMacroPdf417FileSize()](#setmacropdf417filesize) | MacroPdf417 파일 크기 (선택 필드). MicroPDF417 파일 크기 (구조화된 추가 모드용 선택 필드) 파일 크기 |
| [setMacroPdf417SegmentID()](#setmacropdf417segmentid) | MacroPdf417 바코드 세그먼트 ID (필수 필드), 0부터 MacroSegmentsCount - 1까지 시작합니다. MicroPDF417 바코드의 |
| [setMacroPdf417SegmentsCount()](#setmacropdf417segmentscount) | MacroPdf417 바코드 세그먼트 수 (선택 필드). MicroPDF417 바코드 세그먼트 수 (구조화된 A용 선택 필드 |
| [setMacroPdf417Sender()](#setmacropdf417sender) | MacroPdf417 바코드 발신자 이름 (선택 필드). MicroPDF417 바코드 발신자 이름 (구조화된 추가용 선택 필드 |
| [setMacroPdf417Terminator()](#setmacropdf417terminator) | 인코더에 매크로 PDF417 종결자(codeword 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PD에만 적용됩니다. |
| [setMacroPdf417TimeStamp()](#setmacropdf417timestamp) | MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조화된 추가 모드용 선택 필드 |
| [setPdf417CompactionMode()](#setpdf417compactionmode) | BarCode의 압축 모드에 대한 Pdf417 심볼 유형. 기본값: Pdf417CompactionMode.AUTO. |
| [setPdf417ECIEncoding()](#setpdf417eciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers(확장 채널 해석 식별자)입니다. 이는 바코드 리더에게 사용된 참조에 대한 자세한 정보를 알려주는 데 사용됩니다. |
| [setPdf417EncodeMode()](#setpdf417encodemode) ~~(deprecated)~~ | Pdf417 인코드 모드를 식별합니다. 기본값: Auto. |
| [setPdf417ErrorLevel()](#setpdf417errorlevel) ~~(deprecated)~~ | Pdf417 심볼 유형의 BarCode 오류 정정 수준을 level0부터 level8까지 설정합니다. level0은 오류 정정이 없음을 의미합니다. |
| [setPdf417MacroAddressee()](#setpdf417macroaddressee) ~~(deprecated)~~ | 매크로 Pdf417 바코드 수신자 이름을 설정합니다. |
| [setPdf417MacroChecksum(value)](#setpdf417macrochecksum) ~~(deprecated)~~ | 매크로 Pdf417 바코드 체크섬을 설정합니다. |
| [setPdf417MacroECIEncoding()](#setpdf417macroeciencoding) ~~(deprecated)~~ | 확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다. |
| [setPdf417MacroFileID()](#setpdf417macrofileid) ~~(deprecated)~~ | 매크로 Pdf417 바코드의 파일 ID를 설정합니다. MacroPdf417에 사용됩니다. |
| [setPdf417MacroFileName()](#setpdf417macrofilename) ~~(deprecated)~~ | 매크로 Pdf417 바코드 파일 이름을 설정합니다. |
| [setPdf417MacroFileSize(value)](#setpdf417macrofilesize) ~~(deprecated)~~ | 매크로 Pdf417 파일 크기를 설정합니다. |
| [setPdf417MacroSegmentID()](#setpdf417macrosegmentid) ~~(deprecated)~~ | 매크로 Pdf417 바코드의 세그먼트 ID를 설정합니다. 이 값은 0부터 시작하여 MacroSegmentsCount - 1까지입니다. |
| [setPdf417MacroSegmentsCount()](#setpdf417macrosegmentscount) ~~(deprecated)~~ | 매크로 Pdf417 바코드 세그먼트 수를 설정합니다. |
| [setPdf417MacroSender()](#setpdf417macrosender) ~~(deprecated)~~ | 매크로 Pdf417 바코드 발신자 이름을 설정합니다. |
| [setPdf417MacroTerminator()](#setpdf417macroterminator) ~~(deprecated)~~ | 인코더에 매크로 PDF417 종결자(codeword 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PD에만 적용됩니다. |
| [setPdf417MacroTimeStamp()](#setpdf417macrotimestamp) ~~(deprecated)~~ | 매크로 Pdf417 바코드 타임스탬프를 설정합니다. |
| [setPdf417Truncate()](#setpdf417truncate) ~~(deprecated)~~ | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). |
| [setReaderInitialization(value)](#setreaderinitialization) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setRows()](#setrows) | 행 개수. |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | DotCode 구조화된 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. |
| [setTruncate()](#settruncate) | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). CompactPDF417이라고도 합니다. 오른쪽 행 표시 |
| [toString()](#tostring) | 이 Pdf417Parameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### getAspectRatio() {#getaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### getColumns() {#getcolumns}

열 개수.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation Identifiers. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

### getEncodeMode() {#getencodemode}

Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

### getErrorLevel() {#geterrorlevel}

Pdf417 심볼 유형의 BarCode 오류 정정 수준을 level0부터 level8까지 가져옵니다. level0은 오류 정정 정보가 없으며, level8은 더 큰 이미지가 되는 최상의 오류 정정을 의미합니다.

**Returns:** Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.

### getMacroCharacters() {#getmacrocharacters}

Macro Characters 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None. 이 샘플은 MicroPdf417에서 Macro Characters를 인코딩하는 방법을 보여줍니다.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### getMacroPdf417Addressee() {#getmacropdf417addressee}

MacroPdf417 바코드 수신자 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 수신자 이름

### getMacroPdf417Checksum() {#getmacropdf417checksum}

MacroPdf417 바코드 체크섬 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 체크섬 (선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다.

### getMacroPdf417ECIEncoding() {#getmacropdf417eciencoding}

확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다.

### getMacroPdf417FileID() {#getmacropdf417fileid}

MacroPdf417 바코드의 파일 ID (필수 필드). Structured Append 모드용 필수 필드인 MicroPDF417 바코드의 파일 ID

### getMacroPdf417FileName() {#getmacropdf417filename}

MacroPdf417 바코드 파일 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 파일 이름

### getMacroPdf417FileSize() {#getmacropdf417filesize}

MacroPdf417 파일 크기 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 파일 크기 (선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 크기를 포함합니다.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

MacroPdf417 바코드의 세그먼트 ID (필수 필드), 0부터 시작하여 MacroSegmentsCount - 1까지입니다. Structured Append 모드용 필수 필드인 MicroPDF417 바코드의 세그먼트 ID

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

MacroPdf417 바코드 세그먼트 수 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 세그먼트 수

### getMacroPdf417Sender() {#getmacropdf417sender}

MacroPdf417 바코드 발신자 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 발신자 이름

### getMacroPdf417Terminator() {#getmacropdf417terminator}

인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가해야 하는지 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다.

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조적 추가 모드용 선택 필드)

### getPdf417CompactionMode() {#getpdf417compactionmode}

BarCode의 압축 모드에 대한 Pdf417 심볼 유형. 기본값: Pdf417CompactionMode.AUTO.

### getPdf417ECIEncoding() {#getpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. 기호에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩으로 구성됩니다.

### getPdf417EncodeMode() {#getpdf417encodemode}

Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

### getPdf417ErrorLevel() {#getpdf417errorlevel}

> **Deprecated.** See method description for replacement.

Pdf417 심볼 유형의 BarCode 오류 정정 수준을 level0부터 level8까지 가져옵니다. level0은 오류 정정 정보가 없으며, level8은 더 큰 이미지가 되는 최상의 오류 정정을 의미합니다.

### getPdf417MacroAddressee() {#getpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 수신자 이름을 가져옵니다.

### getPdf417MacroChecksum() {#getpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 체크섬을 가져옵니다.

**Returns:** The checksum field contains the value of the 16-bit (2 bytes) CRC checksum using the CCITT-16 polynomial.

### getPdf417MacroECIEncoding() {#getpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다.

### getPdf417MacroFileID() {#getpdf417macrofileid}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드의 파일 ID를 가져옵니다. MacroPdf417에 사용됩니다.

### getPdf417MacroFileName() {#getpdf417macrofilename}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 파일 이름을 가져옵니다.

### getPdf417MacroFileSize() {#getpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 파일 크기를 가져옵니다.

**Returns:** The file size field contains the size in bytes of the entire source file.

### getPdf417MacroSegmentID() {#getpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드의 세그먼트 ID를 가져옵니다. 0부터 MacroSegmentsCount - 1까지 시작합니다.

### getPdf417MacroSegmentsCount() {#getpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 세그먼트 수를 가져옵니다.

### getPdf417MacroSender() {#getpdf417macrosender}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 발신자 이름을 가져옵니다.

### getPdf417MacroTerminator() {#getpdf417macroterminator}

> **Deprecated.** See method description for replacement.

인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가해야 하는지 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다.

### getPdf417MacroTimeStamp() {#getpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 타임스탬프를 가져옵니다.

### getPdf417Truncate() {#getpdf417truncate}

> **Deprecated.** See method description for replacement.

BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해).

### getRows() {#getrows}

행 개수.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### getTruncate() {#gettruncate}

BarCode의 Pdf417 심볼 유형이 축소(공간 절감)되는지 여부입니다. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다.

### isCode128Emulation() {#iscode128emulation}

MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치에서 FNC1을 인코딩할 수 있는 모드 908 및 909을 지원하며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다. 이 예제들은 두 번째 위치에 FNC1이 있는 경우와 없는 경우의 Code 128 에뮬레이션 모드를 인코딩하는 방법을 보여줍니다. 이렇게 하면 MicroPdf417를 Code 128 바코드로 디코딩할 수 있습니다.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### isLinked() {#islinked}

GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼로는 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼로는 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. 이 예제들은 GS1MicroPdf417에서 "Linked" UCC/EAN-128 모드를 인코딩하고 MicroPdf417와 Pdf417 바코드에서 연결 플래그(918)를 인코딩하는 방법을 보여줍니다.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### isReaderInitialization() {#isreaderinitialization}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Returns:** boolean value

### setAspectRatio() {#setaspectratio}

2D 바코드 모듈의 높이/너비 비율.

### setCode128Emulation() {#setcode128emulation}

MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치에서 FNC1을 인코딩할 수 있는 모드 908 및 909을 지원하며, 910 및 911도 인코딩할 수 있는데 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다. 이 예제들은 두 번째 위치에 FNC1이 있는 경우와 없는 경우의 Code 128 에뮬레이션 모드를 인코딩하는 방법을 보여줍니다. 이렇게 하면 MicroPdf417를 Code 128 바코드로 디코딩할 수 있습니다.

**Example:**

```js
# Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a\u001d1222322323");
generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
}
```

### setColumns() {#setcolumns}

열 개수.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation Identifiers. 심볼에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

### setEncodeMode() {#setencodemode}

Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

### setErrorLevel(value) {#seterrorlevel}

BarCode의 Pdf417 심볼 유형 오류 정정 수준을 level0부터 level8까지 설정합니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됨을 의미합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | BarCode의 Pdf417 심볼 유형 오류 정정 수준은 level0부터 level8까지이며, level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하여 더 큰 이미지가 됩니다. |

### setLinked() {#setlinked}

GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼로는 906, 907, 912, 913, 914, 915 "Linked" UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼로는 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. 이 예제들은 GS1MicroPdf417에서 "Linked" UCC/EAN-128 모드를 인코딩하고 MicroPdf417와 Pdf417 바코드에서 연결 플래그(918)를 인코딩하는 방법을 보여줍니다.

**Example:**

```js
# Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
let generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
generator.getParameters().getBarcode().getPdf417().setLinked(true);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.GS_1_MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked();
}
```

### setMacroCharacters() {#setmacrocharacters}

Macro Characters 05와 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None. 이 샘플은 MicroPdf417에서 Macro Characters를 인코딩하는 방법을 보여줍니다.

**Example:**

```js
# Encodes MicroPdf417 with 05 Macro the string: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
let generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
let reader = new BarCodeReader(generator.generateBarCodeImage(BarcodeImageFormat.PNG), null, DecodeType.MICRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log( result.getCodeText());
}
```

### setMacroPdf417Addressee() {#setmacropdf417addressee}

MacroPdf417 바코드 수신자 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 수신자 이름

### setMacroPdf417Checksum() {#setmacropdf417checksum}

MacroPdf417 바코드 체크섬 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 체크섬 (선택 필드) 체크섬 필드는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다.

### setMacroPdf417ECIEncoding() {#setmacropdf417eciencoding}

확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다.

### setMacroPdf417FileID() {#setmacropdf417fileid}

MacroPdf417 바코드의 파일 ID (필수 필드). Structured Append 모드용 필수 필드인 MicroPDF417 바코드의 파일 ID

### setMacroPdf417FileName() {#setmacropdf417filename}

MacroPdf417 바코드 파일 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 파일 이름

### setMacroPdf417FileSize() {#setmacropdf417filesize}

MacroPdf417 파일 크기 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 파일 크기 (선택 필드) 파일 크기 필드는 전체 원본 파일의 바이트 크기를 포함합니다.

### setMacroPdf417SegmentID() {#setmacropdf417segmentid}

MacroPdf417 바코드의 세그먼트 ID (필수 필드), 0부터 시작하여 MacroSegmentsCount - 1까지입니다. Structured Append 모드용 필수 필드인 MicroPDF417 바코드의 세그먼트 ID

### setMacroPdf417SegmentsCount() {#setmacropdf417segmentscount}

MacroPdf417 바코드 세그먼트 수 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 세그먼트 수

### setMacroPdf417Sender() {#setmacropdf417sender}

MacroPdf417 바코드 발신자 이름 (선택 필드). Structured Append 모드용 선택 필드인 MicroPDF417 바코드 발신자 이름

### setMacroPdf417Terminator() {#setmacropdf417terminator}

인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가해야 하는지 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다.

### setMacroPdf417TimeStamp() {#setmacropdf417timestamp}

MacroPdf417 바코드 타임스탬프 (선택 필드). MicroPDF417 바코드 타임스탬프 (구조적 추가 모드용 선택 필드)

### setPdf417CompactionMode() {#setpdf417compactionmode}

BarCode의 압축 모드에 대한 Pdf417 심볼 유형. 기본값: Pdf417CompactionMode.AUTO.

### setPdf417ECIEncoding() {#setpdf417eciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. 기호에 데이터를 인코딩하기 위해 사용된 참조에 대한 세부 정보를 바코드 리더에게 전달하는 데 사용됩니다. 현재 구현은 알려진 모든 문자 집합 인코딩으로 구성됩니다.

### setPdf417EncodeMode() {#setpdf417encodemode}

> **Deprecated.** See method description for replacement.

Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

### setPdf417ErrorLevel() {#setpdf417errorlevel}

> **Deprecated.** See method description for replacement.

BarCode의 Pdf417 심볼 유형 오류 정정 수준을 level0부터 level8까지 설정합니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됨을 의미합니다.

### setPdf417MacroAddressee() {#setpdf417macroaddressee}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 수신자 이름을 설정합니다.

### setPdf417MacroChecksum(value) {#setpdf417macrochecksum}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 체크섬을 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 체크섬 필드는 CCITT-16 다항식을 사용한 16비트(2바이트) CRC 체크섬 값을 포함합니다. |

### setPdf417MacroECIEncoding() {#setpdf417macroeciencoding}

> **Deprecated.** See method description for replacement.

확장 채널 해석 식별자. Macro PDF417 텍스트 필드에 적용됩니다.

### setPdf417MacroFileID() {#setpdf417macrofileid}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드의 파일 ID를 설정합니다. MacroPdf417에 사용됩니다.

### setPdf417MacroFileName() {#setpdf417macrofilename}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 파일 이름을 설정합니다.

### setPdf417MacroFileSize(value) {#setpdf417macrofilesize}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 파일 크기를 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 파일 크기 필드는 전체 원본 파일의 바이트 단위 크기를 포함합니다. |

### setPdf417MacroSegmentID() {#setpdf417macrosegmentid}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드의 세그먼트 ID를 설정합니다. 이 값은 0부터 시작하여 MacroSegmentsCount - 1까지입니다.

### setPdf417MacroSegmentsCount() {#setpdf417macrosegmentscount}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 세그먼트 수를 설정합니다.

### setPdf417MacroSender() {#setpdf417macrosender}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 발신자 이름을 설정합니다.

### setPdf417MacroTerminator() {#setpdf417macroterminator}

> **Deprecated.** See method description for replacement.

인코더에게 세그먼트에 Macro PDF417 Terminator(코드워드 922)를 추가해야 하는지 알려주는 데 사용됩니다. Macro PDF417에만 적용됩니다.

### setPdf417MacroTimeStamp() {#setpdf417macrotimestamp}

> **Deprecated.** See method description for replacement.

매크로 Pdf417 바코드 타임스탬프를 설정합니다.

### setPdf417Truncate() {#setpdf417truncate}

> **Deprecated.** See method description for replacement.

BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해).

### setReaderInitialization(value) {#setreaderinitialization}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 |  |

### setRows() {#setrows}

행 개수.

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

DotCode 구조적 추가 모드 바코드의 ID를 식별합니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

### setTruncate() {#settruncate}

BarCode의 Pdf417 심볼 유형이 축소(공간 절감)되는지 여부입니다. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다.

### toString() {#tostring}

이 Pdf417Parameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this Pdf417Parameters.
