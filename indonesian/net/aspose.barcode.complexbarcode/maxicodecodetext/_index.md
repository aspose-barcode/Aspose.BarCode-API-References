---
title: MaxiCodeCodetext
second_title: Aspose.BarCode untuk .NET API Referensi
description: Kelas dasar untuk menyandikan dan mendekode teks yang disematkan dalam kode MaxiCode.
type: docs
weight: 500
url: /id/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

Kelas dasar untuk menyandikan dan mendekode teks yang disematkan dalam kode MaxiCode.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Mendapat atau menyetel enkode ECI. Digunakan saat MaxiCodeEncodeMode adalah Auto. Nilai default: ISO-8859-1 |
| [MaxiCodeEncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/maxicodeencodemode/) { get; set; } | Mendapat atau menyetel mode penyandian MaxiCode. Nilai default: Otomatis. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Mendapat jenis barcode. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Membuat codetext |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Mendapat mode MaxiCode. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Menginisialisasi instance dari teks kode yang dibuat. |

### Contoh

Contoh ini menunjukkan cara mendekode teks kode MaxiCode mentah ke instance MaxiCodeCodetext.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Lihat juga

* interface [IComplexCodetext](../icomplexcodetext/)
* ruang nama [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->