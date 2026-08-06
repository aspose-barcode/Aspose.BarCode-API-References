---
title: USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode for Android via Java API-referens
description: Valfria elementfält för kortet
type: docs
weight: 11
url: /sv/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Valfria element (fält) på kortet
## Constructors

| Constructor | Beskrivning |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Andra raden av gatuadressen i kortinnehavarens adress, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, DHS‑kravfält som anger efterlevnad: \u201cF\u201d = efterlevande; och, \u201cN\u201d = icke‑efterlevande, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Datum då den farligt material‑godkännande som beviljats av dokumentet inte längre är giltig. |
| [getHairColor()](#getHairColor--) | DAZ, Skallig, svart, blond, brun, grå, röd/mahogny, sandig, vit, okänd. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat material osv.) som används vid produktion av körkort och ID‑kort. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = \u201c1\u201d, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS osv.), måste suffixet samlas in och visas på DL/ID samt i MRT). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Fält som anger att kortinnehavaren är organdonator = \u201c1\u201d, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Land och kommun och/eller stat/provins, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Text som beskriver de jurisdiktionsspecifika restriktionskoderna som begränsar körbehörigheter, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Standardgodkännandekoder för kortinnehavare. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Standardrestriktionskoder för kortinnehavare. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Standardfordonsklassificeringskoder för kortinnehavare. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Datum då kortinnehavaren fyller 18 år. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Datum då kortinnehavaren fyller 19 år. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Datum då kortinnehavaren fyller 21 år. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är behörig att köra, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Fält som indikerar att kortinnehavaren är veteran = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Kortinnehavarens vikt i kilogram, Ex. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Kortinnehavarens vikt i pund, Ex. |
| [getWeightRange()](#getWeightRange--) | DCE, Anger den ungefärliga viktintervallen för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Andra raden av gatuadressen i kortinnehavarens adress, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, DHS‑kravfält som anger efterlevnad: \u201cF\u201d = efterlevande; och, \u201cN\u201d = icke‑efterlevande, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Skallig, svart, blond, brun, grå, röd/mahogny, sandig, vit, okänd. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat material osv.) som används vid produktion av körkort och ID‑kort. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = \u201c1\u201d, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS osv.), måste suffixet samlas in och visas på DL/ID samt i MRT). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Fält som anger att kortinnehavaren är organdonator = \u201c1\u201d, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Land och kommun och/eller stat/provins, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Text som beskriver de jurisdiktionsspecifika restriktionskoderna som begränsar körbehörigheter, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Standardgodkännandekoder för kortinnehavare. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Standardrestriktionskoder för kortinnehavare. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Standardfordonsklassificeringskoder för kortinnehavare. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Datum då kortinnehavaren fyller 18 år. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Datum då kortinnehavaren fyller 19 år. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Datum då kortinnehavaren fyller 21 år. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är behörig att köra, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Fält som indikerar att kortinnehavaren är veteran = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Kortinnehavarens vikt i kilogram, Ex. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Kortinnehavarens vikt i pund, Ex. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Anger den ungefärliga viktintervallen för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Andra raden av gatuadressen i kortinnehavarens adress, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. Om revisionsinformation inte används på kortet eller MRT måste den inkluderas i förarposten, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

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


DDA, DHS‑kravfält som anger efterlevnad: \u201cF\u201d = efterlevande; och, \u201cN\u201d = icke‑efterlevande, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Datum då den farligt material‑godkännande som utfärdats av dokumentet inte längre är giltig. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, Skallig, svart, blond, brun, grå, röd/akanel, sandig, vit, okänd. Om den utfärdande jurisdiktionen vill förkorta färger måste de treteckenkoder som anges i AAMVA D20 användas, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat material etc.) som används vid produktion av körkort och ID‑kort. (DHS‑rekommenderat fält), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS etc.) måste suffixet samlas in och visas på DL/ID och i MRT). JR (Junior), SR (Senior), 1ST eller I (Första), upp till 9TH eller IX (Nionde), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Fält som anger att kortinnehavaren är organdonator = \u201c1\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Land och kommun och/eller stat/provins, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Text som beskriver de jurisdiktionsspecifika restriktionskoderna som begränsar körbehörigheter, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Standardgodkännandekod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera godkännandekoder, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera restriktionskoder, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida arbete med att standardisera fordonsklassificeringar, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Datum då kortinnehavaren fyller 18 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är behörig att köra, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Fält som indikerar att kortinnehavaren är veteran = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Anger den ungefärliga viktintervallen för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

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


DAH, Andra raden av gatuadressen i kortinnehavarens adress, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. Om revisionsinformation inte används på kortet eller MRT måste den inkluderas i förarposten, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, DHS‑kravfält som anger efterlevnad: \u201cF\u201d = efterlevande; och, \u201cN\u201d = icke‑efterlevande, DL/ID, F1A

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, Skallig, svart, blond, brun, grå, röd/akanel, sandig, vit, okänd. Om den utfärdande jurisdiktionen vill förkorta färger måste de treteckenkoder som anges i AAMVA D20 användas, DL/ID, V12A

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat material etc.) som används vid produktion av körkort och ID‑kort. (DHS‑rekommenderat fält), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS etc.) måste suffixet samlas in och visas på DL/ID och i MRT). JR (Junior), SR (Senior), 1ST eller I (Första), upp till 9TH eller IX (Nionde), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Fält som anger att kortinnehavaren är organdonator = \u201c1\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Land och kommun och/eller stat/provins, DL/ID, V33A

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Text som beskriver de jurisdiktionsspecifika restriktionskoderna som begränsar körbehörigheter, DL, V50ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Standardgodkännandekod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera godkännandekoder, DL, F5AN

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera restriktionskoder, DL, F12AN

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida arbete med att standardisera fordonsklassificeringar, DL, F4AN

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Datum då kortinnehavaren fyller 18 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är behörig att köra, DL, V50ANS

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Fält som indikerar att kortinnehavaren är veteran = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Anger den ungefärliga viktintervallen för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 \\u2013 45 kg (71 \\u2013 100 lb), 2 = 46 - 59 kg (101 \\u2013 130 lb), 3 = 60 - 70 kg (131 \\u2013 160 lb), 4 = 71 - 86 kg (161 \\u2013 190 lb), 5 = 87 - 100 kg (191 \\u2013 220 lb), 6 = 101 - 113 kg (221 \\u2013 250 lb), 7 = 114 - 127 kg (251 \\u2013 280 lb), 8 = 128 \\u2013 145 kg (281 \\u2013 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

