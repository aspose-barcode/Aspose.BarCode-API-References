---
title: "BarCodeConfidence Enum"
linktitle: "BarCodeConfidence"
articleTitle: "BarCodeConfidence"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Contains recognition confidence level."
type: docs
weight: 1500
url: /nodejs/barcodeconfidence/
---
## BarCodeConfidence enumeration

Contains recognition confidence level

```javascript
public enum BarCodeConfidence
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| NONE | `0` | Recognition confidence of barcode where codetext was not recognized correctly or barcode was detected as posible fake |
| MODERATE | `80` | Recognition confidence of barcode (mostly 1D barcodes) with weak checksumm or even without it. Could contains some misrecognitions in codetext or even fake recognitions if  is low |
| STRONG | `100` | Recognition confidence which was confirmed with BCH codes like Reed–Solomon. There must not be errors in read codetext or fake recognitions |

## Examples

```javascript
//This sample shows how BarCodeConfidence changed, depending on barcode type
//Moderate confidence
let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
console.log("BarCode Confidence: " + result.getConfidence());
console.log("BarCode ReadingQuality: " + result.getReadingQuality());
}
```

```javascript
//Strong confidence
let generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.QR]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
console.log("BarCode Confidence: " + result.getConfidence());
console.log("BarCode ReadingQuality: " + result.getReadingQuality());
}
```

### See Also

* assembly [Aspose.BarCode](../)

