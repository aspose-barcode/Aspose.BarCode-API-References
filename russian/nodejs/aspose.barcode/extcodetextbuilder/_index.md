---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Вспомогательный класс для автоматической генерации кодового текста в режиме Extended Codetext Mode"
type: docs
weight: 400
url: /ru/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Вспомогательный класс для автоматической генерации кодового текста в режиме Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Методы

| Имя | Описание |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Добавляет кодовый текст с расширенным идентификатором канала |
| [addPlainCodetext(codetext)](#addplaincodetext) | Добавляет простой кодовый текст к элементам расширенного кодового текста |
| [clear()](#clear) | Очищает элементы расширенного кодового текста |
| [getExtendedCodetext()](#getextendedcodetext) | Генерировать расширенный кодовый текст из списка элементов генерации |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Добавляет кодовый текст с расширенным идентификатором канала

| Параметр | Описание |
| --- | --- |
| ECIEncoding | Расширенный идентификатор канала |
| codetext | Кодовый текст в Unicode, который добавляется как элемент расширенного кодового текста с расширенным идентификатором канала |

### addPlainCodetext(codetext) {#addplaincodetext}

Добавляет простой кодовый текст к элементам расширенного кодового текста

| Параметр | Описание |
| --- | --- |
| codetext | Текст кода в Unicode для добавления как элемент расширенного текста кода |

### clear() {#clear}

Очищает элементы расширенного кодового текста

### getExtendedCodetext() {#getextendedcodetext}

Генерировать расширенный кодовый текст из списка элементов генерации

**Returns:** Return string of extended codetext
