---
title: "Sınıf USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields sınıfı. Kartın isteğe bağlı öğe alanları"
type: docs
weight: 830
url: /tr/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Kartın isteğe bağlı öğeleri (alanları)

```csharp
public class OptionalFields
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Kart sahibi adresinin sokak kısmının ikinci satırı, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Kart sahibinin bilindiği diğer soyadı, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Kart sahibinin bilindiği diğer adı, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Kart sahibinin bilindiği diğer ek adı, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Sürücü lisansı/kimlik kartının ne zaman, nerede ve kim tarafından yapıldığını belirten harf ve/veya sayı dizisi. Kartta veya MRT'de denetim bilgisi kullanılmazsa, sürücü kaydına eklenmelidir, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, DHS tarafından zorunlu kılınan, DL/ID'nin görünür formatındaki en son sürüm değişikliği veya modifikasyon tarihini gösteren alan. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, DHS zorunlu alanı; uyumu gösterir: “F” = uyumlu; “N” = uyumsuz, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Araç sınıfının ötesinde kart sahibine verilen ek sürüş ayrıcalıklarını gösteren yargı bölgesi‑özel kod(lar)ı açıklayan metin, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Kelli, siyah, sarışın, kahverengi, gri, kırmızı/kızıl, kumlu, beyaz, bilinmiyor. Veren yargı bölgesi renkleri kısaltmak isterse, AAMVA D20'de verilen üç karakterli kodlar kullanılmalıdır, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Belge tarafından verilen tehlikeli madde ekinin geçerliliğini yitirdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Sürücü lisansları ve kimlik kartları üretiminde kullanılan ham malzemelere (kart kağıdı, laminat vb.) yapıştırılan harf ve/veya sayı dizisi. (DHS önerilen alan), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, DHS zorunlu alanı; kart sahibinin geçici yasal statüsü olduğunu gösterir = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, İsim Soneki (Yargı bölgesi isim soneki gerektiren sistemlere (PDPS, CDLIS vb.) katılıyorsa, sonek DL/ID ve MRT'de toplanıp gösterilmelidir). JR (Junior), SR (Senior), 1ST veya I (First), 9TH veya IX (Ninth) kadar, DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Kart sahibinin organ bağışı yapan biri olduğunu gösteren alan = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Ülke ve belediye ve/veya eyalet/il, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Kart sahibinin ırk veya etnik kökeni için AAMVA D20'de tanımlanan kodlar, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Sürüş ayrıcalıklarını kısıtlayan yargı bölgesi‑özel kısıtlama kod(lar)ını açıklayan metin, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Kart sahibi için standart ek kod(lar). D20'deki kodlara bakın. Bu veri öğesi, ek kodlarını standartlaştırma çabaları için gelecekteki bir yer tutucudur, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, kart sahibi için standart kısıtlama kodları. D20'deki kodlara bakın. Bu veri öğesi, kısıtlama kodlarını standartlaştırma çabaları için gelecekteki bir yer tutucudur, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, kart sahibi için standart araç sınıflandırma kodları. Bu veri öğesi, araç sınıflandırmalarını standartlaştırma çabaları için gelecekteki bir yer tutucudur, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, kart sahibinin 18 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, kart sahibinin 19 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, kart sahibinin 21 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, kart sahibinin sürmesine yetkili olduğu araç sınıflandırmaları için yargı bölgesi özel kodları açıklayan metin, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, kart sahibinin bir gazisi olduğunu gösteren alan = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, kart sahibinin kilogram cinsinden ağırlığı, ör. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, kart sahibinin pound cinsinden ağırlığı, ör. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, kart sahibinin yaklaşık ağırlık aralığını gösterir: 0 = 31 kg'ye kadar (70 lb'ye kadar), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Ayrıca Bakınız

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


