---
title: "BarcodeParameters.ThrowExceptionWhenCodeTextIncorrect"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "BarcodeParameters 属性。仅适用于 1D 条码。如果 codetext 不正确且值设为 true，将抛出异常。否则 codetext 将被纠正以符合条码规范。如果 codetext 不正确，Databar 符号始终会抛出异常。对于 AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号，如果 codetext 不正确，则始终不会抛出异常。"
type: docs
weight: 290
url: /zh/net/aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/
---
## BarcodeParameters.ThrowExceptionWhenCodeTextIncorrect property

仅适用于 1D 条码。如果 codetext 不正确且值设置为 true——将抛出异常。否则 codetext 将被纠正以符合条码规范。以下情况始终会抛出异常：Databar 符号如果 codetext 不正确。以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果 codetext 不正确。

```csharp
public bool ThrowExceptionWhenCodeTextIncorrect { get; set; }
```

### 另见

* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


