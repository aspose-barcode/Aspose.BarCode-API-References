---
title: "Class DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.Generation.DataMatrixExtCodetextBuilder. Generator kode teks ekstensi untuk kode batang DataMatrix 2D dalam Mode ExtendedCodetext dari EncodeMode"
type: docs
weight: 1210
url: /id/net/aspose.barcode.generation/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

Generator kode teks ekstensi untuk kode batang DataMatrix 2D dalam Mode ExtendedCodetext dari EncodeMode

```csharp
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DataMatrixExtCodetextBuilder](datamatrixextcodetextbuilder/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddCodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addcodetextwithencodemode/)(DataMatrixEncodeMode, string) | Menambahkan kode teks dengan mode enkode yang ditentukan ke item kode teks ekstensi |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Menambahkan kode teks dengan Identifikasi Saluran Diperluas |
| [AddECICodetextWithEncodeMode](../../aspose.barcode.generation/datamatrixextcodetextbuilder/addecicodetextwithencodemode/)(ECIEncodings, DataMatrixEncodeMode, string) | Menambahkan kode teks dengan Identifier Saluran Ekstensi dengan mode enkode yang ditentukan |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Menambahkan kode teks biasa ke item kode teks yang diperluas |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Menghapus item kode teks yang diperluas |
| override [GetExtendedCodetext](../../aspose.barcode.generation/datamatrixextcodetextbuilder/getextendedcodetext/)() | Menghasilkan kode teks Diperluas dari daftar kode teks yang diperluas. |

## Contoh

```csharp
[C#]
//Mode kode teks ekstensi

//buat kode teks
DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
codetextBuilder.AddECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.Bytes, "World");
codetextBuilder.AddPlainCodetext("Will");
codetextBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
codetextBuilder.AddCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");

//hasilkan kode teks
string codetext = textBuilder.GetExtendedCodetext();    

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Lihat Juga

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


