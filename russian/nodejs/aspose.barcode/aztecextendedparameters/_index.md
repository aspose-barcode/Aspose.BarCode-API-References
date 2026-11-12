---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет специальные данные распознанного штрих‑кода Aztec. Этот пример показывает, как получить необработанные значения Aztec: let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /ru/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Сохраняет специальные данные распознанного штрих‑кода Aztec. Этот пример показывает, как получить необработанные значения Aztec: let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `AztecExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Получает идентификатор штрих‑кода режима структурного добавления Aztec. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Получает количество штрих‑кодов режима структурного добавления Aztec. Значение по умолчанию — 0. Количество должно быть в диапазоне от 1 до 26. Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Получает идентификатор файла режима структурного добавления Aztec. Значение по умолчанию — пустая строка. Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isReaderInitialization()](#isreaderinitialization) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого `AztecExtendedParameters`. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению `AztecExtendedParameters`.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Получает идентификатор штрих‑кода режима структурного добавления Aztec. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрих‑кодов. Значение по умолчанию — 0. Value: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Получает количество штрих‑кодов режима структурного добавления Aztec. Значение по умолчанию — 0. Количество должно быть от 1 до 26. Value: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Получает идентификатор файла режима структурного добавления Aztec. Значение по умолчанию — пустая строка. Value: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
