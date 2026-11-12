---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет специальные данные распознанного штрих‑кода Code128. Представляет регион распознанного штрих‑кода и угол штрих‑кода."
type: docs
weight: 240
url: /ru/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Сохраняет специальные данные распознанного штрих‑кода Code128. Представляет регион распознанного штрих‑кода и угол штрих‑кода.

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению Code128ExtendedParameters. |
| [getCode128DataPortions()](#getcode128dataportions) | Получает массив Code128DataPortion распознанного штрихкода Code128. Значение Code128DataPortion. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого Code128ExtendedParameters. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению Code128ExtendedParameters.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Получает массив Code128DataPortion распознанного штрихкода Code128. Значение Code128DataPortion.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
