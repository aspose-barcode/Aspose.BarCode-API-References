---
title: "클래스 USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for .NET API 참조"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields 클래스. 카드의 필수 요소 필드"
type: docs
weight: 820
url: /ko/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

카드의 필수 요소 (필드)

```csharp
public class MandatoryFields
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, 카드 소지자 주소의 도시 부분, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, 미국 및 캐나다의 카드 소지자 주소에서 우편번호 부분. 미국 우편번호의 뒤쪽 부분을 알 수 없는 경우, 9자리까지 남은 숫자를 0으로 채웁니다, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, 카드 소지자 주소의 주(州) 부분, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, 카드 소지자 주소의 거리 부분, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, DL/ID가 발행된 국가. 미국 = USA, 캐나다 = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, 발행 기관이 할당하거나 계산한 번호, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, 문서가 발행된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, 번호는 해당 고객에게 발행된 특정 문서를 과거에 발행된 다른 문서와 구별하도록 고유해야 합니다. 이 번호는 문서 구분, 감사 정보 번호 및/또는 재고 관리 등 여러 용도로 사용될 수 있습니다, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, 관할 구역별 승인 코드, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, 문서 만료일, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, 카드 소지자 눈 색상. (ANSI D-20 코드). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, 카드 소지자 성, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, 필드가 잘렸는지 여부를 나타내는 코드(T=잘림, N=미잘림, U=불명), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, 카드 소지자 이름, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, 필드가 잘렸는지 여부를 나타내는 코드(T=잘림, N=미잘림, U=불명), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, 카드 소지자 키. 인치(in): 인치 수 뒤에 " in"을 붙임 예: 6'1'' = "073 in" 센티미터(cm): 센티미터 수 뒤에 " cm"을 붙임 예: 181 센티미터 = "181 cm", DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, 문서가 발행된 날짜, 미국은 MMDDCCYY, 캐나다는 CCYYMMDD, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, 카드 소지자 중간 이름(들). 중간 이름이 여러 개인 경우 쉼표 "," 로 구분합니다., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, 필드가 잘렸는지 여부를 나타내는 코드(T=잘림, N=미잘림, U=불명), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, 관할 구역별 제한 코드, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, 카드 소지자 성별. 1 = 남성, 2 = 여성, 9 = 지정되지 않음, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, 관할 구역별 차량 클래스/그룹 코드, DL, V6ANS |

### 또 보기

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


