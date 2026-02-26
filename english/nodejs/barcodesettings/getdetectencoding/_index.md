---
title: "BarcodeSettings.getDetectEncoding"
linktitle: "getDetectEncoding"
articleTitle: "getDetectEncoding"
second_title: "Aspose.BarCode for Node.js via Java"
description: "The flag which force engine to detect codetext encoding for Unicode codesets. Default value is true."
type: docs
weight: 80
url: /nodejs/barcodesettings/getdetectencoding/
---
## getDetectEncoding() {#getdetectencoding}

The flag which force engine to detect codetext encoding for Unicode codesets. Default value is true.

```javascript
getDetectEncoding()
```

### Return Value

The

flag which force engine to detect codetext encoding for Unicode codesets

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);
//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log ("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
//detect encoding is disabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* class [BarcodeSettings](../)
* assembly [Aspose.BarCode](../../)

