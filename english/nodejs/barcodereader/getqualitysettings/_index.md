---
title: BarCodeReader.getQualitySettings
linktitle: getQualitySettings
articleTitle: getQualitySettings
second_title: Aspose.BarCode for Node.js via Java
description: "QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality."
type: docs
weight: 160
url: /nodejs/barcodereader/getqualitysettings/
---
## getQualitySettings() {#getqualitysettings}

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

```javascript
getQualitySettings()
```

### Return Value

[QualitySettings](../../..//qualitysettings/)

to configure recognition quality and speed.

## Examples

```javascript
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

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//normal quality mode is set by default
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
//set separate options
reader.getQualitySettings().setAllowMedianSmoothing(true);
reader.getQualitySettings().setMedianSmoothingWindowSize(5);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* assembly [Aspose.BarCode](../../)

