---
title: "GS1Codetext.TryParse"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "GS1Codetext method. Tente d'analyser une chaîne d'élément GS1 entre crochets sous la forme AIvalueAIvalue et renvoie des erreurs de validation structurées. Un littéral  à l'intérieur d'une valeur doit être écrit comme  aucune autre séquence d'échappement n'est prise en charge et  ne nécessite d'échappement"
type: docs
weight: 140
url: /fr/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Tente d'analyser une chaîne d'élément GS1 entre crochets sous la forme (AI)valeur(AI)valeur et renvoie des erreurs de validation structurées. Un '(' littéral à l'intérieur d'une valeur doit être écrit comme \(; aucune autre séquence d'échappement n'est prise en charge, et ')' ne nécessite pas d'échappement.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | String | Chaîne d'élément GS1 entre crochets à analyser. |
| résultat | GS1Codetext& | Lorsque cette méthode renvoie true, contient le texte codé GS1 analysé ; sinon null. |
| validationResult | GS1ValidationResult& | Contient le résultat de validation, ou null lorsque *value* est null. |

### Valeur de retour

True lorsque l'analyse réussit ; sinon false.

### Voir aussi

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


