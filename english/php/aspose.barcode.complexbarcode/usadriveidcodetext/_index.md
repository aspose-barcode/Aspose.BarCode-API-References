---
title: "USADriveIdCodetext"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for encoding and decoding the text embedded in the USA Driving License PDF417 code."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for encoding and decoding the text embedded in the USA Driving License PDF417 code.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [addSubfileDesignator](#addsubfiledesignator) | No | Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically. |
| [initFromString](#initfromstring) | No | Initialize USA DL object from codetext |
| [saveToXml](#savetoxml) | No |  |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [AAMVAVersionNumber](#aamvaversionnumber) | Read/Write | AAMVA Version Number 00-99 |
| [BarcodeType](#barcodetype) | Read-only | Returns barcode type of USA DL (Pdf417) |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Construct codetext from USA DL data |
| [IssuerIdentificationNumber](#issueridentificationnumber) | Read/Write | This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded. |
| [JurisdictionSpecificSubfile](#jurisdictionspecificsubfile) | Read/Write | Jurisdiction Specific Fields |
| [JurisdictionVersionNumber](#jurisdictionversionnumber) | Read/Write | Jurisdiction Version Number 00-99 |
| [MandatoryElements](#mandatoryelements) | Read/Write | Mandatory elements (fields) of the card |
| [NumberOfEntries](#numberofentries) | Read/Write | Number 00-99 of subfiles |
| [OptionalElements](#optionalelements) | Read/Write | Optional elements (fields) of the card |
| [SubfileDesignator](#subfiledesignator) | Read/Write | Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically. |

### USADriveIdCodetext__construct() {#constructor}

### addSubfileDesignatoraddSubfileDesignator(SubfileProperties $value) {#addsubfiledesignator}

Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `SubfileProperties` |  |

### initFromStringinitFromString(string $constructedCodetext) {#initfromstring}

Initialize USA DL object from codetext

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `string` | Constructed codetext |

### saveToXmlsaveToXml() {#savetoxml}

### AAMVAVersionNumber {#aamvaversionnumber}

**Access:** Read/Write

AAMVA Version Number 00-99

AAMVA Version Number 00-99

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### BarcodeType {#barcodetype}

**Access:** Read-only

**Returns:** Barcode type (Pdf417)

Returns barcode type of USA DL (Pdf417)

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** Constructed codetext

Construct codetext from USA DL data

### IssuerIdentificationNumber {#issueridentificationnumber}

**Access:** Read/Write

This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded.

This number uniquely identifies the issuing jurisdiction and can be obtained by contacting the ISO Issuing Authority(AAMVA). The full 6-digit IIN should be encoded.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### JurisdictionSpecificSubfile {#jurisdictionspecificsubfile}

**Access:** Read/Write

Jurisdiction Specific Fields

Jurisdiction Specific Fields

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `USADriveIdJurisdSubfile` |  |

### JurisdictionVersionNumber {#jurisdictionversionnumber}

**Access:** Read/Write

Jurisdiction Version Number 00-99

Jurisdiction Version Number 00-99

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### MandatoryElements {#mandatoryelements}

**Access:** Read/Write

Mandatory elements (fields) of the card

Mandatory elements (fields) of the card

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `MandatoryFields` |  |

### NumberOfEntries {#numberofentries}

**Access:** Read/Write

Number 00-99 of subfiles

Number 00-99 of subfiles

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### OptionalElements {#optionalelements}

**Access:** Read/Write

Optional elements (fields) of the card

Optional elements (fields) of the card

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `OptionalFields` |  |

### SubfileDesignator {#subfiledesignator}

**Access:** Read/Write

Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically.

Contains information about following subfiles, types, offsets and lengths. Important: set only type, offset and length will be set automatically.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `array` |  |

