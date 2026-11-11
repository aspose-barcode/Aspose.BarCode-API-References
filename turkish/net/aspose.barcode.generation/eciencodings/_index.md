---
title: "Enum ECIEncodings"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.ECIEncodings enum. Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Semboldeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya detayları bildirmek için kullanılır."
type: docs
weight: 1270
url: /tr/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Sembol içindeki veriyi kodlamak için kullanılan referanslar hakkında barkod okuyucuya bilgi vermek için kullanılır.

```csharp
public enum ECIEncodings
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 Latin alfabesi No. 1 kodlaması. ECI Id:\"\\000003\" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 Latin alfabesi No. 2 kodlaması. ECI Id:\"\\000004\" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 Latin alfabesi No. 3 kodlaması. ECI Id:\"\\000005\" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 Latin alfabesi No. 4 kodlaması. ECI Id:\"\\000006\" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Latin/Kiril alfabesi kodlaması. ECI Id:\"\\000007\" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Latin/Arap alfabesi kodlaması. ECI Id:\"\\000008\" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 Latin/Yunan alfabesi kodlaması. ECI Id:\"\\000009\" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 Latin/İbranice alfabesi kodlaması. ECI Id:\"\\000010\" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 Latin alfabesi No. 5 kodlaması. ECI Id:\"\\000011\" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 Latin alfabesi No. 6 kodlaması. ECI Id:\"\\000012\" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Latin/Tay alfabesi kodlaması. ECI Id:\"\\000013\" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 Latin alfabesi No. 7 (Baltık Kenarı) kodlaması. ECI Id:\"\\000015\" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 Latin alfabesi No. 8 (Keltik) kodlaması. ECI Id:\"\\000016\" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 Latin alfabesi No. 9 kodlaması. ECI Id:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 Latin alfabesi No. 10 kodlaması. ECI Id:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Ek 1 + JIS X 0201) kodlaması. ECI Id:"\000020" |
| Win1250 | `21` | Windows 1250 Latin 2 (Orta Avrupa) kodlaması. ECI Id:"\000021" |
| Win1251 | `22` | Windows 1251 Kiril kodlaması. ECI Id:"\000022" |
| Win1252 | `23` | Windows 1252 Latin 1 kodlaması. ECI Id:"\000023" |
| Win1256 | `24` | Windows 1256 Arap kodlaması. ECI Id:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (Yüksek sıra baytı önce) kodlaması. ECI Id:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 kodlaması. ECI Id:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 ISO 7-bit kodlu karakter seti kodlamasının Uluslararası Referans Versiyonu. ECI Id:"\000027" |
| Big5 | `28` | Big 5 (Tayvan) Çince Karakter Seti kodlaması. ECI Id:"\000028" |
| GB2312 | `29` | GB2312 Çince Karakter Seti kodlaması. ECI Id:"\000029" |
| EUC_KR | `30` | Kore Karakter Seti kodlaması. ECI Id:"\000030" |
| GBK | `31` | GBK (GB2312'nin Basitleştirilmiş Çince için uzantısı) kodlaması. ECI Id:"\000031" |
| GB18030 | `32` | GGB18030 Çince Karakter Seti kodlaması. ECI Id:"\000032" |
| UTF16LE | `33` | ISO/IEC 10646 UTF-16LE kodlaması. ECI Id:"\000033" |
| UTF32BE | `34` | ISO/IEC 10646 UTF-32BE kodlaması. ECI Id:"\000034" |
| UTF32LE | `35` | ISO/IEC 10646 UTF-32LE kodlaması. ECI Id:"\000035" |
| INVARIANT | `170` | ISO/IEC 646: ISO 7-bit kodlu karakter seti - Değişmez Karakterler seti kodlaması. ECI Id:"\000170" |
| BINARY | `899` | 8-bit ikili veri. ECI Id:"\000899" |
| NONE | `0` | Genişletilmiş Kanal Yorumlaması Yok |

## Örnekler

Bu örnek, ECI kodlamasını nasıl kullanacağınızı ve bir BarCode görüntüsü nasıl kaydedileceğini gösterir.

```csharp
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

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


