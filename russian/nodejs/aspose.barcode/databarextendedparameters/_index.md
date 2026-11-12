---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Сохраняет дополнительную информацию DataBar распознанного штрих‑кода"
type: docs
weight: 310
url: /ru/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Сохраняет дополнительную информацию DataBar распознанного штрих‑кода

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли данный экземпляр указанному значению DataBarExtendedParameters. |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Получает флаг составного компонента DataBar 2D. Значение по умолчанию — false. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого объекта. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли данный экземпляр указанному значению DataBarExtendedParameters.

| Параметр | Описание |
| --- | --- |
| obj | Значение DataBarExtendedParameters для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Получает флаг составного компонента DataBar 2D. Значение по умолчанию — false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого объекта.

**Returns:** A string that represents this .
