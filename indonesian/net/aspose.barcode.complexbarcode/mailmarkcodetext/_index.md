---
title: MailmarkCodetext
second_title: Aspose.BarCode untuk .NET API Referensi
description: Kelas untuk menyandikan dan mendekode teks yang disematkan dalam kode Royal Mailmark 4status.
type: docs
weight: 490
url: /id/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

Kelas untuk menyandikan dan mendekode teks yang disematkan dalam kode Royal Mailmark 4-status.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Null atau Test "1" - 1C (Ritel) "2" - 2C (Ritel) "3" - 3C (Ritel) "4" - Premium (Surat Penerbitan Ritel) (untuk kemungkinan penggunaan di masa mendatang) "5" - Ditangguhkan (Ritel) "6" - Udara (Ritel) (untuk kemungkinan penggunaan di masa mendatang) "7" - Permukaan (Ritel) (untuk kemungkinan penggunaan di masa mendatang) "8" - Premium (Akses Jaringan) "9" - Standar (Akses Jaringan) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | PC dan DP harus sesuai dengan format PAF. Sembilan karakter string yang menunjukkan internasional "XY11 " (perhatikan 5 spasi tambahan) atau pola karakter yang menunjukkan kode urut domestik. Kode urut domestik terdiri dari kode pos luar, kode pos ke dalam, dan Akhiran Titik Pengiriman. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Null atau Test "1" – Letter "2" – Huruf Besar |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Nilai maksimum adalah 99999999. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Nilai maksimum adalah 99 untuk Barcode C dan 999999 untuk Barcode L. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Saat ini "1" – Untuk kode batang Mailmark (0 dan 2 hingga 9 dan cadangan A hingga Z untuk penggunaan mendatang) |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Mendapat jenis barcode. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Buat teks kode dari data Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Menginisialisasi data Mailmark dari teks kode yang dibuat. |

### Lihat juga

* interface [IComplexCodetext](../icomplexcodetext/)
* ruang nama [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->