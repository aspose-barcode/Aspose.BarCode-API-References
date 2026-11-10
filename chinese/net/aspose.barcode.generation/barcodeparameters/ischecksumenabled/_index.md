---
title: "BarcodeParameters.IsChecksumEnabled"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeParameters 属性。生成 1D 条码时启用校验和"
type: docs
weight: 200
url: /zh/net/aspose.barcode.generation/barcodeparameters/ischecksumenabled/
---
## BarcodeParameters.IsChecksumEnabled property

在生成 1D 条码时启用校验和。

默认情况下，对于必须包含校验和的符号系统视为 Yes，对于仅可能包含校验和的情况视为 No。

校验和可用：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar

校验和始终使用：其余符号系统

```csharp
public EnableChecksum IsChecksumEnabled { get; set; }
```

### 另见

* enum [EnableChecksum](../../enablechecksum/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


