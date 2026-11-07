---
title: "enum"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " enum. Mode enkoding untuk kode batang QR dalam C++."
type: docs
weight: 8100
url: /id/cpp/aspose.barcode.generation/qrencodemode/
---
## QREncodeMode enum


Mode enkoding untuk barcode QR.

```cpp
enum class QREncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Otomatis | 0 | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dienkode dalam mode kanji jika memungkinkan, atau mereka dienkode ulang dengan enkoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh enkoding ECI yang dipilih, sebuah pengecualian akan dilempar. |
| Extended | 6 |  |
| Biner | 7 | Dalam mode Biner, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | 8 | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding ECIEncoding yang ditentukan dengan penyisipan identifier ECI. Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilemparkan. Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. Mode ini tidak didukung oleh MicroQR barcodes. |

## Catatan


Contoh-contoh ini menunjukkan cara meng-encode dan menyimpan QR barcode dengan format data yang diperluas.
```cpp
//Contoh ini menunjukkan cara menggunakan encoding ECI dan menyimpan gambar BarCode.

[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = "12345TEXT"
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
        generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8
        generator.Save("test.png")
    End Using

//Contoh ini menunjukkan cara menggunakan posisi pertama FNC1 dalam Extended Mode.

Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
It is better to use QrExtCodetextBuilder for extended codetext generation.
Use Display2DText property to set visible text by removing managing characters.
Encoding Principles:
All symbols "\" must be doubled "\\" in the codetext.
FNC1 in first position is set in codetext as "<FNC1>".
FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
Group Separator for FNC1 modes is set as 0x1D character '\u001D'.
If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
To switch from another ECI mode to the default ECI mode, use "\000003".
All unicode characters after ECI identifier are automatically encoded into correct character codeset.
QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
"\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
The default compaction mode is "\auto".
Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
This mode is not supported by MicroQR barcodes.

[C#]
//buat codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1FirstPosition();
textBuilder.AddPlainCodetext("000%89%%0");
textBuilder.AddFNC1GroupSeparator();
textBuilder.AddPlainCodetext("12345<FNC1>");
//buat kode batang
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
    [VB.NET]
    'create codetext
    Dim textBuilder As New QrExtCodetextBuilder()
    textBuilder.AddFNC1FirstPosition()
    textBuilder.AddPlainCodetext("000%89%%0")
    textBuilder.AddFNC1GroupSeparator()
    textBuilder.AddPlainCodetext("12345<FNC1>")
    'generate barcode
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = textBuilder.GetExtendedCodetext()
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
        generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
        generator.Save("test.png")
    End Using

//Contoh ini menunjukkan cara menggunakan posisi kedua FNC1 dalam Extended Mode.

[C#]
//buat codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddFNC1SecondPosition("12");
textBuilder.AddPlainCodetext("TRUE3456");
//buat kode batang
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
    [VB.NET]
    'create codetext
    Dim textBuilder As New QrExtCodetextBuilder()
textBuilder.AddFNC1SecondPosition("12")
textBuilder.AddPlainCodetext("TRUE3456")
    'generate barcode
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = textBuilder.GetExtendedCodetext()
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
        generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
        generator.Save("test.png")
    End Using

//Contoh ini menunjukkan cara menggunakan mode multi ECI dalam Extended Mode.

[C#]
//buat codetext
QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
textBuilder.AddPlainCodetext(@"t\e\\st");
textBuilder.AddAlphaNumericCodetext(@"ASPOSE2001");
textBuilder.AddNumericCodetext(@"20012026");

//buat kode batang
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = textBuilder.GetExtendedCodetext();
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
    generator.Save(@"d:\test.png");
}
    [VB.NET]
    'create codetext
    Dim textBuilder As New QrExtCodetextBuilder()
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will")
textBuilder.AddECICodetext(ECIEncodings.UTF8, "Right")
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power")
textBuilder.AddPlainCodetext(@"t\e\\st")
textBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
textBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");
@verbatim
'generate barcode
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = textBuilder.GetExtendedCodetext()
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.Extended
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text"
    generator.Save("test.png")
End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
