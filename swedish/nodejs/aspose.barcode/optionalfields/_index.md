---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Valfria element (fält) i kortet"
type: docs
weight: 730
url: /sv/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Valfria element (fält) i kortet

```js
new OptionalFields()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. If a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet av t |
| [getComplianceType()](#getcompliancetype) | DDA, DHS‑kravfält som anger efterlevnad: “F” = efterlevande; och, “N” = icke‑efterlevande, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Text som förklarar de jurisdiktionsspecifika kod(erna) som anger ytterligare körbehörigheter som beviljats till ca |
| [getHairColor()](#gethaircolor) | DAZ, Skallig, svart, blond, brun, grå, röd/ljusbrun, sandig, vit, okänd. If the issuing jurisdiction wishes to abbrevia |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Datum då den farliga material‑godkännande som utfärdats av dokumentet inte längre är giltig. (MMDDCCYY för USA, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialen (kortpapper, laminerat etc.) som används i produci |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS, etc.), måste suffixet vara |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Fält som anger att kortinnehavaren är organdonator = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Land och kommun och/eller delstat/provins, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Text som beskriver de jurisdiktionsspecifika restriktionskod(erna) som begränsar körbehörigheter, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Standardgodkännandekod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida insatser att st |
| [getUnder18Until()](#getunder18until) | DDH, Datum då kortinnehavaren fyller 18 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är auktoriserad att köra |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Fält som anger att kortinnehavaren är veteran = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Anger den ungefärliga viktintervallet för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Andra raden av gatuavsnittet i kortinnehavarens adress, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. If a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet av t |
| [setComplianceType()](#setcompliancetype) | DDA, DHS‑kravfält som anger efterlevnad: “F” = efterlevande; och, “N” = icke‑efterlevande, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Text som förklarar de jurisdiktionsspecifika kod(erna) som anger ytterligare körbehörigheter som beviljats till ca |
| [setHairColor()](#sethaircolor) | DAZ, Skallig, svart, blond, brun, grå, röd/ljusbrun, sandig, vit, okänd. If the issuing jurisdiction wishes to abbrevia |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialen (kortpapper, laminerat etc.) som används i produci |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS, etc.), måste suffixet vara |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Fält som anger att kortinnehavaren är organdonator = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Land och kommun och/eller delstat/provins, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Text som beskriver de jurisdiktionsspecifika restriktionskod(erna) som begränsar körbehörigheter, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Standardgodkännandekod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida insatser att st |
| [setUnder18Until()](#setunder18until) | DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Text som förklarar de jurisdiktionsspecifika kod(erna) för klassificering av fordon som kortinnehavaren är auktoriserad att köra |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Fält som anger att kortinnehavaren är veteran = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Anger den ungefärliga viktintervallet för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. Om revisionsinformation inte används på kortet eller MRT måste den inkluderas i förarposten, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, DHS‑kravfält som anger efterlevnad: “F” = efterlevande; och, “N” = icke‑efterlevande, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Skallig, svart, blond, brun, grå, röd/mahogny, sandig, vit, okänd. Om den utfärdande jurisdiktionen vill förkorta färger måste de treteckenkoder som anges i AAMVA D20 användas, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Datum då den farliga materialtillägg som beviljats av dokumentet inte längre är giltig. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat etc.) som används vid framställning av körkort och ID‑kort. (DHS rekommenderat fält), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS etc.) måste suffixet samlas in och visas på DL/ID och i MRT). JR (Junior), SR (Senior), 1ST eller I (Första), upp till 9TH eller IX (Nionde), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Fält som anger att kortinnehavaren är organdonator = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Land och kommun och/eller delstat/provins, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Text som beskriver de jurisdiktionsspecifika restriktionskod(erna) som begränsar körbehörigheter, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Standardtilläggskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera tilläggskoder, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera restriktionskoder, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida arbete med att standardisera fordonsklassificeringar, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Datum då kortinnehavaren fyller 18 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Text som förklarar de jurisdiktionsspecifika koderna för klassificeringar av fordon som kortinnehavaren är behörig att köra, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Fält som anger att kortinnehavaren är veteran = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Anger den ungefärliga viktintervallet för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32–45 kg (71–100 lb), 2 = 46–59 kg (101–130 lb), 3 = 60–70 kg (131–160 lb), 4 = 71–86 kg (161–190 lb), 5 = 87–100 kg (191–220 lb), 6 = 101–113 kg (221–250 lb), 7 = 114–127 kg (251–280 lb), 8 = 128–145 kg (281–320 lb), 9 = 146 kg eller mer (321 lb eller mer), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Andra raden av gatuavsnittet i kortinnehavarens adress, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. Om revisionsinformation inte används på kortet eller MRT måste den inkluderas i förarposten, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, DHS‑kravfält som anger efterlevnad: “F” = efterlevande; och, “N” = icke‑efterlevande, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Text som förklarar de jurisdiktionsspecifika koderna som anger ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Skallig, svart, blond, brun, grå, röd/mahogny, sandig, vit, okänd. Om den utfärdande jurisdiktionen vill förkorta färger måste de treteckenkoder som anges i AAMVA D20 användas, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat etc.) som används vid framställning av körkort och ID‑kort. (DHS rekommenderat fält), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS etc.) måste suffixet samlas in och visas på DL/ID och i MRT). JR (Junior), SR (Senior), 1ST eller I (Första), upp till 9TH eller IX (Nionde), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Fält som anger att kortinnehavaren är organdonator = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Land och kommun och/eller delstat/provins, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Koder för kortinnehavarens ras eller etnicitet, enligt AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Text som beskriver de jurisdiktionsspecifika restriktionskod(erna) som begränsar körbehörigheter, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Standardtilläggskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera tilläggskoder, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Standardrestriktionskod(er) för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida arbete med att standardisera restriktionskoder, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Standardfordonsklassificeringskod(er) för kortinnehavaren. Detta dataelement är en platshållare för framtida arbete med att standardisera fordonsklassificeringar, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Text som förklarar de jurisdiktionsspecifika koderna för klassificeringar av fordon som kortinnehavaren är behörig att köra, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Fält som anger att kortinnehavaren är veteran = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Anger den ungefärliga viktintervallet för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32–45 kg (71–100 lb), 2 = 46–59 kg (101–130 lb), 3 = 60–70 kg (131–160 lb), 4 = 71–86 kg (161–190 lb), 5 = 87–100 kg (191–220 lb), 6 = 101–113 kg (221–250 lb), 7 = 114–127 kg (251–280 lb), 8 = 128–145 kg (281–320 lb), 9 = 146 kg eller mer (321 lb eller mer), DL/ID, F1N
