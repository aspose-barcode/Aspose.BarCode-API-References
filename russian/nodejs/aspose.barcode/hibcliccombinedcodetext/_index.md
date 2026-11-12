---
title: "HIBCLICCombinedCodetext"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные и вторичные данные."
type: docs
weight: 440
url: /ru/nodejs/aspose.barcode/hibcliccombinedcodetext/
---

## HIBCLICCombinedCodetext class

Класс для кодирования и декодирования текста, встроенного в код HIBC LIC, который хранит первичные и вторичные данные. Этот пример показывает, как кодировать и декодировать HIBC LIC с использованием HIBCLICCombinedCodetext.

```js
new HIBCLICCombinedCodetext()
```

**Example:**

```js
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCLICCombinedCodetext`. |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [getPrimaryData()](#getprimarydata) | Определяет первичные данные. |
| [getSecondaryAndAdditionalData()](#getsecondaryandadditionaldata) | Определяет вторичные и дополнительные вспомогательные данные. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setPrimaryData()](#setprimarydata) | Определяет первичные данные. |
| [setSecondaryAndAdditionalData()](#setsecondaryandadditionaldata) | Определяет вторичные и дополнительные вспомогательные данные. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `HIBCLICCombinedCodetext`.

| Параметр | Описание |
| --- | --- |
| obj | Значение `HIBCLICCombinedCodetext` для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### getPrimaryData() {#getprimarydata}

Определяет первичные данные.

### getSecondaryAndAdditionalData() {#getsecondaryandadditionaldata}

Определяет вторичные и дополнительные вспомогательные данные.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setPrimaryData() {#setprimarydata}

Определяет первичные данные.

### setSecondaryAndAdditionalData() {#setsecondaryandadditionaldata}

Определяет вторичные и дополнительные вспомогательные данные.
