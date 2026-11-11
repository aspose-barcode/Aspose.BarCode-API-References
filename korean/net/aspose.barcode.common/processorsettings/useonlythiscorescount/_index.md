---
title: "ProcessorSettings.UseOnlyThisCoresCount"
second_title: "Aspose.BarCode for .NET API 참조"
description: "ProcessorSettings 속성. 사용할 코어 수를 지정합니다. 속성 UseAllCores를 false로 변경해야 합니다."
type: docs
weight: 30
url: /ko/net/aspose.barcode.common/processorsettings/useonlythiscorescount/
---
## ProcessorSettings.UseOnlyThisCoresCount property

사용할 코어 수를 지정합니다. 속성 "UseAllCores"를 "false"로 변경해야 합니다.

```csharp
public int UseOnlyThisCoresCount { get; set; }
```

## 예제

```csharp
[C#]
BarCodeReader.ProcessorSettings.UseAllCores = false;
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2);
[VB.NET]
BarCodeReader.ProcessorSettings.UseAllCores = False
BarCodeReader.ProcessorSettings.UseOnlyThisCoresCount = Math.Max(1, Environment.ProcessorCount / 2)
```

### 또 보기

* class [ProcessorSettings](../)
* namespace [Aspose.BarCode.Common](../../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../../)


