---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "카드의 선택적 요소(필드)"
type: docs
weight: 730
url: /ko/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

카드의 선택적 요소(필드)

```js
new OptionalFields()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, 카드 소지자가 알려진 기타 성, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, 카드 소지자가 알려진 기타 이름, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, 카드 소지자가 알려진 기타 접미사, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, 운전 면허증/신분증이 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열입니다. If a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, DHS에서 요구하는 필드로, 가장 최근 버전 변경 또는 가시 형식 수정 날짜를 나타냅니다 t의 |
| [getComplianceType()](#getcompliancetype) | DDA, DHS에서 요구하는 필드로, 준수 여부를 나타냅니다: “F” = 준수; 그리고, “N” = 비준수, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, 관할 구역별 코드가 추가 운전 권한을 부여함을 설명하는 텍스트, ca에 |
| [getHairColor()](#gethaircolor) | DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 황갈색, 흰색, 알 수 없음. 발행 관할 구역이 약어를 원할 경우 |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, 문서에 의해 부여된 위험물 허가가 더 이상 유효하지 않은 날짜. (미국은 MMDDCCYY, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, 생산에 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열 |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, DHS에서 요구하는 필드로, 카드 소지자가 임시 합법 상태임을 나타냅니다 = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, 국가 및 시/군 및/또는 주/도, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, 운전 권한을 제한하는 관할 구역별 제한 코드에 대한 설명 텍스트, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, 카드 소지자를 위한 표준 허가 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, 카드 소지자를 위한 표준 제한 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, 카드 소지자를 위한 표준 차량 분류 코드. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [getUnder18Until()](#getunder18until) | DDH, 카드 소지자가 18세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, 카드 소지자가 운전 허가를 받은 차량 분류에 대한 관할 구역별 코드를 설명하는 텍스트 |
| [getVeteranIndicator()](#getveteranindicator) | DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, 카드 소지자의 체중(kg), 예: 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, 카드 소지자의 체중(파운드), 예: 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31 kg 이하(70 lbs 이하), 1 = 32 – 45 kg(71 – 100 lbs |
| [setAddressStreet2()](#setaddressstreet2) | DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, 카드 소지자가 알려진 기타 성, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, 카드 소지자가 알려진 기타 이름, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, 카드 소지자가 알려진 기타 접미사, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, 운전 면허증/신분증이 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열입니다. If a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, DHS에서 요구하는 필드로, 가장 최근 버전 변경 또는 가시 형식 수정 날짜를 나타냅니다 t의 |
| [setComplianceType()](#setcompliancetype) | DDA, DHS에서 요구하는 필드로, 준수 여부를 나타냅니다: “F” = 준수; 그리고, “N” = 비준수, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, 관할 구역별 코드가 추가 운전 권한을 부여함을 설명하는 텍스트, ca에 |
| [setHairColor()](#sethaircolor) | DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 황갈색, 흰색, 알 수 없음. 발행 관할 구역이 약어를 원할 경우 |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, 생산에 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열 |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, DHS에서 요구하는 필드로, 카드 소지자가 임시 합법 상태임을 나타냅니다 = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, 국가 및 시/군 및/또는 주/도, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, 운전 권한을 제한하는 관할 구역별 제한 코드에 대한 설명 텍스트, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, 카드 소지자를 위한 표준 허가 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, 카드 소지자를 위한 표준 제한 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, 카드 소지자를 위한 표준 차량 분류 코드. 이 데이터 요소는 향후 작업을 위한 자리표시자입니다 |
| [setUnder18Until()](#setunder18until) | DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, 카드 소지자가 운전 허가를 받은 차량 분류에 대한 관할 구역별 코드를 설명하는 텍스트 |
| [setVeteranIndicator()](#setveteranindicator) | DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, 카드 소지자의 체중(kg), 예: 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, 카드 소지자의 체중(파운드), 예: 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31 kg 이하(70 lbs 이하), 1 = 32 – 45 kg(71 – 100 lbs |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, 카드 소지자가 알려진 기타 성, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, 카드 소지자가 알려진 기타 이름, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, 카드 소지자가 알려진 기타 접미사, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, 운전 면허증/ID 카드가 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열. 카드나 MRT에 감사 정보가 사용되지 않은 경우, 운전자 기록에 포함되어야 합니다, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, DHS에서 요구하는 필드로, DL/ID의 표시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타냅니다. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, DHS에서 요구하는 필드로, 준수 여부를 나타냅니다: “F” = 준수; 그리고, “N” = 비준수, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, 관할 구역별 코드가 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 내용을 설명하는 텍스트, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 샌디, 흰색, 알 수 없음. 발행 관할 구역이 색상을 약어로 표시하려면 AAMVA D20에서 제공하는 세 글자 코드를 사용해야 합니다, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, 문서에서 부여된 위험물 승인이 더 이상 유효하지 않은 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, 운전 면허증 및 신분증을 제작할 때 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. (DHS 권장 필드), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, DHS에서 요구하는 필드로, 카드 소지자가 임시 합법 상태임을 나타냅니다 = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 합니다). JR(주니어), SR(시니어), 1ST 또는 I(첫 번째), 9TH 또는 IX(아홉 번째)까지, DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, 국가 및 시/군 및/또는 주/도, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, 운전 권한을 제한하는 관할 구역별 제한 코드에 대한 설명 텍스트, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, 카드 소지자를 위한 표준 승인 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 승인 코드를 표준화하기 위한 자리표시자입니다, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, 카드 소지자를 위한 표준 제한 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 제한 코드를 표준화하기 위한 자리표시자입니다, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, 카드 소지자를 위한 표준 차량 분류 코드. 이 데이터 요소는 향후 차량 분류를 표준화하기 위한 자리표시자입니다, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, 카드 소지자가 18세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, 카드 소지자가 운전 허가된 차량 분류에 대한 관할 구역별 코드를 설명하는 텍스트, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, 카드 소지자의 체중(kg), 예: 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, 카드 소지자의 체중(파운드), 예: 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32 – 45kg(71 – 100lb), 2 = 46 - 59kg(101 – 130lb), 3 = 60 - 70kg(131 – 160lb), 4 = 71 - 86kg(161 – 190lb), 5 = 87 - 100kg(191 – 220lb), 6 = 101 - 113kg(221 – 250lb), 7 = 114 - 127kg(251 – 280lb), 8 = 128 – 145kg(281 – 320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, 카드 소지자가 알려진 기타 성, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, 카드 소지자가 알려진 기타 이름, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, 카드 소지자가 알려진 기타 접미사, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, 운전 면허증/ID 카드가 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열. 카드나 MRT에 감사 정보가 사용되지 않은 경우, 운전자 기록에 포함되어야 합니다, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, DHS에서 요구하는 필드로, DL/ID의 표시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타냅니다. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, DHS에서 요구하는 필드로, 준수 여부를 나타냅니다: “F” = 준수; 그리고, “N” = 비준수, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, 관할 구역별 코드가 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 내용을 설명하는 텍스트, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 샌디, 흰색, 알 수 없음. 발행 관할 구역이 색상을 약어로 표시하려면 AAMVA D20에서 제공하는 세 글자 코드를 사용해야 합니다, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, 운전 면허증 및 신분증을 제작할 때 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. (DHS 권장 필드), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, DHS에서 요구하는 필드로, 카드 소지자가 임시 합법 상태임을 나타냅니다 = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 합니다). JR(주니어), SR(시니어), 1ST 또는 I(첫 번째), 9TH 또는 IX(아홉 번째)까지, DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, 국가 및 시/군 및/또는 주/도, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, 운전 권한을 제한하는 관할 구역별 제한 코드에 대한 설명 텍스트, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, 카드 소지자를 위한 표준 승인 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 승인 코드를 표준화하기 위한 자리표시자입니다, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, 카드 소지자를 위한 표준 제한 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 제한 코드를 표준화하기 위한 자리표시자입니다, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, 카드 소지자를 위한 표준 차량 분류 코드. 이 데이터 요소는 향후 차량 분류를 표준화하기 위한 자리표시자입니다, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, 카드 소지자가 운전 허가된 차량 분류에 대한 관할 구역별 코드를 설명하는 텍스트, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, 카드 소지자의 체중(kg), 예: 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, 카드 소지자의 체중(파운드), 예: 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32 – 45kg(71 – 100lb), 2 = 46 - 59kg(101 – 130lb), 3 = 60 - 70kg(131 – 160lb), 4 = 71 - 86kg(161 – 190lb), 5 = 87 - 100kg(191 – 220lb), 6 = 101 - 113kg(221 – 250lb), 7 = 114 - 127kg(251 – 280lb), 8 = 128 – 145kg(281 – 320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N
