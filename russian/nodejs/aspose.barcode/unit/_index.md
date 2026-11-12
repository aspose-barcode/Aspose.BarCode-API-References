---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Указывает значение размера в разных единицах (пиксели, дюймы и т.д.)."
type: docs
weight: 960
url: /ru/nodejs/aspose.barcode/unit/
---

## Unit class

Указывает значение размера в разных единицах (пиксели, дюймы и т.д.).

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом Unit, одинаковое значение. |
| [getDocument()](#getdocument) | Получает значение размера в единицах документа. |
| [getInches()](#getinches) | Получает значение размера в дюймах. |
| [getMillimeters()](#getmillimeters) | Получает значение размера в миллиметрах. |
| [getPixels()](#getpixels) | Получает значение размера в пикселях. |
| [getPoint()](#getpoint) | Получает значение размера в пунктах. |
| [setDocument()](#setdocument) | Устанавливает значение размера в единицах документа. |
| [setInches()](#setinches) | Устанавливает значение размера в дюймах. |
| [setMillimeters()](#setmillimeters) | Устанавливает значение размера в миллиметрах. |
| [setPixels()](#setpixels) | Устанавливает значение размера в пикселях. |
| [setPoint()](#setpoint) | Устанавливает значение размера в пунктах. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого Unit. |

### equals(obj) {#equals}

Определяет, имеют ли этот экземпляр и указанный объект, который также должен быть объектом Unit, одинаковое значение.

| Параметр | Описание |
| --- | --- |
| obj | Объект Unit для сравнения с этим экземпляром. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Получает значение размера в единицах документа.

### getInches() {#getinches}

Получает значение размера в дюймах.

### getMillimeters() {#getmillimeters}

Получает значение размера в миллиметрах.

### getPixels() {#getpixels}

Получает значение размера в пикселях.

### getPoint() {#getpoint}

Получает значение размера в пунктах.

### setDocument() {#setdocument}

Устанавливает значение размера в единицах документа.

### setInches() {#setinches}

Устанавливает значение размера в дюймах.

### setMillimeters() {#setmillimeters}

Устанавливает значение размера в миллиметрах.

### setPixels() {#setpixels}

Устанавливает значение размера в пикселях.

### setPoint() {#setpoint}

Устанавливает значение размера в пунктах.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого Unit.

**Returns:** A string that represents this Unit.
