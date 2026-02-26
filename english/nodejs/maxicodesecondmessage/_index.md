---
title: "MaxiCodeSecondMessage Class"
linktitle: "MaxiCodeSecondMessage"
articleTitle: "MaxiCodeSecondMessage"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6."
type: docs
weight: 140
url: /nodejs/maxicodesecondmessage/
---
## MaxiCodeSecondMessage class

Class for encoding and decoding MaxiCode codetext for modes 4, 5 and 6.

```javascript
public class MaxiCodeSecondMessage : joint.BaseJavaClass
```

## Methods

| Name | Description |
| --- | --- |
| [getMessage](./getmessage/) |  |

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

