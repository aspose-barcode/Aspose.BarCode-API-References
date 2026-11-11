---
title: "Kelas USADriveIdCodetext"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.ComplexBarcode.USADriveIdCodetext. Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 Lisensi Mengemudi USA"
type: docs
weight: 810
url: /id/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode PDF417 Lisensi Mengemudi USA.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Nomor Versi AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Nomor ini secara unik mengidentifikasi yurisdiksi penerbit dan dapat diperoleh dengan menghubungi Otoritas Penerbit ISO (AAMVA). IIN lengkap 6 digit harus dikodekan. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Bidang Khusus Yurisdiksi |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Nomor Versi Yurisdiksi 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Elemen wajib (field) kartu |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Nomor 00-99 dari subfile |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Elemen (bidang) opsional dari kartu |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Berisi informasi tentang subfile berikut, tipe, offset, dan panjang. Penting: atur hanya tipe, offset dan panjang akan diatur secara otomatis. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Mengembalikan tipe barcode dari USA DL (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Menyusun codetext dari data USA DL |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Inisialisasi objek USA DL dari codetext |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Menyimpan ke XML |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Elemen wajib (field) kartu |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Elemen (bidang) opsional dari kartu |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Properti subfile DL USA, offset dan panjangnya diatur secara otomatis. |

### Lihat Juga

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


