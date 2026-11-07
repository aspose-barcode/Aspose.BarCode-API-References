---
title: "Kelas Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan kelas Aspose::BarCode::Generation::DataMatrixExtCodetextBuilder dalam C++."
type: docs
weight: 1900
url: /id/cpp/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class




```cpp
class DataMatrixExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddCodetextWithEncodeMode](./addcodetextwithencodemode/)(DataMatrixEncodeMode, System::String) | Menambahkan codetext dengan mode enkode yang ditentukan ke item codetext yang diperluas |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Menambahkan codetext dengan Extended Channel Identifier |
| [AddECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, System::String) | Menambahkan codetext dengan Extended Channel Identifier dengan mode enkode yang ditentukan |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Menambahkan codetext biasa ke item codetext yang diperluas |
| virtual [Clear](../extcodetextbuilder/clear/)() | Menghapus item codetext yang diperluas |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Menghasilkan Extended codetext dari daftar extended codetext. |
## Catatan


Generator codetext yang diperluas untuk barcode DataMatrix 2D untuk Mode ExtendedCodetext dari EncodeMode


```cpp
[C#]
//Mode teks kode yang diperluas

//buat codetext
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//hasilkan codetext
string codetext = textBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
