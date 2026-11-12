---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Optionele elementen (velden) van de kaart"
type: docs
weight: 730
url: /nl/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

Optionele elementen (velden) van de kaart

```js
new OptionalFields()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, Andere achternaam waaronder kaarthouder bekend is, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, Andere voornaam waaronder kaarthouder bekend is, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, Andere suffix waaronder kaarthouder bekend is, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, Een tekenreeks van letters en/of cijfers die aangeeft wanneer, waar en door wie een rijbewijs/ID-kaart is gemaakt. Als een |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, DHS vereist veld dat de datum aangeeft van de meest recente versiewijziging of wijziging van het zichtbare formaat van t |
| [getComplianceType()](#getcompliancetype) | DDA, DHS vereist veld dat de naleving aangeeft: “F” = nalevend; en, “N” = niet-nalevend, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, Tekst die de jurisdictiespecifieke code(s) uitlegt die extra rijbevoegdheden aangeven die aan de ca zijn verleend |
| [getHairColor()](#gethaircolor) | DAZ, Kale, zwart, blond, bruin, grijs, rood/kastanjebruin, zandkleurig, wit, onbekend. Als de uitgevende jurisdictie wil afkorten |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, Datum waarop de gevaarlijke stoffen endorsement verleend door het document niet meer geldig is. (MMDDCCYY voor VS, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, Een reeks letters en/of cijfers die wordt aangebracht op de grondstoffen (karton, laminaat, enz.) die worden gebruikt in de productie |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, DHS vereist veld dat aangeeft dat de kaarthouder een tijdelijke wettelijke status heeft = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, Naamachtervoegsel (Als de jurisdictie deelneemt aan systemen die een naamachtervoegsel vereisen (PDPS, CDLIS, enz.), moet het achtervoegsel |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, Veld dat aangeeft dat de kaarthouder een orgaandonor is = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, Land en gemeente en/of staat/provincie, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, Codes voor ras of etniciteit van de kaarthouder, zoals gedefinieerd in AAMVA D20, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, Tekst die de jurisdictiespecifieke restrictiecode(s) beschrijft die rijbevoegdheden beperken, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, Standaard endorsementcode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, Standaard restrictiecode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, Standaard voertuigclassificatiecode(s) voor kaarthouder. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen om te st |
| [getUnder18Until()](#getunder18until) | DDH, Datum waarop de kaarthouder 18 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, Datum waarop de kaarthouder 21 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, Tekst die de jurisdictiespecifieke code(s) uitlegt voor classificaties van voertuigen waarvoor de kaarthouder bevoegd is om te rijden |
| [getVeteranIndicator()](#getveteranindicator) | DDL, Veld dat aangeeft dat de kaarthouder een veteraan is = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, Gewicht van de kaarthouder in kilogram, bijv. 84 kg = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, Gewicht van de kaarthouder in ponden, bijv. 185 lb = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, Geeft het geschatte gewicht bereik van de kaarthouder aan: 0 = tot 31 kg (tot 70 lb), 1 = 32 – 45 kg (71 – 100 lb |
| [setAddressStreet2()](#setaddressstreet2) | DAH, Tweede regel van het straatdeel van het adres van de kaarthouder, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, Andere achternaam waaronder kaarthouder bekend is, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, Andere voornaam waaronder kaarthouder bekend is, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, Andere suffix waaronder kaarthouder bekend is, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, Een tekenreeks van letters en/of cijfers die aangeeft wanneer, waar en door wie een rijbewijs/ID-kaart is gemaakt. Als een |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, DHS vereist veld dat de datum aangeeft van de meest recente versiewijziging of wijziging van het zichtbare formaat van t |
| [setComplianceType()](#setcompliancetype) | DDA, DHS vereist veld dat de naleving aangeeft: “F” = nalevend; en, “N” = niet-nalevend, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, Tekst die de jurisdictiespecifieke code(s) uitlegt die extra rijbevoegdheden aangeven die aan de ca zijn verleend |
| [setHairColor()](#sethaircolor) | DAZ, Kale, zwart, blond, bruin, grijs, rood/kastanjebruin, zandkleurig, wit, onbekend. Als de uitgevende jurisdictie wil afkorten |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, Een reeks letters en/of cijfers die wordt aangebracht op de grondstoffen (karton, laminaat, enz.) die worden gebruikt in de productie |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, DHS vereist veld dat aangeeft dat de kaarthouder een tijdelijke wettelijke status heeft = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, Naamachtervoegsel (Als de jurisdictie deelneemt aan systemen die een naamachtervoegsel vereisen (PDPS, CDLIS, enz.), moet het achtervoegsel |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, Veld dat aangeeft dat de kaarthouder een orgaandonor is = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, Land en gemeente en/of staat/provincie, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, Codes voor ras of etniciteit van de kaarthouder, zoals gedefinieerd in AAMVA D20, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, Tekst die de jurisdictiespecifieke restrictiecode(s) beschrijft die rijbevoegdheden beperken, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, Standaard endorsementcode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, Standaard restrictiecode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, Standaard voertuigclassificatiecode(s) voor kaarthouder. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen om te st |
| [setUnder18Until()](#setunder18until) | DDI, Datum waarop de kaarthouder 19 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, Datum waarop de kaarthouder 19 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, Datum waarop de kaarthouder 21 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, Tekst die de jurisdictiespecifieke code(s) uitlegt voor classificaties van voertuigen waarvoor de kaarthouder bevoegd is om te rijden |
| [setVeteranIndicator()](#setveteranindicator) | DDL, Veld dat aangeeft dat de kaarthouder een veteraan is = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, Gewicht van de kaarthouder in kilogram, bijv. 84 kg = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, Gewicht van de kaarthouder in ponden, bijv. 185 lb = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, Geeft het geschatte gewicht bereik van de kaarthouder aan: 0 = tot 31 kg (tot 70 lb), 1 = 32 – 45 kg (71 – 100 lb |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, Andere achternaam waaronder kaarthouder bekend is, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, Andere voornaam waaronder kaarthouder bekend is, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, Andere suffix waaronder kaarthouder bekend is, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, Een reeks letters en/of cijfers die aangeeft wanneer, waar en door wie een rijbewijs/ID-kaart is gemaakt. Als auditinformatie niet op de kaart of de MRT wordt gebruikt, moet deze worden opgenomen in het bestuurderrecord, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, vereist veld van DHS dat de datum aangeeft van de meest recente versiewijziging of aanpassing van het zichtbare formaat van de DL/ID. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, DHS vereist veld dat de naleving aangeeft: “F” = nalevend; en, “N” = niet-nalevend, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, Tekst die de rechtsgebiedspecifieke code(s) uitlegt die extra rijbevoegdheden aangeven die aan de kaarthouder worden verleend bovenop de voertuigklasse, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, Kaal, zwart, blond, bruin, grijs, rood/kastanjebruin, zandkleurig, wit, onbekend. Als het uitgevende rechtsgebied kleuren wil afkorten, moeten de drieletterige codes uit AAMVA D20 worden gebruikt, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, Datum waarop de gevaarlijke stoffen‑toelating die door het document is verleend niet meer geldig is. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, Een reeks letters en/of cijfers die wordt aangebracht op de grondstoffen (kaartpapier, laminaat, enz.) die worden gebruikt bij het produceren van rijbewijzen en ID-kaarten. (aanbevolen veld van DHS), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, DHS vereist veld dat aangeeft dat de kaarthouder een tijdelijke wettelijke status heeft = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, Naamachtervoegsel (Als het rechtsgebied deelneemt aan systemen die een naamachtervoegsel vereisen (PDPS, CDLIS, enz.), moet het achtervoegsel worden verzameld en weergegeven op de DL/ID en in de MRT). JR (Junior), SR (Senior), 1ST of I (Eerste), tot 9TH of IX (Negende), DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, Veld dat aangeeft dat de kaarthouder een orgaandonor is = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, Land en gemeente en/of staat/provincie, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, Codes voor ras of etniciteit van de kaarthouder, zoals gedefinieerd in AAMVA D20, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, Tekst die de jurisdictiespecifieke restrictiecode(s) beschrijft die rijbevoegdheden beperken, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, Standaard toelatingscode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om toelatingscodes te standaardiseren, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, Standaard restrictiecode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om restrictiecodes te standaardiseren, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, Standaard voertuigclassificatiecode(s) voor kaarthouder. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om voertuigclassificaties te standaardiseren, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, Datum waarop de kaarthouder 18 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, Datum waarop de kaarthouder 21 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, Tekst die de rechtsgebiedspecifieke code(s) uitlegt voor de classificaties van voertuigen die de kaarthouder mag besturen, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, Veld dat aangeeft dat de kaarthouder een veteraan is = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, Gewicht van de kaarthouder in kilogram, bijv. 84 kg = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, Gewicht van de kaarthouder in ponden, bijv. 185 lb = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, Geeft het geschatte gewichtsspectrum van de kaarthouder aan: 0 = tot 31 kg (tot 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, Tweede regel van het straatdeel van het adres van de kaarthouder, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, Andere achternaam waaronder kaarthouder bekend is, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, Andere voornaam waaronder kaarthouder bekend is, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, Andere suffix waaronder kaarthouder bekend is, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, Een reeks letters en/of cijfers die aangeeft wanneer, waar en door wie een rijbewijs/ID-kaart is gemaakt. Als auditinformatie niet op de kaart of de MRT wordt gebruikt, moet deze worden opgenomen in het bestuurderrecord, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, vereist veld van DHS dat de datum aangeeft van de meest recente versiewijziging of aanpassing van het zichtbare formaat van de DL/ID. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, DHS vereist veld dat de naleving aangeeft: “F” = nalevend; en, “N” = niet-nalevend, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, Tekst die de rechtsgebiedspecifieke code(s) uitlegt die extra rijbevoegdheden aangeven die aan de kaarthouder worden verleend bovenop de voertuigklasse, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, Kaal, zwart, blond, bruin, grijs, rood/kastanjebruin, zandkleurig, wit, onbekend. Als het uitgevende rechtsgebied kleuren wil afkorten, moeten de drieletterige codes uit AAMVA D20 worden gebruikt, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, Een reeks letters en/of cijfers die wordt aangebracht op de grondstoffen (kaartpapier, laminaat, enz.) die worden gebruikt bij het produceren van rijbewijzen en ID-kaarten. (aanbevolen veld van DHS), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, DHS vereist veld dat aangeeft dat de kaarthouder een tijdelijke wettelijke status heeft = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, Naamachtervoegsel (Als het rechtsgebied deelneemt aan systemen die een naamachtervoegsel vereisen (PDPS, CDLIS, enz.), moet het achtervoegsel worden verzameld en weergegeven op de DL/ID en in de MRT). JR (Junior), SR (Senior), 1ST of I (Eerste), tot 9TH of IX (Negende), DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, Veld dat aangeeft dat de kaarthouder een orgaandonor is = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, Land en gemeente en/of staat/provincie, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, Codes voor ras of etniciteit van de kaarthouder, zoals gedefinieerd in AAMVA D20, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, Tekst die de jurisdictiespecifieke restrictiecode(s) beschrijft die rijbevoegdheden beperken, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, Standaard toelatingscode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om toelatingscodes te standaardiseren, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, Standaard restrictiecode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om restrictiecodes te standaardiseren, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, Standaard voertuigclassificatiecode(s) voor kaarthouder. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige pogingen om voertuigclassificaties te standaardiseren, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, Datum waarop de kaarthouder 19 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, Datum waarop de kaarthouder 19 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, Datum waarop de kaarthouder 21 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, Tekst die de rechtsgebiedspecifieke code(s) uitlegt voor de classificaties van voertuigen die de kaarthouder mag besturen, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, Veld dat aangeeft dat de kaarthouder een veteraan is = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, Gewicht van de kaarthouder in kilogram, bijv. 84 kg = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, Gewicht van de kaarthouder in ponden, bijv. 185 lb = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, Geeft het geschatte gewichtsspectrum van de kaarthouder aan: 0 = tot 31 kg (tot 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N
