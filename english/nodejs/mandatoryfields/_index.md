---
title: "MandatoryFields Class"
linktitle: "MandatoryFields"
articleTitle: "MandatoryFields"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Mandatory elements (fields) of the card."
type: docs
weight: 370
url: /nodejs/mandatoryfields/
---
## MandatoryFields class

Mandatory elements (fields) of the card

```javascript
public class MandatoryFields : BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [MandatoryFields](./mandatoryfields/#constructor)(*object*) | Initializes a new instance of the MandatoryFields class. |

## Methods

| Name | Description |
| --- | --- |
| [getAddressCity](./getaddresscity/) | DAI, City portion of the cardholder address, DL/ID, V20ANS. |
| [getAddressPostalCode](./getaddresspostalcode/) | DAK, Postal code portion of the cardholder address in the U.S.and Canada. If the trailing portion of the postal code in the U.S. is not known, zeros will be used to fill the trailing set of numbers up to 9 digits, DL/ID, F11ANS. |
| [getAddressState](./getaddressstate/) | DAJ, State portion of the cardholder address, DL/ID, F2A. |
| [getAddressStreet1](./getaddressstreet1/) | DAG, Street portion of the cardholder address, DL/ID, V35ANS. |
| [getCountryIdentification](./getcountryidentification/) | DCG, Country in which DL/ID is issued. U.S. = USA, Canada = CAN, DL/ID, F3A. |
| [getCustomerIDNumber](./getcustomeridnumber/) | DAQ, The number assigned or calculated by the issuing authority, DL/ID, V25ANS. |
| [getDateOfBirth](./getdateofbirth/) | DBB, Date on which the document was issued, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N. |
| [getDocumentDiscriminator](./getdocumentdiscriminator/) | DCF, Number must uniquely identify a particular document issued to that customer from others that may have been issued in the past. This number may serve multiple purposes of document discrimination, audit information number, and/or inventory control, DL/ID, V25ANS. |
| [getEndorsementCodes](./getendorsementcodes/) | DCD, Jurisdiction specific endorsement codes, DL, V5ANS. |
| [getEyeColor](./geteyecolor/) | DAY, Color of cardholder's eyes. (ANSI D-20 codes). DL/ID, F3A. |
| [getFamilyName](./getfamilyname/) | DCS, Family name of the cardholder, DL/ID, V40ANS. |
| [getFamilyNameTruncation](./getfamilynametruncation/) | DDE, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [getFirstName](./getfirstname/) | DAC, First name of the cardholder, DL/ID, V40ANS. |
| [getFirstNameTruncation](./getfirstnametruncation/) | DDF, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [getHeight](./getheight/) | DAU, Height of cardholder. Inches (in): number of inches followed by " in" ex. 6'1'' = "073 in" Centimeters(cm) : number of centimeters followed by " cm" ex. 181 centimeters="181 cm" , DL/ID, F6ANS. |
| [getMiddleName](./getmiddlename/) | DAD, Middle name(s) of the cardholder. In the case of multiple middle names they shall be separated by a comma ",". , DL/ID, V40ANS. |
| [getMiddleNameTruncation](./getmiddlenametruncation/) | DDG, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [getRestrictionCodes](./getrestrictioncodes/) | DCB, Jurisdiction-specific restrictions codes, DL, V12ANS. |
| [getSex](./getsex/) | DBC, Gender of the cardholder. 1 = male, 2 = female, 9 = not specified, DL/ID, F1N. |
| [getVehicleClass](./getvehicleclass/) | DCA, Jurisdiction-specific vehicle class / group code, DL, V6ANS. |
| [init](./init/) |  |
| [setAddressCity](./setaddresscity/)(*object*) | DAI, City portion of the cardholder address, DL/ID, V20ANS. |
| [setAddressPostalCode](./setaddresspostalcode/)(*object*) | DAK, Postal code portion of the cardholder address in the U.S.and Canada. If the trailing portion of the postal code in the U.S. is not known, zeros will be used to fill the trailing set of numbers up to 9 digits, DL/ID, F11ANS. |
| [setAddressState](./setaddressstate/)(*object*) | DAJ, State portion of the cardholder address, DL/ID, F2A. |
| [setAddressStreet1](./setaddressstreet1/)(*object*) | DAG, Street portion of the cardholder address, DL/ID, V35ANS. |
| [setCountryIdentification](./setcountryidentification/)(*object*) | DCG, Country in which DL/ID is issued. U.S. = USA, Canada = CAN, DL/ID, F3A. |
| [setCustomerIDNumber](./setcustomeridnumber/)(*object*) | DAQ, The number assigned or calculated by the issuing authority, DL/ID, V25ANS. |
| [setDateOfBirth](./setdateofbirth/)(*object*) | DBB, Date on which the document was issued, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N. |
| [setDocumentDiscriminator](./setdocumentdiscriminator/)(*object*) | DCF, Number must uniquely identify a particular document issued to that customer from others that may have been issued in the past. This number may serve multiple purposes of document discrimination, audit information number, and/or inventory control, DL/ID, V25ANS. |
| [setEndorsementCodes](./setendorsementcodes/)(*object*) | DCD, Jurisdiction specific endorsement codes, DL, V5ANS. |
| [setEyeColor](./seteyecolor/)(*object*) | DAY, Color of cardholder's eyes. (ANSI D-20 codes). DL/ID, F3A. |
| [setFamilyName](./setfamilyname/)(*object*) | DCS, Family name of the cardholder, DL/ID, V40ANS. |
| [setFamilyNameTruncation](./setfamilynametruncation/)(*object*) | DDE, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [setFirstName](./setfirstname/)(*object*) | DAC, First name of the cardholder, DL/ID, V40ANS. |
| [setFirstNameTruncation](./setfirstnametruncation/)(*object*) | DDF, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [setHeight](./setheight/)(*object*) | DAU, Height of cardholder. Inches (in): number of inches followed by " in" ex. 6'1'' = "073 in" Centimeters(cm) : number of centimeters followed by " cm" ex. 181 centimeters="181 cm" , DL/ID, F6ANS. |
| [setMiddleName](./setmiddlename/)(*object*) | DAD, Middle name(s) of the cardholder. In the case of multiple middle names they shall be separated by a comma ",". , DL/ID, V40ANS. |
| [setMiddleNameTruncation](./setmiddlenametruncation/)(*object*) | DDG, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A. |
| [setRestrictionCodes](./setrestrictioncodes/)(*object*) | DCB, Jurisdiction-specific restrictions codes, DL, V12ANS. |
| [setSex](./setsex/)(*object*) | DBC, Gender of the cardholder. 1 = male, 2 = female, 9 = not specified, DL/ID, F1N. |
| [setVehicleClass](./setvehicleclass/)(*object*) | DCA, Jurisdiction-specific vehicle class / group code, DL, V6ANS. |

### See Also

* assembly [Aspose.BarCode](../)

