---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " enum. Coderingsmodus voor Code128 barcodes. Code 128-specificatie in C++."
type: docs
weight: 5900
url: /nl/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Coderingsmodus voor Code128-streepjescodes. Code 128

specificatie.

```cpp
enum class Code128EncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | 0 | Codeer codetekst in klassieke ISO 15417-modus. Deze modus moet in alle gewone gevallen worden gebruikt. |
| CodeA | 1 | Codeer codetekst alleen in 128A-codeset. |
| CodeB | 2 | Codeer codetekst alleen in 128B-codeset. |
| CodeC | 4 | Codeer codetekst alleen in 128C-codeset. |
| CodeAB | 3 | Codeer codetekst alleen in 128A- en 128B-codesets. |
| CodeAC | 5 | Codeer codetekst alleen in 128A- en 128C-codesets. |
| CodeBC | 6 | Codeer codetekst alleen in 128B- en 128C-codesets. |

## Opmerkingen


Deze code toont hoe code 128 te genereren met verschillende coderingen
```cpp
[C#]
//Genereer code 128 met ISO 15417-codering
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Genereer code 128 alleen met Codeset A-codering
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
