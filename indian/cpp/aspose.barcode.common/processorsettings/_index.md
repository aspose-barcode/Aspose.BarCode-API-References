---
title: "Aspose::BarCode::Common::ProcessorSettings class"
linktitle: "ProcessorSettings"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::Common::ProcessorSettings class. ProcessorSettings C++ में प्रदर्शन को बहु-थ्रेडेड तरीके से बढ़ाकर बारकोड को पहचानने की अनुमति देता है।"
type: docs
weight: 500
url: /hi/cpp/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class


[ProcessorSettings](./) allow to recognize barcodes with multi-threaded increasing of performance

```cpp
class ProcessorSettings : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_MaxAdditionalAllowedThreads](./get_maxadditionalallowedthreads/)() const | कोड को समानांतर चलाने के लिए अतिरिक्त थ्रेड्स की अधिकतम संख्या निर्दिष्ट करें |
| [get_UseAllCores](./get_useallcores/)() const | सभी कोर का उपयोग करने के लिए आवश्यक है। |
| [get_UseOnlyThisCoresCount](./get_useonlythiscorescount/)() const | उपयोग करने वाले कोर की संख्या निर्दिष्ट करें। आपको प्रॉपर्टी "UseAllCores" को "false" में बदलना होगा। |
| [set_MaxAdditionalAllowedThreads](./set_maxadditionalallowedthreads/)(int32_t) | कोड को समानांतर चलाने के लिए अतिरिक्त थ्रेड्स की अधिकतम संख्या निर्दिष्ट करें |
| [set_UseAllCores](./set_useallcores/)(bool) | सभी कोर का उपयोग करने के लिए आवश्यक है। |
| [set_UseOnlyThisCoresCount](./set_useonlythiscorescount/)(int32_t) | उपयोग करने वाले कोर की संख्या निर्दिष्ट करें। आपको प्रॉपर्टी "UseAllCores" को "false" में बदलना होगा। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि अधिकतम बहु-थ्रेडेड प्रदर्शन जोड़ने के लिए [ProcessorSettings](./) का उपयोग कैसे करें
```cpp
[C#]
int workerThreads = Environment.ProcessorCount * 2;
int portThreads = Environment.ProcessorCount * 2;
System.Threading.ThreadPool.GetMinThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads);
System.Threading.ThreadPool.GetMaxThreads(out workerThreads, out portThreads);
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads);
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2;

//यह एकल BarCodeReader कॉल के लिए सभी कोर का उपयोग करने की अनुमति देता है
BarCodeReader.ProcessorSettings.UseAllCores = true;
//यह वर्तमान कोर की संख्या का उपयोग करने की अनुमति देता है
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
Dim workerThreads As Integer = Environment.ProcessorCount * 2
Dim portThreads As Integer = Environment.ProcessorCount * 2
System.Threading.ThreadPool.GetMinThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMinThreads(Math.Max(workerThreads, Environment.ProcessorCount* 2), portThreads)
System.Threading.ThreadPool.GetMaxThreads(workerThreads, portThreads)
System.Threading.ThreadPool.SetMaxThreads(Math.Max(workerThreads, Environment.ProcessorCount* 4), portThreads)
BarCodeReader.ProcessorSettings.MaxAdditionalAllowedThreads = Environment.ProcessorCount* 2

'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## और देखें

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
