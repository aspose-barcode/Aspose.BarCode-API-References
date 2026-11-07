---
title: "methode"
linktitle: "set_Reference"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Stelt de crediteurbetalingsreferentie in in C++."
type: docs
weight: 1200
url: /nl/cpp/aspose.barcode.complexbarcode/swissqrbill/set_reference/
---
## SwissQRBill::set_Reference method


Stelt de betalingsreferentie van de crediteur in.

```cpp
void Aspose::BarCode::ComplexBarcode::SwissQRBill::set_Reference(System::String value)
```

## Opmerkingen


De referentie is verplicht voor SwissQR-IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx.

Indien gespecificeerd, moet de referentie een geldige SwissQR-referentie (overeenkomend met het ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

De crediteur betalingsreferentie.
## Zie ook

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
