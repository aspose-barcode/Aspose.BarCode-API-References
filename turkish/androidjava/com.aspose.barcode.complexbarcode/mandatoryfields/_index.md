---
title: "USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Kartın zorunlu öğe alanları"
type: docs
weight: 10
url: /tr/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Kartın zorunlu öğeleri (alanları)
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Kart sahibinin adresinin şehir bölümü, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, ABD ve Kanada'daki kart sahibinin adresinin posta kodu bölümü. |
| [getAddressState()](#getAddressState--) | DAJ, Kart sahibinin adresinin eyalet bölümü, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Kart sahibinin adresinin sokak bölümü, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, DL/ID'nin verildiği ülke. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Yetkili kurum tarafından atanan veya hesaplanan numara, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Numara, o müşteriye verilen belirli belgeyi geçmişte verilmiş diğer belgelerden benzersiz şekilde tanımlamalıdır. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Yargı bölgesine özgü onay kodları, DL, V5ANS |
| [getExpirationDate()](#getExpirationDate--) | DBA, Belge Son Kullanma Tarihi, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [getEyeColor()](#getEyeColor--) | DAY, Kart sahibinin göz rengi. |
| [getFamilyName()](#getFamilyName--) | DCS, Kart sahibinin soyadı, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Kart sahibinin adı, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Kart sahibinin boyu. |
| [getIssueDate()](#getIssueDate--) | DBD, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [getMiddleName()](#getMiddleName--) | DAD, Kart sahibinin orta adı (adları). |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Yargı bölgesine özgü kısıtlama kodları, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Kart sahibinin cinsiyeti. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Yargı bölgesine özgü araç sınıfı / grup kodu, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Kart sahibinin adresinin şehir bölümü, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, ABD ve Kanada'daki kart sahibinin adresinin posta kodu bölümü. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Kart sahibinin adresinin eyalet bölümü, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Kart sahibinin adresinin sokak bölümü, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, DL/ID'nin verildiği ülke. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Yetkili kurum tarafından atanan veya hesaplanan numara, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Numara, o müşteriye verilen belirli belgeyi geçmişte verilmiş diğer belgelerden benzersiz şekilde tanımlamalıdır. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Yargı bölgesine özgü onay kodları, DL, V5ANS |
| [setExpirationDate(LocalDate value)](#setExpirationDate-java.time.LocalDate-) | DBA, Belge Son Kullanma Tarihi, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Kart sahibinin göz rengi. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Kart sahibinin soyadı, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Kart sahibinin adı, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Kart sahibinin boyu. |
| [setIssueDate(LocalDate value)](#setIssueDate-java.time.LocalDate-) | DBD, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Kart sahibinin orta adı (adları). |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Yargı bölgesine özgü kısıtlama kodları, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Kart sahibinin cinsiyeti. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Yargı bölgesine özgü araç sınıfı / grup kodu, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
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
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Kart sahibinin adresinin şehir bölümü, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, ABD ve Kanada'daki kart sahibinin adresinin posta kodu bölümü. ABD'de posta kodunun son kısmı bilinmiyorsa, sıfırlar 9 basamağa kadar son sayı setini doldurmak için kullanılacaktır, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Kart sahibinin adresinin eyalet bölümü, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Kart sahibinin adresinin sokak bölümü, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG, DL/ID'nin verildiği ülke. ABD = USA, Kanada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Yetkili kurum tarafından atanan veya hesaplanan numara, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Numara, müşteriye daha önce verilmiş olabilecek diğer belgelerden belirli bir belgeyi benzersiz şekilde tanımlamalıdır. Bu numara belge ayırt etme, denetim bilgi numarası ve/veya envanter kontrolü gibi birden fazla amaç için kullanılabilir, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Yargı bölgesine özgü onay kodları, DL, V5ANS

**Returns:**
java.lang.String
### getExpirationDate() {#getExpirationDate--}
```
public final LocalDate getExpirationDate()
```


DBA, Belge Son Kullanma Tarihi, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Kart sahibinin göz rengi. (ANSI D-20 kodları). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Kart sahibinin soyadı, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Kart sahibinin adı, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Kart sahibinin boyu. İnç (in): inç sayısı ardından " in" gelmelidir, ör. 6'1'' = "073 in" Santimetre(cm): santimetre sayısı ardından " cm" gelmelidir, ör. 181 santimetre="181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getIssueDate() {#getIssueDate--}
```
public final LocalDate getIssueDate()
```


DBD, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Kart sahibinin ikinci adı (adları). Birden fazla ikinci ad varsa virgül "," ile ayrılmalıdır. , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Yargı bölgesine özgü kısıtlama kodları, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Kart sahibinin cinsiyeti. 1 = erkek, 2 = kadın, 9 = belirtilmemiş, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Yargı bölgesine özgü araç sınıfı / grup kodu, DL, V6ANS

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




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, Kart sahibinin adresinin şehir bölümü, DL/ID, V20ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, ABD ve Kanada'daki kart sahibinin adresinin posta kodu bölümü. ABD'de posta kodunun son kısmı bilinmiyorsa, sıfırlar 9 basamağa kadar son sayı setini doldurmak için kullanılacaktır, DL/ID, F11ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Kart sahibinin adresinin eyalet bölümü, DL/ID, F2A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Kart sahibinin adresinin sokak bölümü, DL/ID, V35ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, DL/ID'nin verildiği ülke. ABD = USA, Kanada = CAN, DL/ID, F3A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Yetkili kurum tarafından atanan veya hesaplanan numara, DL/ID, V25ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Numara, müşteriye daha önce verilmiş olabilecek diğer belgelerden belirli bir belgeyi benzersiz şekilde tanımlamalıdır. Bu numara belge ayırt etme, denetim bilgi numarası ve/veya envanter kontrolü gibi birden fazla amaç için kullanılabilir, DL/ID, V25ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Yargı bölgesine özgü onay kodları, DL, V5ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setExpirationDate(LocalDate value) {#setExpirationDate-java.time.LocalDate-}
```
public final void setExpirationDate(LocalDate value)
```


DBA, Belge Son Kullanma Tarihi, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Kart sahibinin göz rengi. (ANSI D-20 kodları). DL/ID, F3A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Kart sahibinin soyadı, DL/ID, V40ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Kart sahibinin adı, DL/ID, V40ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Kart sahibinin boyu. İnç (in): inç sayısı ardından " in" gelmelidir, ör. 6'1'' = "073 in" Santimetre(cm): santimetre sayısı ardından " cm" gelmelidir, ör. 181 santimetre="181 cm" , DL/ID, F6ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setIssueDate(LocalDate value) {#setIssueDate-java.time.LocalDate-}
```
public final void setIssueDate(LocalDate value)
```


DBD, Belgenin verildiği tarih, ABD için MMDDCCYY, Kanada için CCYYMMDD, DL/ID, F8N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.time.LocalDate |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Kart sahibinin ikinci adı (adları). Birden fazla ikinci ad varsa virgül "," ile ayrılmalıdır. , DL/ID, V40ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, Bir alanın kesilip kesilmediğini gösteren kod (Kesildi=T), (Kesilmedi=N), (Bilinmiyor=U), DL/ID, F1A

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Yargı bölgesine özgü kısıtlama kodları, DL, V12ANS

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Kart sahibinin cinsiyeti. 1 = erkek, 2 = kadın, 9 = belirtilmemiş, DL/ID, F1N

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Yargı bölgesine özgü araç sınıfı / grup kodu, DL, V6ANS

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

