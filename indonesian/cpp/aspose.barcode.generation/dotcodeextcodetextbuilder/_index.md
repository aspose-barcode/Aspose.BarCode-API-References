---
title: "Aspose::BarCode::Generation::DotCodeExtCodetextBuilder class"
linktitle: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Bagaimana cara menggunakan kelas Aspose::BarCode::Generation::DotCodeExtCodetextBuilder dalam C++."
type: docs
weight: 2100
url: /id/cpp/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class




```cpp
class DotCodeExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Menambahkan codetext dengan Extended Channel Identifier |
| [AddFNC1FormatIdentifier](./addfnc1formatidentifier/)() | Menambahkan pengidentifikasi format FNC1 ke item codetext yang diperluas |
| [AddFNC3ReaderInitialization](./addfnc3readerinitialization/)() | Menambahkan inisialisasi pembaca FNC3 ke item codetext yang diperluas |
| [AddFNC3SymbolSeparator](./addfnc3symbolseparator/)() | Menambahkan pemisah simbol FNC3 ke item codetext yang diperluas |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Menambahkan codetext biasa ke item codetext yang diperluas |
| [AddStructuredAppendMode](./addstructuredappendmode/)(int32_t, int32_t) | Menambahkan mode penambahan terstruktur ke item codetext yang diperluas |
| virtual [Clear](../extcodetextbuilder/clear/)() | Menghapus item codetext yang diperluas |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Menghasilkan Extended codetext dari daftar extended codetext. |
## Catatan


Generator codetext yang diperluas untuk barcode DotCode 2D untuk Mode ExtendedCodetext dari DotCodeEncodeMode


```cpp
[C#]
//Mode teks kode yang diperluas
//buat codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//hasilkan codetext
string codetext = textBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
