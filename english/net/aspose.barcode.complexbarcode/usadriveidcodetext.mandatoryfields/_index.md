---
title: Class USADriveIdCodetext.MandatoryFields
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields class. Mandatory elements fields of the card
type: docs
weight: 720
url: /net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

Mandatory elements (fields) of the card

```csharp
public class MandatoryFields
```

## Constructors

| Name | Description |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI, City portion of the cardholder address, DL/ID, V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK, Postal code portion of the cardholder address in the U.S.and Canada. If the trailing portion of the postal code in the U.S. is not known, zeros will be used to fill the trailing set of numbers up to 9 digits, DL/ID, F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ, State portion of the cardholder address, DL/ID, F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG, Street portion of the cardholder address, DL/ID, V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG, Country in which DL/ID is issued. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ, The number assigned or calculated by the issuing authority, DL/ID, V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB, Date on which the document was issued, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF, Number must uniquely identify a particular document issued to that customer from others that may have been issued in the past. This number may serve multiple purposes of document discrimination, audit information number, and/or inventory control, DL/ID, V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD, Jurisdiction specific endorsement codes, DL, V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA, Document Expiration Date, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY, Color of cardholder's eyes. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS, Family name of the cardholder, DL/ID, V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC, First name of the cardholder, DL/ID, V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU, Height of cardholder. Inches (in): number of inches followed by " in" ex. 6'1'' = "073 in" Centimeters(cm) : number of centimeters followed by " cm" ex. 181 centimeters="181 cm" , DL/ID, F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD, Date on which the document was issued, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD, Middle name(s) of the cardholder. In the case of multiple middle names they shall be separated by a comma ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB, Jurisdiction-specific restrictions codes, DL, V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC, Gender of the cardholder. 1 = male, 2 = female, 9 = not specified, DL/ID, F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA, Jurisdiction-specific vehicle class / group code, DL, V6ANS |

### See Also

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


