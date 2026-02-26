---
title: HIBCLICPrimaryDataCodetext Class
linktitle: HIBCLICPrimaryDataCodetext
articleTitle: HIBCLICPrimaryDataCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary data."
type: docs
weight: 240
url: /nodejs/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary data.

```javascript
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/#constructor) | Initializes a new instance of the HIBCLICPrimaryDataCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified HIBCLICPrimaryDataCodetext value. |
| [getBarcodeType](../hibcliccomplexcodetext/getbarcodetype/) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. *(Inherited from HIBCLICComplexCodetext)* |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [getData](./getdata/) | Identifies primary data. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setBarcodeType](../hibcliccomplexcodetext/setbarcodetype/)(*object*) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. *(Inherited from HIBCLICComplexCodetext)* |
| [setData](./setdata/)(*object*) | Identifies primary data. |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |
| [data](./data/) |  |

## Examples

```javascript
let complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
complexCodetext.setData(new PrimaryData());
complexCodetext.getData().setProductOrCatalogNumber("12345");
complexCodetext.getData().setLabelerIdentificationCode("A999");
complexCodetext.getData().setUnitOfMeasureID(1);
let generator = new ComplexBarcodeGenerator(complexCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getData().getUnitOfMeasureID());
```

### See Also

* assembly [Aspose.BarCode](../)

