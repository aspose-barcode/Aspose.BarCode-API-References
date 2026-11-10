---
title: "एनम XDimensionMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode एनम। पहचान मोड जो बारकोड के न्यूनतम तत्व मैट्रिक्स सेल या बार का आकार 1 से अनंत तक सेट करता है।"
type: docs
weight: 400
url: /hi/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

मान्यता मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) सेट करता है: मैट्रिक्स सेल या बार।

```csharp
public enum XDimensionMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | XDimension का मान AI (SVM) द्वारा पता लगाया जाता है। वर्तमान में यह सामान्य के समान है। |
| Small | `1` | BarcodeQuality से गुणवत्ता के साथ 1 पिक्सेल या अधिक में छोटे XDimension वाले बारकोड का पता लगाता है। |
| Normal | `2` | BarcodeQuality या उच्च गुणवत्ता वाले बारकोड से गुणवत्ता के साथ 2 पिक्सेल या अधिक में क्लासिक XDimension वाले बारकोड का पता लगाता है। |
| Large | `3` | उच्च-रिज़ॉल्यूशन कैमरों से कैप्चर किए गए BarcodeQuality की गुणवत्ता के साथ बड़े XDimension वाले बारकोड का पता लगाता है। |
| UseMinimalXDimension | `4` | BarcodeQuality की गुणवत्ता के साथ MinimalXDimension में सेट आकार से बारकोड का पता लगाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि XDimension मोड का उपयोग कैसे करें

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


