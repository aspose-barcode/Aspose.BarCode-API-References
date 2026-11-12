---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "카드의 필수 요소(필드)"
type: docs
weight: 590
url: /ko/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

카드의 필수 요소(필드)

```js
new MandatoryFields()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, 카드 소지자 주소의 도시 부분, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, 미국 및 캐나다의 카드 소지자 주소 우편번호 부분. 우편번호의 뒤쪽 부분이 |
| [getAddressState()](#getaddressstate) | DAJ, 카드 소지자 주소의 주 부분, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, 카드 소지자 주소의 거리 부분, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, DL/ID가 발급되는 국가. 미국 = USA, 캐나다 = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, 발급 기관에서 할당하거나 계산한 번호, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, 문서가 발급된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, 해당 고객에게 발급된 특정 문서를 다른 발급 문서와 구별할 수 있도록 고유하게 식별하는 번호 |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, 관할 구역별 승인 코드, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, 카드 소지자의 눈 색상. (ANSI D-20 코드). DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, 카드 소지자의 성, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [getFirstName()](#getfirstname) | DAC, 카드 소지자의 이름, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [getHeight()](#getheight) | DAU, 카드 소지자의 키. 인치(in): 인치 수 뒤에 " in"을 붙이며, 예. 6'1'' = "073 in" 센티미터(cm): 센티미터 수 |
| [getMiddleName()](#getmiddlename) | DAD, 카드 소지자의 중간 이름(들). 중간 이름이 여러 개인 경우 쉼표 "," 로 구분해야 함., DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, 관할 구역별 제한 코드, DL, V12ANS |
| [getSex()](#getsex) | DBC, 카드 소지자의 성별. 1 = 남성, 2 = 여성, 9 = 지정되지 않음, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, 관할 구역별 차량 클래스/그룹 코드, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, 카드 소지자 주소의 도시 부분, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, 미국 및 캐나다의 카드 소지자 주소 우편번호 부분. 우편번호의 뒤쪽 부분이 |
| [setAddressState()](#setaddressstate) | DAJ, 카드 소지자 주소의 주 부분, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, 카드 소지자 주소의 거리 부분, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, DL/ID가 발급되는 국가. 미국 = USA, 캐나다 = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, 발급 기관에서 할당하거나 계산한 번호, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, 문서가 발급된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, 해당 고객에게 발급된 특정 문서를 다른 발급 문서와 구별할 수 있도록 고유하게 식별하는 번호 |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, 관할 구역별 승인 코드, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, 카드 소지자의 눈 색상. (ANSI D-20 코드). DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, 카드 소지자의 성, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [setFirstName()](#setfirstname) | DAC, 카드 소지자의 이름, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [setHeight()](#setheight) | DAU, 카드 소지자의 키. 인치(in): 인치 수 뒤에 " in"을 붙이며, 예. 6'1'' = "073 in" 센티미터(cm): 센티미터 수 |
| [setMiddleName()](#setmiddlename) | DAD, 카드 소지자의 중간 이름(들). 중간 이름이 여러 개인 경우 쉼표 "," 로 구분해야 함., DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드 |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, 관할 구역별 제한 코드, DL, V12ANS |
| [setSex()](#setsex) | DBC, 카드 소지자의 성별. 1 = 남성, 2 = 여성, 9 = 지정되지 않음, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, 관할 구역별 차량 클래스/그룹 코드, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, 카드 소지자 주소의 도시 부분, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, 미국 및 캐나다의 카드 소지자 주소에서 우편번호 부분. 미국 우편번호의 뒤쪽 부분을 알 수 없을 경우, 9자리까지 0으로 채워 넣음, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, 카드 소지자 주소의 주 부분, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, 카드 소지자 주소의 거리 부분, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, DL/ID가 발급되는 국가. 미국 = USA, 캐나다 = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, 발급 기관에서 할당하거나 계산한 번호, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, 문서가 발급된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, 해당 고객에게 발급된 특정 문서를 과거에 발급된 다른 문서와 구별할 수 있도록 고유하게 식별하는 번호. 이 번호는 문서 구분, 감사 정보 번호, 재고 관리 등 여러 용도로 사용될 수 있음, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, 관할 구역별 승인 코드, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, 카드 소지자의 눈 색상. (ANSI D-20 코드). DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, 카드 소지자의 성, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, 카드 소지자의 이름, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### getHeight() {#getheight}

DAU, 카드 소지자의 키. 인치(in): 인치 수 뒤에 " in"을 붙이며, 예. 6'1'' = "073 in" 센티미터(cm): 센티미터 수 뒤에 " cm"을 붙이며, 예. 181 centimeters="181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, 카드 소지자의 중간 이름(들). 중간 이름이 여러 개인 경우 쉼표 "," 로 구분해야 함., DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, 관할 구역별 제한 코드, DL, V12ANS

### getSex() {#getsex}

DBC, 카드 소지자의 성별. 1 = 남성, 2 = 여성, 9 = 지정되지 않음, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, 관할 구역별 차량 클래스/그룹 코드, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, 카드 소지자 주소의 도시 부분, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, 미국 및 캐나다의 카드 소지자 주소에서 우편번호 부분. 미국 우편번호의 뒤쪽 부분을 알 수 없을 경우, 9자리까지 0으로 채워 넣음, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, 카드 소지자 주소의 주 부분, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, 카드 소지자 주소의 거리 부분, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, DL/ID가 발급되는 국가. 미국 = USA, 캐나다 = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, 발급 기관에서 할당하거나 계산한 번호, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, 문서가 발급된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, 해당 고객에게 발급된 특정 문서를 과거에 발급된 다른 문서와 구별할 수 있도록 고유하게 식별하는 번호. 이 번호는 문서 구분, 감사 정보 번호, 재고 관리 등 여러 용도로 사용될 수 있음, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, 관할 구역별 승인 코드, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, 카드 소지자의 눈 색상. (ANSI D-20 코드). DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, 카드 소지자의 성, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, 카드 소지자의 이름, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### setHeight() {#setheight}

DAU, 카드 소지자의 키. 인치(in): 인치 수 뒤에 " in"을 붙이며, 예. 6'1'' = "073 in" 센티미터(cm): 센티미터 수 뒤에 " cm"을 붙이며, 예. 181 centimeters="181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, 카드 소지자의 중간 이름(들). 중간 이름이 여러 개인 경우 쉼표 "," 로 구분해야 함., DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, 필드가 잘렸는지(T), 잘리지 않았는지(N), 혹은 잘렸는지 알 수 없는지(U)를 나타내는 코드, DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, 관할 구역별 제한 코드, DL, V12ANS

### setSex() {#setsex}

DBC, 카드 소지자의 성별. 1 = 남성, 2 = 여성, 9 = 지정되지 않음, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, 관할 구역별 차량 클래스/그룹 코드, DL, V6ANS
