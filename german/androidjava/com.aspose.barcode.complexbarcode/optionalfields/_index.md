---
title: USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Optionale Elementfelder der Karte
type: docs
weight: 11
url: /de/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

Optionale Elemente (Felder) der Karte
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH, Zweite Zeile des Straßenanteils der Karteninhaberadresse, DL/ID, V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN, Anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG, Anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS, Andere Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis hergestellt wurde. |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des Führerscheins/Personalausweises angibt. |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA, Von DHS erforderliches Feld, das die Konformität angibt: “F” = konform; und “N” = nicht konform, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien für den Karteninhaber über die Fahrzeugklasse hinaus anzeigen, DL, V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC, Datum, an dem die durch das Dokument gewährte Gefahrgutberechtigung nicht mehr gültig ist. |
| [getHairColor()](#getHairColor--) | DAZ, Glatz, schwarz, blond, braun, grau, rot/kastanienbraun, sandig, weiß, unbekannt. |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die den Rohmaterialien (Kartenpapier, Laminat usw.) angebracht ist, die bei der Herstellung von Führerscheinen und Personalausweisen verwendet werden. |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD, Von DHS erforderliches Feld, das anzeigt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status hat = “1”, DL/ID, F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix erfasst und auf dem Führerschein/Personalausweis sowie im MRT angezeigt werden). |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK, Feld, das anzeigt, dass der Karteninhaber Organspender ist = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN, Standard-Berechtigungscode(s) für den Karteninhaber. |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO, Standard-Einschränkungscode(s) für den Karteninhaber. |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM, Standard-Fahrzeugklassifizierungscode(s) für den Karteninhaber. |
| [getUnder18Until()](#getUnder18Until--) | DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. |
| [getUnder19Until()](#getUnder19Until--) | DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. |
| [getUnder21Until()](#getUnder21Until--) | DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. |
| [getVehClassDescription()](#getVehClassDescription--) | DCP, Text, der die behördenspezifischen Code(s) für Fahrzeugklassifikationen erklärt, für die der Karteninhaber berechtigt ist zu fahren, DL, V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = \\u201c1\\u201d, DL/ID, F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX, Gewicht des Karteninhabers in Kilogramm, Bsp. |
| [getWeightPounds()](#getWeightPounds--) | DAW, Gewicht des Karteninhabers in Pfund, Bsp. |
| [getWeightRange()](#getWeightRange--) | DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH, Zweite Zeile des Straßenanteils der Karteninhaberadresse, DL/ID, V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN, Anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG, Anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS, Andere Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis hergestellt wurde. |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des Führerscheins/Personalausweises angibt. |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA, Von DHS erforderliches Feld, das die Konformität angibt: “F” = konform; und “N” = nicht konform, DL/ID, F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien für den Karteninhaber über die Fahrzeugklasse hinaus anzeigen, DL, V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ, Glatz, schwarz, blond, braun, grau, rot/kastanienbraun, sandig, weiß, unbekannt. |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die den Rohmaterialien (Kartenpapier, Laminat usw.) angebracht ist, die bei der Herstellung von Führerscheinen und Personalausweisen verwendet werden. |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD, Von DHS erforderliches Feld, das anzeigt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status hat = “1”, DL/ID, F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix erfasst und auf dem Führerschein/Personalausweis sowie im MRT angezeigt werden). |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK, Feld, das anzeigt, dass der Karteninhaber Organspender ist = “1”, DL/ID, F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN, Standard-Berechtigungscode(s) für den Karteninhaber. |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO, Standard-Einschränkungscode(s) für den Karteninhaber. |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM, Standard-Fahrzeugklassifizierungscode(s) für den Karteninhaber. |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP, Text, der die behördenspezifischen Code(s) für Fahrzeugklassifikationen erklärt, für die der Karteninhaber berechtigt ist zu fahren, DL, V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = \\u201c1\\u201d, DL/ID, F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX, Gewicht des Karteninhabers in Kilogramm, Bsp. |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW, Gewicht des Karteninhabers in Pfund, Bsp. |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH, Zweite Zeile des Straßenanteils der Karteninhaberadresse, DL/ID, V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN, Anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG, Anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS, Andere Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis hergestellt wurde. Wenn Audit-Informationen nicht auf der Karte oder dem MRT verwendet werden, muss sie im Fahrerdatensatz enthalten sein, DL/ID, V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des DL/ID angibt. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

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


DDA, Von DHS erforderliches Feld, das die Konformität angibt: “F” = konform; und “N” = nicht konform, DL/ID, F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien für den Karteninhaber über die Fahrzeugklasse hinaus anzeigen, DL, V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC, Datum, an dem die durch das Dokument gewährte Gefahrgutbefugnis nicht mehr gültig ist. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL, F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ, kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Behörde Farben abkürzen möchte, müssen die dreistelligen Codes aus AAMVA D20 verwendet werden, DL/ID, V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die den Rohmaterialien (Kartenpapier, Laminat usw.) zugeordnet ist, die bei der Herstellung von Führerscheinen und Personalausweisen verwendet werden. (Von DHS empfohlenes Feld), DL/ID, V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD, Von DHS erforderliches Feld, das anzeigt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status hat = “1”, DL/ID, F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU, Namenssuffix (Wenn die Behörde an Systemen teilnimmt, die Namenssuffixe erfordern (PDPS, CDLIS usw.), muss das Suffix erfasst und auf dem DL/ID sowie im MRT angezeigt werden). JR (Junior), SR (Senior), 1ST oder I (Erster), bis 9TH oder IX (Neunter), DL/ID, V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK, Feld, das anzeigt, dass der Karteninhaber Organspender ist = “1”, DL/ID, F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN, Standardmäßige Befähigungs‑Code(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Befähigungs‑Codes zu standardisieren, DL, F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO, Standardmäßige Einschränkungs‑Code(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Einschränkungs‑Codes zu standardisieren, DL, F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM, Standardmäßige Fahrzeugklassifikations‑Code(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Fahrzeugklassifikationen zu standardisieren, DL, F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP, Text, der die behördenspezifischen Code(s) für Fahrzeugklassifikationen erklärt, für die der Karteninhaber berechtigt ist zu fahren, DL, V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = \\u201c1\\u201d, DL/ID, F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX, Gewicht des Karteninhabers in Kilogramm, Bsp. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW, Gewicht des Karteninhabers in Pfund, Bsp. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

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


DAH, Zweite Zeile des Straßenanteils der Karteninhaberadresse, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN, Anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG, Anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS, Andere Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis hergestellt wurde. Wenn Audit-Informationen nicht auf der Karte oder dem MRT verwendet werden, muss sie im Fahrerdatensatz enthalten sein, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des DL/ID angibt. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA, Von DHS erforderliches Feld, das die Konformität angibt: “F” = konform; und “N” = nicht konform, DL/ID, F1A

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien für den Karteninhaber über die Fahrzeugklasse hinaus anzeigen, DL, V50ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ, kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Behörde Farben abkürzen möchte, müssen die dreistelligen Codes aus AAMVA D20 verwendet werden, DL/ID, V12A

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die den Rohmaterialien (Kartenpapier, Laminat usw.) zugeordnet ist, die bei der Herstellung von Führerscheinen und Personalausweisen verwendet werden. (Von DHS empfohlenes Feld), DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD, Von DHS erforderliches Feld, das anzeigt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status hat = “1”, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU, Namenssuffix (Wenn die Behörde an Systemen teilnimmt, die Namenssuffixe erfordern (PDPS, CDLIS usw.), muss das Suffix erfasst und auf dem DL/ID sowie im MRT angezeigt werden). JR (Junior), SR (Senior), 1ST oder I (Erster), bis 9TH oder IX (Neunter), DL/ID, V5ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK, Feld, das anzeigt, dass der Karteninhaber Organspender ist = “1”, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN, Standardmäßige Befähigungs‑Code(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Befähigungs‑Codes zu standardisieren, DL, F5AN

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO, Standardmäßige Einschränkungs‑Code(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Einschränkungs‑Codes zu standardisieren, DL, F12AN

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM, Standardmäßige Fahrzeugklassifikations‑Code(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen, Fahrzeugklassifikationen zu standardisieren, DL, F4AN

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP, Text, der die behördenspezifischen Code(s) für Fahrzeugklassifikationen erklärt, für die der Karteninhaber berechtigt ist zu fahren, DL, V50ANS

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = \\u201c1\\u201d, DL/ID, F1N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX, Gewicht des Karteninhabers in Kilogramm, Bsp. 84 kg = \\u201c084\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW, Gewicht des Karteninhabers in Pfund, Bsp. 185 lb = \\u201c185\\u201d, DL/ID, F3N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg(up to 70 lbs), 1 = 32 \\u2013 45 kg(71 \\u2013 100 lbs), 2 = 46 - 59 kg(101 \\u2013 130 lbs), 3 = 60 - 70 kg(131 \\u2013 160 lbs), 4 = 71 - 86 kg(161 \\u2013 190 lbs), 5 = 87 - 100 kg(191 \\u2013 220 lbs), 6 = 101 - 113 kg(221 \\u2013 250 lbs), 7 = 114 - 127 kg(251 \\u2013 280 lbs), 8 = 128 \\u2013 145 kg(281 \\u2013 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

