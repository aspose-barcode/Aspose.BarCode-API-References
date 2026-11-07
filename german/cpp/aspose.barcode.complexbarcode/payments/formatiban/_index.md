---
title: "Methode"
linktitle: "FormatIban"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Formatiert eine IBAN oder Gläubigerreferenz, indem Leerzeichen in C++ eingefügt werden."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.complexbarcode/payments/formatiban/
---
## Payments::FormatIban method


Formatiert eine IBAN oder Gläubigerreferenz, indem Leerzeichen eingefügt werden.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatIban(System::String iban)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| IBAN | System::String | Die IBAN oder Gläubigerreferenz ohne Leerzeichen. |

### ReturnValue

Die formatierte IBAN oder Gläubigerreferenz.
## Hinweise


Leerzeichen werden eingefügt, um Gruppen von 4 Buchstaben/Ziffern zu bilden. Wenn eine Gruppe von weniger als 4 Buchstaben/Ziffern benötigt wird, erscheint sie am Ende.

## Siehe auch

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
