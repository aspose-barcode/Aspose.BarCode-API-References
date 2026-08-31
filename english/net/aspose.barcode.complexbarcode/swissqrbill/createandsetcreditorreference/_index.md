---
title: SwissQRBill.CreateAndSetCreditorReference
second_title: Aspose.BarCode for .NET API Reference
description: SwissQRBill method. Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with RF and the modulo 97 checksum
type: docs
weight: 110
url: /net/aspose.barcode.complexbarcode/swissqrbill/createandsetcreditorreference/
---
## SwissQRBill.CreateAndSetCreditorReference method

Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

Whitespace is removed from the reference

```csharp
public void CreateAndSetCreditorReference(string rawReference)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rawReference | String | The raw reference. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | `rawReference` contains invalid characters. |

### See Also

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


