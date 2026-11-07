---
title: "Methode"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Formatiert eine QR-Referenznummer, indem Leerzeichen in C++ eingefügt werden."
type: docs
weight: 700
url: /de/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


Formatiert eine QR-Referenznummer, indem Leerzeichen eingefügt werden.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| refNo | System::String | Die Referenznummer ohne Leerzeichen. |

### ReturnValue

die formatierte Referenznummer.
## Hinweise


Leerzeichen werden eingefügt, um Gruppen von 5 Ziffern zu bilden. Wenn eine Gruppe von weniger als 5 Ziffern benötigt wird, erscheint sie am Anfang der formatierten Referenznummer.

## Siehe auch

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
