---
title: "GS1DigitalLink.TryParse"
second_title: "Aspose.BarCode för .NET API-referens"
description: "GS1DigitalLink-metod. Försöker att parsa en okomprimerad GS1 Digital Link-URI och returnerar strukturerade valideringsfel."
type: docs
weight: 190
url: /sv/net/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink.TryParse method

Försöker att tolka en okomprimerad GS1 Digital Link-URI och returnerar strukturerade valideringsfel.

```csharp
public static bool TryParse(string value, out GS1DigitalLink result, 
    out GS1ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | String | GS1 Digital Link-URI att parsa. |
| result | GS1DigitalLink& | När denna metod returnerar true, innehåller den den parsade GS1 Digital Link; annars null. |
| validationResult | GS1ValidationResult& | Innehåller valideringsresultatet, eller null när *value* är null. |

### Returvärde

Sant när parsning lyckas; annars falskt.

### Se även

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1DigitalLink](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


