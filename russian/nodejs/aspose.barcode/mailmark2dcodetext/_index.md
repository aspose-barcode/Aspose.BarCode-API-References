---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /ru/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Создать экземпляр по умолчанию класса Mailmark2DCodetext.

## Методы

| Имя | Описание |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Получает тип штрих‑кода. |
| [getClass_()](#getclass-) | Идентифицирует класс элемента. Допустимые значения: '1' - 1C (розничный) '2' - 2C (розничный) '3' - Economy (розничный) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Создать кодовый текст из данных Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Опциональное пространство для использования клиентом. Максимальная длина по типу: Type 7: 6 символов Type 9: 45 символов Type 29: 25 символов |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Режим кодирования штрихкода Datamatrix. Значение по умолчанию: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов |
| [getInformationTypeID()](#getinformationtypeid) | Идентифицирует полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Содержит почтовый код возврата отправителю, но без DPS. Почтовый код (без DPS) должен соответствовать формату PAF®. |
| [getRTSFlag()](#getrtsflag) | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
| [getSupplyChainID()](#getsupplychainid) | Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
| [getVersionID()](#getversionid) | Определяет версию штрих‑кода, относящуюся к каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9' ... |
| [initFromString(constructedCodetext)](#initfromstring) | Инициализирует данные Mailmark из построенного кодового текста. |
| [setClass_(value)](#setclass-) | Идентифицирует класс элемента. Допустимые значения: '1' - 1C (розничный) '2' - 2C (розничный) '3' - Economy (розничный) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Опциональное пространство для использования клиентом. Максимальная длина по типу: Type 7: 6 символов Type 9: 45 символов Type 29: 25 символов |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Режим кодирования штрихкода Datamatrix. Значение по умолчанию: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Тип 2D Mailmark определяет размер штрихкода Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов |
| [setInformationTypeID(value)](#setinformationtypeid) | Идентифицирует полезную нагрузку штрихкода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Содержит почтовый код возврата отправителю, но без DPS. Почтовый код (без DPS) должен соответствовать формату PAF®. |
| [setRTSFlag()](#setrtsflag) | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
| [setSupplyChainID(value)](#setsupplychainid) | Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
| [setVersionID(value)](#setversionid) | Определяет версию штрих‑кода, относящуюся к каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9' ... |

### getBarcodeType() {#getbarcodetype}

Получает тип штрих‑кода.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Определяет класс элемента. Допустимые значения: '1' - 1C (розничный) '2' - 2C (розничный) '3' - Economy (розничный) '5' - Deferred (розничный) '8' - Premium (сетевой доступ) '9' - Standard (сетевой доступ)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Создать кодовый текст из данных Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Опциональное пространство для использования клиентом. Максимальная длина по типу: Тип 7: 6 символов; Тип 9: 45 символов; Тип 29: 25 символов.

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Режим кодирования штрихкода Datamatrix. Значение по умолчанию: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Тип 2D Mailmark определяет размер штрихкода Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Подразделение (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Внутренний сортированный и несортированный; 'A' - Онлайн‑почтовые услуги; 'B' - Франкировка; 'C' - Консолидация.

**Returns:** Information type ID

### getItemID() {#getitemid}

Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать минимум 90 дней. Максимальное значение: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Содержит почтовый код возврата отправителю, но без DPS. Почтовый код (без DPS) должен соответствовать формату PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Определяет идентификатор страны UPU. Максимальная длина: 4 символа.

**Returns:** Country ID

### getVersionID() {#getversionid}

Определяет версию штрих‑кода, относящуюся к каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Инициализирует данные Mailmark из построенного кодового текста.

| Параметр | Описание |
| --- | --- |
| constructedCodetext | Построенный codetext. |

### setClass_(value) {#setclass-}

Определяет класс элемента. Допустимые значения: '1' - 1C (розничный) '2' - 2C (розничный) '3' - Economy (розничный) '5' - Deferred (розничный) '8' - Premium (сетевой доступ) '9' - Standard (сетевой доступ)

| Параметр | Описание |
| --- | --- |
| значение | класс элемента |

### setCustomerContent(value) {#setcustomercontent}

Опциональное пространство для использования клиентом. Максимальная длина по типу: Тип 7: 6 символов; Тип 9: 45 символов; Тип 29: 25 символов.

| Параметр | Описание |
| --- | --- |
| значение | Контент клиента |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Режим кодирования штрихкода Datamatrix. Значение по умолчанию: DataMatrixEncodeMode.C40.

| Параметр | Описание |
| --- | --- |
| значение | Режим кодирования штрих‑кода DataMatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

Тип 2D Mailmark определяет размер штрихкода Data Matrix.

| Параметр | Описание |
| --- | --- |
| значение | Размер штрих‑кода Data Matrix. |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Содержит почтовый индекс адреса доставки с DPS. Если внутри страны, почтовый индекс/DP содержит следующее количество символов. Область (1 или 2 символа) Округ (1 или 2 символа) Сектор (1 символ) Подразделение (2 символа) DPS (2 символа). Почтовый индекс и DPS должны соответствовать действительному формату PAF®.

| Параметр | Описание |
| --- | --- |
| значение | почтовый индекс адреса доставки с DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. Допустимые значения: '0' - Внутренний сортированный и несортированный; 'A' - Онлайн‑почтовые услуги; 'B' - Франкировка; 'C' - Консолидация.

| Параметр | Описание |
| --- | --- |
| значение | Идентификатор типа информации |

### setItemID(value) {#setitemid}

Определяет уникальный элемент в рамках идентификатора цепочки поставок. Каждый штрих‑код Mailmark должен содержать идентификатор, чтобы его можно было уникально идентифицировать минимум 90 дней. Максимальное значение: 99999999.

| Параметр | Описание |
| --- | --- |
| значение | элемент в рамках идентификатора цепочки поставок |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Содержит почтовый код возврата отправителю, но без DPS. Почтовый код (без DPS) должен соответствовать формату PAF®.

| Параметр | Описание |
| --- | --- |
| значение | Почтовый код возврата отправителю без DPS |

### setRTSFlag() {#setrtsflag}

Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Определяет уникальную группу клиентов, участвующих в рассылке. Максимальное значение: 9999999.

| Параметр | Описание |
| --- | --- |
| значение | Идентификатор цепочки поставок |

### setUPUCountryID(value) {#setupucountryid}

Определяет идентификатор страны UPU. Максимальная длина: 4 символа.

| Параметр | Описание |
| --- | --- |
| значение | Идентификатор страны |

### setVersionID(value) {#setversionid}

Определяет версию штрих‑кода, относящуюся к каждому идентификатору типа информации. Допустимые значения: в настоящее время '1'. '0' и от '2' до '9', а также от 'A' до 'Z' зарезервированы для потенциального будущего использования.

| Параметр | Описание |
| --- | --- |
| значение | Идентификатор версии |
