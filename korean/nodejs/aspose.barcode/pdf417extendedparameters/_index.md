---
title: "Pdf417ExtendedParameters"
linktitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다"
type: docs
weight: 760
url: /ko/nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

인식된 바코드의 MacroPdf417 메타데이터 정보를 저장합니다

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [equals(obj)](#equals) | 지정된 Pdf417ExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다. |
| [getMacroPdf417Addressee()](#getmacropdf417addressee) | Macro PDF417 수신자 이름 (옵션). |
| [getMacroPdf417Checksum()](#getmacropdf417checksum) | Macro PDF417 체크섬 (옵션). |
| [getMacroPdf417FileID()](#getmacropdf417fileid) | 바코드의 파일 ID를 가져옵니다. MacroPdf417와 함께 사용할 수 있습니다. 값: MacroPdf417의 파일 ID |
| [getMacroPdf417FileName()](#getmacropdf417filename) | Macro PDF417 파일 이름 (선택 사항). |
| [getMacroPdf417FileSize()](#getmacropdf417filesize) | Macro PDF417 파일 크기 (선택 사항). |
| [getMacroPdf417SegmentID()](#getmacropdf417segmentid) | 바코드의 세그먼트 ID를 가져옵니다, MacroPdf417와 함께만 사용할 수 있습니다. Value: 바코드의 세그먼트 ID. |
| [getMacroPdf417SegmentsCount()](#getmacropdf417segmentscount) | macro pdf417 바코드 세그먼트 수를 가져옵니다. 기본값은 -1입니다. Value: 세그먼트 수. |
| [getMacroPdf417Sender()](#getmacropdf417sender) | Macro PDF417 발신자 이름 (선택 사항). |
| [getMacroPdf417Terminator()](#getmacropdf417terminator) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [getMacroPdf417TimeStamp()](#getmacropdf417timestamp) | Macro PDF417 타임스탬프 (선택 사항). |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isCode128Emulation()](#iscode128emulation) | MicroPdf417 바코드가 908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩되었음을 나타내는 플래그. |
| [isLinked()](#islinked) | 바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그. Value: 연결 플래그 |
| [isReaderInitialization()](#isreaderinitialization) | 리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다. |
| [toString()](#tostring) | 이 Pdf417ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |

### equals(obj) {#equals}

지정된 Pdf417ExtendedParameters 값과 이 인스턴스가 같은지 여부를 나타내는 값을 반환합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 이 인스턴스와 비교할 System.Object 값을 제공합니다. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getMacroPdf417Addressee() {#getmacropdf417addressee}

Macro PDF417 수신자 이름 (옵션).

**Returns:** Addressee name.

### getMacroPdf417Checksum() {#getmacropdf417checksum}

Macro PDF417 체크섬 (옵션).

**Returns:** Checksum.

### getMacroPdf417FileID() {#getmacropdf417fileid}

바코드의 파일 ID를 가져옵니다. MacroPdf417와 함께 사용할 수 있습니다. 값: MacroPdf417의 파일 ID

### getMacroPdf417FileName() {#getmacropdf417filename}

Macro PDF417 파일 이름 (선택 사항).

**Returns:** File name.

### getMacroPdf417FileSize() {#getmacropdf417filesize}

Macro PDF417 파일 크기 (선택 사항).

**Returns:** File size.

### getMacroPdf417SegmentID() {#getmacropdf417segmentid}

바코드의 세그먼트 ID를 가져옵니다, MacroPdf417와 함께만 사용할 수 있습니다. Value: 바코드의 세그먼트 ID.

### getMacroPdf417SegmentsCount() {#getmacropdf417segmentscount}

macro pdf417 바코드 세그먼트 수를 가져옵니다. 기본값은 -1입니다. Value: 세그먼트 수.

### getMacroPdf417Sender() {#getmacropdf417sender}

Macro PDF417 발신자 이름 (선택 사항).

**Returns:** Sender name

### getMacroPdf417Terminator() {#getmacropdf417terminator}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Returns:** Reader initialization flag

### getMacroPdf417TimeStamp() {#getmacropdf417timestamp}

Macro PDF417 타임스탬프 (선택 사항).

**Returns:** Time stamp.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 반환합니다.

**Returns:** A 32-bit signed integer hash code.

### isCode128Emulation() {#iscode128emulation}

MicroPdf417 바코드가 908, 909, 910 또는 911 Code 128 에뮬레이션 코드워드로 인코딩되었음을 나타내는 플래그.

**Returns:** Code 128 emulation flag

### isLinked() {#islinked}

바코드가 1D 바코드와 연결되어야 함을 나타내는 플래그. Value: 연결 플래그

### isReaderInitialization() {#isreaderinitialization}

리더에게 심볼에 포함된 데이터를 리더 초기화를 위한 프로그래밍으로 해석하도록 지시하는 데 사용됩니다.

**Returns:** Reader initialization flag

### toString() {#tostring}

이 Pdf417ExtendedParameters의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:** A string that represents this Pdf417ExtendedParameters.
