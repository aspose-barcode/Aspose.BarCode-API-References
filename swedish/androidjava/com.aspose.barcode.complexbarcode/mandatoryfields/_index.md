---
title: "USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Obligatoriska elementfält på kortet"
type: docs
weight: 10
url: /sv/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

Obligatoriska element (fält) på kortet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, Stadsdel av kortinnehavarens adress, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. |
| [getAddressState()](#getAddressState--) | DAJ, Statdel av kortinnehavarens adress, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, Gatuavsnitt av kortinnehavarens adress, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, Land där DL/ID utfärdas. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, Numret som tilldelats eller beräknats av den utfärdande myndigheten, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, Numret måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats tidigare. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS |
| [getExpirationDate()](#getExpirationDate--) | DBA, Dokumentets utgångsdatum, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [getEyeColor()](#getEyeColor--) | DAY, Färg på kortinnehavarens ögon. |
| [getFamilyName()](#getFamilyName--) | DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, Kortinnehavarens längd. |
| [getIssueDate()](#getIssueDate--) | DBD, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [getMiddleName()](#getMiddleName--) | DAD, Mellannamn på kortinnehavaren. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS |
| [getSex()](#getSex--) | DBC, Kortinnehavarens kön. |
| [getVehicleClass()](#getVehicleClass--) | DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, Stadsdel av kortinnehavarens adress, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, Statdel av kortinnehavarens adress, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, Gatuavsnitt av kortinnehavarens adress, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, Land där DL/ID utfärdas. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, Numret som tilldelats eller beräknats av den utfärdande myndigheten, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, Numret måste unikt identifiera ett specifikt dokument utfärdat till den kunden jämfört med andra som kan ha utfärdats tidigare. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS |
| [setExpirationDate(LocalDate value)](#setExpirationDate-java.time.LocalDate-) | DBA, Dokumentets utgångsdatum, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, Färg på kortinnehavarens ögon. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, Kortinnehavarens längd. |
| [setIssueDate(LocalDate value)](#setIssueDate-java.time.LocalDate-) | DBD, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, Mellannamn på kortinnehavaren. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, Kortinnehavarens kön. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, Stadsdel av kortinnehavarens adress, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den avslutande delen av postnumret i USA inte är känd, kommer nollor att användas för att fylla den avslutande siffrasekvensen upp till 9 siffror, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, Statdel av kortinnehavarens adress, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, Gatuavsnitt av kortinnehavarens adress, DL/ID, V35ANS

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


DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, Numret som tilldelats eller beräknats av den utfärdande myndigheten, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden från andra som kan ha utfärdats tidigare. Detta nummer kan tjäna flera syften såsom dokumentdifferentiering, revisionsinformationsnummer och/eller lagerkontroll, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS

**Returns:**
java.lang.String
### getExpirationDate() {#getExpirationDate--}
```
public final LocalDate getExpirationDate()
```


DBA, Dokumentets utgångsdatum, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, Kortinnehavarens längd. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal centimeter följt av " cm" t.ex. 181 centimeter = "181 cm", DL/ID, F6ANS

**Returns:**
java.lang.String
### getIssueDate() {#getIssueDate--}
```
public final LocalDate getIssueDate()
```


DBD, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, Kortinnehavarens kön. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS

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


DAI, Stadsdel av kortinnehavarens adress, DL/ID, V20ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, Postnummerdel av kortinnehavarens adress i USA och Kanada. Om den avslutande delen av postnumret i USA inte är känd, kommer nollor att användas för att fylla den avslutande siffrasekvensen upp till 9 siffror, DL/ID, F11ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, Statdel av kortinnehavarens adress, DL/ID, F2A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, Gatuavsnitt av kortinnehavarens adress, DL/ID, V35ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, Land där DL/ID utfärdas. USA = USA, Kanada = CAN, DL/ID, F3A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, Numret som tilldelats eller beräknats av den utfärdande myndigheten, DL/ID, V25ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, Nummer måste unikt identifiera ett specifikt dokument utfärdat till den kunden från andra som kan ha utfärdats tidigare. Detta nummer kan tjäna flera syften såsom dokumentdifferentiering, revisionsinformationsnummer och/eller lagerkontroll, DL/ID, V25ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, Jurisdiktionsspecifika godkännandekoder, DL, V5ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setExpirationDate(LocalDate value) {#setExpirationDate-java.time.LocalDate-}
```
public final void setExpirationDate(LocalDate value)
```


DBA, Dokumentets utgångsdatum, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, Färg på kortinnehavarens ögon. (ANSI D-20-koder). DL/ID, F3A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, Efternamn på kortinnehavaren, DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller är okänt om det är trunkerat (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, Förnamn på kortinnehavaren, DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, Kortinnehavarens längd. Tum (in): antal tum följt av " in" t.ex. 6'1'' = "073 in" Centimeter (cm): antal centimeter följt av " cm" t.ex. 181 centimeter = "181 cm", DL/ID, F6ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setIssueDate(LocalDate value) {#setIssueDate-java.time.LocalDate-}
```
public final void setIssueDate(LocalDate value)
```


DBD, Datum då dokumentet utfärdades, MMDDCCYY för USA, CCYYMMDD för Kanada, DL/ID, F8N

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, Mellannamn på kortinnehavaren. Vid flera mellannamn ska de separeras med ett kommatecken ",". , DL/ID, V40ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, En kod som indikerar om ett fält har trunkerats (T), inte har trunkerats (N), eller okänt om det är trunkerat (U), DL/ID, F1A

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, Jurisdiktionsspecifika restriktionskoder, DL, V12ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, Kortinnehavarens kön. 1 = man, 2 = kvinna, 9 = ej specificerat, DL/ID, F1N

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, Jurisdiktionsspecifik fordonsklass / gruppkod, DL, V6ANS

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

