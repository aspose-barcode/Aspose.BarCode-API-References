---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이를 통해 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다."
type: docs
weight: 90
url: /ko/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader는 하나 이상의 바코드를 포함할 수 있는 이미지를 캡슐화하며, 이를 통해 ReadBarCodes 작업을 수행하여 바코드를 감지할 수 있습니다.

```js
new BarCodeReader(image, areas, decodeTypes)
```

BarCodeReader의 새 인스턴스를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| image | base64 문자열 또는 이미지 경로로 인코딩됨 |
| areas | Rectangle 유형의 객체 배열 |
| decodeTypes | DecodeType별 객체 배열 |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | 지정된 xml 파일에 BarCode 속성을 내보냅니다 |
| [containsAny()](#containsany) | 주어진 decode types 중 하나가 포함되는지 확인합니다 |
| [exportToXml(xmlFile)](#exporttoxml) | 지정된 xml 파일에 BarCode 속성을 내보냅니다 |
| [getBarCodeReadType()](#getbarcodereadtype) | 입력 바코드 디코딩의 decode type을 가져옵니다 |
| [getBarcodeSettings()](#getbarcodesettings) | 주요 바코드 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다. |
| [getFoundBarCodes()](#getfoundbarcodes) | 인식된 BarCodeResult 배열을 가져옵니다 |
| [getFoundCount()](#getfoundcount) | 인식된 바코드 수를 가져옵니다 |
| [getQualitySettings()](#getqualitysettings) | QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. QualitySettings를 빠르게 설정하려면 em을 사용하세요 |
| [getTimeout()](#gettimeout) | 인식 프로세스의 제한 시간을 밀리초 단위로 가져옵니다. |
| [readBarCodes()](#readbarcodes) | 이미지에서 BarCodeResult를 읽습니다. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | 인식을 위한 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드 호출 전에 반드시 호출해야 합니다. |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | 인식을 위한 SingleDecodeType 타입 배열을 설정합니다. readBarCodes() 메서드 호출 전에 반드시 호출해야 합니다. |
| [setQualitySettings()](#setqualitysettings) | QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. QualitySettings를 빠르게 설정하려면 em을 사용하세요 |
| [setTimeout(value)](#settimeout) | 인식 프로세스의 제한 시간을 밀리초 단위로 설정합니다. |

### importFromXml(xmlFile) (static) {#importfromxml}

지정된 xml 파일에 BarCode 속성을 내보냅니다

| 매개변수 | 설명 |
| --- | --- |
| xmlFile | 파일 이름 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

주어진 decode types 중 하나가 포함되는지 확인합니다

| 매개변수 | 설명 |
| --- | --- |
| ...decodeTypes | 검증할 유형들. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

지정된 xml 파일에 BarCode 속성을 내보냅니다

| 매개변수 | 설명 |
| --- | --- |
| xmlFile | 파일 이름 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

입력 바코드 디코딩의 decode type을 가져옵니다

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

주요 바코드 디코딩 매개변수입니다. 인식된 데이터에 영향을 주는 매개변수를 포함합니다.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

인식된 BarCodeResult 배열을 가져옵니다

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

인식된 바코드 수를 가져옵니다

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

인식 프로세스의 제한 시간을 밀리초 단위로 가져옵니다.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

이미지에서 BarCodeResult를 읽습니다.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

인식을 위한 비트맵 이미지와 영역을 설정합니다. ReadBarCodes() 메서드 호출 전에 반드시 호출해야 합니다.

| 매개변수 | 설명 |
| --- | --- |
| imageResource | 인식을 위한 이미지. |
| areas | 인식을 위한 영역 목록 |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

인식을 위한 SingleDecodeType 타입 배열을 설정합니다. readBarCodes() 메서드 호출 전에 반드시 호출해야 합니다.

| 매개변수 | 설명 |
| --- | --- |
| types | 읽을 SingleDecodeType 타입 배열. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings를 사용하면 인식 품질과 속도를 수동으로 구성할 수 있습니다. 내장 프리셋인 HighPerformance, NormalQuality, HighQuality, MaxBarCodes를 사용하여 빠르게 설정하거나 개별 옵션을 수동으로 구성할 수 있습니다. QualitySettings의 기본값은 NormalQuality입니다.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

인식 프로세스의 제한 시간을 밀리초 단위로 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 제한 시간. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
