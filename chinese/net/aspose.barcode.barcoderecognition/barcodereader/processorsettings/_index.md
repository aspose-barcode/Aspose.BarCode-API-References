---
title: "BarCodeReader.ProcessorSettings"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarCodeReader 属性。获取使用处理器核心的设置"
type: docs
weight: 140
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

获取使用处理器核心的设置。

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## 示例

此示例展示了如何使用 ProcessorSettings 来提升最大多线程性能

```csharp
[C#]
//这允许在单次 BarCodeReader 调用中使用所有核心
BarCodeReader.ProcessorSettings.UseAllCores = true;
//这允许使用当前的核心数
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### 另见

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


