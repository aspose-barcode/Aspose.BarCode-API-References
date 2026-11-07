---
title: "Methode"
linktitle: "get_Reference"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Liest die Gläubigerzahlungsreferenz in C++."
type: docs
weight: 1100
url: /de/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Liefert die Zahlungsreferenz des Gläubigers.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Hinweise


Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx.

Falls angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 (\"RFxxxx\"). Beide können zur Formatierung Leerzeichen enthalten.

Die Gläubigerzahlungsreferenz.
## Siehe auch

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
