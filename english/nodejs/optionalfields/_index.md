---
title: OptionalFields Class
linktitle: OptionalFields
articleTitle: OptionalFields
second_title: Aspose.BarCode for Node.js via Java
description: "Optional elements (fields) of the card."
type: docs
weight: 390
url: /nodejs/optionalfields/
---
## OptionalFields class

Optional elements (fields) of the card

```javascript
public class OptionalFields : BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [OptionalFields](./optionalfields/#constructor)(*object*) | Initializes a new instance of the OptionalFields class. |

## Methods

| Name | Description |
| --- | --- |
| [getAddressStreet2](./getaddressstreet2/) |  |
| [getAliasAKAFamilyName](./getaliasakafamilyname/) | DBN, Other family name by which cardholder is known, DL/ID, V10ANS. |
| [getAliasAKAGivenName](./getaliasakagivenname/) | DBG, Other given name by which cardholder is known, DL/ID, V15ANS. |
| [getAliasAKASuffixName](./getaliasakasuffixname/) | DBS, Other suffix by which cardholder is known, DL/ID, V5ANS. |
| [getAuditInformation](./getauditinformation/) | DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS. |
| [getCardRevisionDate](./getcardrevisiondate/) | DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [getComplianceType](./getcompliancetype/) | DDA, DHS required field that indicates compliance: “F” = compliant; and, “N” = non-compliant, DL/ID, F1A. |
| [getEndorsementCodeDescription](./getendorsementcodedescription/) | DCQ, Text that explains the jurisdiction-specific code(s) that indicates additional driving privileges granted to the cardholder beyond the vehicle class, DL, V50ANS. |
| [getHAZMATEndorsementExpDate](./gethazmatendorsementexpdate/) | DDC, Date on which the hazardous material endorsement granted by the document is no longer valid. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL, F8N. |
| [getHairColor](./gethaircolor/) | DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A. |
| [getInventoryControlNumber](./getinventorycontrolnumber/) | DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS. |
| [getLimitedDurationDocIndicator](./getlimiteddurationdocindicator/) | DDD, DHS required field that indicates that the cardholder has temporary lawful status = “1”, DL/ID, F1N. |
| [getNameSuffix](./getnamesuffix/) | DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS. |
| [getOrganDonorIndicator](./getorgandonorindicator/) | DDK, Field that indicates that the cardholder is an organ donor = “1”, DL/ID, F1N. |
| [getPlaceOfBirth](./getplaceofbirth/) | DCI, Country and municipality and/or state/province, DL/ID, V33A. |
| [getRaceEthnicity](./getraceethnicity/) | DCL, Codes for race or ethnicity of the cardholder, as defined in AAMVA D20, DL/ID, V3A. |
| [getRestrictionCodeDescription](./getrestrictioncodedescription/) | DCR, Text describing the jurisdiction-specific restriction code(s) that curtail driving privileges, DL, V50ANS. |
| [getStandardEndorsementCode](./getstandardendorsementcode/) | DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN. |
| [getStandardRestrictionCode](./getstandardrestrictioncode/) | DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN. |
| [getStandardVehClassification](./getstandardvehclassification/) | DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN. |
| [getUnder18Until](./getunder18until/) | DDH, Date on which the cardholder turns 18 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [getUnder21Until](./getunder21until/) | DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [getVehClassDescription](./getvehclassdescription/) | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS. |
| [getVeteranIndicator](./getveteranindicator/) | DDL, Field that indicates that the cardholder is a veteran = “1”, DL/ID, F1N. |
| [getWeightKilograms](./getweightkilograms/) | DAX, Cardholder weight in kilograms, Ex. 84 kg = “084”, DL/ID, F3N. |
| [getWeightPounds](./getweightpounds/) | DAW, Cardholder weight in pounds, Ex. 185 lb = “185”, DL/ID, F3N. |
| [getWeightRange](./getweightrange/) | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127... |
| [init](./init/) |  |
| [setAddressStreet2](./setaddressstreet2/)(*object*) | DAH, Second line of street portion of the cardholder address, DL/ID, V35ANS. |
| [setAliasAKAFamilyName](./setaliasakafamilyname/)(*object*) | DBN, Other family name by which cardholder is known, DL/ID, V10ANS. |
| [setAliasAKAGivenName](./setaliasakagivenname/)(*object*) | DBG, Other given name by which cardholder is known, DL/ID, V15ANS. |
| [setAliasAKASuffixName](./setaliasakasuffixname/)(*object*) | DBS, Other suffix by which cardholder is known, DL/ID, V5ANS. |
| [setAuditInformation](./setauditinformation/)(*object*) | DCJ, A string of letters and/or numbers that identifies when, where, and by whom a driver license/ID card was made. If audit information is not used on the card or the MRT, it must be included in the driver record, DL/ID, V25ANS. |
| [setCardRevisionDate](./setcardrevisiondate/)(*object*) | DDB, DHS required field that indicates date of the most recent version change or modification to the visible format of the DL/ID. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [setComplianceType](./setcompliancetype/)(*object*) | DDA, DHS required field that indicates compliance: “F” = compliant; and, “N” = non-compliant, DL/ID, F1A. |
| [setEndorsementCodeDescription](./setendorsementcodedescription/)(*object*) | DCQ, Text that explains the jurisdiction-specific code(s) that indicates additional driving privileges granted to the cardholder beyond the vehicle class, DL, V50ANS. |
| [setHairColor](./sethaircolor/)(*object*) | DAZ, Bald, black, blonde, brown, gray, red/auburn, sandy, white, unknown. If the issuing jurisdiction wishes to abbreviate colors, the three-character codes provided in AAMVA D20 must be used, DL/ID, V12A. |
| [setInventoryControlNumber](./setinventorycontrolnumber/)(*object*) | DCK, A string of letters and/or numbers that is affixed to the raw materials(card stock, laminate, etc.) used in producing driver licenses and ID cards. (DHS recommended field), DL/ID, V25ANS. |
| [setLimitedDurationDocIndicator](./setlimiteddurationdocindicator/)(*object*) | DDD, DHS required field that indicates that the cardholder has temporary lawful status = “1”, DL/ID, F1N. |
| [setNameSuffix](./setnamesuffix/)(*object*) | DCU, Name Suffix (If jurisdiction participates in systems requiring name suffix (PDPS, CDLIS, etc.), the suffix must be collected and displayed on the DL/ID and in the MRT). JR(Junior), SR(Senior), 1ST or I(First), up to 9TH or IX (Ninth), DL/ID, V5ANS. |
| [setOrganDonorIndicator](./setorgandonorindicator/)(*object*) | DDK, Field that indicates that the cardholder is an organ donor = “1”, DL/ID, F1N. |
| [setPlaceOfBirth](./setplaceofbirth/)(*object*) | DCI, Country and municipality and/or state/province, DL/ID, V33A. |
| [setRaceEthnicity](./setraceethnicity/)(*object*) | DCL, Codes for race or ethnicity of the cardholder, as defined in AAMVA D20, DL/ID, V3A. |
| [setRestrictionCodeDescription](./setrestrictioncodedescription/)(*object*) | DCR, Text describing the jurisdiction-specific restriction code(s) that curtail driving privileges, DL, V50ANS. |
| [setStandardEndorsementCode](./setstandardendorsementcode/)(*object*) | DCN, Standard endorsement code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize endorsement codes, DL, F5AN. |
| [setStandardRestrictionCode](./setstandardrestrictioncode/)(*object*) | DCO, Standard restriction code(s) for cardholder. See codes in D20.This data element is a placeholder for future efforts to standardize restriction codes, DL, F12AN. |
| [setStandardVehClassification](./setstandardvehclassification/)(*object*) | DCM, Standard vehicle classification code(s) for cardholder. This data element is a placeholder for future efforts to standardize vehicle classifications, DL, F4AN. |
| [setUnder18Until](./setunder18until/)(*object*) | DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [setUnder19Until](./setunder19until/)(*object*) | DDI, Date on which the cardholder turns 19 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [setUnder21Until](./setunder21until/)(*object*) | DDJ, Date on which the cardholder turns 21 years old. (MMDDCCYY for U.S., CCYYMMDD for Canada), DL/ID, F8N. |
| [setVehClassDescription](./setvehclassdescription/)(*object*) | DCP, Text that explains the jurisdiction-specific code(s) for classifications of vehicles cardholder is authorized to drive, DL, V50ANS. |
| [setVeteranIndicator](./setveteranindicator/)(*object*) | DDL, Field that indicates that the cardholder is a veteran = “1”, DL/ID, F1N. |
| [setWeightKilograms](./setweightkilograms/)(*object*) | DAX, Cardholder weight in kilograms, Ex. 84 kg = “084”, DL/ID, F3N. |
| [setWeightPounds](./setweightpounds/)(*object*) | DAW, Cardholder weight in pounds, Ex. 185 lb = “185”, DL/ID, F3N. |
| [setWeightRange](./setweightrange/)(*object*) | DCE, Indicates the approximate weight range of the cardholder: 0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127... |

### See Also

* assembly [Aspose.BarCode](../)

