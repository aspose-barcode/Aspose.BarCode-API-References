---
title: "Pdf417Parameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "PDF417 매개변수."
type: docs
weight: 58
url: /ko/androidjava/com.aspose.barcode.generation/pdf417parameters/
---
**Inheritance:**
java.lang.Object
```
public class Pdf417Parameters
```

PDF417 매개변수. PDF417, MacroPDF417, MicroPDF417 및 GS1MicroPdf417 매개변수를 포함합니다. MacroPDF417는 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다. Structured Append 모드의 MicroPDF417( MacroPDF417 모드와 동일)도 두 개의 필드가 필요합니다: Pdf417MacroFileID 및 Pdf417MacroSegmentID. 다른 모든 필드는 선택 사항입니다.

이 샘플은 GS1MicroPdf417에서 UCC/EAN-128 비연결 모드를 인코딩하는 방법을 보여줍니다.

```

 //Encodes GS1 UCC/EAN-128 non Linked mode 905 with AI 01 (GTIN)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(01)12345678901231");
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes GS1 UCC/EAN-128 non Linked modes 903, 904 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(241)123456789012345(241)ABCD123456789012345");
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D 바코드 모듈의 높이/너비 비율. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | 열 개수. |
| [getECIEncoding()](#getECIEncoding--) | 확장 채널 해석 식별자. |
| [getEncodeMode()](#getEncodeMode--) | Pdf417 인코드 모드를 식별합니다. |
| [getErrorLevel()](#getErrorLevel--) | BarCode의 오류 정정 수준(level0부터 level8까지)의 Pdf417 심볼 유형을 가져옵니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됩니다. |
| [getMacroCharacters()](#getMacroCharacters--) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05와 06 값을 사용합니다. |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | MacroPdf417 바코드 수신자 이름 (선택 필드). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | MacroPdf417 바코드 체크섬 (선택 필드). |
| [getMacroPdf417ECIEncoding()](#getMacroPdf417ECIEncoding--) | 확장 채널 해석 식별자. |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | MacroPdf417 바코드 파일 ID (필수 필드). |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | MacroPdf417 바코드 파일 이름 (선택 필드). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | MacroPdf417 파일 크기 (선택 필드). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | MacroPdf417 바코드 세그먼트 ID (필수 필드), 0부터 시작하여 MacroSegmentsCount - 1까지입니다. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | MacroPdf417 바코드 세그먼트 수 (선택 필드). |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | MacroPdf417 바코드 발신자 이름 (선택 필드). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 인코더에게 세그먼트에 매크로 PDF417 종료자(코드워드 922)를 추가할지 여부를 알려줍니다. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | MacroPdf417 바코드 타임스탬프 (선택 필드). |
| [getRows()](#getRows--) | 행 개수. |
| [getTruncate()](#getTruncate--) | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). |
| [hashCode()](#hashCode--) |  |
| [isCode128Emulation()](#isCode128Emulation--) | MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드인 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데, 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다. |
| [isLinked()](#isLinked--) | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼은 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. |
| [isReaderInitialization()](#isReaderInitialization--) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D 바코드 모듈의 높이/너비 비율. |
| [setCode128Emulation(boolean value)](#setCode128Emulation-boolean-) | MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드인 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데, 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다. |
| [setColumns(int value)](#setColumns-int-) | 열 개수. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 확장 채널 해석 식별자. |
| [setEncodeMode(Pdf417EncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-) | Pdf417 인코드 모드를 식별합니다. |
| [setErrorLevel(Pdf417ErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-) | BarCode의 오류 정정 수준(level0부터 level8까지)의 Pdf417 심볼 유형을 설정합니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됩니다. |
| [setLinked(boolean value)](#setLinked-boolean-) | GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼은 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다. |
| [setMacroCharacters(MacroCharacter value)](#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-) | 특수 모드에서 더 압축된 인코딩을 얻기 위해 매크로 문자 05와 06 값을 사용합니다. |
| [setMacroPdf417Addressee(String value)](#setMacroPdf417Addressee-java.lang.String-) | MacroPdf417 바코드 수신자 이름 (선택 필드). |
| [setMacroPdf417Checksum(int value)](#setMacroPdf417Checksum-int-) | MacroPdf417 바코드 체크섬 (선택 필드). |
| [setMacroPdf417ECIEncoding(int value)](#setMacroPdf417ECIEncoding-int-) | 확장 채널 해석 식별자. |
| [setMacroPdf417FileID(int value)](#setMacroPdf417FileID-int-) | MacroPdf417 바코드 파일 ID (필수 필드). |
| [setMacroPdf417FileName(String value)](#setMacroPdf417FileName-java.lang.String-) | MacroPdf417 바코드 파일 이름 (선택 필드). |
| [setMacroPdf417FileSize(int value)](#setMacroPdf417FileSize-int-) | MacroPdf417 파일 크기 (선택 필드). |
| [setMacroPdf417SegmentID(int value)](#setMacroPdf417SegmentID-int-) | MacroPdf417 바코드 세그먼트 ID (필수 필드), 0부터 시작하여 MacroSegmentsCount - 1까지입니다. |
| [setMacroPdf417SegmentsCount(int value)](#setMacroPdf417SegmentsCount-int-) | MacroPdf417 바코드 세그먼트 수 (선택 필드). |
| [setMacroPdf417Sender(String value)](#setMacroPdf417Sender-java.lang.String-) | MacroPdf417 바코드 발신자 이름 (선택 필드). |
| [setMacroPdf417Terminator(Pdf417MacroTerminator value)](#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-) | 인코더에게 세그먼트에 매크로 PDF417 종료자(코드워드 922)를 추가할지 여부를 알려줍니다. |
| [setMacroPdf417TimeStamp(LocalDateTime value)](#setMacroPdf417TimeStamp-java.time.LocalDateTime-) | MacroPdf417 바코드 타임스탬프 (선택 필드). |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [setRows(int value)](#setRows-int-) | 행 개수. |
| [setTruncate(boolean value)](#setTruncate-boolean-) | BarCode의 Pdf417 심볼 유형이 축소되었는지 여부(공간 절약을 위해). |
| [toString()](#toString--) | 이 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D 바코드 모듈의 높이/너비 비율.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


열 개수.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼 내 데이터 인코딩에 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final Pdf417EncodeMode getEncodeMode()
```


Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final Pdf417ErrorLevel getErrorLevel()
```


BarCode의 오류 정정 수준(level0부터 level8까지)의 Pdf417 심볼 유형을 가져옵니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됩니다.

**Returns:**
[Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) - Pdf417 symbology type of BarCode's error correction level ranging from level0 to level8, level0 means no error correction info, level8 means best error correction which means a larger picture.
### getMacroCharacters() {#getMacroCharacters--}
```
public final MacroCharacter getMacroCharacters()
```


Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와 함께만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None.

이 샘플은 MicroPdf417에서 Macro Characters를 인코딩하는 방법을 보여줍니다.

```

 //Encodes MicroPdf417 with 05 Macro the string: "[)>05abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_05);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());

 //Encodes MicroPdf417 with 06 Macro the string: "[)>06abcde1234"
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "abcde1234");
 generator.getParameters().getBarcode().getPdf417().setMacroCharacters(MacroCharacter.MACRO_06);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText());
 
```

**Returns:**
[MacroCharacter](../../com.aspose.barcode.generation/macrocharacter)
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public final String getMacroPdf417Addressee()
```


MacroPdf417 바코드 수신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름(선택 필드)

**Returns:**
java.lang.String
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public final int getMacroPdf417Checksum()
```


MacroPdf417 바코드 체크섬(선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬(선택 필드) 체크섬 필드에는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값이 포함됩니다.

**Returns:**
int
### getMacroPdf417ECIEncoding() {#getMacroPdf417ECIEncoding--}
```
public final int getMacroPdf417ECIEncoding()
```


Extended Channel Interpretation Identifiers. Macro PDF417 텍스트 필드에 적용됩니다.

**Returns:**
int
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public final int getMacroPdf417FileID()
```


MacroPdf417 바코드 파일 ID(필수 필드). Structured Append 모드용 MicroPDF417 바코드 파일 ID(필수 필드)

**Returns:**
int
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public final String getMacroPdf417FileName()
```


MacroPdf417 바코드 파일 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름(선택 필드)

**Returns:**
java.lang.String
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public final int getMacroPdf417FileSize()
```


MacroPdf417 파일 크기(선택 필드). Structured Append 모드용 MicroPDF417 파일 크기(선택 필드) 파일 크기 필드에는 전체 원본 파일의 바이트 단위 크기가 포함됩니다.

**Returns:**
int
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public final int getMacroPdf417SegmentID()
```


MacroPdf417 바코드 세그먼트 ID(필수 필드), 0부터 MacroSegmentsCount - 1까지. Structured Append 모드용 MicroPDF417 바코드 세그먼트 ID(필수 필드)

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public final int getMacroPdf417SegmentsCount()
```


MacroPdf417 바코드 세그먼트 수(선택 필드). Structured Append 모드용 MicroPDF417 바코드 세그먼트 수(선택 필드)

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public final String getMacroPdf417Sender()
```


MacroPdf417 바코드 발신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 발신자 이름(선택 필드)

**Returns:**
java.lang.String
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public final Pdf417MacroTerminator getMacroPdf417Terminator()
```


인코더에 매크로 PDF417 종료(코드워드 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PDF417에만 적용됩니다.

**Returns:**
[Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator)
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public final LocalDateTime getMacroPdf417TimeStamp()
```


MacroPdf417 바코드 타임스탬프(선택 필드). Structured Append 모드용 MicroPDF417 바코드 타임스탬프(선택 필드)

**Returns:**
java.time.LocalDateTime
### getRows() {#getRows--}
```
public final int getRows()
```


행 개수.

**Returns:**
int
### getTruncate() {#getTruncate--}
```
public final boolean getTruncate()
```


BarCode의 Pdf417 심볼 유형이 축소(공간 절약)되는지 여부. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isCode128Emulation() {#isCode128Emulation--}
```
public final boolean isCode128Emulation()
```


MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드인 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데, 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다.

이 샘플은 두 번째 위치에 FNC1을 포함하거나 포함하지 않은 Code 128 에뮬레이션 모드를 인코딩하는 방법을 보여줍니다. 이렇게 하면 MicroPdf417를 Code 128 바코드로 디코딩할 수 있습니다.

```

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "a1222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "991222322323");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());

 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setCode128Emulation(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsCode128Emulation:" + result.getExtended().getPdf417().isCode128Emulation());
 
```

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public final boolean isLinked()
```


GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼은 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다.

이 샘플은 GS1MicroPdf417에서 "Linked" UCC/EAN-128 모드와 MicroPdf417 및 Pdf417 바코드에서 Linkage Flag(918)를 인코딩하는 방법을 보여줍니다.

```

```

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


2D 바코드 모듈의 높이/너비 비율.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### setCode128Emulation(boolean value) {#setCode128Emulation-boolean-}
```
public final void setCode128Emulation(boolean value)
```


MicroPdf417와 함께만 사용할 수 있으며 Code 128 에뮬레이션 모드를 인코딩합니다. 두 번째 위치 모드인 908 및 909에서 FNC1을 인코딩할 수 있으며, 910 및 911도 인코딩할 수 있는데, 이는 인식된 MicroPdf417가 Code 128으로 해석될 수 있음을 나타냅니다.

이 샘플은 두 번째 위치에 FNC1을 포함하거나 포함하지 않은 Code 128 에뮬레이션 모드를 인코딩하는 방법을 보여줍니다. 이렇게 하면 MicroPdf417를 Code 128 바코드로 디코딩할 수 있습니다.

```

 [C#]
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "a", mode 908.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a1222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode with FNC1 in second position and Application Indicator "99", mode 909.
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "991222322323");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 //Encodes MicroPdf417 in Code 128 emulation mode, modes 910, 911
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
 generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
 using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
     foreach (BarCodeResult result in reader.ReadBarCodes())
         Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
 
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


열 개수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. 바코드 리더에게 심볼 내 데이터 인코딩에 사용된 참조에 대한 세부 정보를 알려주는 데 사용됩니다. Macro PDF417 텍스트 필드에는 적용되지 않습니다. 현재 구현은 모든 잘 알려진 문자 집합 인코딩을 포함합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setEncodeMode(Pdf417EncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.Pdf417EncodeMode-}
```
public final void setEncodeMode(Pdf417EncodeMode value)
```


Pdf417 인코드 모드를 식별합니다. 기본값: Auto.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode) |  |

### setErrorLevel(Pdf417ErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.Pdf417ErrorLevel-}
```
public final void setErrorLevel(Pdf417ErrorLevel value)
```


BarCode의 오류 정정 수준(level0부터 level8까지)의 Pdf417 심볼 유형을 설정합니다. level0은 오류 정정 정보가 없음을 의미하고, level8은 최상의 오류 정정을 의미하며 이는 더 큰 이미지가 됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Pdf417ErrorLevel](../../com.aspose.barcode.generation/pdf417errorlevel) | BarCode의 Pdf417 심볼 유형 오류 정정 수준은 level0부터 level8까지이며, level0은 오류 정정 정보가 없음을, level8은 최상의 오류 정정을 의미하여 더 큰 이미지가 됩니다. |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


GS1MicroPdf417, MicroPdf417 및 Pdf417 바코드와 연결 모드를 정의합니다. GS1MicroPdf417 심볼은 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 모드를 인코딩합니다. MicroPdf417와 Pdf417 심볼은 EAN.UCC가 아닌 연관된 선형 구성 요소에 대한 918 연결 플래그를 인코딩합니다.

이 샘플은 GS1MicroPdf417에서 "Linked" UCC/EAN-128 모드와 MicroPdf417 및 Pdf417 바코드에서 Linkage Flag(918)를 인코딩하는 방법을 보여줍니다.

```

 //Encodes GS1 Linked mode 912 with date field AI 11 (Production date) and AI 10 (Lot number)
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(11)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 13 (Packaging date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(13)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 15 (Sell-by date) and AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(15)991231(10)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 912 with date field AI 17 (Expiration date) and AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(17)991231(21)ABCD");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 914 with AI 10 (Lot number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(10)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked mode 915 with AI 21 (Serial number)
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(21)ABCD12345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes GS1 Linked modes 906, 907 with any AI
 generator = new BarcodeGenerator(EncodeTypes.GS_1_MICRO_PDF_417, "(240)123456789012345");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.GS_1_MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes MicroPdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.MICRO_PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.MICRO_PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());

 //Encodes Pdf417 NON EAN.UCC Linked mode 918
 generator = new BarcodeGenerator(EncodeTypes.PDF_417, "ABCDE123456789012345678");
 generator.getParameters().getBarcode().getPdf417().setLinked(true);
 reader = new BarCodeReader(generator.generateBarCodeImage(), DecodeType.PDF_417);
 for (BarCodeResult result : reader.readBarCodes())
     System.out.println(result.getCodeText() + " IsLinked:" + result.getExtended().getPdf417().isLinked());
 
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setMacroCharacters(MacroCharacter value) {#setMacroCharacters-com.aspose.barcode.generation.MacroCharacter-}
```
public final void setMacroCharacters(MacroCharacter value)
```


Macro Characters 05 및 06 값은 특수 모드에서 더 압축된 인코딩을 얻는 데 사용됩니다. MicroPdf417와 함께만 사용할 수 있으며 916 및 917 MicroPdf417 모드를 인코딩합니다. 기본값: MacroCharacters.None.

이 샘플은 MicroPdf417에서 Macro Characters를 인코딩하는 방법을 보여줍니다.

```

```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [MacroCharacter](../../com.aspose.barcode.generation/macrocharacter) |  |

### setMacroPdf417Addressee(String value) {#setMacroPdf417Addressee-java.lang.String-}
```
public final void setMacroPdf417Addressee(String value)
```


MacroPdf417 바코드 수신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 수신자 이름(선택 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMacroPdf417Checksum(int value) {#setMacroPdf417Checksum-int-}
```
public final void setMacroPdf417Checksum(int value)
```


MacroPdf417 바코드 체크섬(선택 필드). Structured Append 모드용 MicroPDF417 바코드 체크섬(선택 필드) 체크섬 필드에는 CCITT-16 다항식(x^16 + x^12 + x^5 + 1)을 사용한 16비트(2바이트) CRC 체크섬 값이 포함됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417ECIEncoding(int value) {#setMacroPdf417ECIEncoding-int-}
```
public final void setMacroPdf417ECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. Macro PDF417 텍스트 필드에 적용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417FileID(int value) {#setMacroPdf417FileID-int-}
```
public final void setMacroPdf417FileID(int value)
```


MacroPdf417 바코드 파일 ID(필수 필드). Structured Append 모드용 MicroPDF417 바코드 파일 ID(필수 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417FileName(String value) {#setMacroPdf417FileName-java.lang.String-}
```
public final void setMacroPdf417FileName(String value)
```


MacroPdf417 바코드 파일 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 파일 이름(선택 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMacroPdf417FileSize(int value) {#setMacroPdf417FileSize-int-}
```
public final void setMacroPdf417FileSize(int value)
```


MacroPdf417 파일 크기(선택 필드). Structured Append 모드용 MicroPDF417 파일 크기(선택 필드) 파일 크기 필드에는 전체 원본 파일의 바이트 단위 크기가 포함됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417SegmentID(int value) {#setMacroPdf417SegmentID-int-}
```
public final void setMacroPdf417SegmentID(int value)
```


MacroPdf417 바코드 세그먼트 ID(필수 필드), 0부터 MacroSegmentsCount - 1까지. Structured Append 모드용 MicroPDF417 바코드 세그먼트 ID(필수 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417SegmentsCount(int value) {#setMacroPdf417SegmentsCount-int-}
```
public final void setMacroPdf417SegmentsCount(int value)
```


MacroPdf417 바코드 세그먼트 수(선택 필드). Structured Append 모드용 MicroPDF417 바코드 세그먼트 수(선택 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setMacroPdf417Sender(String value) {#setMacroPdf417Sender-java.lang.String-}
```
public final void setMacroPdf417Sender(String value)
```


MacroPdf417 바코드 발신자 이름(선택 필드). Structured Append 모드용 MicroPDF417 바코드 발신자 이름(선택 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMacroPdf417Terminator(Pdf417MacroTerminator value) {#setMacroPdf417Terminator-com.aspose.barcode.generation.Pdf417MacroTerminator-}
```
public final void setMacroPdf417Terminator(Pdf417MacroTerminator value)
```


인코더에 매크로 PDF417 종료(코드워드 922)를 세그먼트에 추가할지 여부를 알려줍니다. 매크로 PDF417에만 적용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Pdf417MacroTerminator](../../com.aspose.barcode.generation/pdf417macroterminator) |  |

### setMacroPdf417TimeStamp(LocalDateTime value) {#setMacroPdf417TimeStamp-java.time.LocalDateTime-}
```
public final void setMacroPdf417TimeStamp(LocalDateTime value)
```


MacroPdf417 바코드 타임스탬프(선택 필드). Structured Append 모드용 MicroPDF417 바코드 타임스탬프(선택 필드)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDateTime |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


행 개수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setTruncate(boolean value) {#setTruncate-boolean-}
```
public final void setTruncate(boolean value)
```


BarCode의 Pdf417 심볼 유형이 축소(공간 절약)되는지 여부. CompactPDF417라고도 합니다. 이 모드에서는 오른쪽 행 표시기와 오른쪽 정지 패턴이 제거됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


이 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)의 인간이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 [Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)을 나타내는 문자열입니다.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

