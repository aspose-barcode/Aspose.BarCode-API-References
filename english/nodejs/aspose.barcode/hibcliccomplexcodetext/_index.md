---
title: "HIBCLICComplexCodetext Class"
linktitle: "HIBCLICComplexCodetext"
articleTitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Base class for encoding and decoding the text embedded in the HIBC LIC code. This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext ..."
type: docs
weight: 450
url: /nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Base class for encoding and decoding the text embedded in the HIBC LIC code. This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
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

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType()](./getbarcodetype/) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](./getconstructedcodetext/) | Constructs codetext |
| [initFromString(constructedCodetext)](./initfromstring/) | Initializes instance from constructed codetext. |
| [setBarcodeType()](./setbarcodetype/) | Gets or sets barcode type. HIBC LIC codetext can be encoded using HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
