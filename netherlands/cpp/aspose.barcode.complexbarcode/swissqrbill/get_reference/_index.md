---
title: "methode"
linktitle: "get_Reference"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " method. Haalt de crediteur betalingsreferentie op in C++."
type: docs
weight: 1100
url: /nl/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


Haalt de betalingsreferentie van de crediteur op.

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## Opmerkingen


De referentie is verplicht voor SwissQR-IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx.

Indien gespecificeerd, moet de referentie een geldige SwissQR-referentie (overeenkomend met het ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

De crediteur betalingsreferentie.
## Zie ook

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
