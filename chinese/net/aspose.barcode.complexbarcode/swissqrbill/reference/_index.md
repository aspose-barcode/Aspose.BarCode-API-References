---
title: "SwissQRBill.Reference"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "SwissQRBill 属性。获取或设置债权人付款参考"
type: docs
weight: 80
url: /zh/net/aspose.barcode.complexbarcode/swissqrbill/reference/
---
## SwissQRBill.Reference property

获取或设置债权人付款参考。

对于 SwissQR IBAN，参考号是必填的，即范围在 CHxx30000xxxxxx 到 CHxx31999xxxxx 之间的 IBAN。

如果指定，参考号必须是有效的 SwissQR 参考号（对应 ISR 参考表格）或符合 ISO 11649（\"RFxxxx\"）的有效债权人参考号。两者均可包含空格用于格式化。

```csharp
public string Reference { get; set; }
```

### Property Value

债权人付款参考。

### 另见

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


