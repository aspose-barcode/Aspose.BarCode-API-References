---
title: UseOnlyThisCoresCount
second_title: Справочник по API Aspose.BarCode для .NET
description: Укажите количество используемых ядер. Вам нужно изменить свойство UseAllCores на false.
type: docs
weight: 30
url: /ru/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

Укажите количество используемых ядер. Вам нужно изменить свойство «UseAllCores» на «false».

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

### Примеры

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### Смотрите также

* class [ProcessorSettings](../../processorsettings)
* пространство имен [Aspose.BarCode.Common](../../processorsettings)
* сборка [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->