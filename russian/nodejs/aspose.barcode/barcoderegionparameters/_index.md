---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Представляет регион распознанного штрихкода и угол штрихкода"
type: docs
weight: 100
url: /ru/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Представляет регион распознанного штрихкода и угол штрихкода

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению BarCodeRegionParameters. |
| [getAngle()](#getangle) | Получает угол штрихкода (0-360). Значение: угол штрихкода (0-360). |
| [getPoints()](#getpoints) | Получает массив Points, ограничивающий регион штрихкода. Значение: Возвращает массив Points, ограничивающий регион штрихкода |
| [getQuadrangle()](#getquadrangle) | Получает Quadrangle, ограничивающий регион штрихкода. Значение: Возвращает Quadrangle, ограничивающий регион штрихкода |
| [getRectangle()](#getrectangle) | Получает Rectangle, ограничивающий регион штрихкода. Значение: Возвращает Rectangle, ограничивающий регион штрихкода |
| [hashCode()](#hashcode) | Возвращает хеш-код для этого экземпляра. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этих BarCodeRegionParameters. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению BarCodeRegionParameters.

| Параметр | Описание |
| --- | --- |
| obj | Значение System.Object для сравнения с этим экземпляром. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Получает угол штрихкода (0-360). Значение: угол штрихкода (0-360).

### getPoints() {#getpoints}

Получает массив Points, ограничивающий регион штрихкода. Значение: Возвращает массив Points, ограничивающий регион штрихкода

### getQuadrangle() {#getquadrangle}

Получает Quadrangle, ограничивающий регион штрихкода. Значение: Возвращает Quadrangle, ограничивающий регион штрихкода

### getRectangle() {#getrectangle}

Получает Rectangle, ограничивающий регион штрихкода. Значение: Возвращает Rectangle, ограничивающий регион штрихкода

### hashCode() {#hashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этих BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
