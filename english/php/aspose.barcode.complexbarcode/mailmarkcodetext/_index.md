---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Initializes a new instance of the class. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [initFromString](#initfromstring) | No | Initializes Mailmark data from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarcodeType](#barcodetype) | Read-only | Gets barcode type. |
| [Class_](#class_) | Read/Write | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Construct codetext from Mailmark data. |
| [DestinationPostCodePlusDPS](#destinationpostcodeplusdps) | Read/Write | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [Format](#format) | Read/Write | "0" – Null or Test "1" – Letter "2" – Large Letter |
| [ItemID](#itemid) | Read/Write | Maximum value is 99999999. |
| [SupplyChainID](#supplychainid) | Read/Write | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [VersionID](#versionid) | Read/Write | Currently 1 – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |

### MailmarkCodetext__construct() {#constructor}

Initializes a new instance of the class.

### initFromStringinitFromString($constructedCodetext) {#initfromstring}

Initializes Mailmark data from constructed codetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `$constructedCodetext` | `` |  |

### BarcodeType {#barcodetype}

**Access:** Read-only

**Returns:** int Barcode type.

Gets barcode type.

### Class_ {#class_}

**Access:** Read/Write

"0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

"0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access)

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Construct codetext from Mailmark data.

### DestinationPostCodePlusDPS {#destinationpostcodeplusdps}

**Access:** Read/Write

The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### Format {#format}

**Access:** Read/Write

"0" – Null or Test "1" – Letter "2" – Large Letter

"0" – Null or Test "1" – LetterN "2" – Large Letter

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### ItemID {#itemid}

**Access:** Read/Write

Maximum value is 99999999.

Maximum value is 99999999.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### SupplyChainID {#supplychainid}

**Access:** Read/Write

Maximum values are 99 for Barcode C and 999999 for Barcode L.

Maximum values are 99 for Barcode C and 999999 for Barcode L.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### VersionID {#versionid}

**Access:** Read/Write

Currently 1 – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

Currently 1 – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use)

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

