---
title: Mailmark2DCodetext Class
linktitle: Mailmark2DCodetext
articleTitle: Mailmark2DCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code."
type: docs
weight: 120
url: /nodejs/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.

```javascript
public class Mailmark2DCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [Mailmark2DCodetext](./mailmark2dcodetext/#constructor) | Create default instance of Mailmark2DCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [getBarcodeType](./getbarcodetype/) | Gets barcode type. |
| [getClass_](./getclass_/) | Identifies the class of the item. |
| [getConstructedCodetext](./getconstructedcodetext/) | Construct codetext from Mailmark data. |
| [getCustomerContent](./getcustomercontent/) | Optional space for use by customer. |
| [getCustomerContentEncodeMode](./getcustomercontentencodemode/) | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [getDataMatrixType](./getdatamatrixtype/) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS](./getdestinationpostcodeanddps/) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [getInformationTypeID](./getinformationtypeid/) | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values:. |
| [getItemID](./getitemid/) | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [getRTSFlag](./getrtsflag/) | Flag which indicates what level of Return to Sender service is being requested. |
| [getReturnToSenderPostCode](./getreturntosenderpostcode/) | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [getSupplyChainID](./getsupplychainid/) | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [getUPUCountryID](./getupucountryid/) | Identifies the UPU Country ID.Max length: 4 characters. |
| [getVersionID](./getversionid/) | Identifies the barcode version as relevant to each Information Type ID. Valid Values:. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes Mailmark data from constructed codetext. |
| [setClass_](./setclass_/)(*object*) | Identifies the class of the item. |
| [setCustomerContent](./setcustomercontent/)(*object*) | Optional space for use by customer. |
| [setCustomerContentEncodeMode](./setcustomercontentencodemode/)(*object*) | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [setDataMatrixType](./setdatamatrixtype/)(*object*) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS](./setdestinationpostcodeanddps/)(*object*) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [setInformationTypeID](./setinformationtypeid/)(*object*) | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values:. |
| [setItemID](./setitemid/)(*object*) | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [setRTSFlag](./setrtsflag/)(*object*) | Flag which indicates what level of Return to Sender service is being requested. |
| [setReturnToSenderPostCode](./setreturntosenderpostcode/)(*object*) | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [setSupplyChainID](./setsupplychainid/)(*object*) | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [setUPUCountryID](./setupucountryid/)(*object*) | Identifies the UPU Country ID.Max length: 4 characters. |
| [setVersionID](./setversionid/)(*object*) | Identifies the barcode version as relevant to each Information Type ID. Valid Values:. |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |

### See Also

* assembly [Aspose.BarCode](../)

