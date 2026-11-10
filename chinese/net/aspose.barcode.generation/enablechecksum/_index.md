---
title: "枚举 EnableChecksum"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Generation.EnableChecksum 枚举。在生成 1D 条形码时启用校验和"
type: docs
weight: 1280
url: /zh/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

在生成 1D 条码时启用校验和。

默认情况下，对于必须包含校验和的符号视为 Yes，对于仅可能包含校验和的符号视为 No。

从不使用校验和：Codabar

校验和是可能的：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

校验和始终使用：其余符号

```csharp
public enum EnableChecksum
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 如果规范要求校验和——它将被附加。 |
| Yes | `1` | 如果可能，始终使用校验和。 |
| No | `2` | 不要使用校验和。 |

### 另见

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


