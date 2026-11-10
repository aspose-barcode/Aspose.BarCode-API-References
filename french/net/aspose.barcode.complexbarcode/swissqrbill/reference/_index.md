---
title: "SwissQRBill.Reference"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Propriété SwissQRBill. Obtient ou définit la référence de paiement du créancier."
type: docs
weight: 80
url: /fr/net/aspose.barcode.complexbarcode/swissqrbill/reference/
---
## SwissQRBill.Reference property

Obtient ou définit la référence de paiement du créancier.

La référence est obligatoire pour les IBAN SwissQR, c.-à-d. les IBAN dans la plage CHxx30000xxxxxx à CHxx31999xxxxx.

Si elle est spécifiée, la référence doit être soit une référence SwissQR valide (correspondant au formulaire de référence ISR), soit une référence de créancier valide selon la norme ISO 11649 ("RFxxxx"). Les deux peuvent contenir des espaces pour le formatage.

```csharp
public string Reference { get; set; }
```

### Property Value

La référence de paiement du créancier.

### Voir aussi

* class [SwissQRBill](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


