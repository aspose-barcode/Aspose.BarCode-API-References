---
title: "Aspose::BarCode::Generation::AztecExtCodetextBuilder class"
linktitle: "AztecExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan kelas Aspose::BarCode::Generation::AztecExtCodetextBuilder dalam C++."
type: docs
weight: 200
url: /id/cpp/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class




```cpp
class AztecExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Menambahkan codetext dengan Extended Channel Identifier |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Menambahkan codetext biasa ke item codetext yang diperluas |
| virtual [Clear](../extcodetextbuilder/clear/)() | Menghapus item codetext yang diperluas |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Menghasilkan Extended codetext dari daftar extended codetext. |
## Catatan


Generator Extended codetext untuk kode batang Aztec untuk Mode ExtendedCodetext dari AztecEncodeMode

Gunakan properti TwoDDisplayText dari [BarcodeGenerator](../barcodegenerator/) untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Contoh ini menunjukkan cara menggunakan [AztecExtCodetextBuilder](./) dalam Mode Diperluas.
```cpp
[C#]
//buat codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//hasilkan codetext
string codetext = textBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
