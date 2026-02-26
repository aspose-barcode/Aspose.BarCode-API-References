---
title: HIBCLICCombinedCodetext Class
linktitle: HIBCLICCombinedCodetext
articleTitle: HIBCLICCombinedCodetext
second_title: Aspose.BarCode for Node.js via Java
description: Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary and secodary data.
type: docs
weight: 230
url: /nodejs/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

Class for encoding and decoding the text embedded in the HIBC LIC code which stores primary and secodary data.

```javascript
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/#constructor) | Initializes a new instance of the HIBCLICCombinedCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified HIBCLICCombinedCodetext value. |
| [getBarcodeType](../hibcliccomplexcodetext/getbarcodetype/) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. *(Inherited from HIBCLICComplexCodetext)* |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [getPrimaryData](./getprimarydata/) | Identifies primary data. |
| [getSecondaryAndAdditionalData](./getsecondaryandadditionaldata/) | Identifies secondary and additional supplemental data. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setBarcodeType](../hibcliccomplexcodetext/setbarcodetype/)(*object*) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. *(Inherited from HIBCLICComplexCodetext)* |
| [setPrimaryData](./setprimarydata/)(*object*) | Identifies primary data. |
| [setSecondaryAndAdditionalData](./setsecondaryandadditionaldata/)(*object*) | Identifies secondary and additional supplemental data. |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |
| [auto_PrimaryData](./auto_primarydata/) |  |
| [auto_SecondaryAndAdditionalData](./auto_secondaryandadditionaldata/) |  |

## Examples

```javascript
let combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.setBarcodeType(EncodeTypes.HIBCQRLIC);
combinedCodetext.setPrimaryData(new PrimaryData());
combinedCodetext.getPrimaryData().setProductOrCatalogNumber("12345");
combinedCodetext.getPrimaryData().setLabelerIdentificationCode("A999");
combinedCodetext.getPrimaryData().setUnitOfMeasureID(1);
combinedCodetext.setSecondaryAndAdditionalData(new SecondaryAndAdditionalData());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDate(new Date());
combinedCodetext.getSecondaryAndAdditionalData().setExpiryDateFormat(HIBCLICDateFormat.MMDDYY);
combinedCodetext.getSecondaryAndAdditionalData().setQuantity(30);
combinedCodetext.getSecondaryAndAdditionalData().setLotNumber("LOT123");
combinedCodetext.getSecondaryAndAdditionalData().setSerialNumber("SERIAL123");
combinedCodetext.getSecondaryAndAdditionalData().setDateOfManufacture(new Date());
ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext);
let image = generator.generateBarCodeImage(BarCodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.HIBCQRLIC);
reader.readBarCodes();
let codetext = reader.getFoundBarCodes()[0].getCodeText();
let result = ComplexCodetextReader.tryDecodeHIBCLIC(codetext) ;
print("Product or catalog number: " + result.getPrimaryData().getProductOrCatalogNumber());
print("Labeler identification code: " + result.getPrimaryData().getLabelerIdentificationCode());
print("Unit of measure ID: " + result.getPrimaryData().getUnitOfMeasureID());
print("Expiry date: " + result.getSecondaryAndAdditionalData().getExpiryDate());
print("Quantity: " + result.getSecondaryAndAdditionalData().getQuantity());
print("Lot number: " + result.getSecondaryAndAdditionalData().getLotNumber());
print("Serial number: " + result.getSecondaryAndAdditionalData().getSerialNumber());
print("Date of manufacture: " + result.getSecondaryAndAdditionalData().getDateOfManufacture());
```

### See Also

* assembly [Aspose.BarCode](../)

