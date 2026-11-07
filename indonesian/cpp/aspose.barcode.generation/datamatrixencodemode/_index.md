---
title: "enum"
linktitle: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "enum. Mode pengkodean encoder DataMatrix, default ke Auto dalam C++."
type: docs
weight: 6300
url: /id/cpp/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enum


Mode enkoding encoder DataMatrix, default ke Auto

```cpp
enum class DataMatrixEncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| ASCII | 1 | Mengenkripsi satu karakter alfanumerik atau dua karakter numerik per byte |
| C40 | 8 | Menggunakan enkoding C40. Mengenkripsi alfanumerik huruf besar, huruf kecil, dan karakter khusus |
| Teks | 9 | Menggunakan enkoding Text. Mengenkripsi alfanumerik huruf kecil, huruf besar, dan karakter khusus |
| EDIFACT | 10 | Menggunakan enkoding EDIFACT. Menggunakan enam bit per karakter, mengenkripsi digit, huruf besar, dan banyak tanda baca, tetapi tidak mendukung huruf kecil. |
| ANSIX12 | 11 | Menggunakan enkoding ANSI X12. |
| Extended | 13 |  |
| Base256 | 14 | Enkode nilai 8 bit |
| Biner | 15 | Dalam mode Biner, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | 16 | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |

## Catatan


Contoh ini menunjukkan cara melakukan codetext dalam Mode Extended.
```cpp
[C#]
//Mode Auto
string codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix, codetext))
{
    generator.Parameters.Barcode.DataMatrix.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Mode Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DataMatrix))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}


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
    generator.Parameters.Barcode.DataMatrix.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
