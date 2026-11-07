---
title: "विधि"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. C++ में प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है।"
type: docs
weight: 100
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


प्रोसेसर कोर के उपयोग की सेटिंग प्राप्त करता है।

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## टिप्पणियाँ


यह उदाहरण दिखाता है कि ProcessorSettings का उपयोग करके अधिकतम मल्टी-थ्रेडेड प्रदर्शन कैसे जोड़ें
```cpp
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

## और देखें

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
