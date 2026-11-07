---
title: "Methode"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Validiert, ob die Zeichenkette eine gültige QR‑Referenz in C++ ist."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Validiert, ob die Zeichenkette eine gültige QR-Referenz ist.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Referenz | System::String | Die zu validierende QR‑Referenznummer. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Hinweise


Eine gültige QR-Referenz ist eine gültige ISR-Referenz.

Die Zeichenkette wird auf gültige Zeichen, gültige Länge und eine gültige Prüfziffer geprüft. Leerzeichen werden ignoriert.

## Siehe auch

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
