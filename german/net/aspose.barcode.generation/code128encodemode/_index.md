---
title: "Enum Code128EncodeMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.Code128EncodeMode-Enum. Kodierungsmodus für Code128‑Barcodes. Code‑128‑Spezifikation"
type: docs
weight: 1120
url: /de/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Kodierungsmodus für Code128-Barcodes. [Code 128](https://en.wikipedia.org/wiki/Code_128) Spezifikation.

```csharp
public enum Code128EncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Kodiert den Code-Text im klassischen ISO‑15417‑Modus. Der Modus sollte in allen üblichen Fällen verwendet werden. |
| CodeA | `1` | Kodiert den Code-Text nur im 128A‑Codesatz. |
| CodeB | `2` | Kodiert den Code-Text nur im 128B‑Codesatz. |
| CodeC | `4` | Kodiert den Code-Text nur im 128C‑Codesatz. |
| CodeAB | `3` | Kodiert den Code-Text nur in den 128A‑ und 128B‑Codesätzen. |
| CodeAC | `5` | Kodiert den Code-Text nur in den 128A‑ und 128C‑Codesätzen. |
| CodeBC | `6` | Kodiert den Code-Text nur in den 128B‑ und 128C‑Codesätzen. |

## Beispiele

Dieser Code demonstriert, wie man Code 128 mit verschiedenen Kodierungen erzeugt

```csharp
[C#]
//Erstelle Code 128 mit ISO‑15417‑Kodierung
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Nur Code 128 mit Codeset A Codierung generieren
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


