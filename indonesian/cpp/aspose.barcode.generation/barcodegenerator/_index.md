---
title: "Aspose::BarCode::Generation::BarcodeGenerator kelas"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::Generation::BarcodeGenerator kelas. BarcodeGenerator untuk pembuatan gambar barcode backend dalam C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Membuat sebuah instance dari [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Membuat sebuah instance dari [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Bersihkan semua sumber daya yang sedang digunakan. |
| [ExportToXml](./exporttoxml/)(System::String) | Mengekspor properti [BarCode](../../aspose.barcode/) ke file xml yang ditentukan |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Mengekspor properti [BarCode](../../aspose.barcode/) ke aliran xml yang ditentukan |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Hasilkan gambar barcode dengan pengaturan saat ini. |
| [get_BarcodeType](./get_barcodetype/)() | Tipe simbolologi barcode. |
| [get_CodeText](./get_codetext/)() | Teks yang akan dienkode. |
| [get_Parameters](./get_parameters/)() const | [Generation](../) parameter. |
| static [ImportFromXml](./importfromxml/)(System::String) | Mengimpor properti [BarCode](../../aspose.barcode/) dari xml-file yang ditentukan dan membuat instance [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Mengimpor properti [BarCode](../../aspose.barcode/) dari xml-stream yang ditentukan dan membuat instance [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Simpan gambar barcode ke stream dalam format tertentu. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Simpan gambar barcode ke file tertentu dalam format tertentu. |
| [Save](./save/)(System::String) | Simpan gambar barcode ke file tertentu. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Tipe simbolologi barcode. |
| [set_CodeText](./set_codetext/)(System::String) | Teks yang akan dienkode. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Atur codetext sebagai urutan byte. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Catatan


simbolologi yang didukung: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Contoh ini menunjukkan cara membuat dan menyimpan gambar barcode.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
