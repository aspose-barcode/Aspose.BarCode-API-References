---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Данные счета SwissQR"
type: docs
weight: 920
url: /ru/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Данные счета SwissQR

```js
new SwissQRBill()
```

## Методы

| Имя | Описание |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Создаёт и задаёт ссылку кредитора ISO11649 из исходной строки, добавляя к строке префикс \"RF\" и вычисляя контрольную сумму modulo 97 che |
| [equals(obj)](#equals) | Определяет, равен ли указанный объект текущему объекту. |
| [getAccount()](#getaccount) | Получает номер счёта кредитора. Номера счетов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Получает или задаёт альтернативные схемы оплаты. Допускается максимум две схемы с параметрами. |
| [getAmount()](#getamount) | Получает сумму платежа. Допустимые значения от 0,01 до 999 999 999,99. |
| [getBillInformation()](#getbillinformation) | Получает дополнительную структурированную информацию счёта. |
| [getCreditor()](#getcreditor) | Получает адрес кредитора. |
| [getCurrency()](#getcurrency) | Получает валюту платежа. Допустимые значения: \"CHF\" и \"EUR\". |
| [getDebtor()](#getdebtor) | Получает адрес должника. Должник является необязательным. Если он опущен, допускается как установка этого поля в null, так и указание адреса |
| [getReference()](#getreference) | Получает платёжную ссылку кредитора. Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Получает дополнительное неструктурированное сообщение. |
| [getVersion()](#getversion) | Получает версию стандарта счёта SwissQR. |
| [hashCode()](#hashcode) | Получает хеш-код для этого экземпляра. |
| [setAccount(value:)](#setaccount) | Устанавливает номер счёта кредитора. Номера счётов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Пробел |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Получает или устанавливает альтернативные схемы оплаты. Разрешено максимум две схемы с параметрами. |
| [setAmount(value)](#setamount) | Устанавливает сумму платежа. Допустимые значения от 0.01 до 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Устанавливает дополнительную структурированную информацию счёта. |
| [setCreditor(value:)](#setcreditor) | Устанавливает адрес кредитора. |
| [setCurrency(value)](#setcurrency) | Устанавливает валюту платежа. |
| [setDebtor(value:)](#setdebtor) | Устанавливает адрес должника. Должник является необязательным. Если он опущен, допускается как установка этого поля в null, так и указание адреса |
| [setReference(value)](#setreference) | Устанавливает платёжную ссылку кредитора. Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Устанавливает дополнительное неструктурированное сообщение. |
| [setVersion(value)](#setversion) | Устанавливает версию стандарта счёта SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Создаёт и устанавливает ссылку кредитора ISO11649 из необработанной строки, добавляя к строке префикс "RF" и контрольную сумму по модулю 97. Пробелы удаляются из ссылки.

| Параметр | Описание |
| --- | --- |
| rawReference | Необработанная ссылка. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Определяет, равен ли указанный объект текущему объекту.

| Параметр | Описание |
| --- | --- |
| obj | Объект для сравнения с текущим объектом. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Получает номер счёта кредитора. Номера счётов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Пробелы разрешены в номере счёта.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Получает или задаёт альтернативные схемы оплаты. Допускается максимум две схемы с параметрами.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Получает сумму платежа. Допустимые значения от 0,01 до 999 999 999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Получает дополнительную структурированную информацию счёта.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Получает адрес кредитора.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Получает валюту платежа. Допустимые значения: \"CHF\" и \"EUR\".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Получает адрес должника. Должник является необязательным. Если он опущен, допускается как установка этого поля в null, так и указание адреса со всеми значениями null или пустыми.

**Returns:** The debtor address.

### getReference() {#getreference}

Получает платёжную ссылку кредитора. Ссылка обязательна для SwissQR IBAN, т.е. IBAN в диапазоне от CHxx30000xxxxxx до CHxx31999xxxxx. Если указана, ссылка должна быть либо действительной SwissQR ссылкой (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx"). Обе могут содержать пробелы для форматирования.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Получает дополнительное неструктурированное сообщение.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Получает версию стандарта счёта SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Получает хеш-код для этого экземпляра.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Устанавливает номер счёта кредитора. Номера счётов должны быть действительными IBAN банков Швейцарии или Лихтенштейна. Пробелы разрешены в номере счёта.

| Параметр | Описание |
| --- | --- |
| значение: | Номер счёта кредитора. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Получает или устанавливает альтернативные схемы оплаты. Разрешено максимум две схемы с параметрами.

| Параметр | Описание |
| --- | --- |
| значение: | Альтернативные схемы оплаты. |

### setAmount(value) {#setamount}

Устанавливает сумму платежа. Допустимые значения от 0.01 до 999,999,999.99.

| Параметр | Описание |
| --- | --- |
| значение | Сумма платежа. |

### setBillInformation(value:) {#setbillinformation}

Устанавливает дополнительную структурированную информацию счёта.

| Параметр | Описание |
| --- | --- |
| значение: | Структурированная информация счёта. |

### setCreditor(value:) {#setcreditor}

Устанавливает адрес кредитора.

| Параметр | Описание |
| --- | --- |
| значение: | Адрес кредитора. |

### setCurrency(value) {#setcurrency}

Устанавливает валюту платежа.

| Параметр | Описание |
| --- | --- |
| значение | Допустимые значения: "CHF" и "EUR". |

### setDebtor(value:) {#setdebtor}

Устанавливает адрес должника. Должник является необязательным. Если он опущен, допустимо как установить это поле в null, так и задать адрес со всеми значениями null или пустыми — ок.

| Параметр | Описание |
| --- | --- |
| значение: | Адрес должника. |

### setReference(value) {#setreference}

Устанавливает ссылку платежа кредитора. Ссылка обязательна для SwissQR IBANs, т.е. IBAN в диапазоне CHxx30000xxxxxx до CHxx31999xxxxx. Если указана, ссылка должна быть либо действительной SwissQR ссылкой (соответствующей форме ISR), либо действительной ссылкой кредитора согласно ISO 11649 ("RFxxxx"). Оба могут содержать пробелы для форматирования.

| Параметр | Описание |
| --- | --- |
| значение | Ссылка платежа кредитора. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Устанавливает дополнительное неструктурированное сообщение.

| Параметр | Описание |
| --- | --- |
| значение: | Неструктурированное сообщение. |

### setVersion(value) {#setversion}

Устанавливает версию стандарта счёта SwissQR.

| Параметр | Описание |
| --- | --- |
| значение | Версия стандарта счета SwissQR. |
