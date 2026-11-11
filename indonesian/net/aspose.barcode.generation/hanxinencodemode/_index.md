---
title: "Enum HanXinEncodeMode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Enum Aspose.BarCode.Generation.HanXinEncodeMode. Mode enkoding Han Xin Code. Disarankan menggunakan Auto dengan karakter ASCII / China atau Unicode untuk karakter Unicode"
type: docs
weight: 1360
url: /id/net/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enumeration

Mode enkoding Han Xin Code. Disarankan menggunakan Auto dengan karakter ASCII / China atau Unicode untuk karakter Unicode.

```csharp
public enum HanXinEncodeMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Auto | `0` | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. Karakter Unicode dienkode menggunakan encoding GB18030 sesuai spesifikasi kode batang HanXin. |
| Binary | `1` | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. Jika ditemukan karakter Unicode, sebuah pengecualian akan dilempar. |
| ECI | `2` | Dalam mode ECI, seluruh pesan di-encode ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan identifier ECI. Jika sebuah karakter ditemukan yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian akan dilempar. Harap perhatikan bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| Unicode | `3` | Mode Unicode merancang cara untuk merepresentasikan data teks apa pun yang merujuk pada encoding/charset UTF8 dalam Han Xin Code. |
| URI | `4` | Mode URI menunjukkan bahwa data yang direpresentasikan dalam Han Xin Code adalah Uniform Resource Identifier (URI) yang mengacu pada RFC 3986. |
| Extended | `5` | Mode Extended memungkinkan kombinasi mode internal: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Codetext dapat dibangun secara manual dengan awalan dan backslash ganda, misalnya: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" atau menggunakan HanXinExtCodetextBuilder. Jika codetext berisi fragmen ECI, maka hanya mode berikut yang dapat berada dalam codetext setelah fragmen ECI: Auto, Binary, Text, Numeric, URI, ECI. |

## Contoh

```csharp
[C#]
// Mode Auto
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Mode Binary
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// Mode ECI
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Mode Unicode
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// Mode URI
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Mode Extended
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Menggunakan HanXinExtCodetextBuilder untuk mode Extended (codetext yang sama seperti pada contoh sebelumnya)
//buat kode teks
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//hasilkan kode teks
var str = codeTextBuilder.GetExtendedCodetext();

//hasilkan
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

### Lihat Juga

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


