---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "ProcessorSettings प्रॉपर्टी। उपयोग करने के लिए कोर की संख्या निर्दिष्ट करें। आपको प्रॉपर्टी UseAllCores को false पर बदलना होगा"
type: docs
weight: 30
url: /hi/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

उपयोग किए जाने वाले कोर की संख्या निर्दिष्ट करें। आपको प्रॉपर्टी "UseAllCores" को "false" में बदलना होगा।

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## उदाहरण

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### और देखें

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)


