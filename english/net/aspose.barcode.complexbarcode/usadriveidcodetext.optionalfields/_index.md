---
title: Class USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields class. Optional elements fields of the card
type: docs
weight: 730
url: /net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

Optional elements (fields) of the card

```csharp
public class OptionalFields
```

## Constructors

| Name | Description |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH, Second line of street portion of the cardholder address, DL/ID, V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN, Other family name by which cardholder is known, DL/ID, V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG, Other given name by which cardholder is known, DL/ID, V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS, Other suffix by which cardholder is known, DL/ID, V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA, DHS required field that indicates compliance: “F” = compliant; and, “N” = non-compliant, DL/ID, F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ, Text that explains the jurisdiction-specific code(s) that indicates additional driving privileges granted to the cardholder beyond the vehicle class, DL, V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC, Date on which the hazardous material endorsement granted by the document is no longer valid. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL, F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD, DHS required field that indicates that the cardholder has temporary lawful status = “1”, DL/ID, F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK, Field that indicates that the cardholder is an organ donor = “1”, DL/ID, F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI, Country and municipality and/or state/province, DL/ID, V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL, Codes for race or ethnicity of the cardholder, as defined in AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR, Text describing the jurisdiction-specific restriction code(s) that curtail driving privileges, DL, V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH, Date on which the cardholder turns 18 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL, Field that indicates that the cardholder is a veteran = “1”, DL/ID, F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX, Cardholder weight in kilograms, Ex. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW, Cardholder weight in pounds, Ex. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |

### See Also

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


