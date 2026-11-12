---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного текста кода для 2D QR штрихкодов в режиме ExtendedCodetext режима QREncodeMode. Используйте свойство Display2DText класса BarCodeBuilder, чтобы установить видимый текст в rem"
type: docs
weight: 820
url: /ru/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Генератор расширенного текста кода для 2D QR штрихкодов в режиме ExtendedCodetext режима QREncodeMode. Используйте свойство Display2DText класса BarCodeBuilder, чтобы установить видимый текст, удаляя управляющие символы.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Методы

| Имя | Описание |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Добавляет текст кода с указанным режимом сжатия QR к элементам расширенного текста кода. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Добавляет FNC1 в первую позицию к элементам расширенного текста кода. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Добавляет разделитель группы (GS - '\\u001D') к элементам расширенного текста кода. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Добавляет FNC1 во вторую позицию к элементам расширенного текста кода. |
| [clear()](#clear) | Очищает элементы расширенного кодового текста |
| [getExtendedCodetext()](#getextendedcodetext) | Создаёт расширенный код текста из списка расширенных кодов текста. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Добавляет текст кода с указанным режимом сжатия QR к элементам расширенного текста кода.

| Параметр | Описание |
| --- | --- |
| режим | Режим сжатия QR для текста кода. |
| codetext | Текст кода в Unicode для добавления как элемент расширенного текста кода. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Добавляет FNC1 в первую позицию к элементам расширенного текста кода.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Добавляет разделитель группы (GS - '\\u001D') к элементам расширенного текста кода.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Добавляет FNC1 во вторую позицию к элементам расширенного текста кода.

| Параметр | Описание |
| --- | --- |
| codetext | Значение FNC1 во второй позиции |

### clear() {#clear}

Очищает элементы расширенного кодового текста

### getExtendedCodetext() {#getextendedcodetext}

Создаёт расширенный код текста из списка расширенных кодов текста.

**Returns:** Extended codetext as string
