---
title: BarCodeReader.ProcessorSettings
second_title: Aspose.BarCode for .NET API Reference
description: BarCodeReader property. Gets a settings of using processor cores
type: docs
weight: 140
url: /net/aspose.barcode.barcoderecognition/barcodereader/processorsettings/
---
## BarCodeReader.ProcessorSettings property

Gets a settings of using processor cores.

```csharp
public static ProcessorSettings ProcessorSettings { get; }
```

## Examples

This sample shows how to use ProcessorSettings to add maximum multi-threaded performnce

```csharp
[C#]
//this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = true;
//this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### See Also

* class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* class [BarCodeReader](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


