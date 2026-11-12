---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в 4-state код Royal Mailmark."
type: docs
weight: 580
url: /ru/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Класс для кодирования и декодирования текста, встроенного в 4-state код Royal Mailmark.

```js
new MailmarkCodetext()
```

Инициализирует новый экземпляр класса `MailmarkCodetext`.

## Методы

| Имя | Описание |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Получает тип штрих‑кода. |
| [getClass_()](#getclass-) | \"0\" - Null или Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (for pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Создать кодовый текст из данных Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный \"XY11 \" (обратите внимание на 5 завершающих пробелов). |
| [getFormat()](#getformat) | \"0\" – Null или Test \"1\" – Letter \"2\" – Large Letter |
| [getItemID()](#getitemid) | Максимальное значение равно 99999999. |
| [getSupplychainID()](#getsupplychainid) | Максимальные значения: 99 для Barcode C и 999999 для Barcode L. |
| [getVersionID()](#getversionid) | В настоящее время \"1\" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует данные Mailmark из построенного кодового текста. |
| [setClass_()](#setclass-) | \"0\" - Null или Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (for pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный \"XY11 \" (обратите внимание на 5 завершающих пробелов). |
| [setFormat()](#setformat) | \"0\" – Null или Test \"1\" – LetterN \"2\" – Large Letter |
| [setItemID()](#setitemid) | Максимальное значение равно 99999999. |
| [setSupplychainID()](#setsupplychainid) | Максимальные значения: 99 для Barcode C и 999999 для Barcode L. |
| [setVersionID()](#setversionid) | В настоящее время \"1\" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |

### getBarcodeType() {#getbarcodetype}

Получает тип штрих‑кода.

**Returns:** Barcode type.

### getClass_() {#getclass-}

\"0\" - Null или Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (для потенциального будущего использования) \"5\" - Deferred (Retail) (для потенциального будущего использования) \"6\" - Air (Retail) (для потенциального будущего использования) \"7\" - Surface (Retail) (для потенциального будущего использования) \"8\" - Premium (Network Access) \"9\" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Создать кодовый текст из данных Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный \"XY11 \" (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки.

### getFormat() {#getformat}

\"0\" – Null или Test \"1\" – Letter \"2\" – Large Letter

### getItemID() {#getitemid}

Максимальное значение равно 99999999.

### getSupplychainID() {#getsupplychainid}

Максимальные значения: 99 для Barcode C и 999999 для Barcode L.

### getVersionID() {#getversionid}

В настоящее время \"1\" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования)

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует данные Mailmark из построенного кодового текста.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setClass_() {#setclass-}

\"0\" - Null или Test \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - Premium (RetailPublishing Mail) (для потенциального будущего использования) \"5\" - Deferred (Retail) (для потенциального будущего использования) \"6\" - Air (Retail) (для потенциального будущего использования) \"7\" - Surface (Retail) (для потенциального будущего использования) \"8\" - Premium (Network Access) \"9\" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC и DP должны соответствовать формату PAF. Девятисимвольная строка, обозначающая международный \"XY11 \" (обратите внимание на 5 завершающих пробелов) или шаблон символов, обозначающий внутренний сортировочный код. Внутренний сортировочный код состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки.

### setFormat() {#setformat}

\"0\" – Null или Test \"1\" – LetterN \"2\" – Large Letter

### setItemID() {#setitemid}

Максимальное значение равно 99999999.

### setSupplychainID() {#setsupplychainid}

Максимальные значения: 99 для Barcode C и 999999 для Barcode L.

### setVersionID() {#setversionid}

В настоящее время \"1\" – Для штрихкода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования)
