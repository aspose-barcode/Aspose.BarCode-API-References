---
title: "metod"
linktitle: "set_Reference"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Ställer in borgenärens betalningsreferens i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Sätter kreditorns betalningsreferens.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Anmärkningar


Referensen är obligatorisk för SwissQR-IBAN, d.v.s. IBAN i intervallet CHxx30000xxxxxx till CHxx31999xxxxx.

Om angiven måste referensen vara antingen en giltig SwissQR-referens (motsvarande ISR-referensform) eller en giltig borgenärsreferens enligt ISO 11649 (\"RFxxxx\"). Båda kan innehålla mellanslag för formatering.

Borgenärens betalningsreferens.
## Se även

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
