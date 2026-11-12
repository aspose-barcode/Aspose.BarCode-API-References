---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет специальные данные распознанного штрихкода DataMatrix. Этот пример показывает, как получить необработанные значения DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /ru/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Сохраняет специальные данные распознанного штрихкода DataMatrix. Этот пример показывает, как получить необработанные значения DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `DataMatrixExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Получает идентификатор штрихкода DataMatrix в режиме структурного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Получает количество штрихкодов DataMatrix в режиме структурного добавления. Значение по умолчанию — -1. Количество должно быть от 1 до 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Получает идентификатор штрихкода DataMatrix в режиме структурного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов cou |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isReaderProgramming()](#isreaderprogramming) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `DataMatrixExtendedParameters`.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Получает идентификатор штрихкода DataMatrix в режиме структурного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. Значение: идентификатор штрихкода DataMatrix в режиме структурного добавления.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Получает количество штрихкодов DataMatrix в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. Значение: количество штрихкода DataMatrix в режиме структурированного добавления.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Получает идентификатор штрихкода DataMatrix в режиме структурного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. Значение по умолчанию — -1. Значение: идентификатор штрихкода DataMatrix в режиме структурного добавления.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
