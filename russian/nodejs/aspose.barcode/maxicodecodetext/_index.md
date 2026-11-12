---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode."
type: docs
weight: 600
url: /ru/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode. Этот пример показывает, как декодировать необработанный код MaxiCode в экземпляр MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Методы

| Имя | Описание |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Получает тип штрих‑кода. |
| [getECIEncoding()](#geteciencoding) | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в AUTO. |
| [getEncodeMode()](#getencodemode) | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Получает режим кодирования MaxiCode. |
| [getMode()](#getmode) | Получает режим MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в AUTO. |
| [setEncodeMode(value)](#setencodemode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Устанавливает режим кодирования MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Получает тип штрих‑кода.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в AUTO.

### getEncodeMode() {#getencodemode}

Получает режим кодирования MaxiCode. Значение по умолчанию: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Получает режим кодирования MaxiCode.

### getMode() {#getmode}

Получает режим MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в AUTO.

### setEncodeMode(value) {#setencodemode}

Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto.

| Параметр | Описание |
| --- | --- |
| значение | режим кодирования MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Устанавливает режим кодирования MaxiCode.
