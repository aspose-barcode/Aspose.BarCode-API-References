---
title: "Kelas HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.Generation.HanXinExtCodetextBuilder. Generator teks kode yang diperluas untuk Han Xin Code pada Mode Ekstensi EncodeMode"
type: docs
weight: 1380
url: /id/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Generator teks kode yang diperluas untuk Han Xin Code pada Mode Ekstensi EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Konstruktor default. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Menambahkan fragmen teks kode dalam mode Auto |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Menambahkan fragmen teks kode dalam mode Biner |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Menambahkan fragmen teks kode dalam mode Common Chinese Region One |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Menambahkan fragmen teks kode dalam mode Common Chinese Region Two |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Menambahkan fragmen teks kode dalam mode ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Menambahkan fragmen teks kode dalam mode GB18030 Empat Byte |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Menambahkan fragmen teks kode dalam mode GB18030 Dua Byte |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Menambahkan fragmen teks kode dalam mode Numerik |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Menambahkan fragmen teks kode dalam mode Teks |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Menambahkan fragmen teks kode dalam mode Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Menambahkan fragmen teks kode dalam mode URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Mengembalikan teks kode dari pembuat teks kode mode Ekstensi |

## Contoh

```csharp
[C#]
//Mode kode teks ekstensi
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

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//hasilkan kode teks
var str = codeTextBuilder.GetExtendedCodetext();

//hasilkan
using (var bg = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    bg.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    var img = bg.GenerateBarCodeImage();
    using (var r = new BarCodeReader(img, DecodeType.HanXin))
     {
        var found = r.ReadBarCodes();
        Assert.AreEqual(1, found.Length);
        Assert.AreEqual(expectedStr, found[0].CodeText);
      }
}
```

### Lihat Juga

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


