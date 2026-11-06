---
title: "method"
linktitle: "get_ProcessorSettings"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。获取在 C++ 中使用处理器核心的设置。"
type: docs
weight: 100
url: /zh/cpp/aspose.barcode.barcoderecognition/barcodereader/get_processorsettings/
---
## BarCodeReader::get_ProcessorSettings method


获取使用处理器核心的设置。

```cpp
static System::SharedPtr<Aspose::BarCode::Common::ProcessorSettings> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_ProcessorSettings()
```

## 备注


此示例展示了如何使用 ProcessorSettings 来实现最大的多线程性能
```cpp
[C#]
//这允许在单次 BarCodeReader 调用中使用所有核心
BarCodeReader.ProcessorSettings.UseAllCores = true;
//这允许使用当前核心数
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
'this allows to use all cores for single BarCodeReader call
BarCodeReader.ProcessorSettings.UseAllCores = True
'this allows to use current count of cores
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## 另见

* Class [ProcessorSettings](../../../aspose.barcode.common/processorsettings/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
