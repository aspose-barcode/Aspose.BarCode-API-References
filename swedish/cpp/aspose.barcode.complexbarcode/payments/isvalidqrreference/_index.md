---
title: "metod"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Validerar om strängen är en giltig QR‑referens i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Validerar om strängen är en giltig QR-referens.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| referens | System::String | QR‑referensnumret att validera. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Anmärkningar


En giltig QR‑referens är en giltig ISR‑referens.

Strängen kontrolleras för giltiga tecken, giltig längd och en giltig kontrollsiffra. Blanksteg ignoreras.

## Se även

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
