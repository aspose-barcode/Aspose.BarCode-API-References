---
title: "클래스 USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields 클래스. 카드의 선택적 요소 필드"
type: docs
weight: 830
url: /ko/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

카드의 선택적 요소(필드)

```csharp
public class OptionalFields
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, 카드 소지자 주소의 거리 부분 두 번째 줄, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, 카드 소지자가 알려진 다른 성, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, 카드 소지자가 알려진 다른 이름, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, 카드 소지자가 알려진 다른 접미사, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, 운전 면허증/ID 카드가 언제, 어디서, 누가 제작했는지를 식별하는 문자 및/또는 숫자 문자열. 카드나 MRT에 감사 정보가 사용되지 않은 경우 운전 기록에 포함되어야 합니다, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, DHS에서 요구하는 필드로, DL/ID의 가시 형식에 대한 최신 버전 변경 또는 수정 날짜를 나타냅니다. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, DHS에서 요구하는 필드로, 준수 여부를 나타냅니다: “F” = 준수; “N” = 비준수, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, 차량 등급을 초과하여 카드 소지자에게 부여된 추가 운전 권한을 나타내는 관할 구역별 코드에 대한 설명 텍스트, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, 대머리, 검정, 금발, 갈색, 회색, 적색/적갈색, 황갈색, 흰색, 알 수 없음. 발행 관할 구역이 색상을 약어로 표시하려면 AAMVA D20에 제공된 세 글자 코드를 사용해야 합니다, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, 문서에 의해 부여된 위험물 허가가 더 이상 유효하지 않은 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, 운전 면허증 및 ID 카드를 제작하는 데 사용되는 원자재(카드지, 라미네이트 등)에 부착되는 문자 및/또는 숫자 문자열. (DHS 권장 필드), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, 카드 소지자가 임시 합법 상태임을 나타내는 DHS 요구 필드 = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, 이름 접미사 (관할 구역이 이름 접미사를 요구하는 시스템(PDPS, CDLIS 등)에 참여하는 경우, 접미사는 DL/ID와 MRT에 수집 및 표시되어야 합니다). JR(주니어), SR(시니어), 1ST 또는 I(첫 번째), 최대 9TH 또는 IX(아홉 번째), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, 카드 소지자가 장기 기증자임을 나타내는 필드 = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, 국가 및 시/군 및/또는 주/도, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, AAMVA D20에 정의된 카드 소지자의 인종 또는 민족 코드, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, 운전 권한을 제한하는 관할 구역별 제한 코드에 대한 설명 텍스트, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, 카드 소지자를 위한 표준 허가 코드. D20의 코드를 참조하십시오. 이 데이터 요소는 향후 허가 코드 표준화를 위한 자리표시자입니다, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, 카드 소지자를 위한 표준 제한 코드(들). D20에서 코드를 확인하십시오. 이 데이터 요소는 제한 코드를 표준화하기 위한 향후 작업을 위한 자리표시자입니다, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, 카드 소지자를 위한 표준 차량 분류 코드(들). 이 데이터 요소는 차량 분류를 표준화하기 위한 향후 작업을 위한 자리표시자입니다, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, 카드 소지자가 18세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, 카드 소지자가 19세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, 카드 소지자가 21세가 되는 날짜. (미국은 MMDDCCYY, 캐나다는 CCYYMMDD), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, 카드 소지자가 운전 허가된 차량 분류에 대한 관할 구역별 코드(들)를 설명하는 텍스트, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, 카드 소지자가 베테랑임을 나타내는 필드 = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, 카드 소지자의 체중(킬로그램), 예: 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, 카드 소지자의 체중(파운드), 예: 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, 카드 소지자의 대략적인 체중 범위를 나타냅니다: 0 = 31 kg 이하(70 lbs 이하), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |

### 또 보기

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


