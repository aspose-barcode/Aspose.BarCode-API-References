---
title: EnableChecksum
second_title: Aspose.BarCode for .NET API 参考
description: 在生成一维条码期间启用校验和
type: docs
weight: 710
url: /zh/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

在生成一维条码期间启用校验和。

对于必须包含校验和的符号，默认被视为是，在仅可能校验和的情况下被视为否。

从未使用过校验和：Codabar

可以使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN

始终使用校验和：其余符号

```csharp
public enum EnableChecksum
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Default | `0` | 如果规范要求校验和 - 它将被附加。 |
| Yes | `1` | 如果可能，请始终使用校验和。 |
| No | `2` | 不要使用校验和。 |

### 也可以看看

* 命名空间 [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
