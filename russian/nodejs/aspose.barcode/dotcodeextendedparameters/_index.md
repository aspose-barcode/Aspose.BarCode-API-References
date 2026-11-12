---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет специальные данные распознанного штрих‑кода DotCode. Этот пример показывает, как получить необработанные значения DotCode"
type: docs
weight: 380
url: /ru/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Сохраняет специальные данные распознанного штрих‑кода DotCode. Этот пример показывает, как получить необработанные значения DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `DotCodeExtendedParameters`. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Получает идентификатор штрих‑кода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Получает количество штрих‑кодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. Значение: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Получает идентификатор штрих‑кода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Получает количество штрих‑кодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. Значение: |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isReaderInitialization()](#isreaderinitialization) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению `DotCodeExtendedParameters`.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Получает идентификатор штрих‑кода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — -1. Значение: Идентификатор штрих‑кода DotCode в режиме структурированного добавления.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Получает количество штрих‑кодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. Значение: Количество штрих‑кодов DotCode в режиме структурированного добавления.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Получает идентификатор штрих‑кода DotCode в режиме структурированного добавления. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — -1. Значение: Идентификатор штрих‑кода DotCode в режиме структурированного добавления.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Получает количество штрих‑кодов DotCode в режиме структурированного добавления. Значение по умолчанию — -1. Количество должно быть в диапазоне от 1 до 35. Значение: Количество штрих‑кодов DotCode в режиме структурированного добавления.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
