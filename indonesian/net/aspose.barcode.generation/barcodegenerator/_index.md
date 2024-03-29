---
title: BarcodeGenerator
second_title: Aspose.BarCode untuk .NET API Referensi
description: BarcodeGenerator untuk pembuatan gambar barcode backend.
type: docs
weight: 700
url: /id/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator untuk pembuatan gambar barcode backend.

supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14 , SingaporePost ... 2D: Aztec, DataMatrix, PDf417, kode QR ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Membuat instance dari BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Membuat instance dari BarcodeGenerator. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Jenis simbologi kode batang. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Teks yang akan dikodekan. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Parameter pembuatan. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Mengimpor properti BarCode dari xml-stream yang ditentukan dan membuat instance BarcodeGenerator. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Mengimpor properti BarCode dari file xml yang ditentukan dan membuat instance BarcodeGenerator. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Menggambar gambar barcode pada kanvas WPF. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Mengekspor properti BarCode ke aliran xml yang ditentukan |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Mengekspor properti BarCode ke file xml yang ditentukan |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Hasilkan gambar barcode di bawah pengaturan saat ini. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Simpan gambar barcode ke file tertentu. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Simpan gambar barcode untuk streaming dalam format tertentu. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Simpan gambar barcode ke file tertentu dalam format tertentu. |

### Contoh

Contoh ini menunjukkan cara membuat dan menyimpan gambar barcode.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
