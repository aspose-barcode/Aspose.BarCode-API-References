---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры Aztec."
type: docs
weight: 70
url: /ru/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Параметры Aztec.

```js
new AztecParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Получает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Получает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Получает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [getErrorLevel()](#geterrorlevel) | Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95. |
| [getLayersCount()](#getlayerscount) | Получает количество слоёв символа Aztec. Количество слоёв должно быть в диапазоне от 1 до 3 для компактного режима и в диапазоне от 1 до 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Идентификатор штрихкода для режима Structured Append штрихкода Aztec. Идентификатор штрихкода должен быть в диапазоне от 1 до количества штрихкодов. По умолчанию |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Количество штрихкодов для режима Structured Append штрихкода Aztec. Количество штрихкодов должно быть в диапазоне от 1 до 26. Значение по умолчанию |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: |
| [getSymbolMode()](#getsymbolmode) | Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setAspectRatio()](#setaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Устанавливает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto. |
| [setErrorLevel()](#seterrorlevel) | Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95. |
| [setLayersCount()](#setlayerscount) | Устанавливает количество слоёв символа Aztec. Количество слоёв должно быть в диапазоне от 1 до 3 для режима Compact и в диапазоне от 1 до 3 |
| [setReaderInitialization()](#setreaderinitialization) | Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Идентификатор штрихкода для режима Structured Append штрихкода Aztec. Идентификатор штрихкода должен быть в диапазоне от 1 до количества штрихкодов. По умолчанию |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Количество штрихкодов для режима Structured Append штрихкода Aztec. Количество штрихкодов должно быть в диапазоне от 1 до 26. Значение по умолчанию |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: |
| [setSymbolMode(value)](#setsymbolmode) | Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Возвращает читаемое строковое представление этого `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Получает режим кодирования Aztec. Значение по умолчанию: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Получает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

### getEncodeMode() {#getencodemode}

Получает режим кодирования Aztec. Значение по умолчанию: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

### getLayersCount() {#getlayerscount}

Получает количество слоёв символа Aztec. Количество слоёв должно быть в диапазоне от 1 до 3 для режима Compact и в диапазоне от 1 до 32 для режима Full Range. Значение по умолчанию: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Идентификатор штрихкода для режима Structured Append штрихкода Aztec. Идентификатор штрихкода должен быть в диапазоне от 1 до количества штрихкодов. Значение по умолчанию: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Количество штрихкодов для режима Structured Append штрихкода Aztec. Количество штрихкодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка

### getSymbolMode() {#getsymbolmode}

Получает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

### setAspectRatio() {#setaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Устанавливает кодировку ECI. Используется, когда AztecEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Устанавливает режим кодирования Aztec. Значение по умолчанию: Auto.

| Параметр | Описание |
| --- | --- |
| значение | режим кодирования Aztec. |

### setErrorLevel() {#seterrorlevel}

Уровень коррекции ошибок для штрихкодов типа Aztec. Значение должно быть от 5 до 95.

### setLayersCount() {#setlayerscount}

Устанавливает количество слоёв символа Aztec. Количество слоёв должно быть в диапазоне от 1 до 3 для режима Compact и в диапазоне от 1 до 32 для режима Full Range. Значение по умолчанию: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Используется для указания считывателю интерпретировать данные, содержащиеся в символе, как программу для инициализации считывателя.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Идентификатор штрихкода для режима Structured Append штрихкода Aztec. Идентификатор штрихкода должен быть в диапазоне от 1 до количества штрихкодов. Значение по умолчанию: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Количество штрихкодов для режима Structured Append штрихкода Aztec. Количество штрихкодов должно быть в диапазоне от 1 до 26. Значение по умолчанию: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Идентификатор файла для режима Structured Append штрихкода Aztec (необязательное поле). Идентификатор файла не должен содержать пробелы. Значение по умолчанию: пустая строка

### setSymbolMode(value) {#setsymbolmode}

Устанавливает режим символа Aztec. Значение по умолчанию: AztecSymbolMode.Auto.

| Параметр | Описание |
| --- | --- |
| значение | режим символа Aztec. |

### toString() {#tostring}

Возвращает читаемое строковое представление этого `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
