---
title: MaxiCodeExtCodetextBuilder
second_title: Aspose.BarCode untuk .NET API Referensi
description: Generator codetext yang diperluas untuk kode batang MaxiCode untuk Mode ExtendedCodetext dari MaxiCodeEncodeMode
type: docs
weight: 1040
url: /id/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Generator codetext yang diperluas untuk kode batang MaxiCode untuk Mode ExtendedCodetext dari MaxiCodeEncodeMode

Gunakan properti TwoDDisplayText dari BarcodeGenerator untuk menyetel teks yang terlihat untuk menghapus karakter pengelola.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Konstruktor default. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Menambahkan teks kode dengan Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Menambahkan teks kode biasa ke item teks kode yang diperluas |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Menghapus item teks kode yang diperluas |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Menghasilkan teks kode yang diperluas dari daftar teks kode yang diperluas. |

### Contoh

Contoh ini menunjukkan cara menggunakan MaxiCodeExtCodetextBuilder dalam Extended Mode.

```csharp
[C#]
//membuat teks kode
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

// menghasilkan teks kode
string codetext = textBuilder.GetExtendedCodetext();    

//menghasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Lihat juga

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* ruang nama [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
