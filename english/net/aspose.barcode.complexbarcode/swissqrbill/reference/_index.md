---
title: SwissQRBill.Reference
second_title: Aspose.BarCode for .NET API Reference
description: SwissQRBill property. Gets or sets the creditor payment reference
type: docs
weight: 80
url: /net/aspose.barcode.complexbarcode/swissqrbill/reference/
---
## SwissQRBill.Reference property

Gets or sets the creditor payment reference.

The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx.

If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

```csharp
public string Reference { get; set; }
```

### Property Value

The creditor payment reference.

### See Also

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


