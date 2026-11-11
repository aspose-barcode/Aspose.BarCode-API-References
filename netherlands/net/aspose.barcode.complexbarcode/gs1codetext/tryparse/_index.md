---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "GS1Codetext-methode. Probeert een haakjes-omsloten GS1-elementstring in de vorm AIwaardeAIwaarde te parseren en retourneert gestructureerde validatiefouten. Een letterlijke  binnen een waarde moet worden geschreven als  er wordt geen andere escape‑reeks ondersteund en  hoeft niet te worden geescaped."
type: docs
weight: 140
url: /nl/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Probeert een tussen haakjes geplaatste GS1-elementstring in de vorm (AI)waarde(AI)waarde te parseren en retourneert gestructureerde validatiefouten. Een letterlijke '(' binnen een waarde moet worden geschreven als \(; geen andere escape‑reeks wordt ondersteund, en ')' hoeft niet te worden geescaped.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | String | Haakjes-omsloten GS1-elementstring om te parseren. |
| result | GS1Codetext& | Wanneer deze methode true retourneert, bevat deze de geparseerde GS1-codetekst; anders null. |
| validationResult | GS1ValidationResult& | Bevat het validatieresultaat, of null wanneer *value* null is. |

### Retourwaarde

True wanneer het parseren slaagt; anders false.

### Zie ook

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


