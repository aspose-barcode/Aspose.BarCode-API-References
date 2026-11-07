---
title: "metode"
linktitle: "IsValidQrReference"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Memvalidasi apakah string merupakan referensi QR yang valid dalam C++."
type: docs
weight: 600
url: /id/cpp/aspose.barcode.complexbarcode/payments/isvalidqrreference/
---
## Payments::IsValidQrReference method


Memvalidasi apakah string merupakan referensi QR yang valid.

```cpp
static bool Aspose::BarCode::ComplexBarcode::Payments::IsValidQrReference(System::String reference)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| referensi | System::String | Nomor referensi QR yang akan divalidasi. |

### ReturnValue

**true** if the reference number is valid, **false** otherwise.
## Catatan


Referensi QR yang valid adalah referensi ISR yang valid.

String diperiksa untuk karakter yang valid, panjang yang valid, dan digit pemeriksaan yang valid. Spasi diabaikan.

## Lihat Juga

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
