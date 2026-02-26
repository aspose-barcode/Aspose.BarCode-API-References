---
title: MaxiCodeMode Enum
linktitle: MaxiCodeMode
articleTitle: MaxiCodeMode
second_title: Aspose.BarCode for Node.js via Java
description: Encoding mode for MaxiCode barcodes.
type: docs
weight: 1140
url: /nodejs/maxicodemode/
---
## MaxiCodeMode enumeration

Encoding mode for MaxiCode barcodes.

```javascript
public enum MaxiCodeMode
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| MODE_2 | `2` | Mode 2 encodes postal information in first message and data in second message. Has 9 digits postal code (used only in USA). |
| MODE_3 | `3` | Mode 3 encodes postal information in first message and data in second message. Has 6 alphanumeric postal code, used in the world. |
| MODE_4 | `4` | Mode 4 encodes data in first and second message, with short ECC correction. |
| MODE_5 | `5` | Mode 5 encodes data in first and second message, with long ECC correction. |
| MODE_6 | `6` | Mode 6 encodes data in first and second message, with short ECC correction. Used to encode device. |

## Examples

This sample shows how to genereate MaxiCode barcodes using ComplexBarcodeGenerator

```javascript
//Mode 2 with standart second message
let maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.setPostalCode("524032140");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.setMessage("Test message");
maxiCodeCodetext.setSecondMessage(maxiCodeStandartSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 2 with structured second message
let maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.setPostalCode("524032140");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.add("PITTSBURGH");
maxiCodeStructuredSecondMessage.add("PA");
maxiCodeStructuredSecondMessage.setYear(99);
maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 3 with standart second message
let maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.setPostalCode("B1050");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let maxiCodeStandartSecondMessage = new MaxiCodeStandartSecondMessage();
maxiCodeStandartSecondMessage.setMessage("Test message");
maxiCodeCodetext.setSecondMessage(maxiCodeStandartSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext);
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 3 with structured second message
let maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.setPostalCode("B1050");
maxiCodeCodetext.setCountryCode(056);
maxiCodeCodetext.setServiceCategory(999);
let maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.add("PITTSBURGH");
maxiCodeStructuredSecondMessage.add("PA");
maxiCodeStructuredSecondMessage.setYear(99);
maxiCodeCodetext.setSecondMessage(maxiCodeStructuredSecondMessage);
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext();
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext();
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 5
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext())
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

```javascript
//Mode 6
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext();
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

