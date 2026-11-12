---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрих‑кодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрих‑кодов."
type: docs
weight: 90
url: /ru/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрих‑кодов, после чего может выполнить операцию ReadBarCodes для обнаружения штрих‑кодов.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Инициализирует новый экземпляр BarCodeReader

| Параметр | Описание |
| --- | --- |
| изображение | закодировано как строка base64 или путь к изображению |
| области | массив объектов типа Rectangle |
| decodeTypes | массив объектов по DecodeType |

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

## Методы

| Имя | Описание |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Экспортирует свойства BarCode в указанный xml-файл |
| [containsAny()](#containsany) | Определяет, включён ли любой из заданных типов декодирования в |
| [exportToXml(xmlFile)](#exporttoxml) | Экспортирует свойства BarCode в указанный xml-файл |
| [getBarCodeReadType()](#getbarcodereadtype) | Получает тип декодирования входного штрихкода |
| [getBarcodeSettings()](#getbarcodesettings) | Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные. |
| [getFoundBarCodes()](#getfoundbarcodes) | Получает массив распознанных BarCodeResult |
| [getFoundCount()](#getfoundcount) | Получает количество распознанных штрихкодов |
| [getQualitySettings()](#getqualitysettings) | QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро настроить QualitySettings с помощью em. |
| [getTimeout()](#gettimeout) | Получает тайм-аут процесса распознавания в миллисекундах. |
| [readBarCodes()](#readbarcodes) | Читает BarCodeResult из изображения. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Устанавливает растровое изображение и области для распознавания. Должно вызываться до метода ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Устанавливает массив типов SingleDecodeType для распознавания. Должно вызываться до метода readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings позволяет вручную настраивать качество и скорость распознавания. Вы можете быстро настроить QualitySettings с помощью em. |
| [setTimeout(value)](#settimeout) | Устанавливает тайм-аут процесса распознавания в миллисекундах. |

### importFromXml(xmlFile) (static) {#importfromxml}

Экспортирует свойства BarCode в указанный xml-файл

| Параметр | Описание |
| --- | --- |
| xmlFile | Имя файла |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Определяет, включён ли любой из заданных типов декодирования в

| Параметр | Описание |
| --- | --- |
| ...decodeTypes | Типы для проверки. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Экспортирует свойства BarCode в указанный xml-файл

| Параметр | Описание |
| --- | --- |
| xmlFile | Имя файла |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Получает тип декодирования входного штрихкода

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Получает массив распознанных BarCodeResult

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

Получает количество распознанных штрихкодов

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

QualitySettings позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро настроить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

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

Получает тайм-аут процесса распознавания в миллисекундах.

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

Читает BarCodeResult из изображения.

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

Устанавливает растровое изображение и области для распознавания. Должно вызываться до метода ReadBarCodes().

| Параметр | Описание |
| --- | --- |
| imageResource | Изображение для распознавания. |
| области | Список областей для распознавания |

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

Устанавливает массив типов SingleDecodeType для распознавания. Должно вызываться до метода readBarCodes().

| Параметр | Описание |
| --- | --- |
| типы | Массив типов SingleDecodeType для чтения. |

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

QualitySettings позволяет вручную настраивать качество распознавания и скорость. Вы можете быстро настроить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, либо вручную настроить отдельные параметры. Значение по умолчанию для QualitySettings — NormalQuality.

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

Устанавливает тайм-аут процесса распознавания в миллисекундах.

| Параметр | Описание |
| --- | --- |
| значение | Тайм-аут. |

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
