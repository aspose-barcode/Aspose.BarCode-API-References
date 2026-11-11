---
title: "Class AztecExtCodetextBuilder"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder class. Generator kode teks yang diperluas untuk kode batang Aztec untuk Mode ExtendedCodetext dari AztecEncodeMode"
type: docs
weight: 950
url: /id/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Generator kode teks yang diperluas untuk kode batang Aztec untuk Mode ExtendedCodetext dari AztecEncodeMode

Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk mengatur teks yang terlihat dengan menghapus karakter pengelola.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Menambahkan kode teks dengan Identifikasi Saluran Diperluas |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Menambahkan kode teks biasa ke item kode teks yang diperluas |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Menghapus item kode teks yang diperluas |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Menghasilkan kode teks Diperluas dari daftar kode teks yang diperluas. |

## Contoh

Contoh ini menunjukkan cara menggunakan AztecExtCodetextBuilder dalam Mode Diperluas.

```csharp
[C#]
//buat kode teks
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//hasilkan kode teks
string codetext = textBuilder.GetExtendedCodetext();    

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Lihat Juga

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


