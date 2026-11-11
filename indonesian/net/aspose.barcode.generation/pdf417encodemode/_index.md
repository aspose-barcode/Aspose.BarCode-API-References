---
title: "Enum Pdf417EncodeMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.Generation.Pdf417EncodeMode. Mode enkode barcode Pdf417"
type: docs
weight: 1540
url: /id/net/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enumeration

Mode enkode barcode Pdf417

```csharp
public enum Pdf417EncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | In Auto mode, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika sebuah karakter ditemukan yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| Binary | `1` | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | `2` | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika sebuah karakter ditemukan yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap perhatikan bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| Extended | `3` | Mode Extended yang mendukung beberapa mode ECI. |

### Lihat Juga

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


