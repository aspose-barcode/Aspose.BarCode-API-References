---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Optionale Elemente (Felder) der Karte."
type: docs
weight: 730
url: /de/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Optionale Elemente (Felder) der Karte.

```js
new OptionalFields()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, anderes Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis erstellt wurde. Wenn ein |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats von t angibt |
| [getComplianceType()](#getcompliancetype) | DDA, von DHS erforderliches Feld, das die Konformität angibt: „F“ = konform; und „N“ = nicht konform, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien, die dem ca gewährt werden, anzeigt |
| [getHairColor()](#gethaircolor) | DAZ, kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Jurisdiktion abbrevia |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Datum, an dem die durch das Dokument gewährte Gefahrgutbefugnis nicht mehr gültig ist. (MMDDCCYY für die USA, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, eine Zeichenfolge aus Buchstaben und/oder Zahlen, die an den Rohmaterialien (Papier, Laminat usw.) angebracht wird, die bei der Produktion verwendet werden |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, von DHS erforderliches Feld, das angibt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status = „1“ hat, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Feld, das angibt, dass der Karteninhaber Organspender ist = „1“, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Standardbefähigungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Standardeinschränkungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Standardfahrzeugklassifizierungscode(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen, um st |
| [getUnder18Until()](#getunder18until) | DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Text, der die jurisdictionsspezifischen Code(s) für Fahrzeugklassifizierungen erklärt, zu denen der Karteninhaber berechtigt ist zu fahren |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Gewicht des Karteninhabers in Kilogramm, z.B. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Gewicht des Karteninhabers in Pfund, z.B. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Gibt die ungefähre Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg (bis zu 70 lb), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Zweite Zeile des Straßenanteils der Adresse des Karteninhabers, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, anderes Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis erstellt wurde. Wenn ein |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats von t angibt |
| [setComplianceType()](#setcompliancetype) | DDA, von DHS erforderliches Feld, das die Konformität angibt: „F“ = konform; und „N“ = nicht konform, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien, die dem ca gewährt werden, anzeigt |
| [setHairColor()](#sethaircolor) | DAZ, kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Jurisdiktion abbrevia |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, eine Zeichenfolge aus Buchstaben und/oder Zahlen, die an den Rohmaterialien (Papier, Laminat usw.) angebracht wird, die bei der Produktion verwendet werden |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, von DHS erforderliches Feld, das angibt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status = „1“ hat, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Feld, das angibt, dass der Karteninhaber Organspender ist = „1“, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Standardbefähigungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Standardeinschränkungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Standardfahrzeugklassifizierungscode(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen, um st |
| [setUnder18Until()](#setunder18until) | DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Text, der die jurisdictionsspezifischen Code(s) für Fahrzeugklassifizierungen erklärt, zu denen der Karteninhaber berechtigt ist zu fahren |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Gewicht des Karteninhabers in Kilogramm, z.B. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Gewicht des Karteninhabers in Pfund, z.B. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Gibt die ungefähre Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg (bis zu 70 lb), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, anderes Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/ID-Karte erstellt wurde. Wenn Prüfungsinformationen nicht auf der Karte oder dem MRT verwendet werden, müssen sie im Fahrer‑Datensatz enthalten sein, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des DL/ID angibt. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, von DHS erforderliches Feld, das die Konformität angibt: „F“ = konform; und „N“ = nicht konform, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien anzeigen, die dem Karteninhaber über die Fahrzeugklasse hinaus gewährt werden, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Jurisdiktion Farben abkürzen möchte, müssen die in AAMVA D20 bereitgestellten dreistelligen Codes verwendet werden, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Datum, an dem die durch das Dokument gewährte Gefahrgutbefugnis nicht mehr gültig ist. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die an den Rohmaterialien (Papier, Laminat usw.) befestigt ist, die bei der Herstellung von Führerscheinen und ID‑Karten verwendet werden. (Von DHS empfohlenes Feld), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, von DHS erforderliches Feld, das angibt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status = „1“ hat, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix erfasst und auf dem DL/ID sowie im MRT angezeigt werden). JR (Junior), SR (Senior), 1ST oder I (Erster), bis 9TH oder IX (Neunter), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Feld, das angibt, dass der Karteninhaber Organspender ist = „1“, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Standard‑Befähigungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Befähigungscodes, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Standard‑Einschränkungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Einschränkungscodes, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Standard‑Fahrzeugklassifizierungscode(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Fahrzeugklassifizierungen, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Text, der die jurisdictionsspezifischen Code(s) für Fahrzeugklassifizierungen erklärt, zu denen der Karteninhaber berechtigt ist zu fahren, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Gewicht des Karteninhabers in Kilogramm, z.B. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Gewicht des Karteninhabers in Pfund, z.B. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg (bis zu 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Zweite Zeile des Straßenanteils der Adresse des Karteninhabers, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, anderes Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/ID-Karte erstellt wurde. Wenn Prüfungsinformationen nicht auf der Karte oder dem MRT verwendet werden, müssen sie im Fahrer‑Datensatz enthalten sein, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, Von DHS erforderliches Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des DL/ID angibt. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, von DHS erforderliches Feld, das die Konformität angibt: „F“ = konform; und „N“ = nicht konform, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Text, der die jurisdictionsspezifischen Code(s) erklärt, die zusätzliche Fahrprivilegien anzeigen, die dem Karteninhaber über die Fahrzeugklasse hinaus gewährt werden, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Kahl, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Jurisdiktion Farben abkürzen möchte, müssen die in AAMVA D20 bereitgestellten dreistelligen Codes verwendet werden, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Eine Zeichenfolge aus Buchstaben und/oder Zahlen, die an den Rohmaterialien (Papier, Laminat usw.) befestigt ist, die bei der Herstellung von Führerscheinen und ID‑Karten verwendet werden. (Von DHS empfohlenes Feld), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, von DHS erforderliches Feld, das angibt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status = „1“ hat, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die einen Namenssuffix erfordern (PDPS, CDLIS usw.), muss der Suffix erfasst und auf dem DL/ID sowie im MRT angezeigt werden). JR (Junior), SR (Senior), 1ST oder I (Erster), bis 9TH oder IX (Neunter), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Feld, das angibt, dass der Karteninhaber Organspender ist = „1“, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Text, der die jurisdictionsspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Standard‑Befähigungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Befähigungscodes, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Standard‑Einschränkungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Einschränkungscodes, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Standard‑Fahrzeugklassifizierungscode(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bestrebungen zur Standardisierung von Fahrzeugklassifizierungen, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Text, der die jurisdictionsspezifischen Code(s) für Fahrzeugklassifizierungen erklärt, zu denen der Karteninhaber berechtigt ist zu fahren, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Gewicht des Karteninhabers in Kilogramm, z.B. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Gewicht des Karteninhabers in Pfund, z.B. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Gibt den ungefähren Gewichtsbereich des Karteninhabers an: 0 = bis zu 31 kg (bis zu 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N
