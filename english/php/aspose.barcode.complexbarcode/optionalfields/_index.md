---
title: "OptionalFields Class"
linktitle: "OptionalFields"
articleTitle: "OptionalFields"
second_title: "Aspose.BarCode for PHP via Java"
description: "Optional elements (fields) of the card"
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/optionalfields/
---

## OptionalFields class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Optional elements (fields) of the card


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./optionalfields/) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [setUnder19Until](./setunder19until/) | No | DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AddressStreet2](./addressstreet2/) | Read/Write | DAH, Second line of street portion of the cardholder address, DL/ID, V35ANS |
| [AliasAKAFamilyName](./aliasakafamilyname/) | Read/Write | DBN, Other family name by which cardholder is known, DL/ID, V10ANS |
| [AliasAKAGivenName](./aliasakagivenname/) | Read/Write | DBG, Other given name by which cardholder is known, DL/ID, V15ANS |
| [AliasAKASuffixName](./aliasakasuffixname/) | Read/Write | DBS, Other suffix by which cardholder is known, DL/ID, V5ANS |
| [AuditInformation](./auditinformation/) | Read/Write | DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS |
| [CardRevisionDate](./cardrevisiondate/) | Read/Write | DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [ComplianceType](./compliancetype/) | Read/Write | DDA, DHS required field that indicates compliance: “F” = compliant; and, “N” = non-compliant, DL/ID, F1A |
| [EndorsementCodeDescription](./endorsementcodedescription/) | Read/Write | DCQ, Text that explains the jurisdiction-specific code(s) that indicates additional driving privileges granted to the cardholder beyond the vehicle class, DL, V50ANS |
| [HAZMATEndorsementExpDate](./hazmatendorsementexpdate/) | Read-only | DDC, Date on which the hazardous material endorsement granted by the document is no longer valid. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL, F8N |
| [HairColor](./haircolor/) | Read/Write | DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A |
| [InventoryControlNumber](./inventorycontrolnumber/) | Read/Write | DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS |
| [LimitedDurationDocIndicator](./limiteddurationdocindicator/) | Read/Write | DDD, DHS required field that indicates that the cardholder has temporary lawful status = “1”, DL/ID, F1N |
| [NameSuffix](./namesuffix/) | Read/Write | DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS |
| [OrganDonorIndicator](./organdonorindicator/) | Read/Write | DDK, Field that indicates that the cardholder is an organ donor = “1”, DL/ID, F1N |
| [PlaceOfBirth](./placeofbirth/) | Read/Write | DCI, Country and municipality and/or state/province, DL/ID, V33A |
| [RaceEthnicity](./raceethnicity/) | Read/Write | DCL, Codes for race or ethnicity of the cardholder, as defined in AAMVA D20, DL/ID, V3A |
| [RestrictionCodeDescription](./restrictioncodedescription/) | Read/Write | DCR, Text describing the jurisdiction-specific restriction code(s) that curtail driving privileges, DL, V50ANS |
| [StandardEndorsementCode](./standardendorsementcode/) | Read/Write | DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN |
| [StandardRestrictionCode](./standardrestrictioncode/) | Read/Write | DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN |
| [StandardVehClassification](./standardvehclassification/) | Read/Write | DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN |
| [Under18Until](./under18until/) | Read/Write | DDH, Date on which the cardholder turns 18 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [Under21Until](./under21until/) | Read/Write | DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N |
| [VehClassDescription](./vehclassdescription/) | Read/Write | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS |
| [VeteranIndicator](./veteranindicator/) | Read/Write | DDL, Field that indicates that the cardholder is a veteran = “1”, DL/ID, F1N |
| [WeightKilograms](./weightkilograms/) | Read/Write | DAX, Cardholder weight in kilograms, Ex. 84 kg = “084”, DL/ID, F3N |
| [WeightPounds](./weightpounds/) | Read/Write | DAW, Cardholder weight in pounds, Ex. 185 lb = “185”, DL/ID, F3N |
| [WeightRange](./weightrange/) | Read/Write | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs), DL/ID, F1N |
