---
title: "metod"
linktitle: "FormatQrReferenceNumber"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Formaterar ett QR‑referensnummer genom att infoga mellanslag i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.complexbarcode/payments/formatqrreferencenumber/
---
## Payments::FormatQrReferenceNumber method


Formaterar ett QR-referensnummer genom att infoga mellanslag.

```cpp
static System::String Aspose::BarCode::ComplexBarcode::Payments::FormatQrReferenceNumber(System::String refNo)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| refNo | System::String | Referensnumret utan mellanslag. |

### ReturnValue

det formaterade referensnumret.
## Anmärkningar


Mellanslag infogas för att skapa grupper om 5 siffror. Om en grupp med färre än 5 siffror behövs, visas den i början av det formaterade referensnumret.

## Se även

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
