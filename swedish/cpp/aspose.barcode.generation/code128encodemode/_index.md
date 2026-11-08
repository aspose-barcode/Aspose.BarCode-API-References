---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API-referens"
description: " enum. Kodningsläge för Code128 streckkoder. Code 128specifikation i C++."
type: docs
weight: 5900
url: /sv/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Kodningsläge för Code128-streckkoder. Code 128

specifikation.

```cpp
enum class Code128EncodeMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Auto | 0 | Koda kodtext i klassiskt ISO 15417-läge. Läget bör användas i alla vanliga fall. |
| CodeA | 1 | Koda kodtext endast i 128A-koduppsättning. |
| CodeB | 2 | Koda kodtext endast i 128B-koduppsättning. |
| CodeC | 4 | Koda kodtext endast i 128C-koduppsättning. |
| CodeAB | 3 | Koda kodtext endast i 128A- och 128B-koduppsättningar. |
| CodeAC | 5 | Koda kodtext endast i 128A- och 128C-koduppsättningar. |
| CodeBC | 6 | Koda kodtext endast i 128B- och 128C-koduppsättningar. |

## Anmärkningar


Denna kod demonstrerar hur man genererar kod 128 med olika kodningar
```cpp
[C#]
//Generera kod 128 med ISO 15417-kodning
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generera kod 128 endast med koduppsättning A-kodning
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
