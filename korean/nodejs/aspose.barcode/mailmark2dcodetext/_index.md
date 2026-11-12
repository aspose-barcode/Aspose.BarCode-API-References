---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다."
type: docs
weight: 570
url: /ko/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하는 클래스입니다.

```js
new Mailmark2DCodetext()
```

Mailmark2DCodetext 클래스의 기본 인스턴스를 생성합니다.

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 바코드 유형을 가져옵니다. |
| [getClass_()](#getclass-) | 항목의 클래스를 식별합니다. 유효값: '1' - 1C(소매) '2' - 2C(소매) '3' - Economy(소매) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Mailmark 데이터에서 코드 텍스트를 구성합니다. |
| [getCustomerContent()](#getcustomercontent) | 고객이 사용할 수 있는 선택적 공간입니다. 유형별 최대 길이: Type 7: 6자, Type 9: 45자, Type 29: 25자 |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Datamatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | DPS가 포함된 배송 주소의 우편번호를 포함합니다. 내륙인 경우 우편번호/DP는 다음 문자 수를 포함합니다. |
| [getInformationTypeID()](#getinformationtypeid) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬 |
| [getItemID()](#getitemid) | 공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드에는 식별을 위해 ID가 포함되어야 합니다. |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | 반송자 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식에 따라야 합니다. |
| [getRTSFlag()](#getrtsflag) | 요청된 반송자 서비스 수준을 나타내는 플래그입니다. |
| [getSupplyChainID()](#getsupplychainid) | 메일링에 관여하는 고유 고객 그룹을 식별합니다. 최대값: 9999999. |
| [getUPUCountryID()](#getupucountryid) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [getVersionID()](#getversionid) | 각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9' 및 |
| [initFromString(constructedCodetext)](#initfromstring) | 구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다. |
| [setClass_(value)](#setclass-) | 항목의 클래스를 식별합니다. 유효값: '1' - 1C(소매) '2' - 2C(소매) '3' - Economy(소매) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | 고객이 사용할 수 있는 선택적 공간입니다. 유형별 최대 길이: Type 7: 6자, Type 9: 45자, Type 29: 25자 |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Datamatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | DPS가 포함된 배송 주소의 우편번호를 포함합니다. 내륙인 경우 우편번호/DP는 다음 문자 수를 포함합니다. |
| [setInformationTypeID(value)](#setinformationtypeid) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬 |
| [setItemID(value)](#setitemid) | 공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드에는 식별을 위해 ID가 포함되어야 합니다. |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | 반송자 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식에 따라야 합니다. |
| [setRTSFlag()](#setrtsflag) | 요청된 반송자 서비스 수준을 나타내는 플래그입니다. |
| [setSupplyChainID(value)](#setsupplychainid) | 메일링에 관여하는 고유 고객 그룹을 식별합니다. 최대값: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [setVersionID(value)](#setversionid) | 각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9' 및 |

### getBarcodeType() {#getbarcodetype}

바코드 유형을 가져옵니다.

**Returns:** Barcode type.

### getClass_() {#getclass-}

항목의 클래스를 식별합니다. 유효값: '1' - 1C (소매) '2' - 2C (소매) '3' - Economy (소매) '5' - Deffered (소매) '8' - Premium (네트워크 액세스) '9' - Standard (네트워크 액세스)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Mailmark 데이터에서 코드 텍스트를 구성합니다.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

고객이 사용할 수 있는 선택 공간입니다. 유형별 최대 길이: 유형 7: 6자, 유형 9: 45자, 유형 29: 25자

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Datamatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

배송 주소의 우편번호와 DPS를 포함합니다. 내륙인 경우 우편번호/DP는 다음 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편번호와 DPS는 유효한 PAF® 형식을 따라야 합니다.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

각 제품 유형에 대한 로열 메일 Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬 'A' - 온라인 우편 'B' - 프랭킹 'C' - 통합

**Returns:** Information type ID

### getItemID() {#getitemid}

Supply Chain ID 내에서 고유 항목을 식별합니다. 모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다. 최대값: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

반송자 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식에 따라야 합니다.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

요청된 반송자 서비스 수준을 나타내는 플래그입니다.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

메일링에 관여하는 고유 고객 그룹을 식별합니다. 최대값: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

UPU 국가 ID를 식별합니다. 최대 길이: 4자.

**Returns:** Country ID

### getVersionID() {#getversionid}

각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9' 및 'A'~'Z'는 향후 사용을 위해 예약됩니다.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

구성된 코드 텍스트에서 Mailmark 데이터를 초기화합니다.

| 매개변수 | 설명 |
| --- | --- |
| constructedCodetext | 구성된 코드텍스트. |

### setClass_(value) {#setclass-}

항목의 클래스를 식별합니다. 유효값: '1' - 1C (소매) '2' - 2C (소매) '3' - Economy (소매) '5' - Deffered (소매) '8' - Premium (네트워크 액세스) '9' - Standard (네트워크 액세스)

| 매개변수 | 설명 |
| --- | --- |
| 값 | 항목의 클래스 |

### setCustomerContent(value) {#setcustomercontent}

고객이 사용할 수 있는 선택 공간입니다. 유형별 최대 길이: 유형 7: 6자, 유형 9: 45자, 유형 29: 25자

| 매개변수 | 설명 |
| --- | --- |
| 값 | 고객 콘텐츠 |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Datamatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Datamatrix 바코드의 인코드 모드. |

### setDataMatrixType(value) {#setdatamatrixtype}

2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Data Matrix 바코드의 크기. |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

배송 주소의 우편번호와 DPS를 포함합니다. 내륙인 경우 우편번호/DP는 다음 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편번호와 DPS는 유효한 PAF® 형식을 따라야 합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 배송 주소의 우편번호와 DPS |

### setInformationTypeID(value) {#setinformationtypeid}

각 제품 유형에 대한 로열 메일 Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬 'A' - 온라인 우편 'B' - 프랭킹 'C' - 통합

| 매개변수 | 설명 |
| --- | --- |
| 값 | 정보 유형 ID |

### setItemID(value) {#setitemid}

Supply Chain ID 내에서 고유 항목을 식별합니다. 모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다. 최대값: 99999999.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Supply Chain ID 내의 항목 |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

반송자 우편번호를 포함하지만 DPS는 포함하지 않습니다. DPS가 없는 PC는 PAF® 형식에 따라야 합니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | 반송 우편 번호(하지만 DPS 없음) |

### setRTSFlag() {#setrtsflag}

요청된 반송자 서비스 수준을 나타내는 플래그입니다.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

메일링에 관여하는 고유 고객 그룹을 식별합니다. 최대값: 9999999.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Supply chain ID |

### setUPUCountryID(value) {#setupucountryid}

UPU 국가 ID를 식별합니다. 최대 길이: 4자.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Country ID |

### setVersionID(value) {#setversionid}

각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9' 및 'A'~'Z'는 향후 사용을 위해 예약됩니다.

| 매개변수 | 설명 |
| --- | --- |
| 값 | Version ID |
