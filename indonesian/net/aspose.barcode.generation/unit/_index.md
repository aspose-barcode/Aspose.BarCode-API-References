---
title: Unit
second_title: Aspose.BarCode untuk .NET API Referensi
description: Menentukan nilai ukuran dalam satuan yang berbeda Piksel Inci dll..
type: docs
weight: 1260
url: /id/net/aspose.barcode.generation/unit/
---
## Unit class

Menentukan nilai ukuran dalam satuan yang berbeda (Piksel, Inci, dll.).

```csharp
public sealed class Unit
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Mendapat atau menetapkan nilai ukuran dalam satuan dokumen. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | Mendapat atau menetapkan nilai ukuran dalam inci. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Mendapat atau menetapkan nilai ukuran dalam milimeter. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Mendapat atau menetapkan nilai ukuran dalam piksel. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Mendapat atau menetapkan nilai ukuran dalam poin. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Resolusi |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Menentukan apakah instance ini dan objek tertentu, yang juga harus berupa`Unit` objek, memiliki nilai yang sama. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Mengembalikan kode hash untuk objek ini. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari ini`Unit` . |

### Contoh

Contoh ini menunjukkan cara membuat dan menyimpan gambar BarCode.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Lihat juga

* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->