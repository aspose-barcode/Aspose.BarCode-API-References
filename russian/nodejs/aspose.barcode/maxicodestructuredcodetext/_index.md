---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode, для режимов 2 и 3."
type: docs
weight: 700
url: /ru/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode, для режимов 2 и 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Методы

| Имя | Описание |
| --- | --- |
| [equals(obj)](#equals) | Возвращает значение, указывающее, равен ли этот экземпляр указанному значению. |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [getCountryCode()](#getcountrycode) | Определяет трехзначный код страны. |
| [getHashCode()](#gethashcode) | Возвращает хеш-код для этого экземпляра. |
| [getPostalCode()](#getpostalcode) | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [getSecondMessage()](#getsecondmessage) | Определяет второе сообщение штрих‑кода. |
| [getServiceCategory()](#getservicecategory) | Определяет трехзначную категорию сервиса. |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setCountryCode()](#setcountrycode) | Определяет трехзначный код страны. |
| [setPostalCode()](#setpostalcode) | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3. |
| [setSecondMessage()](#setsecondmessage) | Определяет второе сообщение штрих‑кода. |
| [setServiceCategory()](#setservicecategory) | Определяет трехзначную категорию сервиса. |

### equals(obj) {#equals}

Возвращает значение, указывающее, равен ли этот экземпляр указанному значению.

| Параметр | Описание |
| --- | --- |
| obj | Значение для сравнения с этим экземпляром |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Определяет трехзначный код страны.

### getHashCode() {#gethashcode}

Возвращает хеш-код для этого экземпляра.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3.

### getSecondMessage() {#getsecondmessage}

Определяет второе сообщение штрих‑кода.

### getServiceCategory() {#getservicecategory}

Определяет трехзначную категорию сервиса.

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setCountryCode() {#setcountrycode}

Определяет трехзначный код страны.

### setPostalCode() {#setpostalcode}

Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или 6 буквенно-цифровых символов в режиме 3.

### setSecondMessage() {#setsecondmessage}

Определяет второе сообщение штрих‑кода.

### setServiceCategory() {#setservicecategory}

Определяет трехзначную категорию сервиса.
