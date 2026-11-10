---
title: "क्लास ProcessorSettings"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Common.ProcessorSettings क्लास। ProcessorSettings मल्टीथ्रेडेड प्रदर्शन वृद्धि के साथ बारकोड को पहचानने की अनुमति देता है।"
type: docs
weight: 470
url: /hi/net/aspose.barcode.common/processorsettings/
---
## ProcessorSettings class

ProcessorSettings प्रदर्शन में मल्टी-थ्रेडेड वृद्धि के साथ बारकोड पहचान की अनुमति देते हैं।

```csharp
public class ProcessorSettings
```

## गुण

| नाम | विवरण |
| --- | --- |
| [MaxAdditionalAllowedThreads](../../aspose.barcode.common/processorsettings/maxadditionalallowedthreads/) { get; set; } | कोड को समानांतर चलाने के लिए अतिरिक्त थ्रेड्स की अधिकतम संख्या निर्दिष्ट करें |
| [UseAllCores](../../aspose.barcode.common/processorsettings/useallcores/) { get; set; } | सभी कोर का उपयोग करने के लिए आवश्यक है। |
| [UseOnlyThisCoresCount](../../aspose.barcode.common/processorsettings/useonlythiscorescount/) { get; set; } | उपयोग किए जाने वाले कोर की संख्या निर्दिष्ट करें। आपको प्रॉपर्टी "UseAllCores" को "false" में बदलना होगा। |

## उदाहरण

यह उदाहरण दिखाता है कि अधिकतम मल्टी-थ्रेडेड प्रदर्शन जोड़ने के लिए ProcessorSettings का उपयोग कैसे करें

```csharp
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

### और देखें

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


