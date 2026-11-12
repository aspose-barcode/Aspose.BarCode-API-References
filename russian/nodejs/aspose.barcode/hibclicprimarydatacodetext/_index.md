---
title: "HIBCLICPrimaryDataCodetext"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные данные."
type: docs
weight: 460
url: /ru/nodejs/aspose.barcode/hibclicprimarydatacodetext/
---

## HIBCLICPrimaryDataCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные данные. Этот пример показывает, как кодировать и декодировать HIBC LIC с использованием HIBCLICPrimaryCodetext.

```js
new HIBCLICPrimaryDataCodetext()
```

**Example:**

```js
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `HIBCLICPrimaryDataCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [getData()](#getdata) | Определяет первичные данные. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setData()](#setdata) | Определяет первичные данные. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `HIBCLICPrimaryDataCodetext`.

| Параметр | Описание |
| --- | --- |
| obj | `HIBCLICPrimaryDataCodetext` значение для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### getData() {#getdata}

Определяет первичные данные.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setData() {#setdata}

Определяет первичные данные.
