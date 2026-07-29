---
title: "MandatoryFields Class"
linktitle: "MandatoryFields"
articleTitle: "MandatoryFields"
second_title: "Aspose.BarCode for PHP via Java"
description: "Mandatory elements (fields) of the card"
type: docs
weight: 10
url: /php/aspose/barcode/complexbarcode/mandatoryfields/
---

## MandatoryFields class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Mandatory elements (fields) of the card


## Constructors

| Name | Description |
| --- | --- |
| [__construct](./mandatoryfields/) |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AddressCity](./addresscity/) | Read/Write | DAI, City portion of the cardholder address, DL/ID, V20ANS |
| [AddressPostalCode](./addresspostalcode/) | Read/Write | DAK, Postal code portion of the cardholder address in the U.S.and Canada. If the trailing portion of the postal code in the U.S. is not known, zeros will be used to fill the trailing set of numbers up to 9 digits, DL/ID, F11ANS |
| [AddressState](./addressstate/) | Read/Write | DAJ, State portion of the cardholder address, DL/ID, F2A |
| [AddressStreet1](./addressstreet1/) | Read/Write | DAG, Street portion of the cardholder address, DL/ID, V35ANS |
| [CountryIdentification](./countryidentification/) | Read/Write | DCG, Country in which DL/ID is issued. U.S. = USA, Canada = CAN, DL/ID, F3A |
| [CustomerIDNumber](./customeridnumber/) | Read/Write | DAQ, The number assigned or calculated by the issuing authority, DL/ID, V25ANS |
| [DateOfBirth](./dateofbirth/) | Read/Write | DBB, Date on which the document was issued, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [DocumentDiscriminator](./documentdiscriminator/) | Read/Write | DCF, Number must uniquely identify a particular document issued to that customer from others that may have been issued in the past. This number may serve multiple purposes of document discrimination, audit information number, and/or inventory control, DL/ID, V25ANS |
| [EndorsementCodes](./endorsementcodes/) | Read/Write | DCD, Jurisdiction specific endorsement codes, DL, V5ANS |
| [EyeColor](./eyecolor/) | Read/Write | DAY, Color of cardholder's eyes. (ANSI D-20 codes). DL/ID, F3A |
| [FamilyName](./familyname/) | Read/Write | DCS, Family name of the cardholder, DL/ID, V40ANS |
| [FamilyNameTruncation](./familynametruncation/) | Read/Write | DDE, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [FirstName](./firstname/) | Read/Write | DAC, First name of the cardholder, DL/ID, V40ANS |
| [FirstNameTruncation](./firstnametruncation/) | Read/Write | DDF, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [Height](./height/) | Read/Write | DAU, Height of cardholder. Inches (in): number of inches followed by " in" ex. 6'1'' = "073 in" Centimeters(cm) : number of centimeters followed by " cm" ex. 181 centimeters="181 cm" , DL/ID, F6ANS |
| [MiddleName](./middlename/) | Read/Write | DAD, Middle name(s) of the cardholder. In the case of multiple middle names they shall be separated by a comma ",". , DL/ID, V40ANS |
| [MiddleNameTruncation](./middlenametruncation/) | Read/Write | DDG, A code that indicates whether a field has been truncated(T), has not been truncated(N), or unknown whether truncated(U), DL/ID, F1A |
| [RestrictionCodes](./restrictioncodes/) | Read/Write | DCB, Jurisdiction-specific restrictions codes, DL, V12ANS |
| [Sex](./sex/) | Read/Write | DBC, Gender of the cardholder. 1 = male, 2 = female, 9 = not specified, DL/ID, F1N |
| [VehicleClass](./vehicleclass/) | Read/Write | DCA, Jurisdiction-specific vehicle class / group code, DL, V6ANS |
