---
title: HIBCLICPrimaryDataCodetext
second_title: Aspose.BarCode untuk .NET API Referensi
description: Kelas untuk encoding dan decoding teks yang disematkan dalam kode HIBC LIC yang menyimpan data primer.
type: docs
weight: 400
url: /id/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Kelas untuk encoding dan decoding teks yang disematkan dalam kode HIBC LIC yang menyimpan data primer.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | Konstruktor default. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Mendapat atau menyetel jenis barcode. Teks kode HIBC LIC dapat dikodekan menggunakan jenis enkode HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC, dan HIBCQRLIC. Nilai default: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Mengidentifikasi data primer. |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan yang ditentukan`HIBCLICPrimaryDataCodetext` nilai. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Mendapat jenis barcode. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Membuat codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Menginisialisasi instance dari teks kode yang dibuat. |

### Contoh

Contoh ini menunjukkan cara menyandikan dan mendekode HIBC LIC menggunakan HIBCLICPrimaryCodetext.

```csharp
[C#]
HIBCLICPrimaryCodetext complexCodetext  = new HIBCLICPrimaryCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryCodetext result = (HIBCLICPrimaryCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### Lihat juga

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* ruang nama [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->