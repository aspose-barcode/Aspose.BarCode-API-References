---
title: "Methode"
linktitle: "set_Reference"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Zahlungsreferenz des Gläubigers in C++."
type: docs
weight: 1200
url: /de/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Setzt die Zahlungsreferenz des Gläubigers.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Hinweise


Die Referenz ist für SwissQR-IBANs obligatorisch, d.h. IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx.

Falls angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 (\"RFxxxx\"). Beide können zur Formatierung Leerzeichen enthalten.

Die Gläubigerzahlungsreferenz.
## Siehe auch

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
