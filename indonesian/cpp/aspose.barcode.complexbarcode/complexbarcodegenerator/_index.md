---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. ComplexBarcodeGenerator untuk pembuatan gambar kode batang kompleks backend (mis. SwissQR) dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Membuat sebuah instance dari [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Bersihkan semua sumber daya yang sedang digunakan. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Menghasilkan gambar kode batang kompleks dengan pengaturan saat ini. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parameter. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Menghasilkan dan menyimpan gambar kode batang kompleks dengan pengaturan saat ini. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Menghasilkan dan menyimpan gambar kode batang kompleks dengan pengaturan saat ini. |
| [Save](./save/)(System::String) | Menghasilkan dan menyimpan gambar kode batang kompleks dengan pengaturan saat ini. |
## Catatan


Contoh ini menunjukkan cara membuat dan menyimpan gambar SwissQR.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // inisialisasi sisa bidang
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Lihat Juga

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
