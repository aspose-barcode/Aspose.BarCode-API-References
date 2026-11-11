---
title: "Klasse USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields klasse. Optionele elementvelden van de kaart"
type: docs
weight: 830
url: /nl/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Optionele elementen (velden) van de kaart

```csharp
public class OptionalFields
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Tweede regel van het straatgedeelte van het adres van de kaarthouder, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Andere achternaam waaronder de kaarthouder bekend staat, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Andere voornaam waaronder de kaarthouder bekend staat, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Andere achtervoegsel waaronder de kaarthouder bekend staat, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Een reeks letters en/of cijfers die aangeeft wanneer, waar en door wie een rijbewijs/ID-kaart is gemaakt. Als auditinformatie niet op de kaart of de MRT wordt gebruikt, moet deze worden opgenomen in het bestuurdersrecord, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Door DHS verplicht veld dat de datum aangeeft van de meest recente versiewijziging of wijziging van het zichtbare formaat van de DL/ID. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Door DHS verplicht veld dat de naleving aangeeft: “F” = conform; en, “N” = niet-conform, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Tekst die de jurisdictiespecifieke code(s) uitlegt die extra rijprivileges aangeven die aan de kaarthouder zijn verleend bovenop de voertuigklasse, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Kale, zwart, blond, bruin, grijs, rood/bruine, zandkleurig, wit, onbekend. Als de uitgevende jurisdictie kleuren wil afkorten, moeten de drieletterige codes uit AAMVA D20 worden gebruikt, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Datum waarop de door het document verleende gevaarlijke stoffen-endorsement niet meer geldig is. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Een reeks letters en/of cijfers die wordt bevestigd aan de grondstoffen (kaartpapier, laminaat, enz.) die worden gebruikt bij het produceren van rijbewijzen en ID-kaarten. (Door DHS aanbevolen veld), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Door DHS verplicht veld dat aangeeft dat de kaarthouder een tijdelijke wettelijke status heeft = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Naamachtervoegsel (Als de jurisdictie deelneemt aan systemen die een naamachtervoegsel vereisen (PDPS, CDLIS, enz.), moet het achtervoegsel worden verzameld en weergegeven op de DL/ID en in de MRT). JR (Junior), SR (Senior), 1ST of I (Eerste), tot 9TH of IX (Negende), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Veld dat aangeeft dat de kaarthouder orgaandonor is = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Land en gemeente en/of staat/provincie, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Codes voor ras of etniciteit van de kaarthouder, zoals gedefinieerd in AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Tekst die de jurisdictiespecifieke restrictiecode(s) beschrijft die rijprivileges beperken, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Standaard endorsementcode(s) voor de kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen om endorsementcodes te standaardiseren, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Standaard restrictiecode(s) voor kaarthouder. Zie codes in D20. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen om restrictiecodes te standaardiseren, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Standaard voertuigclassificatiecode(s) voor kaarthouder. Dit gegevenselement is een tijdelijke aanduiding voor toekomstige inspanningen om voertuigclassificaties te standaardiseren, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Datum waarop de kaarthouder 18 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Datum waarop de kaarthouder 19 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Datum waarop de kaarthouder 21 jaar wordt. (MMDDCCYY voor VS, CCYYMMDD voor Canada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Tekst die de jurisdictiespecifieke code(s) voor voertuigclassificaties verklaart die de kaarthouder mag besturen, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Veld dat aangeeft dat de kaarthouder een veteraan is = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Gewicht van de kaarthouder in kilogram, Bv. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Gewicht van de kaarthouder in ponden, Bv. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Geeft het geschatte gewichtsspectrum van de kaarthouder aan: 0 = tot 31 kg (tot 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 - 59 kg (101 – 130 lb), 3 = 60 - 70 kg (131 – 160 lb), 4 = 71 - 86 kg (161 – 190 lb), 5 = 87 - 100 kg (191 – 220 lb), 6 = 101 - 113 kg (221 – 250 lb), 7 = 114 - 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Zie ook

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


