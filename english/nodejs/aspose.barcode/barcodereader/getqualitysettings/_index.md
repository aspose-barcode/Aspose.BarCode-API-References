---
title: "BarCodeReader.getQualitySettings"
linktitle: "getQualitySettings"
articleTitle: "getQualitySettings"
second_title: "Aspose.BarCode for Node.js via Java"
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, Norm..."
type: docs
weight: 80
url: /nodejs/aspose.barcode/barcodereader/getqualitysettings/
---

## getQualitySettings()

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```
