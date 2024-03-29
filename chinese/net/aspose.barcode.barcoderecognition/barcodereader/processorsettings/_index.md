---
title: ProcessorSettings
second_title: Aspose.BarCode for .NET API 参考
description: 获取使用处理器内核的设置
type: docs
weight: 130
url: /zh/net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

获取使用处理器内核的设置。

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

### 例子

这个示例展示了如何使用 ProcessorSettings 添加最大多线程性能

```csharp
[C#]
//这允许将所有内核用于单个 BarCodeReader 调用
BarCodeReader.ProcessorSettings.UseAllCores = true;
//这允许使用当前的核心数
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'这允许将所有内核用于单个 BarCodeReader 调用
BarCodeReader.ProcessorSettings.UseAllCores = True
'这允许使用当前的核心数
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### 也可以看看

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings)
* class [BarCodeReader](../../barcodereader)
* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../barcodereader)
* 部件 [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
