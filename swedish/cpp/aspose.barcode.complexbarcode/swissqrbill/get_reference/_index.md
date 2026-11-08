---
title: "metod"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Hämtar borgenärens betalningsreferens i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Hämtar kreditorns betalningsreferens.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Anmärkningar


Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx till CHxx31999xxxxx.

Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande ISR-referensform) eller en giltig borgenärsreferens enligt ISO 11649 (\"RFxxxx\"). Båda kan innehålla mellanslag för formatering.

Borgenärens betalningsreferens.
## Se även

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
