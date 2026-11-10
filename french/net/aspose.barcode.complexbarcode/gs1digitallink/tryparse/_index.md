---
title: "GS1DigitalLink.TryParse"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Méthode GS1DigitalLink. Tente d'analyser une URI GS1 Digital Link non compressée et renvoie des erreurs de validation structurées"
type: docs
weight: 190
url: /fr/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Tente d'analyser une URI de lien numérique GS1 non compressée et renvoie des erreurs de validation structurées.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | String | URI GS1 Digital Link à analyser. |
| résultat | GS1DigitalLink& | Lorsque cette méthode renvoie true, contient le GS1 Digital Link analysé ; sinon null. |
| validationResult | GS1ValidationResult& | Contient le résultat de validation, ou null lorsque *value* est null. |

### Valeur de retour

True lorsque l'analyse réussit ; sinon false.

### Voir aussi

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


