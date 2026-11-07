---
title: "method"
linktitle: "get_UseOnlyThisCoresCount"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Specifica il numero di core da utilizzare. È necessario modificare la proprietà \"UseAllCores\" in \"false\" in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode.common/processorsettings/get_useonlythiscorescount/
---
## ProcessorSettings::get_UseOnlyThisCoresCount method


Specifica il numero di core da utilizzare. È necessario modificare la proprietà "UseAllCores" in "false".

```cpp
int32_t Aspose::BarCode::Common::ProcessorSettings::get_UseOnlyThisCoresCount() const
```

## Osservazioni



```cpp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

## Vedi anche

* Class [ProcessorSettings](../)
* Namespace [Aspose::BarCode::Common](../../)
* Library [Aspose.BarCode for C++](../../../)
