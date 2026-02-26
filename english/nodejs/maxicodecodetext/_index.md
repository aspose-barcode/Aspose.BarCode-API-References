---
title: MaxiCodeCodetext Class
linktitle: MaxiCodeCodetext
articleTitle: MaxiCodeCodetext
second_title: Aspose.BarCode for Node.js via Java
description: "Base class for encoding and decoding the text embedded in the MaxiCode code."
type: docs
weight: 130
url: /nodejs/maxicodecodetext/
---
## MaxiCodeCodetext class

Base class for encoding and decoding the text embedded in the MaxiCode code.

```javascript
public class MaxiCodeCodetext : IComplexCodetext
```

## Methods

| Name | Description |
| --- | --- |
| [getBarcodeType](./getbarcodetype/) | Gets barcode type. |
| [getECIEncoding](./geteciencoding/) | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. |
| [getEncodeMode](./getencodemode/) | Gets a MaxiCode encode mode. Default value: Auto. |
| [getMaxiCodeEncodeMode](./getmaxicodeencodemode/) | Gets a MaxiCode encode mode. |
| [getMode](./getmode/) | Gets MaxiCode mode. |
| [setECIEncoding](./seteciencoding/)(*object*) | Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. |
| [setEncodeMode](./setencodemode/)(*object*) | Sets a MaxiCode encode mode. Default value: Auto. |
| [setMaxiCodeEncodeMode](./setmaxicodeencodemode/)(*object*) | Sets a MaxiCode encode mode. |

## Examples

```javascript
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

### See Also

* assembly [Aspose.BarCode](../)

