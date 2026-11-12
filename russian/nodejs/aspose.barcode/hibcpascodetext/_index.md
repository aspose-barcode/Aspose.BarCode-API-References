---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в код HIBC PAS."
type: docs
weight: 480
url: /ru/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## Методы

| Имя | Описание |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Конструктор HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Добавляет новую запись |
| [addRecord(dataType, data)](#addrecord) | Добавляет новую запись |
| [clear()](#clear) | Очищает список записей |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCPASCodetext`. |
| [getBarcodeType()](#getbarcodetype) | Получает тип штрих‑кода. |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [getDataLocation()](#getdatalocation) | Определяет расположение данных. |
| [getRecords()](#getrecords) | Получает список записей |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setBarcodeType()](#setbarcodetype) | Получает или задает тип штрихкода. Код текста HIBC PAS может быть закодирован с использованием HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Определяет расположение данных. |

### _fromMwObject() (static) {#-frommwobject}

Конструктор HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Добавляет новую запись

| Параметр | Описание |
| --- | --- |
| запись | Запись для добавления |

### addRecord(dataType, data) {#addrecord}

Добавляет новую запись

| Параметр | Описание |
| --- | --- |
| dataType | Тип данных |
| данные | Строка данных |

### clear() {#clear}

Очищает список записей

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCPASCodetext`.

| Параметр | Описание |
| --- | --- |
| obj | Значение `HIBCPASCodetext` для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Получает тип штрих‑кода.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Определяет расположение данных.

### getRecords() {#getrecords}

Получает список записей

**Returns:** List of records

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setBarcodeType() {#setbarcodetype}

Получает или задает тип штрихкода. Код текста HIBC PAS может быть закодирован с использованием типов кодирования HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS и HIBCQRPAS. Значение по умолчанию: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Определяет расположение данных.
