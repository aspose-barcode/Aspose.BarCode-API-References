---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "4-state Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다."
type: docs
weight: 580
url: /ko/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

4-state Royal Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다.

```js
new MailmarkCodetext()
```

`MailmarkCodetext` 클래스의 새 인스턴스를 초기화합니다.

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져옵니다. |
| [getClass_()](#getclass-) | "0" - Null 또는 테스트 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (용 pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark 데이터에서 코드 텍스트를 구성합니다. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC와 DP는 PAF 형식을 준수해야 합니다. 국제 "XY11 "을 나타내는 9자 문자열(뒤에 5개의 공백이 있음). |
| [getFormat()](#getformat) | "0" – Null 또는 테스트 "1" – 문자 "2" – 대문자 |
| [getItemID()](#getitemid) | 최대값은 99999999입니다. |
| [getSupplychainID()](#getsupplychainid) | Barcode C의 최대값은 99이고 Barcode L의 최대값은 999999입니다. |
| [getVersionID()](#getversionid) | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약) |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다. |
| [setClass_()](#setclass-) | "0" - Null 또는 테스트 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (용 pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC와 DP는 PAF 형식을 준수해야 합니다. 국제 "XY11 "을 나타내는 9자 문자열(뒤에 5개의 공백이 있음). |
| [setFormat()](#setformat) | "0" – Null 또는 테스트 "1" – LetterN "2" – 대문자 |
| [setItemID()](#setitemid) | 최대값은 99999999입니다. |
| [setSupplychainID()](#setsupplychainid) | Barcode C의 최대값은 99이고 Barcode L의 최대값은 999999입니다. |
| [setVersionID()](#setversionid) | 현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약) |

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져옵니다.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null 또는 테스트 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (잠재적 향후 사용을 위해) "5" - Deferred (Retail) "6" - Air (Retail) (잠재적 향후 사용을 위해) "7" - Surface (Retail) (잠재적 향후 사용을 위해) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark 데이터에서 코드 텍스트를 구성합니다.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC와 DP는 PAF 형식을 준수해야 합니다. 국제 "XY11 "을 나타내는 9자 문자열(뒤에 5개의 공백이 있음) 또는 국내 정렬 코드를 나타내는 문자 패턴입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다.

### getFormat() {#getformat}

"0" – Null 또는 테스트 "1" – 문자 "2" – 대문자

### getItemID() {#getitemid}

최대값은 99999999입니다.

### getSupplychainID() {#getsupplychainid}

Barcode C의 최대값은 99이고 Barcode L의 최대값은 999999입니다.

### getVersionID() {#getversionid}

현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약)

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setClass_() {#setclass-}

"0" - Null 또는 테스트 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (잠재적 향후 사용을 위해) "5" - Deferred (Retail) "6" - Air (Retail) (잠재적 향후 사용을 위해) "7" - Surface (Retail) (잠재적 향후 사용을 위해) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC와 DP는 PAF 형식을 준수해야 합니다. 국제 "XY11 "을 나타내는 9자 문자열(뒤에 5개의 공백이 있음) 또는 국내 정렬 코드를 나타내는 문자 패턴입니다. 국내 정렬 코드는 외부 우편번호, 내부 우편번호 및 Delivery Point Suffix로 구성됩니다.

### setFormat() {#setformat}

"0" – Null 또는 테스트 "1" – LetterN "2" – 대문자

### setItemID() {#setitemid}

최대값은 99999999입니다.

### setSupplychainID() {#setsupplychainid}

Barcode C의 최대값은 99이고 Barcode L의 최대값은 999999입니다.

### setVersionID() {#setversionid}

현재 "1" – Mailmark 바코드용 (0 및 2~9와 A~Z는 향후 사용을 위해 예약)
