---
title: "Enum Code128EncodeMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.Generation.Code128EncodeMode. Mode enkoding untuk barcode Code128. Spesifikasi Code 128"
type: docs
weight: 1120
url: /id/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Mode enkoding untuk barcode Code128. Spesifikasi [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Enkode teks kode dalam mode klasik ISO 15417. Mode ini harus digunakan dalam semua kasus biasa. |
| CodeA | `1` | Enkode teks kode hanya dalam set kode 128A. |
| CodeB | `2` | Enkode teks kode hanya dalam set kode 128B. |
| CodeC | `4` | Enkode teks kode hanya dalam set kode 128C. |
| CodeAB | `3` | Enkode teks kode hanya dalam set kode 128A dan 128B. |
| CodeAC | `5` | Enkode teks kode hanya dalam set kode 128A dan 128C. |
| CodeBC | `6` | Enkode teks kode hanya dalam set kode 128B dan 128C. |

## Contoh

Kode ini menunjukkan cara menghasilkan code 128 dengan enkoding yang berbeda

```csharp
[C#]
//Hasilkan code 128 dengan enkoding ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Hasilkan code 128 hanya dengan enkoding Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Lihat Juga

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


