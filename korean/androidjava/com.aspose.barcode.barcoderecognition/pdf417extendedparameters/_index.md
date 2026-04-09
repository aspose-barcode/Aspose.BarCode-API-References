---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: 인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다
type: docs
weight: 40
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class Pdf417ExtendedParameters extends BaseExtendedParameters
```

인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다

--------------------

> ```
> This sample shows how to get Macro Pdf417 metadata
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
>  generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MACRO_PDF_417);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
>      System.out.println("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
>      System.out.println("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
>  }
> ```
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 지정된 Pdf417ExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getMacroPdf417Addressee()](#getMacroPdf417Addressee--) | Macro PDF417 수신자 이름 (옵션). |
| [getMacroPdf417Checksum()](#getMacroPdf417Checksum--) | Macro PDF417 체크섬 (옵션). |
| [getMacroPdf417FileID()](#getMacroPdf417FileID--) | 바코드의 파일 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다. |
| [getMacroPdf417FileName()](#getMacroPdf417FileName--) | Macro PDF417 파일 이름 (옵션). |
| [getMacroPdf417FileSize()](#getMacroPdf417FileSize--) | Macro PDF417 파일 크기 (옵션). |
| [getMacroPdf417SegmentID()](#getMacroPdf417SegmentID--) | 바코드의 세그먼트 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다. |
| [getMacroPdf417SegmentsCount()](#getMacroPdf417SegmentsCount--) | macro pdf417 바코드 세그먼트 수를 가져옵니다. |
| [getMacroPdf417Sender()](#getMacroPdf417Sender--) | Macro PDF417 발신자 이름 (옵션). |
| [getMacroPdf417Terminator()](#getMacroPdf417Terminator--) | 세그먼트가 Macro PDF417 파일의 마지막 세그먼트인지 여부를 나타냅니다. |
| [getMacroPdf417TimeStamp()](#getMacroPdf417TimeStamp--) | Macro PDF417 타임스탬프 (옵션). |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isCode128Emulation()](#isCode128Emulation--) | 908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩된 MicroPdf417 바코드를 나타내는 플래그입니다. |
| [isEmpty()](#isEmpty--) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [isLinked()](#isLinked--) | 바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그입니다. |
| [isReaderInitialization()](#isReaderInitialization--) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 Pdf417ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


지정된 Pdf417ExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMacroPdf417Addressee() {#getMacroPdf417Addressee--}
```
public String getMacroPdf417Addressee()
```


Macro PDF417 수신자 이름 (옵션).

**Returns:**
java.lang.String - 수신자 이름.
### getMacroPdf417Checksum() {#getMacroPdf417Checksum--}
```
public int getMacroPdf417Checksum()
```


Macro PDF417 체크섬 (옵션).

**Returns:**
int - 체크섬.
### getMacroPdf417FileID() {#getMacroPdf417FileID--}
```
public String getMacroPdf417FileID()
```


바코드의 파일 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다.

값: MacroPdf417의 파일 ID

**Returns:**
java.lang.String
### getMacroPdf417FileName() {#getMacroPdf417FileName--}
```
public String getMacroPdf417FileName()
```


Macro PDF417 파일 이름 (옵션).

**Returns:**
java.lang.String - 파일 이름.
### getMacroPdf417FileSize() {#getMacroPdf417FileSize--}
```
public int getMacroPdf417FileSize()
```


Macro PDF417 파일 크기 (옵션).

**Returns:**
int - 파일 크기.
### getMacroPdf417SegmentID() {#getMacroPdf417SegmentID--}
```
public int getMacroPdf417SegmentID()
```


바코드의 세그먼트 ID를 가져옵니다. MacroPdf417에서만 사용할 수 있습니다.

값: 바코드의 세그먼트 ID.

**Returns:**
int
### getMacroPdf417SegmentsCount() {#getMacroPdf417SegmentsCount--}
```
public int getMacroPdf417SegmentsCount()
```


macro pdf417 바코드 세그먼트 수를 가져옵니다. 기본값은 -1입니다.

값: 세그먼트 수.

**Returns:**
int
### getMacroPdf417Sender() {#getMacroPdf417Sender--}
```
public String getMacroPdf417Sender()
```


Macro PDF417 발신자 이름 (옵션).

**Returns:**
java.lang.String - 발신자 이름
### getMacroPdf417Terminator() {#getMacroPdf417Terminator--}
```
public boolean getMacroPdf417Terminator()
```


세그먼트가 Macro PDF417 파일의 마지막 세그먼트인지 여부를 나타냅니다.

**Returns:**
boolean - 종료자.
### getMacroPdf417TimeStamp() {#getMacroPdf417TimeStamp--}
```
public LocalDateTime getMacroPdf417TimeStamp()
```


Macro PDF417 타임스탬프 (옵션).

**Returns:**
java.time.LocalDateTime - Time stamp.
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
### isCode128Emulation() {#isCode128Emulation--}
```
public boolean isCode128Emulation()
```


908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩된 MicroPdf417 바코드를 나타내는 플래그입니다.

**Returns:**
boolean - Code 128 emulation flag
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


모든 매개변수가 기본값만 가지고 있는지 테스트합니다.

값: 모든 매개변수가 기본값만 가지고 있으면 **true**, 그렇지 않으면 **false**를 반환합니다.

**Returns:**
boolean
### isLinked() {#isLinked--}
```
public boolean isLinked()
```


바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그입니다.

Value: Linkage flag

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public boolean isReaderInitialization()
```


리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

Value: Reader initialization flag

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




### toString() {#toString--}
```
public String toString()
```


이 Pdf417ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - A string that represents this  Pdf417ExtendedParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

