---
title: "Klass USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields-klass. Valfria elementfält för kortet"
type: docs
weight: 830
url: /sv/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Valfria element (fält) på kortet

```csharp
public class OptionalFields
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Andra raden i gatadelen av kortinnehavarens adress, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Annat efternamn som kortinnehavaren är känd under, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Annat förnamn som kortinnehavaren är känd under, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Annan suffix som kortinnehavaren är känd under, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, En sträng av bokstäver och/eller siffror som identifierar när, var och av vem ett körkort/ID‑kort tillverkades. Om revisionsinformation inte används på kortet eller MRT måste den inkluderas i förarposten, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, DHS‑kravfält som anger datum för den senaste versionsändringen eller modifieringen av det synliga formatet för DL/ID. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, DHS‑kravfält som anger efterlevnad: “F” = efterlevande; och, “N” = icke‑efterlevande, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Text som förklarar de jurisdiktionsspecifika koderna som indikerar ytterligare körbehörigheter som beviljats kortinnehavaren utöver fordonsklassen, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Skallig, svart, blond, brun, grå, röd/akanel, sandig, vit, okänd. Om den utfärdande jurisdiktionen vill förkorta färger måste de treteckenkoder som anges i AAMVA D20 användas, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Datum då den farliga materialgodkännande som beviljats av dokumentet inte längre är giltig. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, En sträng av bokstäver och/eller siffror som fästs på råmaterialet (kortpapper, laminerat etc.) som används vid produktion av körkort och ID‑kort. (DHS‑rekommenderat fält), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, DHS‑kravfält som anger att kortinnehavaren har tillfällig laglig status = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Namnsuffix (Om jurisdiktionen deltar i system som kräver namnsuffix (PDPS, CDLIS, etc.), måste suffixet samlas in och visas på DL/ID och i MRT). JR(Junior), SR(Senior), 1ST eller I(Första), upp till 9TH eller IX (Nionde), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Fält som indikerar att kortinnehavaren är organdonator = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Land och kommun och/eller delstat/provins, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Koder för ras eller etnicitet för kortinnehavaren, enligt AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Text som beskriver den jurisdiktionsspecifika restriktionskoden/koderna som begränsar körbehörigheten, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Standardiserade godkännandekoder för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser att standardisera godkännandekoder, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Standardiserade restriktionskoder för kortinnehavaren. Se koder i D20. Detta dataelement är en platshållare för framtida insatser att standardisera restriktionskoder, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Standardiserade fordonsklassificeringskoder för kortinnehavaren. Detta dataelement är en platshållare för framtida insatser att standardisera fordonsklassificeringar, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Datum då kortinnehavaren fyller 18 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Datum då kortinnehavaren fyller 19 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Datum då kortinnehavaren fyller 21 år. (MMDDCCYY för USA, CCYYMMDD för Kanada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Text som förklarar den jurisdiktionsspecifika koden/koderna för klassificering av fordon som kortinnehavaren är behörig att köra, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Fält som indikerar att kortinnehavaren är veteran = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Kortinnehavarens vikt i kilogram, Ex. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Kortinnehavarens vikt i pund, Ex. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Anger det ungefärliga viktintervallet för kortinnehavaren: 0 = upp till 31 kg (upp till 70 lb), 1 = 32–45 kg (71–100 lb), 2 = 46–59 kg (101–130 lb), 3 = 60–70 kg (131–160 lb), 4 = 71–86 kg (161–190 lb), 5 = 87–100 kg (191–220 lb), 6 = 101–113 kg (221–250 lb), 7 = 114–127 kg (251–280 lb), 8 = 128–145 kg (281–320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Se även

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


