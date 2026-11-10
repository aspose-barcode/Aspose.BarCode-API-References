---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "ProcessorSettings 属性。指定要使用的核心数。您需要将属性 UseAllCores 设置为 false"
type: docs
weight: 30
url: /zh/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

指定要使用的核心数。您需要将属性 "UseAllCores" 更改为 "false"。

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## 示例

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### 另见

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)


