---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры ITF."
type: docs
weight: 540
url: /ru/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

Параметры ITF.

```js
new ITFParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | Получает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt. |
| [getBorderType()](#getbordertype) | Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.Bar. |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | Получает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt. |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.BAR. |
| [getQuietZoneCoef()](#getquietzonecoef) | Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, если xDimension = 2px, то тихие зоны будут 20px. |
| [setBorderThickness(value)](#setborderthickness) | Устанавливает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt. |
| [setBorderType()](#setbordertype) | Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.Bar. |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | Устанавливает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt. |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.BAR. |
| [setQuietZoneCoef()](#setquietzonecoef) | Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, если xDimension = 2px, то тихие зоны будут 20px. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого ITFParameters. |

### getBorderThickness() {#getborderthickness}

Получает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt.

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.Bar.

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

Получает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt.

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.BAR.

### getQuietZoneCoef() {#getquietzonecoef}

Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, если xDimension = 2px, то тихие зоны будут 20px.

**Throws:** IllegalArgumentException
Значение параметра QuietZoneCoef меньше 10.

### setBorderThickness(value) {#setborderthickness}

Устанавливает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt.

| Параметр | Описание |
| --- | --- |
| значение | толщина границы ITF (опорной полосы) в единицах. |

### setBorderType() {#setbordertype}

Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.Bar.

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

Устанавливает толщину границы ITF (опорной полосы) в единицах. Значение по умолчанию: 12pt.

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

Тип границы штрихкода ITF. Значение по умолчанию: ITF14BorderType.BAR.

### setQuietZoneCoef() {#setquietzonecoef}

Размер тихих зон в xDimension. Значение по умолчанию: 10, что означает, если xDimension = 2px, то тихие зоны будут 20px.

**Throws:** IllegalArgumentException
Значение параметра QuietZoneCoef меньше 10.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого ITFParameters.

**Returns:** A string that represents this ITFParameters.
