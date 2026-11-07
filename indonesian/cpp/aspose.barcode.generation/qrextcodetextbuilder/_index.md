---
title: "kelas Aspose::BarCode::Generation::QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan kelas Aspose::BarCode::Generation::QrExtCodetextBuilder dalam C++."
type: docs
weight: 4300
url: /id/cpp/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class




```cpp
class QrExtCodetextBuilder : public Aspose::BarCode::Generation::ExtCodetextBuilder
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddCodetextWithCompactionMode](./addcodetextwithcompactionmode/)(QrExtCompactionMode, System::String) | Menambahkan teks kode dengan mode kompaksi QR yang ditentukan ke item teks kode yang diperluas. |
| [AddECICodetext](../extcodetextbuilder/addecicodetext/)(ECIEncodings, System::String) | Menambahkan codetext dengan Extended Channel Identifier |
| [AddFNC1FirstPosition](./addfnc1firstposition/)() | Mengatur FNC1 pada posisi pertama. Jika mode FNC1 lain telah diatur sebelumnya, maka akan diganti. |
| [AddFNC1GroupSeparator](./addfnc1groupseparator/)() | Menambahkan Group Separator (GS - '\u001D') ke item codetext yang diperluas. |
| [AddFNC1SecondPosition](./addfnc1secondposition/)(System::String) | Mengatur FNC1 pada posisi kedua. Jika mode FNC1 lain telah diatur sebelumnya, maka akan diganti. |
| [AddPlainCodetext](../extcodetextbuilder/addplaincodetext/)(System::String) | Menambahkan codetext biasa ke item codetext yang diperluas |
| [Clear](./clear/)() override | Menghapus item codetext yang diperluas |
| [ExtCodetextBuilder](../extcodetextbuilder/extcodetextbuilder/)() |  |
| [GetExtendedCodetext](./getextendedcodetext/)() override | Menghasilkan Extended codetext dari daftar extended codetext. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/)() |  |
## Catatan


Generator codetext yang diperluas untuk barcode QR 2D untuk Mode ExtendedCodetext dari EncodeMode.

Gunakan properti TwoDDisplayText dari [BarcodeGenerator](../barcodegenerator/) untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

Contoh ini menunjukkan cara menggunakan posisi pertama FNC1 dalam Extended Mode.
```cpp
[C#]
//buat codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//hasilkan codetext
string codetext = TextBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Contoh ini menunjukkan cara menggunakan posisi kedua FNC1 dalam Extended Mode.
```cpp
[C#]
//buat codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456");

//hasilkan codetext
string codetext = TextBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```


Contoh ini menunjukkan cara menggunakan mode multi ECI dalam Extended Mode.
```cpp
[C#]
//buat codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//hasilkan codetext
string codetext = TextBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
    generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Class [ExtCodetextBuilder](../extcodetextbuilder/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
