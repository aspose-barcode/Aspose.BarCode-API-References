---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for PHP via Java"
description: "Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code."
type: docs
weight: 10
url: /php/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

**Namespace:** `Aspose.Barcode.ComplexBarcode`


Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | Create default instance of Mailmark2DCodetext class. |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [construct](#construct) | Yes |  |
| [initFromString](#initfromstring) | No | Initializes Mailmark data from constructed codetext. |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [BarcodeType](#barcodetype) | Read-only | Gets barcode type. |
| [Class_](#class_) | Read/Write | Identifies the class of the item. Valid Values: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deffered (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [ConstructedCodetext](#constructedcodetext) | Read-only | Construct codetext from Mailmark data. |
| [CustomerContent](#customercontent) | Read/Write | Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters |
| [CustomerContentEncodeMode](#customercontentencodemode) | Read/Write | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [DataMatrixType](#datamatrixtype) | Read/Write | 2D Mailmark Type defines size of Data Matrix barcode. |
| [DestinationPostCodeAndDPS](#destinationpostcodeanddps) | Read/Write | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [InformationTypeID](#informationtypeid) | Read/Write | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: "0" - Domestic Sorted & Unsorted "A" - Online Postage "B" - Franking "C" - Consolidation |
| [ItemID](#itemid) | Read/Write | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [RTSFlag](#rtsflag) | Read/Write | Flag which indicates what level of Return to Sender service is being requested. |
| [ReturnToSenderPostCode](#returntosenderpostcode) | Read/Write | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [SupplyChainID](#supplychainid) | Read/Write | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [UPUCountryID](#upucountryid) | Read/Write | Identifies the UPU Country ID.Max length: 4 characters. |
| [VersionID](#versionid) | Read/Write | Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently "1". "0" & "2" to "9" and "A" to "Z" spare reserved for potential future use. |

### Mailmark2DCodetext__construct() {#constructor}

Create default instance of Mailmark2DCodetext class.

### constructconstruct($complexCodetextDTO) (static) {#construct}

| Parameter | Type | Description |
| --- | --- | --- |
| `$complexCodetextDTO` | `` |  |

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

**Returns:** string class of the item

Identifies the class of the item. Valid Values: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deffered (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

Identifies the class of the item. Valid Values: "1" - 1C (Retail) "2" - 2C (Retail) "3" - Economy (Retail) "5" - Deffered (Retail) "8" - Premium (Network Access) "9" - Standard (Network Access)

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### ConstructedCodetext {#constructedcodetext}

**Access:** Read-only

**Returns:** string Constructed codetext

Construct codetext from Mailmark data.

### CustomerContent {#customercontent}

**Access:** Read/Write

**Returns:** string Customer content

Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### CustomerContentEncodeMode {#customercontentencodemode}

**Access:** Read/Write

**Returns:** int Encode mode of Datamatrix barcode.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DataMatrixType {#datamatrixtype}

**Access:** Read/Write

**Returns:** int Size of Data Matrix barcode

2D Mailmark Type defines size of Data Matrix barcode.

2D Mailmark Type defines size of Data Matrix barcode.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### DestinationPostCodeAndDPS {#destinationpostcodeanddps}

**Access:** Read/Write

**Returns:** string the Postcode of the Delivery Address with DPS

Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### InformationTypeID {#informationtypeid}

**Access:** Read/Write

**Returns:** string Information type ID

Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: "0" - Domestic Sorted & Unsorted "A" - Online Postage "B" - Franking "C" - Consolidation

Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: "0" - Domestic Sorted & Unsorted "A" - Online Postage "B" - Franking "C" - Consolidation

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### ItemID {#itemid}

**Access:** Read/Write

**Returns:** int item within the Supply Chain ID

Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### RTSFlag {#rtsflag}

**Access:** Read/Write

**Returns:** string RTS Flag

Flag which indicates what level of Return to Sender service is being requested.

Flag which indicates what level of Return to Sender service is being requested.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### ReturnToSenderPostCode {#returntosenderpostcode}

**Access:** Read/Write

**Returns:** string Return to Sender Post Code but no DPS

Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### SupplyChainID {#supplychainid}

**Access:** Read/Write

**Returns:** int Supply chain ID

Identifies the unique group of customers involved in the mailing. Max value: 9999999.

Identifies the unique group of customers involved in the mailing. Max value: 9999999.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### UPUCountryID {#upucountryid}

**Access:** Read/Write

**Returns:** string Country ID

Identifies the UPU Country ID.Max length: 4 characters.

Identifies the UPU Country ID.Max length: 4 characters.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

### VersionID {#versionid}

**Access:** Read/Write

**Returns:** string Version ID

Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently "1". "0" & "2" to "9" and "A" to "Z" spare reserved for potential future use.

Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently "1". "0" & "2" to "9" and "A" to "Z" spare reserved for potential future use.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `string` |  |

