---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarCodeReader प्रॉपर्टी। प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है"
type: docs
weight: 140
url: /hi/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

प्रोसेसर कोर उपयोग की सेटिंग प्राप्त करता है।

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## उदाहरण

यह उदाहरण दिखाता है कि अधिकतम मल्टी-थ्रेडेड प्रदर्शन जोड़ने के लिए ProcessorSettings का उपयोग कैसे करें

```csharp
[C#]
//यह एकल BarCodeReader कॉल के लिए सभी कोर का उपयोग करने की अनुमति देता है
BarCodeReader.ProcessorSettings.UseAllCores = true;
//यह वर्तमान कोर की संख्या का उपयोग करने की अनुमति देता है
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### और देखें

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


