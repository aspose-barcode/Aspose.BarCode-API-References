---
title: USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode for Android via Java API Reference
description: 카드의 선택적 요소 필드
type: docs
weight: 11
url: /ko/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

카드의 선택적 요소(필드)
## Constructors

| Constructor | 설명 |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, 카드 소지자가 알려진 다른 성, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, 카드 소지자가 알려진 다른 이름, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, 카드 소지자가 알려진 다른 접미사, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, 운전 면허증/신분증이 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, DL/ID의 가시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타내는 DHS 필수 필드. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, 준수를 나타내는 DHS 필수 필드: \u201cF\u201d = 준수; 그리고 \u201cN\u201d = 비준수, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, 문서에 부여된 위험 물질 허가가 더 이상 유효하지 않은 날짜. |
| [getHairColor()](#getHairColor--) | DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 황갈색, 흰색, 알 수 없음. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, 운전 면허증 및 신분증 제작에 사용되는 원자재(카드 재질, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, 카드 소지자가 임시 합법 상태임을 나타내는 DHS 필수 필드 = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 함). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, 국가 및 지방자치단체 및/또는 주/도, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, 운전 권한을 제한하는 관할 구역별 제한 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, 카드 소지자를 위한 표준 승인 코드(들). |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, 카드 소지자를 위한 표준 제한 코드(들). |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, 카드 소지자를 위한 표준 차량 분류 코드(들). |
| [getUnder18Until()](#getUnder18Until--) | DDH, 카드 소지자가 18세가 되는 날짜. |
| [getUnder19Until()](#getUnder19Until--) | DDI, 카드 소지자가 19세가 되는 날짜. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, 카드 소지자가 21세가 되는 날짜. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, 카드 소지자가 운전할 수 있는 차량 분류에 대한 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, 카드 소지자의 체중(kg), 예. |
| [getWeightPounds()](#getWeightPounds--) | DAW, 카드 소지자의 체중(파운드), 예. |
| [getWeightRange()](#getWeightRange--) | DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32–45kg(71–100lb), 2 = 46 - 59kg(101–130lb), 3 = 60 - 70kg(131–160lb), 4 = 71 - 86kg(161–190lb), 5 = 87 - 100kg(191–220lb), 6 = 101 - 113kg(221–250lb), 7 = 114 - 127kg(251–280lb), 8 = 128–145kg(281–320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, 카드 소지자가 알려진 다른 성, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, 카드 소지자가 알려진 다른 이름, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, 카드 소지자가 알려진 다른 접미사, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, 운전 면허증/신분증이 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, DL/ID의 가시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타내는 DHS 필수 필드. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, 준수를 나타내는 DHS 필수 필드: \u201cF\u201d = 준수; 그리고 \u201cN\u201d = 비준수, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/밤색, 황갈색, 흰색, 알 수 없음. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, 운전 면허증 및 신분증 제작에 사용되는 원자재(카드 재질, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, 카드 소지자가 임시 합법 상태임을 나타내는 DHS 필수 필드 = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 함). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, 국가 및 지방자치단체 및/또는 주/도, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, 운전 권한을 제한하는 관할 구역별 제한 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, 카드 소지자를 위한 표준 승인 코드(들). |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, 카드 소지자를 위한 표준 제한 코드(들). |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, 카드 소지자를 위한 표준 차량 분류 코드(들). |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, 카드 소지자가 18세가 되는 날짜. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, 카드 소지자가 19세가 되는 날짜. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, 카드 소지자가 21세가 되는 날짜. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, 카드 소지자가 운전할 수 있는 차량 분류에 대한 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, 카드 소지자의 체중(kg), 예. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, 카드 소지자의 체중(파운드), 예. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32–45kg(71–100lb), 2 = 46 - 59kg(101–130lb), 3 = 60 - 70kg(131–160lb), 4 = 71 - 86kg(161–190lb), 5 = 87 - 100kg(191–220lb), 6 = 101 - 113kg(221–250lb), 7 = 114 - 127kg(251–280lb), 8 = 128–145kg(281–320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, 카드 소지자가 알려진 다른 성, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, 카드 소지자가 알려진 다른 이름, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, 카드 소지자가 알려진 다른 접미사, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, 운전 면허/ID 카드가 언제, 어디서, 누가 제작했는지 식별하는 문자 및/또는 숫자 문자열. 카드나 MRT에 감사 정보가 사용되지 않은 경우 운전 기록에 포함되어야 함, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, DHS 필수 필드로, DL/ID의 가시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타냄. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA, 준수를 나타내는 DHS 필수 필드: \u201cF\u201d = 준수; 그리고 \u201cN\u201d = 비준수, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, 문서에 의해 부여된 위험물 허가가 더 이상 유효하지 않은 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, 대머리, 검정, 금발, 갈색, 회색, 빨강/적갈색, 황갈색, 흰색, 알 수 없음. 발행 관할 구역이 색상을 약어로 표시하려면 AAMVA D20에 제공된 세 글자 코드를 사용해야 함, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, 운전 면허 및 ID 카드를 제작하는 데 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. (DHS 권장 필드), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, 카드 소지자가 임시 합법 상태임을 나타내는 DHS 필수 필드 = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, 이름 접미사 (관할 구역이 PDPS, CDLIS 등 이름 접미사를 요구하는 시스템에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 함). JR(주니어), SR(시니어), 1ST 또는 I(첫 번째), 최대 9TH 또는 IX(아홉 번째), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, 국가 및 지방자치단체 및/또는 주/도, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, 운전 권한을 제한하는 관할 구역별 제한 코드(들)를 설명하는 텍스트, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, 카드 소지자를 위한 표준 허가 코드(들). D20의 코드를 참조. 이 데이터 요소는 향후 허가 코드 표준화를 위한 자리표시자임, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, 카드 소지자를 위한 표준 제한 코드(들). D20의 코드를 참조. 이 데이터 요소는 향후 제한 코드 표준화를 위한 자리표시자임, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, 카드 소지자를 위한 표준 차량 분류 코드(들). 이 데이터 요소는 향후 차량 분류 표준화를 위한 자리표시자임, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, 카드 소지자가 18세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, 카드 소지자가 운전할 수 있는 차량 분류에 대한 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, 카드 소지자의 체중(kg), 예. 84 kg = "084", DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, 카드 소지자의 체중(파운드), 예. 185 lb = "185", DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32–45kg(71–100lb), 2 = 46 - 59kg(101–130lb), 3 = 60 - 70kg(131–160lb), 4 = 71 - 86kg(161–190lb), 5 = 87 - 100kg(191–220lb), 6 = 101 - 113kg(221–250lb), 7 = 114 - 127kg(251–280lb), 8 = 128–145kg(281–320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, 카드 소지자가 알려진 다른 성, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, 카드 소지자가 알려진 다른 이름, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, 카드 소지자가 알려진 다른 접미사, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, 운전 면허/ID 카드가 언제, 어디서, 누가 제작했는지 식별하는 문자 및/또는 숫자 문자열. 카드나 MRT에 감사 정보가 사용되지 않은 경우 운전 기록에 포함되어야 함, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, DHS 필수 필드로, DL/ID의 가시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타냄. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, 준수를 나타내는 DHS 필수 필드: \u201cF\u201d = 준수; 그리고 \u201cN\u201d = 비준수, DL/ID, F1A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, 대머리, 검정, 금발, 갈색, 회색, 빨강/적갈색, 황갈색, 흰색, 알 수 없음. 발행 관할 구역이 색상을 약어로 표시하려면 AAMVA D20에 제공된 세 글자 코드를 사용해야 함, DL/ID, V12A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, 운전 면허 및 ID 카드를 제작하는 데 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. (DHS 권장 필드), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, 카드 소지자가 임시 합법 상태임을 나타내는 DHS 필수 필드 = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, 이름 접미사 (관할 구역이 PDPS, CDLIS 등 이름 접미사를 요구하는 시스템에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 함). JR(주니어), SR(시니어), 1ST 또는 I(첫 번째), 최대 9TH 또는 IX(아홉 번째), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, 국가 및 지방자치단체 및/또는 주/도, DL/ID, V33A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, 운전 권한을 제한하는 관할 구역별 제한 코드(들)를 설명하는 텍스트, DL, V50ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, 카드 소지자를 위한 표준 허가 코드(들). D20의 코드를 참조. 이 데이터 요소는 향후 허가 코드 표준화를 위한 자리표시자임, DL, F5AN

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, 카드 소지자를 위한 표준 제한 코드(들). D20의 코드를 참조. 이 데이터 요소는 향후 제한 코드 표준화를 위한 자리표시자임, DL, F12AN

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, 카드 소지자를 위한 표준 차량 분류 코드(들). 이 데이터 요소는 향후 차량 분류 표준화를 위한 자리표시자임, DL, F4AN

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, 카드 소지자가 18세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, 카드 소지자가 운전할 수 있는 차량 분류에 대한 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, 카드 소지자의 체중(kg), 예. 84 kg = "084", DL/ID, F3N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, 카드 소지자의 체중(파운드), 예. 185 lb = "185", DL/ID, F3N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31kg 이하(70lb 이하), 1 = 32–45kg(71–100lb), 2 = 46 - 59kg(101–130lb), 3 = 60 - 70kg(131–160lb), 4 = 71 - 86kg(161–190lb), 5 = 87 - 100kg(191–220lb), 6 = 101 - 113kg(221–250lb), 7 = 114 - 127kg(251–280lb), 8 = 128–145kg(281–320lb), 9 = 146kg 이상(321lb 이상), DL/ID, F1N

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

