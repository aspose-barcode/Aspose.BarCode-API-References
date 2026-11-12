---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста MaxiCode для режимов 4, 5 и 6."
type: docs
weight: 670
url: /ru/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Класс для кодирования и декодирования текста MaxiCode для режимов 4, 5 и 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению. |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [getHashCode()](#gethashcode) | Возвращает хеш-код для этого экземпляра. |
| [getMessage()](#getmessage) | Получает сообщение. |
| [getMode()](#getmode) | Получает режим MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setMessage()](#setmessage) | Устанавливает сообщение. |
| [setMode()](#setmode) | Устанавливает режим MaxiCode. Стандартный кодовый текст может использоваться только с режимами 4, 5 и 6. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению.

| Параметр | Описание |
| --- | --- |
| obj | Значение для сравнения с этим экземпляром. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Получает сообщение.

### getMode() {#getmode}

Получает режим MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setMessage() {#setmessage}

Устанавливает сообщение.

### setMode() {#setmode}

Устанавливает режим MaxiCode. Стандартный кодовый текст может использоваться только с режимами 4, 5 и 6.
