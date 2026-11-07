---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode enkode barcode Pdf417 dalam C++."
type: docs
weight: 7900
url: /id/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Mode enkode barcode Pdf417

```cpp
enum class Pdf417EncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| Biner | 1 | Dalam mode Biner, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | 2 | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| Extended | 3 |  |

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
