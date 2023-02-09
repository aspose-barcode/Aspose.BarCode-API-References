---
title: ECIEncodings
second_title: Aspose.BarCode for .NET API Referansı
description: Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Semboldeki verileri kodlamak için kullanılan referanslar hakkında barkod okuyucu ayrıntılarını anlatmak için kullanılır. Mevcut uygulama tüm iyi bilinen karakter seti kodlamalarını içerir. Şu anda sadece QR 2D barkodu için kullanılmaktadır.
type: docs
weight: 700
url: /tr/net/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enumeration

Genişletilmiş Kanal Yorumlama Tanımlayıcıları. Semboldeki verileri kodlamak için kullanılan referanslar hakkında barkod okuyucu ayrıntılarını anlatmak için kullanılır. Mevcut uygulama tüm iyi bilinen karakter seti kodlamalarını içerir. Şu anda sadece QR 2D barkodu için kullanılmaktadır.

```csharp
public enum ECIEncodings
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ISO_8859_1 | `3` | ISO/IEC 8859-1 Latin alfabesi No. 1 kodlama. ECI Kimliği:"\000003" |
| ISO_8859_2 | `4` | ISO/IEC 8859-2 Latin alfabesi No. 2 kodlama. ECI Kimliği:"\000004" |
| ISO_8859_3 | `5` | ISO/IEC 8859-3 Latin alfabesi No. 3 kodlama. ECI Kimliği:"\000005" |
| ISO_8859_4 | `6` | ISO/IEC 8859-4 Latin alfabesi No. 4 kodlama. ECI Kimliği:"\000006" |
| ISO_8859_5 | `7` | ISO/IEC 8859-5 Latin/Kiril alfabesi kodlaması. ECI Kimliği:"\000007" |
| ISO_8859_6 | `8` | ISO/IEC 8859-6 Latin/Arap alfabesi kodlaması. ECI Kimliği:"\000008" |
| ISO_8859_7 | `9` | ISO/IEC 8859-7 Latin/Yunan alfabesi kodlaması. ECI Kimliği:"\000009" |
| ISO_8859_8 | `10` | ISO/IEC 8859-8 Latin/İbrani alfabesi kodlaması. ECI Kimliği:"\000010" |
| ISO_8859_9 | `11` | ISO/IEC 8859-9 Latin alfabesi No. 5 kodlama. ECI Kimliği:"\000011" |
| ISO_8859_10 | `12` | ISO/IEC 8859-10 Latin alfabesi No. 6 kodlama. ECI Kimliği:"\000012" |
| ISO_8859_11 | `13` | ISO/IEC 8859-11 Latin/Tay alfabesi kodlaması. ECI Kimliği:"\000013" |
| ISO_8859_13 | `15` | ISO/IEC 8859-13 Latin alfabesi No. 7 (Baltık Bölgesi) kodlaması. ECI Kimliği:"\000015" |
| ISO_8859_14 | `16` | ISO/IEC 8859-14 Latin alfabesi No. 8 (Kelt) kodlaması. ECI Kimliği:"\000016" |
| ISO_8859_15 | `17` | ISO/IEC 8859-15 Latin alfabesi No. 9 kodlama. ECI Kimliği:"\000017" |
| ISO_8859_16 | `18` | ISO/IEC 8859-16 Latin alfabesi No. 10 kodlama. ECI Kimliği:"\000018" |
| Shift_JIS | `20` | Shift JIS (JIS X 0208 Ek 1 + JIS X 0201) kodlaması. ECI Kimliği:"\000020" |
| Win1250 | `21` | Windows 1250 Latin 2 (Orta Avrupa) kodlaması. ECI Kimliği:"\000021" |
| Win1251 | `22` | Windows 1251 Kiril kodlaması. ECI Kimliği:"\000022" |
| Win1252 | `23` | Windows 1252 Latin 1 kodlaması. ECI Kimliği:"\000023" |
| Win1256 | `24` | Windows 1256 Arapça kodlama. ECI Kimliği:"\000024" |
| UTF16BE | `25` | ISO/IEC 10646 UCS-2 (önce yüksek sıralı bayt) kodlaması. ECI Kimliği:"\000025" |
| UTF8 | `26` | ISO/IEC 10646 UTF-8 kodlaması. ECI Kimliği:"\000026" |
| US_ASCII | `27` | ISO/IEC 646:1991 ISO 7 bit kodlu karakter seti kodlamasının Uluslararası Referans Sürümü. ECI Kimliği:"\000027" |
| Big5 | `28` | Big 5 (Tayvan) Çince Karakter Seti kodlaması. ECI Kimliği:"\000028" |
| GB18030 | `29` | GB (PRC) Çince Karakter Seti kodlaması. ECI Kimliği:"\000029" |
| EUC_KR | `30` | Korece Karakter Seti kodlaması. ECI Kimliği:"\000030" |
| NONE | `0` | Genişletilmiş Kanal Yorumu Yok |

### Örnekler

Bu örnek, ECI kodlamasının nasıl kullanılacağını ve bir BarCode görüntüsünün nasıl kaydedileceğini gösterir.

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR;
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
    generator.CodeText = "12345TEXT"
    generator.Parameters.Barcode.QR.QrEncodeMode = QREncodeMode.ECIEncoding
    generator.Parameters.Barcode.QR.QrEncodeType = QREncodeType.ForceQR
    generator.Parameters.Barcode.QR.QrECIEncoding = ECIEncodings.UTF8
    generator.Save("test.png")
End Using
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->