---
title: MaxiCodeStructuredCodetext Class
linktitle: MaxiCodeStructuredCodetext
articleTitle: MaxiCodeStructuredCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3."
type: docs
weight: 180
url: /nodejs/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

Base class for encoding and decoding the text embedded in the MaxiCode code for modes 2 and 3.

```javascript
public class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/#constructor)(*object*) | Initializes a new instance of the MaxiCodeStructuredCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified [`MaxiCodeStructuredCodetext`](..//maxicodestructuredcodetext/) value. |
| [getBarcodeType](../maxicodecodetext/getbarcodetype/) | Gets barcode type. *(Inherited from MaxiCodeCodetext)* |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [getCountryCode](./getcountrycode/) | Identifies 3 digit country code. |
| [getECIEncoding](../maxicodecodetext/geteciencoding/) | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [getEncodeMode](../maxicodecodetext/getencodemode/) | Gets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [getHashCode](./gethashcode/) | Returns the hash code for this instance. |
| [getMaxiCodeEncodeMode](../maxicodecodetext/getmaxicodeencodemode/) | Gets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [getMode](../maxicodecodetext/getmode/) | Gets MaxiCode mode. *(Inherited from MaxiCodeCodetext)* |
| [getPostalCode](./getpostalcode/) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [getSecondMessage](./getsecondmessage/) | Identifies second message of the barcode. |
| [getServiceCategory](./getservicecategory/) | Identifies 3 digit service category. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setCountryCode](./setcountrycode/)(*object*) | Identifies 3 digit country code. |
| [setECIEncoding](../maxicodecodetext/seteciencoding/)(*object*) | Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [setEncodeMode](../maxicodecodetext/setencodemode/)(*object*) | Sets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [setMaxiCodeEncodeMode](../maxicodecodetext/setmaxicodeencodemode/)(*object*) | Sets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [setPostalCode](./setpostalcode/)(*object*) | Identifies the postal code. Must be 9 digits in mode 2 or 6 alphanumeric symbols in mode 3. |
| [setSecondMessage](./setsecondmessage/)(*object*) | Identifies second message of the barcode. |
| [setServiceCategory](./setservicecategory/)(*object*) | Identifies 3 digit service category. |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |
| [maxiCodeSecondMessage](./maxicodesecondmessage/) |  |

## Examples

This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

```javascript
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

### See Also

* assembly [Aspose.BarCode](../)

