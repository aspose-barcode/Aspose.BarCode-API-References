---
title: "BarcodeSettings.getStripFNC"
linktitle: "getStripFNC"
articleTitle: "getStripFNC"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false."
type: docs
weight: 60
url: /nodejs/barcodesettings/getstripfnc/
---
## getStripFNC() {#getstripfnc}

Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

```javascript
getStripFNC()
```

### Return Value

Strip

FNC1, FNC2, FNC3 characters from codetext. Default value is false.

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);
//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log ("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);
//StripFNC enabled
reader.getBarcodeSettings().setStripFNC(true);
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

