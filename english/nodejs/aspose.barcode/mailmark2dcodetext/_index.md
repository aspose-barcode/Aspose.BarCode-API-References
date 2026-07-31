---
title: "Mailmark2DCodetext Class"
linktitle: "Mailmark2DCodetext"
articleTitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code."
type: docs
weight: 570
url: /nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.

```js
new Mailmark2DCodetext()
```

Create default instance of Mailmark2DCodetext class.

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType()](./getbarcodetype/) | Gets barcode type. |
| [getClass_()](./getclass-/) | Identifies the class of the item. Valid Values: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [getConstructedCodetext()](./getconstructedcodetext/) | Construct codetext from Mailmark data. |
| [getCustomerContent()](./getcustomercontent/) | Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 character |
| [getCustomerContentEncodeMode()](./getcustomercontentencodemode/) | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](./getdatamatrixtype/) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](./getdestinationpostcodeanddps/) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of charac |
| [getInformationTypeID()](./getinformationtypeid/) | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: '0' - Domestic Sorted & Unsorted |
| [getItemID()](./getitemid/) | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be un |
| [getReturnToSenderPostCode()](./getreturntosenderpostcode/) | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [getRTSFlag()](./getrtsflag/) | Flag which indicates what level of Return to Sender service is being requested. |
| [getSupplyChainID()](./getsupplychainid/) | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [getUPUCountryID()](./getupucountryid/) | Identifies the UPU Country ID.Max length: 4 characters. |
| [getVersionID()](./getversionid/) | Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently '1'. '0' & '2' to '9' an |
| [initFromString(constructedCodetext)](./initfromstring/) | Initializes Mailmark data from constructed codetext. |
| [setClass_(value)](./setclass-/) | Identifies the class of the item. Valid Values: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [setCustomerContent(value)](./setcustomercontent/) | Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 character |
| [setCustomerContentEncodeMode(value)](./setcustomercontentencodemode/) | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](./setdatamatrixtype/) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(value)](./setdestinationpostcodeanddps/) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of charac |
| [setInformationTypeID(value)](./setinformationtypeid/) | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](./setitemid/) | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be un |
| [setReturnToSenderPostCode(value)](./setreturntosenderpostcode/) | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [setRTSFlag()](./setrtsflag/) | Flag which indicates what level of Return to Sender service is being requested. |
| [setSupplyChainID(value)](./setsupplychainid/) | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [setUPUCountryID(value)](./setupucountryid/) | Identifies the UPU Country ID.Max length: 4 characters. |
| [setVersionID(value)](./setversionid/) | Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently '1'. '0' & '2' to '9' an |
