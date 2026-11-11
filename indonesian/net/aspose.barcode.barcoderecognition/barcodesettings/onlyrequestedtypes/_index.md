---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Properti BarcodeSettings. Mengembalikan hanya tipe kode batang yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, kode batang yang dikenali dari tipe lain yang kompatibel atau setara akan disaring. Nilai default adalah false."
type: docs
weight: 50
url: /id/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

Mengembalikan hanya tipe kode batang yang secara eksplisit ditentukan untuk pengenalan. Ketika diaktifkan, kode batang yang dikenali dari tipe lain yang kompatibel atau setara akan disaring. Nilai default adalah false.

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

Mengembalikan hanya tipe kode batang yang secara eksplisit ditentukan untuk pengenalan. Nilai default adalah false.

## Contoh

Contoh ini menunjukkan cara membatasi hasil pengenalan hanya pada jenis barcode yang diminta

```csharp
[C#]
//buat barcode EAN13
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//kenali hanya barcode UPCA (tidak ada hasil, karena sumbernya EAN13)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//kenali tipe yang kompatibel: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 akan dikembalikan sebagai setara UPCA)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```

### Lihat Juga

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


