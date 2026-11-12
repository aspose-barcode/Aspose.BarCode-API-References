---
title: "DotCodeParameters"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры DotCode."
type: docs
weight: 390
url: /ru/nodejs/aspose.barcode/dotcodeparameters/
---

## DotCodeParameters class

Параметры DotCode.

```js
new DotCodeParameters()
```

## Методы

| Имя | Описание |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [getColumns()](#getcolumns) | Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Number o |
| [getDotCodeEncodeMode()](#getdotcodeencodemode) ~~(deprecated)~~ | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35. |
| [getECIEncoding()](#geteciencoding) | Определяет кодировку ECI. Используется, когда DotCodeEncodeMode имеет значение AUTO. Значение по умолчанию: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [getRows()](#getrows) | Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество r |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35. |
| [isReaderInitialization()](#isreaderinitialization) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [setAspectRatio()](#setaspectratio) | Соотношение высоты к ширине модуля 2D штрихкода. |
| [setColumns()](#setcolumns) | Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Number o |
| [setDotCodeEncodeMode()](#setdotcodeencodemode) ~~(deprecated)~~ | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [setDotCodeStructuredAppendModeBarcodeId()](#setdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [setDotCodeStructuredAppendModeBarcodesCount()](#setdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35. |
| [setECIEncoding()](#seteciencoding) | Определяет кодировку ECI. Используется, когда DotCodeEncodeMode имеет значение AUTO. Значение по умолчанию: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Определяет режим кодирования DotCode. Значение по умолчанию: Auto. |
| [setReaderInitialization()](#setreaderinitialization) | Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или |
| [setRows()](#setrows) | Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество r |
| [setStructuredAppendModeBarcodeId()](#setstructuredappendmodebarcodeid) | Определяет идентификатор штрихкода режима Structured Append для DotCode. Идентификатор начинается с 1 и должен быть меньше или равен количеству штрихкодов. |
| [setStructuredAppendModeBarcodesCount()](#setstructuredappendmodebarcodescount) | Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35. |
| [toString()](#tostring) | Возвращает человекочитаемое строковое представление этого DotCodeParameters. |

### getAspectRatio() {#getaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### getColumns() {#getcolumns}

Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1

### getDotCodeEncodeMode() {#getdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35.

### getECIEncoding() {#geteciencoding}

Определяет кодировку ECI. Используется, когда DotCodeEncodeMode имеет значение AUTO. Значение по умолчанию: ISO-8859-1

### getEncodeMode() {#getencodemode}

Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

### getRows() {#getrows}

Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35.

### isReaderInitialization() {#isreaderinitialization}

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### setAspectRatio() {#setaspectratio}

Соотношение высоты к ширине модуля 2D штрихкода.

### setColumns() {#setcolumns}

Определяет количество столбцов. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество столбцов должно быть не менее 5. Значение по умолчанию: -1

### setDotCodeEncodeMode() {#setdotcodeencodemode}

> **Deprecated.** See method description for replacement.

Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

### setDotCodeStructuredAppendModeBarcodeId() {#setdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### setDotCodeStructuredAppendModeBarcodesCount() {#setdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35.

### setECIEncoding() {#seteciencoding}

Определяет кодировку ECI. Используется, когда DotCodeEncodeMode имеет значение AUTO. Значение по умолчанию: ISO-8859-1

### setEncodeMode() {#setencodemode}

Определяет режим кодирования DotCode. Значение по умолчанию: Auto.

### setReaderInitialization() {#setreaderinitialization}

Указывает, используется ли код для указания считывателю интерпретировать последующие данные как инструкции для инициализации или перепрограммирования считывателя штрих‑кода. Значение по умолчанию — false.

### setRows() {#setrows}

Определяет количество строк. Сумма количества строк и количества столбцов символа DotCode должна быть нечётной. Количество строк должно быть не менее 5. Значение по умолчанию: -1

### setStructuredAppendModeBarcodeId() {#setstructuredappendmodebarcodeid}

Определяет ID штрихкода DotCode в режиме структурированного добавления. ID начинается с 1 и должно быть меньше или равно количеству штрихкодов. Значение по умолчанию — -1.

### setStructuredAppendModeBarcodesCount() {#setstructuredappendmodebarcodescount}

Определяет количество штрих‑кодов в режиме структурного добавления DotCode. Значение по умолчанию: -1. Значение должно быть от 1 до 35.

### toString() {#tostring}

Возвращает человекочитаемое строковое представление этого DotCodeParameters.

**Returns:** A string that represents this DotCodeParameters.
