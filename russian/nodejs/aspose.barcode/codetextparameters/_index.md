---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры Codetext."
type: docs
weight: 270
url: /ru/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Параметры Codetext.

```js
new CodetextParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAlignment()](#getalignment) | Получает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER. |
| [getColor()](#getcolor) | Укажите цвет отображаемого CodeText. Значение по умолчанию BLACK. |
| [getFont()](#getfont) | Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. It i |
| [getLocation()](#getlocation) | Укажите расположение отображаемого CodeText, установите CodeLocation.NONE, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false. |
| [getSpace()](#getspace) | Расстояние между CodeText и штрихкодом в единицах. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Текст, который будет отображаться вместо кода текста в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Устанавливает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER. |
| [setColor()](#setcolor) | Укажите цвет отображаемого CodeText. Значение по умолчанию BLACK. |
| [setFont()](#setfont) | Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. It i |
| [setLocation()](#setlocation) | Укажите расположение отображаемого CodeText, установите CodeLocation.NONE, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false. |
| [setSpace()](#setspace) | Расстояние между CodeText и штрихкодом в единицах. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Текст, который будет отображаться вместо кода текста в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого CodetextParameters. |

### getAlignment() {#getalignment}

Получает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER.

### getColor() {#getcolor}

Укажите цвет отображаемого CodeText. Значение по умолчанию BLACK.

### getFont() {#getfont}

Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

### getFontMode() {#getfontmode}

Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

### getLocation() {#getlocation}

Укажите расположение отображаемого CodeText, установите CodeLocation.NONE, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false.

### getSpace() {#getspace}

Расстояние между CodeText и штрихкодом в единицах. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Текст, который будет отображаться вместо кода в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Устанавливает выравнивание текста кода. Значение по умолчанию: TextAlignment.CENTER.

### setColor() {#setcolor}

Укажите цвет отображаемого CodeText. Значение по умолчанию BLACK.

### setFont() {#setfont}

Укажите шрифт отображаемого CodeText. Значение по умолчанию: Arial 5pt regular. Игнорируется, если FontMode установлен в FontMode.AUTO.

### setFontMode() {#setfontmode}

Укажите FontMode. Если FontMode установлен в Auto, размер шрифта будет рассчитываться автоматически на основе значения xDimension. Рекомендуется использовать FontMode.AUTO, особенно в AutoSizeMode.NEAREST или AutoSizeMode.INTERPOLATION. Значение по умолчанию: FontMode.AUTO.

### setLocation() {#setlocation}

Укажите расположение отображаемого CodeText, установите CodeLocation.NONE, чтобы скрыть CodeText. Значение по умолчанию: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Укажите переносы слов (разрывы строк) в тексте. Значение по умолчанию: false.

### setSpace() {#setspace}

Расстояние между CodeText и штрихкодом в единицах. Значение по умолчанию: 2pt. Игнорируется для EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Текст, который будет отображаться вместо кода в 2D штрихкодах. Используется для: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого CodetextParameters.

**Returns:** A string that represents this CodetextParameters.
