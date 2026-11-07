---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Codierungsmodus für Code128-Barcodes. Code 128-Spezifikation in C++."
type: docs
weight: 5900
url: /de/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Kodierungsmodus für Code128-Barcodes. Code 128

Spezifikation.

```cpp
enum class Code128EncodeMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Codetext im klassischen ISO 15417 Modus kodieren. Der Modus sollte in allen üblichen Fällen verwendet werden. |
| CodeA | 1 | Codetext nur im 128A-Codeset kodieren. |
| CodeB | 2 | Codetext nur im 128B-Codeset kodieren. |
| CodeC | 4 | Codetext nur im 128C-Codeset kodieren. |
| CodeAB | 3 | Codetext nur im 128A- und 128B-Codeset kodieren. |
| CodeAC | 5 | Codetext nur im 128A- und 128C-Codeset kodieren. |
| CodeBC | 6 | Codetext nur im 128B- und 128C-Codeset kodieren. |

## Hinweise


Dieser Code demonstriert, wie man Code 128 mit verschiedenen Codierungen erzeugt
```cpp
[C#]
//Generiere Code 128 mit ISO 15417 Codierung
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generiere Code 128 nur mit Codeset A Codierung
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
