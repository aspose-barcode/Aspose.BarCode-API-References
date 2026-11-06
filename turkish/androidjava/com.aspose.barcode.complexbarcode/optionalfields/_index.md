---
title: "USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Kartın isteğe bağlı öğe alanları"
type: docs
weight: 11
url: /tr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Kartın isteğe bağlı öğeleri (alanları)
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Kart sahibinin adresinin sokak bölümünün ikinci satırı, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Kart sahibinin bilindiği diğer soyadı, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Kart sahibinin bilindiği diğer adı, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Kart sahibinin bilindiği diğer ek, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Bir sürücü lisansı/kimlik kartının ne zaman, nerede ve kim tarafından yapıldığını belirten harf ve/veya sayı dizisi. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, DHS tarafından istenen alan, DL/ID'nin görünür formatındaki en son sürüm değişikliği veya modifikasyon tarihini gösterir. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, DHS tarafından istenen alan, uyumu gösterir: \\u201cF\\u201d = uyumlu; ve, \\u201cN\\u201d = uyumsuz, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Kart sahibine araç sınıfının ötesinde verilen ek sürüş ayrıcalıklarını gösteren yargı bölgesi‑özel kod(lar)ı açıklayan metin, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Belge tarafından verilen tehlikeli madde yetkilendirmesinin geçerliliğini yitirdiği tarih. |
| [getHairColor()](#getHairColor--) | DAZ, Kel, siyah, sarışın, kahverengi, gri, kırmızı/kızıl, kumlu, beyaz, bilinmiyor. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Sürücü lisansları ve kimlik kartları üretilirken kullanılan ham malzemelere (kart kağıdı, laminat vb.) yapıştırılan harf ve/veya sayı dizisi. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, DHS tarafından istenen alan, kart sahibinin geçici yasal statüsü olduğunu gösterir = \\u201c1\\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, İsim Soneki (Eğer yargı bölgesi isim soneki gerektiren sistemlere (PDPS, CDLIS vb.) katılıyorsa, sonek DL/ID ve MRT'de toplanmalı ve gösterilmelidir). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Kart sahibinin organ bağışı yapan olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Ülke ve belediye ve/veya eyalet/il, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, AAMVA D20'de tanımlandığı gibi kart sahibinin ırk veya etnik kökeni için kodlar, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Sürüş ayrıcalıklarını kısıtlayan yargı bölgesi‑özel kısıtlama kod(lar)ını açıklayan metin, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Kart sahibi için standart yetkilendirme kod(lar)ı. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Kart sahibi için standart kısıtlama kod(lar)ı. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Kart sahibi için standart araç sınıflandırma kod(lar)ı. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Kart sahibinin 18 yaşına girdiği tarih. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Kart sahibinin 19 yaşına girdiği tarih. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Kart sahibinin 21 yaşına girdiği tarih. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Kart sahibinin sürmesine yetkili olduğu araç sınıflandırmaları için yargı bölgesi‑özel kod(ları) açıklayan metin, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Kart sahibinin bir gazisi olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Kart sahibinin kilogram cinsinden ağırlığı, Ör. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Kart sahibinin pound cinsinden ağırlığı, Ör. |
| [getWeightRange()](#getWeightRange--) | DCE, Kart sahibinin yaklaşık ağırlık aralığını gösterir: 0 = 31 kg'ye kadar (70 lb'ye kadar), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Kart sahibinin adresinin sokak bölümünün ikinci satırı, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Kart sahibinin bilindiği diğer soyadı, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Kart sahibinin bilindiği diğer adı, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Kart sahibinin bilindiği diğer ek, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Bir sürücü lisansı/kimlik kartının ne zaman, nerede ve kim tarafından yapıldığını belirten harf ve/veya sayı dizisi. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, DHS tarafından istenen alan, DL/ID'nin görünür formatındaki en son sürüm değişikliği veya modifikasyon tarihini gösterir. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, DHS tarafından istenen alan, uyumu gösterir: \\u201cF\\u201d = uyumlu; ve, \\u201cN\\u201d = uyumsuz, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Kart sahibine araç sınıfının ötesinde verilen ek sürüş ayrıcalıklarını gösteren yargı bölgesi‑özel kod(lar)ı açıklayan metin, DL, V50ANS |
| [setHAZMATEndorsementExpDate(LocalDate value)](#setHAZMATEndorsementExpDate-java.time.LocalDate-) | DDC, Belge tarafından verilen tehlikeli madde yetkilendirmesinin geçerliliğini yitirdiği tarih. |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Kel, siyah, sarışın, kahverengi, gri, kırmızı/kızıl, kumlu, beyaz, bilinmiyor. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Sürücü lisansları ve kimlik kartları üretilirken kullanılan ham malzemelere (kart kağıdı, laminat vb.) yapıştırılan harf ve/veya sayı dizisi. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, DHS tarafından istenen alan, kart sahibinin geçici yasal statüsü olduğunu gösterir = \\u201c1\\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, İsim Soneki (Eğer yargı bölgesi isim soneki gerektiren sistemlere (PDPS, CDLIS vb.) katılıyorsa, sonek DL/ID ve MRT'de toplanmalı ve gösterilmelidir). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Kart sahibinin organ bağışı yapan olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Ülke ve belediye ve/veya eyalet/il, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, AAMVA D20'de tanımlandığı gibi kart sahibinin ırk veya etnik kökeni için kodlar, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Sürüş ayrıcalıklarını kısıtlayan yargı bölgesi‑özel kısıtlama kod(lar)ını açıklayan metin, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Kart sahibi için standart yetkilendirme kod(lar)ı. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Kart sahibi için standart kısıtlama kod(lar)ı. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Kart sahibi için standart araç sınıflandırma kod(lar)ı. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Kart sahibinin 18 yaşına girdiği tarih. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Kart sahibinin 19 yaşına girdiği tarih. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Kart sahibinin 21 yaşına girdiği tarih. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Kart sahibinin sürmesine yetkili olduğu araç sınıflandırmaları için yargı bölgesi‑özel kod(ları) açıklayan metin, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Kart sahibinin bir gazisi olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Kart sahibinin kilogram cinsinden ağırlığı, Ör. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Kart sahibinin pound cinsinden ağırlığı, Ör. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Kart sahibinin yaklaşık ağırlık aralığını gösterir: 0 = 31 kg'ye kadar (70 lb'ye kadar), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Kart sahibinin adresinin sokak bölümünün ikinci satırı, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Kart sahibinin bilindiği diğer soyadı, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Kart sahibinin bilindiği diğer adı, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Kart sahibinin bilindiği diğer ek, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Sürücü belgesi/kimlik kartının ne zaman, nerede ve kim tarafından üretildiğini belirten harf ve/veya sayı dizisi. Kartta veya MRT'de denetim bilgisi kullanılmazsa, sürücü kaydına eklenmelidir, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Görünür formatındaki en son sürüm değişikliği veya modifikasyon tarihini gösteren DHS zorunlu alanı. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

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


DDA, DHS tarafından istenen alan, uyumu gösterir: \\u201cF\\u201d = uyumlu; ve, \\u201cN\\u201d = uyumsuz, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Kart sahibine araç sınıfının ötesinde verilen ek sürüş ayrıcalıklarını gösteren yargı bölgesi‑özel kod(lar)ı açıklayan metin, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Belge tarafından verilen tehlikeli madde yetkilendirmesinin geçerliliğini yitirdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Kel, siyah, sarışın, kahverengi, gri, kırmızı/kızıl, kumlu, beyaz, bilinmiyor. Veren yargı bölgesi renkleri kısaltmak isterse, AAMVA D20'de verilen üç karakterli kodlar kullanılmalıdır, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Sürücü lisansları ve kimlik kartları üretiminde kullanılan ham malzemelere (kart kağıdı, laminat vb.) yapıştırılan harf ve/veya sayı dizisi. (DHS önerilen alan), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, DHS tarafından istenen alan, kart sahibinin geçici yasal statüsü olduğunu gösterir = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, İsim Soneki (Yargı bölgesi isim soneki gerektiren sistemlere (PDPS, CDLIS vb.) katılıyorsa, sonek DL/ID ve MRT'de toplanıp gösterilmelidir). JR (Junior), SR (Senior), 1ST veya I (First), 9TH veya IX (Ninth) kadar, DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Kart sahibinin organ bağışı yapan olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Ülke ve belediye ve/veya eyalet/il, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, AAMVA D20'de tanımlandığı gibi kart sahibinin ırk veya etnik kökeni için kodlar, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Sürüş ayrıcalıklarını kısıtlayan yargı bölgesi‑özel kısıtlama kod(lar)ını açıklayan metin, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Kart sahibi için standart yetkilendirme kod(ları). D20'deki kodlara bakın. Bu veri öğesi, yetkilendirme kodlarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Kart sahibi için standart kısıtlama kod(ları). D20'deki kodlara bakın. Bu veri öğesi, kısıtlama kodlarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Kart sahibi için standart araç sınıflandırma kod(ları). Bu veri öğesi, araç sınıflandırmalarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Kart sahibinin 18 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Kart sahibinin 19 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Kart sahibinin 21 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Kart sahibinin sürmesine yetkili olduğu araç sınıflandırmaları için yargı bölgesi‑özel kod(ları) açıklayan metin, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Kart sahibinin bir gazisi olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Kart sahibinin kilogram cinsinden ağırlığı, Ör. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Kart sahibinin pound cinsinden ağırlığı, Ör. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Kart sahibinin yaklaşık ağırlık aralığını gösterir: 0 = 31 kg'ye kadar (70 lb'ye kadar), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

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


DAH, Kart sahibinin adresinin sokak bölümünün ikinci satırı, DL/ID, V35ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Kart sahibinin bilindiği diğer soyadı, DL/ID, V10ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Kart sahibinin bilindiği diğer adı, DL/ID, V15ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Kart sahibinin bilindiği diğer ek, DL/ID, V5ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Sürücü belgesi/kimlik kartının ne zaman, nerede ve kim tarafından üretildiğini belirten harf ve/veya sayı dizisi. Kartta veya MRT'de denetim bilgisi kullanılmazsa, sürücü kaydına eklenmelidir, DL/ID, V25ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Görünür formatındaki en son sürüm değişikliği veya modifikasyon tarihini gösteren DHS zorunlu alanı. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, DHS tarafından istenen alan, uyumu gösterir: \\u201cF\\u201d = uyumlu; ve, \\u201cN\\u201d = uyumsuz, DL/ID, F1A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Kart sahibine araç sınıfının ötesinde verilen ek sürüş ayrıcalıklarını gösteren yargı bölgesi‑özel kod(lar)ı açıklayan metin, DL, V50ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setHAZMATEndorsementExpDate(LocalDate value) {#setHAZMATEndorsementExpDate-java.time.LocalDate-}
```
public final void setHAZMATEndorsementExpDate(LocalDate value)
```


DDC, Belge tarafından verilen tehlikeli madde yetkilendirmesinin geçerliliğini yitirdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Kel, siyah, sarışın, kahverengi, gri, kırmızı/kızıl, kumlu, beyaz, bilinmiyor. Veren yargı bölgesi renkleri kısaltmak isterse, AAMVA D20'de verilen üç karakterli kodlar kullanılmalıdır, DL/ID, V12A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Sürücü lisansları ve kimlik kartları üretiminde kullanılan ham malzemelere (kart kağıdı, laminat vb.) yapıştırılan harf ve/veya sayı dizisi. (DHS önerilen alan), DL/ID, V25ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, DHS tarafından istenen alan, kart sahibinin geçici yasal statüsü olduğunu gösterir = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, İsim Soneki (Yargı bölgesi isim soneki gerektiren sistemlere (PDPS, CDLIS vb.) katılıyorsa, sonek DL/ID ve MRT'de toplanıp gösterilmelidir). JR (Junior), SR (Senior), 1ST veya I (First), 9TH veya IX (Ninth) kadar, DL/ID, V5ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Kart sahibinin organ bağışı yapan olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Ülke ve belediye ve/veya eyalet/il, DL/ID, V33A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, AAMVA D20'de tanımlandığı gibi kart sahibinin ırk veya etnik kökeni için kodlar, DL/ID, V3A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Sürüş ayrıcalıklarını kısıtlayan yargı bölgesi‑özel kısıtlama kod(lar)ını açıklayan metin, DL, V50ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Kart sahibi için standart yetkilendirme kod(ları). D20'deki kodlara bakın. Bu veri öğesi, yetkilendirme kodlarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F5AN

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Kart sahibi için standart kısıtlama kod(ları). D20'deki kodlara bakın. Bu veri öğesi, kısıtlama kodlarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F12AN

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Kart sahibi için standart araç sınıflandırma kod(ları). Bu veri öğesi, araç sınıflandırmalarını standartlaştırma çalışmalarının gelecekteki çabaları için bir yer tutucudur, DL, F4AN

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Kart sahibinin 18 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Kart sahibinin 19 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Kart sahibinin 21 yaşına girdiği tarih. (ABD için MMDDCCYY, Kanada için CCYYMMDD), DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Kart sahibinin sürmesine yetkili olduğu araç sınıflandırmaları için yargı bölgesi‑özel kod(ları) açıklayan metin, DL, V50ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Kart sahibinin bir gazisi olduğunu gösteren alan = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Kart sahibinin kilogram cinsinden ağırlığı, Ör. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Kart sahibinin pound cinsinden ağırlığı, Ör. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Kart sahibinin yaklaşık ağırlık aralığını gösterir: 0 = 31 kg'ye kadar (70 lb'ye kadar), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

