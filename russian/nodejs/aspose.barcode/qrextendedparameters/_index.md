---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет информацию о Structured Append QR распознанного штрихкода."
type: docs
weight: 810
url: /ru/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Сохраняет информацию о Structured Append QR распознанного штрихкода.

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению QRExtendedParameters. |
| [getErrorLevel()](#geterrorlevel) | Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Версия распознанного MicroQR Code. От M1 до M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Получает индекс штрихкода режима структурированного добавления QR. Индекс начинается с 0. Значение по умолчанию -1.Значение: количество |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Получает количество штрихкодов режима структурированного добавления QR. Значение по умолчанию -1.Значение: количество QR структурированного добавления |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Получает данные четности режима структурированного добавления QR. Значение по умолчанию -1.Значение: индекс режима структурированного добавления QR |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Версия распознанного QR Code. От Version1 до Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Версия распознанного RectMicroQR Code. От R7x43 до R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Получает индекс штрихкода режима структурированного добавления QR. Индекс начинается с 0. Значение по умолчанию -1. Значение: количество |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Получает количество штрихкодов режима структурированного добавления QR. Значение по умолчанию -1. Значение: количество QR структурированного добавления |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Получает данные четности режима структурированного добавления QR. Значение по умолчанию -1. Значение: индекс режима структурированного добавления QR |
| [getVersion()](#getversion) | Версия распознанного QR Code. От Version1 до Version40. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isempty) | Проверяет, имеют ли все параметры только значения по умолчанию Значение |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого QRExtendedParameters. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению QRExtendedParameters.

| Параметр | Описание |
| --- | --- |
| obj | Объектное значение для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Версия распознанного MicroQR Code. От M1 до M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Уровень коррекции ошибок Рида-Соломона распознанного штрихкода. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Получает индекс штрих‑кода QR в режиме структурированного добавления. Индекс начинается с 0. Значение по умолчанию — -1. Значение: количество штрих‑кода QR в режиме структурированного добавления.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Получает количество штрих‑кодов QR в режиме структурированного добавления. Значение по умолчанию — -1. Значение: количество штрих‑кода QR в режиме структурированного добавления.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Получает данные четности режима структурированного добавления QR. Значение по умолчанию — -1. Значение: индекс штрих‑кода QR в режиме структурированного добавления.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Версия распознанного QR Code. От Version1 до Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Версия распознанного RectMicroQR Code. От R7x43 до R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Получает индекс штрих‑кода QR в режиме структурированного добавления. Индекс начинается с 0. Значение по умолчанию — -1. Значение: количество штрих‑кода QR в режиме структурированного добавления.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Получает количество штрих‑кодов QR в режиме структурированного добавления. Значение по умолчанию — -1. Значение: количество штрих‑кода QR в режиме структурированного добавления.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Получает данные четности режима структурированного добавления QR. Значение по умолчанию — -1. Значение: индекс штрих‑кода QR в режиме структурированного добавления.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Версия распознанного QR Code. От Version1 до Version40.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Проверяет, имеют ли все параметры только значения по умолчанию Значение

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
