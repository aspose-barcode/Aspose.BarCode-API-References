---
title: "metod"
linktitle: "FormatIban"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Formaterar ett IBAN eller en borgenärsreferens genom att infoga mellanslag i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


Formaterar ett IBAN eller en kreditorreferens genom att infoga mellanslag

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iban | System::String | IBAN‑et eller borgenärsreferensen utan mellanslag. |

### ReturnValue

Det formaterade IBAN‑et eller borgenärsreferensen.
## Anmärkningar


Mellanslag infogas för att bilda grupper om 4 tecken/siffror. Om en grupp med färre än 4 tecken/siffror behövs, visas den i slutet.

## Se även

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
