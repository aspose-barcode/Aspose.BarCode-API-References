---
title: HIBCPASCodetext Class
linktitle: HIBCPASCodetext
articleTitle: HIBCPASCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Class for encoding and decoding the text embedded in the HIBC PAS code."
type: docs
weight: 260
url: /nodejs/hibcpascodetext/
---
## HIBCPASCodetext class

Class for encoding and decoding the text embedded in the HIBC PAS code.

```javascript
public class HIBCPASCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [HIBCPASCodetext](./hibcpascodetext/#constructor) | Initializes a new instance of the HIBCPASCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [addHIBCPASRecord](./addhibcpasrecord/)(*object*) | Adds new record. |
| [addRecord](./addrecord/)(*object, object*) | Adds new record. |
| [clear](./clear/) | Clears records list. |
| [construct](./construct/)(*object*) | HIBCPASRecord constructor. |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified HIBCPASCodetext value. |
| [getBarcodeType](./getbarcodetype/) | Gets barcode type. |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [getDataLocation](./getdatalocation/) | Identifies data location. |
| [getRecords](./getrecords/) | Gets records list. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setBarcodeType](./setbarcodetype/)(*object*) | Gets or sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS. |
| [setDataLocation](./setdatalocation/)(*object*) | Identifies data location. |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

## Examples

This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

```javascript
let complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
let generator = new ComplexBarcodeGenerator(complexCodetext);
BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
print("Data location: " + readCodetext.getDataLocation());
print("Data type: " + readCodetext.getRecords()[0].getDataType());
print("Data: " + readCodetext.getRecords()[0].getData());
print("Data type: " + readCodetext.getRecords()[1].getDataType());
print("Data: " + readCodetext.getRecords()[1].getData());
```

### See Also

* assembly [Aspose.BarCode](../)

