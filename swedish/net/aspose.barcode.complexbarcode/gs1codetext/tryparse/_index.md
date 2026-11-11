---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode för .NET API-referens"
description: "GS1Codetext method. Försöker parsa en hakparentesomsluten GS1‑elementsträng i formatet AIvalueAIvalue och returnerar strukturerade valideringsfel. En litteral  inuti ett värde måste skrivas som  ingen annan escape‑sekvens stöds och  kräver ingen escaping"
type: docs
weight: 140
url: /sv/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

Försöker tolka en hakparentes‑GS1‑elementsträng i formatet (AI)value(AI)value och returnerar strukturerade valideringsfel. Ett bokstavligt '(' i ett värde måste skrivas som '\\(' ; ingen annan escape‑sekvens stöds, och ')' kräver ingen escape.

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | String | Hakparentesomsluten GS1‑elementsträng att parsa. |
| result | GS1Codetext& | När den här metoden returnerar true innehåller den den parsade GS1‑kodtexten; annars null. |
| validationResult | GS1ValidationResult& | Innehåller valideringsresultatet, eller null när *value* är null. |

### Returvärde

Sant när parsning lyckas; annars falskt.

### Se även

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


