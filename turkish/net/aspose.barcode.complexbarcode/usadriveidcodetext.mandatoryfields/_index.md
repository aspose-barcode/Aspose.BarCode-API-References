---
title: "Sınıf USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields sınıf. Kartın zorunlu öğe alanları"
type: docs
weight: 820
url: /tr/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Kartın zorunlu öğeleri (alanları)

```csharp
public class MandatoryFields
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, Kart sahibinin adresinin şehir bölümü, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, ABD ve Kanada'daki kart sahibinin adresinin posta kodu bölümü. ABD'de posta kodunun son kısmı bilinmiyorsa, 9 rakama kadar eksik sayılar sıfırlarla doldurulur, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, Kart sahibinin adresinin eyalet bölümü, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Kart sahibinin adresinin sokak bölümü, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, DL/ID'nin verildiği ülke. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, Yetkili kurum tarafından atanan veya hesaplanan numara, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Belgenin verildiği tarih, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Numara, o müşteriye verilen belirli bir belgeyi geçmişte verilmiş diğer belgelerden benzersiz şekilde tanımlamalıdır. Bu numara, belge ayırt etme, denetim bilgisi numarası ve/veya envanter kontrolü gibi birden fazla amaç için kullanılabilir, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Yargı bölgesine özgü onay kodları, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Belge Son Kullanma Tarihi, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Kart sahibinin göz rengi. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Kart sahibinin soyadı, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, Bir alanın kesilip kesilmediğini (T), kesilmediğini (N) veya kesilip kesilmediğinin bilinmediğini (U) gösteren kod, DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, Kart sahibinin adı, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, Bir alanın kesilip kesilmediğini (T), kesilmediğini (N) veya kesilip kesilmediğinin bilinmediğini (U) gösteren kod, DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Kart sahibinin boyu. İnç (in): inç sayısı, ardından " in" eklenir, ör. 6'1'' = "073 in" Santimetre (cm): santimetre sayısı, ardından " cm" eklenir, ör. 181 santimetre = "181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Belgenin verildiği tarih, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Kart sahibinin orta adı (adları). Birden fazla orta ad varsa, virgül "," ile ayrılmalıdır., DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, Bir alanın kesilip kesilmediğini (T), kesilmediğini (N) veya kesilip kesilmediğinin bilinmediğini (U) gösteren kod, DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Yargı bölgesine özgü kısıtlama kodları, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Kart sahibinin cinsiyeti. 1 = male, 2 = female, 9 = not specified, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Yargı bölgesine özgü araç sınıfı / grup kodu, DL, V6ANS |

### Ayrıca Bakınız

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


