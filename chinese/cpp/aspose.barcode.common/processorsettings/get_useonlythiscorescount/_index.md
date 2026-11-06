---
title: "method"
linktitle: "get_UseOnlyThisCoresCount"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。指定要使用的核心数量。您需要在 C++ 中将属性 \"UseAllCores\" 更改为 \"false\"。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode.common/processorsettings/get_useonlythiscorescount/
---
## ProcessorSettings::get_UseOnlyThisCoresCount method


指定要使用的核心数。您需要将属性 "UseAllCores" 更改为 "false"。

```cpp
int32_t Aspose::BarCode::Common::ProcessorSettings::get_UseOnlyThisCoresCount() const
```

## 备注



```cpp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## 另见

* Class [ProcessorSettings](../)
* Namespace [Aspose::BarCode::Common](../../)
* Library [Aspose.BarCode for C++](../../../)
