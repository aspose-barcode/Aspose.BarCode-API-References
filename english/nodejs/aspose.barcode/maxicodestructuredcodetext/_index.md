---
title: "MaxiCodeStructuredCodetext Class"
linktitle: "MaxiCodeStructuredCodetext"
articleTitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3."
type: docs
weight: 700
url: /nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Returns a value indicating whether this instance is equal to a specified value. |
| [getConstructedCodetext()](./getconstructedcodetext/) | Constructs codetext |
| [getCountryCode()](./getcountrycode/) | Identifies 3 digit country code. |
| [getHashCode()](./gethashcode/) | Returns the hash code for this instance. |
| [getPostalCode()](./getpostalcode/) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [getSecondMessage()](./getsecondmessage/) | Identifies second message of the barcode. |
| [getServiceCategory()](./getservicecategory/) | Identifies 3 digit service category. |
| [initFromString(constructedCodetext)](./initfromstring/) | Initializes instance from constructed codetext. |
| [setCountryCode()](./setcountrycode/) | Identifies 3 digit country code. |
| [setPostalCode()](./setpostalcode/) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [setSecondMessage()](./setsecondmessage/) | Identifies second message of the barcode. |
| [setServiceCategory()](./setservicecategory/) | Identifies 3 digit service category. |
