---
title: "Enum Code128EncodeMode"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.Code128EncodeMode enum. Kodningsläge för Code128-streckkoder. Code 128-specifikation"
type: docs
weight: 1120
url: /sv/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Kodningsläge för Code128-streckkoder. [Code 128](https://en.wikipedia.org/wiki/Code_128) specifikation.

```csharp
public enum Code128EncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | `0` | Koda kodtext i klassiskt ISO 15417-läge. Läget bör användas i alla vanliga fall. |
| CodeA | `1` | Koda kodtext endast i 128A-koduppsättning. |
| CodeB | `2` | Koda kodtext endast i 128B-koduppsättning. |
| CodeC | `4` | Koda kodtext endast i 128C-koduppsättning. |
| CodeAB | `3` | Koda kodtext endast i 128A- och 128B-koduppsättningar. |
| CodeAC | `5` | Koda kodtext endast i 128A- och 128C-koduppsättningar. |
| CodeBC | `6` | Koda kodtext endast i 128B- och 128C-koduppsättningar. |

## Exempel

Denna kod demonstrerar hur man genererar kod 128 med olika kodningar

```csharp
[C#]
//Generera kod 128 med ISO 15417-kodning
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generera endast Code 128 med Codeset A-kodning
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Se även

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


