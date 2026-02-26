---
title: MaxiCodeStandardCodetext Class
linktitle: MaxiCodeStandardCodetext
articleTitle: MaxiCodeStandardCodetext
second_title: Aspose.BarCode for Node.js via Java
description: Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.
type: docs
weight: 150
url: /nodejs/maxicodestandardcodetext/
---
## MaxiCodeStandardCodetext class

Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.

```javascript
public class MaxiCodeStandardCodetext : MaxiCodeCodetext
```

## Constructors

| Name | Description |
| --- | --- |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/#constructor) | Initializes a new instance of the MaxiCodeStandardCodetext class. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified [`MaxiCodeStandardCodetext`](..//maxicodestandardcodetext/) value. |
| [getBarcodeType](../maxicodecodetext/getbarcodetype/) | Gets barcode type. *(Inherited from MaxiCodeCodetext)* |
| [getConstructedCodetext](./getconstructedcodetext/) | Constructs codetext. |
| [getECIEncoding](../maxicodecodetext/geteciencoding/) | Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [getEncodeMode](../maxicodecodetext/getencodemode/) | Gets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [getHashCode](./gethashcode/) | Returns the hash code for this instance. |
| [getMaxiCodeEncodeMode](../maxicodecodetext/getmaxicodeencodemode/) | Gets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [getMessage](./getmessage/) | Gets message. |
| [getMode](./getmode/) | Gets MaxiCode mode. |
| [init](./init/) |  |
| [initFromString](./initfromstring/)(*object*) | Initializes instance from constructed codetext. |
| [setECIEncoding](../maxicodecodetext/seteciencoding/)(*object*) | Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. *(Inherited from MaxiCodeCodetext)* |
| [setEncodeMode](../maxicodecodetext/setencodemode/)(*object*) | Sets a MaxiCode encode mode. Default value: Auto. *(Inherited from MaxiCodeCodetext)* |
| [setMaxiCodeEncodeMode](../maxicodecodetext/setmaxicodeencodemode/)(*object*) | Sets a MaxiCode encode mode. *(Inherited from MaxiCodeCodetext)* |
| [setMessage](./setmessage/)(*object*) | Sets message. |
| [setMode](./setmode/)(*object*) | Sets MaxiCode mode. Standart codetext can be used only with modes 4, 5 and 6. |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

## Examples

```javascript
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 5
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 6
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

