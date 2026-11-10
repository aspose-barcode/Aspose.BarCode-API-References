---
title: "SwissQRBill.Reference"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "SwissQRBill-Eigenschaft. Gibt die Zahlungsreferenz des Gläubigers zurück oder legt sie fest"
type: docs
weight: 80
url: /de/net/aspose.barcode.complexbarcode/swissqrbill/reference/
---
## SwissQRBill.Reference property

Liest oder setzt die Zahlungsreferenz des Gläubigers.

Die Referenz ist für SwissQR-IBANs verpflichtend, d.h. für IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx.

Falls angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformular) oder eine gültige Gläubigerreferenz gemäß ISO 11649 (\"RFxxxx\") sein. Beide können zur Formatierung Leerzeichen enthalten.

```csharp
public string Reference { get; set; }
```

### Property Value

Die Gläubigerzahlungsreferenz.

### Siehe auch

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


