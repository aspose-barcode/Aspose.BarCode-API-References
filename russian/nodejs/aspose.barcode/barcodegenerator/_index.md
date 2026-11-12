---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "BarcodeGenerator для генерации изображений штрихкодов на сервере."
type: docs
weight: 130
url: /ru/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator для генерации изображений штрихкодов на сервере. поддерживаемые символьные наборы: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended, Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet, EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Конструктор BarcodeGenerator.

| Параметр | Описание |
| --- | --- |
| encodeType | Тип символьного набора штрихкода. Используйте класс EncodeTypes для настройки символьного набора. |
| codeText | Текст для кодирования. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Методы

| Имя | Описание |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Импортирует свойства BarCode из указанного XML‑файла и создает экземпляр BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Экспортирует свойства BarCode в указанный XML‑файл. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Создайте изображение штрихкода с текущими настройками. Этот пример показывает, как создать и сохранить изображение штрихкода. |
| [getBarcodeType()](#getbarcodetype) | Тип символьного набора штрихкода. |
| [getCodeText()](#getcodetext) | Текст для кодирования. |
| [getParameters()](#getparameters) | Параметры генерации. |
| [save(filePath, format)](#save) | Сохранить изображение штрихкода в указанный файл в определённом формате. |
| [setBarcodeType()](#setbarcodetype) | Тип символьного набора штрихкода. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Кодирует Unicode `codeText ` в последовательность байтов, используя указанное `encoding `. UTF-8 является наиболее часто используемым кодированием. |

### importFromXml(filePath) (static) {#importfromxml}

Импортирует свойства BarCode из указанного XML‑файла и создает экземпляр BarcodeGenerator.

| Параметр | Описание |
| --- | --- |
| filePath | Имя файла |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Экспортирует свойства BarCode в указанный XML‑файл.

| Параметр | Описание |
| --- | --- |
| filePath | XML‑файл |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Создайте изображение штрихкода с текущими настройками. Этот пример показывает, как создать и сохранить изображение штрихкода.

| Параметр | Тип | Описание |
| --- | --- | --- |
| формат | BarCodeImageFormat | Значение BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Тип символьного набора штрихкода.

### getCodeText() {#getcodetext}

Текст для кодирования.

### getParameters() {#getparameters}

Параметры генерации.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Сохранить изображение штрихкода в указанный файл в определённом формате.

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь для сохранения. |
| формат | BarCodeImageFormat | Значение BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Тип символьного набора штрихкода.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Кодирует Unicode `codeText ` в последовательность байтов, используя указанное `encoding `. UTF-8 является наиболее часто используемым кодированием. Если кодировка поддерживает это и `insertBOM ` установлен в `true`, функция добавляет `byte order mark (BOM) `. Эта функция предназначена только для 2D‑штрихкодов (например, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR и др.). Она позволяет вручную кодировать Unicode‑текст с использованием национальных или специальных кодировок; однако этот метод считается устаревшим в современных приложениях. Для современных сценариев рекомендуется кодировка `ECI ` для Unicode‑данных. Использование этой функции с 1D‑штрихкодами, штрихкодами, соответствующими GS1 (включая 2D), или HIBC‑штрихкодами (включая 2D) не поддерживается соответствующими стандартами штрихкодов и может привести к непредсказуемым результатам. Этот пример показывает, как использовать `SetCodeText` с BOM или без него для 2D‑штрихкодов. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Параметр | Описание |
| --- | --- |
| codeText | Строка CodeText |
| кодировка | Применённое кодирование |
| insertBOM | Указывает, следует ли вставлять маркер порядка байтов (BOM), когда указанная кодировка поддерживает его (например, UTF-8, UTF-16, UTF-32). Если установлено `true`, BOM добавляется; если `false`, BOM опускается, даже если кодировка обычно использует его. |
