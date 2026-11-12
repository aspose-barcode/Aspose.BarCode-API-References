---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC."
type: docs
weight: 450
url: /ru/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код HIBC LIC. Этот пример показывает, как декодировать необработанный HIBC LIC codetext в экземпляр HIBCLICComplexCodetext.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Получает или задает тип штрихкода. HIBC LIC codetext может быть закодирован с использованием HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Создаёт codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует экземпляр из построенного codetext. |
| [setBarcodeType()](#setbarcodetype) | Получает или задает тип штрихкода. HIBC LIC codetext может быть закодирован с использованием HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Получает или задает тип штрихкода. HIBC LIC codetext может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Создаёт codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует экземпляр из построенного codetext.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setBarcodeType() {#setbarcodetype}

Получает или задает тип штрихкода. HIBC LIC codetext может быть закодирован с использованием типов кодирования HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC и HIBCQRLIC. Значение по умолчанию: HIBCCode39LIC.

**Returns:** Barcode type.
