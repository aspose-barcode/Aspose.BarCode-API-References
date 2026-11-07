---
title: "metode"
linktitle: "set_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan metode set_EncodeGS1SeparatorInByteMode dari kelas Aspose::BarCode::Generation::QrParameters dalam C++."
type: docs
weight: 1800
url: /id/cpp/aspose.barcode.generation/qrparameters/set_encodegs1separatorinbytemode/
---
## QrParameters::set_EncodeGS1SeparatorInByteMode method




```cpp
void Aspose::BarCode::Generation::QrParameters::set_EncodeGS1SeparatorInByteMode(bool value)
```

## Catatan


Mengatur nilai yang menunjukkan apakah karakter khusus GS1 harus dienkode dalam mode Byte untuk kode batang QR dan RectMicroQR.

Jika false, pemisah GS1 dapat dienkode sebagai '' dalam mode Alfanumerik menurut spesifikasi QR.

Jika true, pemisah grup GS1 dienkode dalam mode Byte sebagai karakter 0x1D, dan karakter '' juga dienkode dalam mode Byte untuk mempertahankannya sebagai data.

Opsi ini dapat meningkatkan kompatibilitas dengan decoder yang mengharapkan pemisah grup GS1 pada tingkat byte dan mencegah karakter data '' diinterpretasikan sebagai pemisah GS1.
## Lihat Juga

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
