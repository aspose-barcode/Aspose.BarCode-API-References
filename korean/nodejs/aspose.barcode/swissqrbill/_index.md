---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "SwissQR 청구서 데이터"
type: docs
weight: 920
url: /ko/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR 청구서 데이터

```js
new SwissQRBill()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | 원시 문자열에 \"RF\"를 접두사로 붙이고 modulo 97 검사를 수행하여 ISO11649 채권자 참조를 생성하고 설정합니다. |
| [equals(obj)](#equals) | 지정된 객체가 현재 객체와 같은지 여부를 결정합니다. |
| [getAccount()](#getaccount) | 채권자의 계좌 번호를 가져옵니다. 계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | 대체 결제 방식을 가져오거나 설정합니다. 매개변수가 있는 최대 두 개의 방식을 허용합니다. |
| [getAmount()](#getamount) | 결제 금액을 가져옵니다. 유효 값은 0.01부터 999,999,999.99까지입니다. |
| [getBillInformation()](#getbillinformation) | 추가 구조화된 청구서 정보를 가져옵니다. |
| [getCreditor()](#getcreditor) | 채권자 주소를 가져옵니다. |
| [getCurrency()](#getcurrency) | 결제 통화를 가져옵니다. 유효 값은 \"CHF\"와 \"EUR\"입니다. |
| [getDebtor()](#getdebtor) | 채무자 주소를 가져옵니다. 채무자는 선택 사항입니다. 생략할 경우, 이 필드를 null로 설정하거나 주소를 설정하는 두 가지 방법이 가능합니다. |
| [getReference()](#getreference) | 채권자 결제 참조를 가져옵니다. 이 참조는 SwissQR IBAN에 필수이며, 예를 들어 CHxx30000xxxxx 범위의 IBAN에 적용됩니다. |
| [getUnstructuredMessage()](#getunstructuredmessage) | 추가 비구조화 메시지를 가져옵니다. |
| [getVersion()](#getversion) | SwissQR 청구서 표준의 버전을 가져옵니다. |
| [hashCode()](#hashcode) | 이 인스턴스의 해시 코드를 가져옵니다. |
| [setAccount(value:)](#setaccount) | 채권자의 계좌 번호를 설정합니다. 계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. 공백 |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | 대체 결제 방식을 가져오거나 설정합니다. 매개변수가 있는 최대 두 개의 방식을 허용합니다. |
| [setAmount(value)](#setamount) | 결제 금액을 설정합니다. 유효한 값은 0.01에서 999,999,999.99 사이입니다. |
| [setBillInformation(value:)](#setbillinformation) | 추가 구조화된 청구서 정보를 설정합니다. |
| [setCreditor(value:)](#setcreditor) | 채권자 주소를 설정합니다. |
| [setCurrency(value)](#setcurrency) | 결제 통화를 설정합니다. |
| [setDebtor(value:)](#setdebtor) | 채무자 주소를 설정합니다. 채무자는 선택 사항입니다. 생략될 경우, 이 필드를 null로 설정하거나 주소를 설정하는 |
| [setReference(value)](#setreference) | 채권자 결제 참조를 설정합니다. 이 참조는 SwissQR IBAN에 대해 필수이며, 예를 들어 CHxx30000xxxxx 범위의 IBAN에 적용됩니다. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | 추가 비구조화 메시지를 설정합니다. |
| [setVersion(value)](#setversion) | SwissQR 청구서 표준의 버전을 설정합니다. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

원시 문자열에 "RF"를 앞에 붙이고 modulo 97 체크섬을 적용하여 ISO11649 채권자 참조를 생성하고 설정합니다. 참조에서 공백이 제거됩니다.

| 매개변수 | 설명 |
| --- | --- |
| rawReference | 원시 참조입니다. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

지정된 객체가 현재 객체와 같은지 여부를 결정합니다.

| 매개변수 | 설명 |
| --- | --- |
| obj | 현재 객체와 비교할 객체. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

채권자의 계좌 번호를 가져옵니다. 계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. 계좌 번호에 공백을 허용합니다.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

대체 결제 방식을 가져오거나 설정합니다. 매개변수가 있는 최대 두 개의 방식을 허용합니다.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

결제 금액을 가져옵니다. 유효 값은 0.01부터 999,999,999.99까지입니다.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

추가 구조화된 청구서 정보를 가져옵니다.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

채권자 주소를 가져옵니다.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

결제 통화를 가져옵니다. 유효 값은 \"CHF\"와 \"EUR\"입니다.

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

채무자 주소를 가져옵니다. 채무자는 선택 사항입니다. 생략될 경우, 이 필드를 null로 설정하거나 모든 값이 null 또는 비어 있는 주소를 설정하는 두 방법 모두 허용됩니다.

**Returns:** The debtor address.

### getReference() {#getreference}

채권자 결제 참조를 가져옵니다. 이 참조는 SwissQR IBAN에 대해 필수이며, 예를 들어 CHxx30000xxxxxx부터 CHxx31999xxxxx까지의 범위에 해당합니다. 지정된 경우, 참조는 유효한 SwissQR 참조( ISR 참조 양식에 해당) 또는 ISO 11649에 따른 유효한 채권자 참조("RFxxxx") 중 하나여야 합니다. 두 경우 모두 형식을 위해 공백을 포함할 수 있습니다.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

추가 비구조화 메시지를 가져옵니다.

**Returns:** The unstructured message.

### getVersion() {#getversion}

SwissQR 청구서 표준의 버전을 가져옵니다.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

이 인스턴스의 해시 코드를 가져옵니다.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

채권자의 계좌 번호를 설정합니다. 계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다. 계좌 번호에 공백을 허용합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 채권자 계좌 번호. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

대체 결제 방식을 가져오거나 설정합니다. 매개변수가 있는 최대 두 개의 방식을 허용합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 대체 결제 방식. |

### setAmount(value) {#setamount}

결제 금액을 설정합니다. 유효한 값은 0.01에서 999,999,999.99 사이입니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 결제 금액. |

### setBillInformation(value:) {#setbillinformation}

추가 구조화된 청구서 정보를 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 구조화된 청구서 정보. |

### setCreditor(value:) {#setcreditor}

채권자 주소를 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 채권자 주소. |

### setCurrency(value) {#setcurrency}

결제 통화를 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 유효한 값은 "CHF"와 "EUR"입니다. |

### setDebtor(value:) {#setdebtor}

채무자 주소를 설정합니다. 채무자는 선택 사항입니다. 생략될 경우, 이 필드를 null로 설정하거나 모든 값이 null 또는 비어 있는 주소를 설정하는 두 방법 모두 허용됩니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 채무자 주소. |

### setReference(value) {#setreference}

채권자 결제 참조를 설정합니다. 이 참조는 SwissQR IBAN에 대해 필수이며, 예를 들어 CHxx30000xxxxxx부터 CHxx31999xxxxx까지의 범위에 해당하는 IBAN입니다. 지정된 경우, 참조는 유효한 SwissQR 참조( ISR 참조 양식에 해당) 또는 ISO 11649("RFxxxx")에 따른 유효한 채권자 참조여야 합니다. 두 경우 모두 형식을 위해 공백을 포함할 수 있습니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 채권자 결제 참조. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

추가 비구조화 메시지를 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값: | 구조화되지 않은 메시지. |

### setVersion(value) {#setversion}

SwissQR 청구서 표준의 버전을 설정합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | SwissQR 청구서 표준 버전. |
