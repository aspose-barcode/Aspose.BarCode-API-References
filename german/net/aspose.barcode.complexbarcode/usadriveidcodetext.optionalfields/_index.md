---
title: "Klasse USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields Klasse. Optionale Elementfelder der Karte"
type: docs
weight: 830
url: /de/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Optionale Elemente (Felder) der Karte

```csharp
public class OptionalFields
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Zweite Zeile des Straßenanteils der Karteninhaberadresse, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Anderer Familienname, unter dem der Karteninhaber bekannt ist, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Anderer Vorname, unter dem der Karteninhaber bekannt ist, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Andere Namenssuffix, unter dem der Karteninhaber bekannt ist, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die angibt, wann, wo und von wem ein Führerschein/Personalausweis hergestellt wurde. Wenn Auditinformationen nicht auf der Karte oder dem MRT verwendet werden, muss sie im Fahrer‑Datensatz enthalten sein, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, Vom DHS gefordertes Feld, das das Datum der letzten Versionsänderung oder Modifikation des sichtbaren Formats des DL/ID angibt. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, Vom DHS gefordertes Feld, das die Konformität angibt: "F" = konform; und "N" = nicht konform, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Text, der die jurisdictionsspezifischen Codes erklärt, die zusätzliche Fahrprivilegien über die Fahrzeugklasse hinaus für den Karteninhaber angeben, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Glatzköpfig, schwarz, blond, braun, grau, rot/rotbraun, sandig, weiß, unbekannt. Wenn die ausstellende Behörde Farben abkürzen möchte, müssen die in AAMVA D20 bereitgestellten Drei‑Buchstaben‑Codes verwendet werden, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Datum, an dem die durch das Dokument gewährte Gefahrgutbefugnis nicht mehr gültig ist. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, Eine Zeichenkette aus Buchstaben und/oder Zahlen, die an den Rohmaterialien (Kartenpapier, Laminat usw.) befestigt ist, die bei der Herstellung von Führerscheinen und Personalausweisen verwendet werden. (Vom DHS empfohlenes Feld), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, Vom DHS gefordertes Feld, das anzeigt, dass der Karteninhaber einen vorübergehenden rechtmäßigen Status hat = "1", DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Namenssuffix (Wenn die Jurisdiktion an Systemen teilnimmt, die ein Namenssuffix erfordern (PDPS, CDLIS usw.), muss das Suffix im DL/ID und im MRT erfasst und angezeigt werden). JR (Junior), SR (Senior), 1ST oder I (Erster), bis 9TH oder IX (Neunter), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Feld, das anzeigt, dass der Karteninhaber Organspender ist = "1", DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Land und Gemeinde und/oder Bundesland/Provinz, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Codes für Rasse oder ethnische Zugehörigkeit des Karteninhabers, wie in AAMVA D20 definiert, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Text, der die behördenspezifischen Einschränkungscode(s) beschreibt, die Fahrprivilegien einschränken, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Standard‑Endorsement‑Code(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen zur Standardisierung von Endorsement‑Codes, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Standard‑Einschränkungscode(s) für den Karteninhaber. Siehe Codes in D20. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen zur Standardisierung von Einschränkungscodes, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Standard‑Fahrzeugklassifikationscode(s) für den Karteninhaber. Dieses Datenelement ist ein Platzhalter für zukünftige Bemühungen zur Standardisierung von Fahrzeugklassifikationen, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Datum, an dem der Karteninhaber 18 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Datum, an dem der Karteninhaber 19 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Datum, an dem der Karteninhaber 21 Jahre alt wird. (MMDDCCYY für die USA, CCYYMMDD für Kanada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Text, der die behördenspezifischen Code(s) für die Fahrzeugklassifikationen erklärt, die der Karteninhaber fahren darf, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Feld, das anzeigt, dass der Karteninhaber ein Veteran ist = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Gewicht des Karteninhabers in Kilogramm, z.B. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Gewicht des Karteninhabers in Pfund, z.B. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Gibt die ungefähre Gewichts­spanne des Karteninhabers an: 0 = bis zu 31 kg (bis zu 70 lb), 1 = 32 – 45 kg (71 – 100 lb), 2 = 46 – 59 kg (101 – 130 lb), 3 = 60 – 70 kg (131 – 160 lb), 4 = 71 – 86 kg (161 – 190 lb), 5 = 87 – 100 kg (191 – 220 lb), 6 = 101 – 113 kg (221 – 250 lb), 7 = 114 – 127 kg (251 – 280 lb), 8 = 128 – 145 kg (281 – 320 lb), 9 = 146+ kg (321+ lb), DL/ID, F1N |

### Siehe auch

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


