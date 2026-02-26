---
title: MailmarkCodetext Class
linktitle: MailmarkCodetext
articleTitle: MailmarkCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code."
type: docs
weight: 110
url: /nodejs/mailmarkcodetext/
---
## MailmarkCodetext class

Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code.

```javascript
public class MailmarkCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MailmarkCodetext](./mailmarkcodetext/#constructor)(*object*) | Initializes a new instance of the MailmarkCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType](./getbarcodetype/) | Gets barcode type. |
| [getClass_](./getclass_/) | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" -... |
| [getConstructedCodetext](./getconstructedcodetext/) | Construct codetext from Mailmark data. |
| [getDestinationPostCodePlusDPS](./getdestinationpostcodeplusdps/) | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [getFormat](./getformat/) | "0" – Null or Test "1" – Letter "2" – Large Letter. |
| [getItemID](./getitemid/) | Maximum value is 99999999. |
| [getSupplychainID](./getsupplychainid/) | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [getVersionID](./getversionid/) | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use). |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes Mailmark data from constructed codetext. |
| [setClass_](./setclass_/)(*object*) | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" -... |
| [setDestinationPostCodePlusDPS](./setdestinationpostcodeplusdps/)(*object*) | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11 " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [setFormat](./setformat/)(*object*) | "0" – Null or Test "1" – LetterN "2" – Large Letter. |
| [setItemID](./setitemid/)(*object*) | Maximum value is 99999999. |
| [setSupplychainID](./setsupplychainid/)(*object*) | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [setVersionID](./setversionid/)(*object*) | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use). |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |

### See Also

* assembly [Aspose.BarCode](../)

