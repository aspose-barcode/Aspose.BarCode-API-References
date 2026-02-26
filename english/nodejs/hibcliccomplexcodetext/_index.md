---
title: HIBCLICComplexCodetext Class
linktitle: HIBCLICComplexCodetext
articleTitle: HIBCLICComplexCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Base class for encoding and decoding the text embedded in the HIBC LIC code."
type: docs
weight: 220
url: /nodejs/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Base class for encoding and decoding the text embedded in the HIBC LIC code.

```javascript
public class HIBCLICComplexCodetext : IComplexCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/#constructor)(*object*) | Initializes a new instance of the HIBCLICComplexCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType](./getbarcodetype/) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setBarcodeType](./setbarcodetype/)(*object*) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC and HIBCQRLIC encode types. Default value: HIBCCode39LIC. |

## Examples

```javascript
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

### See Also

* assembly [Aspose.BarCode](../)

