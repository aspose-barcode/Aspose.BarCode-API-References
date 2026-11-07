---
title: "enum"
linktitle: "DotCodeEncodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode enkoding untuk barcode DotCode di C++."
type: docs
weight: 6500
url: /id/cpp/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enum


Mode enkoding untuk kode batang DotCode.

```cpp
enum class DotCodeEncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| Biner | 3 | Dalam mode Biner, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | 4 | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| Extended | 5 |  |

## Catatan



```cpp
[C#]
//Mode otomatis dengan makro
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Mode Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Mode Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Mode teks kode yang diperluas
//buat codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//hasilkan codetext
string codetext = textBuilder.GetExtendedCodetext();

//hasilkan
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
