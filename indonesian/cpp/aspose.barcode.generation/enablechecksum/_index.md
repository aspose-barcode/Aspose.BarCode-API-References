---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 6700
url: /id/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Bawaan | 0 | Jika checksum diperlukan oleh spesifikasi - itu akan dilampirkan. |
| Ya | 1 | Selalu gunakan checksum jika memungkinkan. |
| Tidak | 2 | Jangan gunakan checksum. |

## Catatan


Aktifkan checksum selama pembuatan barcode 1D.

Bawaan diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai Tidak dimana checksum hanya mungkin.

Checksum tidak pernah digunakan: Codabar

Checksum memungkinkan: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum selalu digunakan: Simbol lainnya
## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
