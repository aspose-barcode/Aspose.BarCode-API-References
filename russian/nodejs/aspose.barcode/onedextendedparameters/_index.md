---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный текст и контрольная сумма."
type: docs
weight: 720
url: /ru/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Сохраняет специальные данные 1D распознанного штрихкода, такие как отдельный текст и контрольная сумма.

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению OneDExtendedParameters. |
| [getCheckSum()](#getchecksum) | Получает контрольную сумму для 1D штрихкодов. Значение: Контрольная сумма для 1D штрихкода. |
| [getValue()](#getvalue) | Получает код текста 1D штрихкодов без контрольной суммы. Значение: Код текста 1D штрихкодов без контрольной суммы. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [isEmpty()](#isempty) | Проверяет, имеют ли все параметры только значения по умолчанию. Значение: Возвращает `true ` если все параметры имеют только значения по умолчанию; o |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого OneDExtendedParameters. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению OneDExtendedParameters.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Получает контрольную сумму для 1D штрихкодов. Значение: Контрольная сумма для 1D штрихкода.

### getValue() {#getvalue}

Получает код текста 1D штрихкодов без контрольной суммы. Значение: Код текста 1D штрихкодов без контрольной суммы.

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Проверяет, имеют ли все параметры только значения по умолчанию. Значение: Возвращает `true ` если все параметры имеют только значения по умолчанию; в противном случае, `false `.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
