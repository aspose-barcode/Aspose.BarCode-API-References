---
title: "enum"
linktitle: "ECIEncodings"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 6600
url: /sv/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| ISO_8859_1 | 3 | ISO/IEC 8859-1 Latin alfabet nr 1 kodning. ECI Id:"\000003" |
| ISO_8859_2 | 4 | ISO/IEC 8859-2 Latin alfabet nr 2 kodning. ECI Id:"\000004" |
| ISO_8859_3 | 5 | ISO/IEC 8859-3 Latin alfabet nr 3 kodning. ECI Id:"\000005" |
| ISO_8859_4 | 6 | ISO/IEC 8859-4 Latin alfabet nr 4 kodning. ECI Id:"\000006" |
| ISO_8859_5 | 7 | ISO/IEC 8859-5 Latin/kyrillisk alfabetkodning. ECI Id:"\000007" |
| ISO_8859_6 | 8 | ISO/IEC 8859-6 Latin/arabiskt alfabet kodning. ECI Id:"\000008" |
| ISO_8859_7 | 9 | ISO/IEC 8859-7 Latin/grekiskt alfabet kodning. ECI Id:"\000009" |
| ISO_8859_8 | 10 | ISO/IEC 8859-8 Latin/hebreiskt alfabet kodning. ECI Id:"\000010" |
| ISO_8859_9 | 11 | ISO/IEC 8859-9 Latin alfabet nr 5 kodning. ECI Id:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 latinalfabet nr 6 kodning. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 latin/thailändskt alfabet kodning. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 latinalfabet nr 7 (Baltisk kant) kodning. ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 latinalfabet nr 8 (keltiskt) kodning. ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 latinalfabet nr 9 kodning. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 latinalfabet nr 10 kodning. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) kodning. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Centraleuropa) kodning. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 kyrillisk kodning. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 Latin 1 kodning. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 arabisk kodning. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (Högsta byte först) kodning. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 kodning. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 internationell referensversion av ISO 7-bitars kodad teckenuppsättning kodning. ECI Id:"\000027" |
| Big5 | 28 | Big 5 (Taiwan) kodning för kinesisk teckenuppsättning. ECI Id:"\000028" |
| GB2312 | 29 | GB2312 kodning för kinesisk teckenuppsättning. ECI Id:"\000029" |
| EUC_KR | 30 | Koreansk teckenuppsättning kodning. ECI Id:"\000030" |
| GBK | 31 | GBK (utökning av GB2312 för förenklad kinesiska) kodning. ECI Id:"\000031" |
| GB18030 | 32 | GGB18030 kodning för kinesisk teckenuppsättning. ECI Id:"\000032" |
| UTF16LE | 33 | ISO/IEC 10646 UTF-16LE kodning. ECI Id:"\000033" |
| UTF32BE | 34 | ISO/IEC 10646 UTF-32BE kodning. ECI Id:"\000034" |
| UTF32LE | 35 | ISO/IEC 10646 UTF-32LE kodning. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: ISO 7-bitars kodad teckenuppsättning - kodning för invariant teckenuppsättning. ECI Id:"\000170" |
| BINARY | 899 | 8-bitars binär data. ECI Id:"\000899" |
| NONE | 0 | Ingen utökad kanalinterpretation |

## Anmärkningar


Identifierare för utökad kanalinterpretation. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen.

Detta exempel visar hur man använder ECI-kodning och sparar en [BarCode](../../aspose.barcode/) bild.
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = "12345TEXT"
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
        generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
        generator.Save("test.png")
    End Using
```

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
