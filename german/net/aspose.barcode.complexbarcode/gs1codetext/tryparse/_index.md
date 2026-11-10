---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "GS1Codetext Methode. Versucht, einen geklammerten GS1-Element-String im Format AIvalueAIvalue zu parsen und gibt strukturierte Validierungsfehler zurück. Ein wörtliches  innerhalb eines Wertes muss als  geschrieben werden; keine andere Escape-Sequenz wird unterstützt und  muss nicht escaped werden."
type: docs
weight: 140
url: /de/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Versucht, einen geklammerten GS1-Element-String in der Form (AI)Wert(AI)Wert zu parsen und gibt strukturierte Validierungsfehler zurück. Ein wörtliches '(' innerhalb eines Wertes muss als \( geschrieben werden; andere Escape-Sequenzen werden nicht unterstützt, und ')' muss nicht escaped werden.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | String | Geklammerter GS1-Element-String zum Parsen. |
| Ergebnis | GS1Codetext& | Wenn diese Methode true zurückgibt, enthält sie den geparsten GS1-Codetext; andernfalls null. |
| Validierungsergebnis | GS1ValidationResult& | Enthält das Validierungsergebnis, oder null, wenn *value* null ist. |

### Rückgabewert

True, wenn das Parsen erfolgreich ist; andernfalls false.

### Siehe auch

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


