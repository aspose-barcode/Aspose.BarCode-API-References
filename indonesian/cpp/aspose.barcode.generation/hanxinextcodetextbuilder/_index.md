---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder kelas"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan Aspose::BarCode::Generation::HanXinExtCodetextBuilder kelas di C++."
type: docs
weight: 2800
url: /id/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Menambahkan fragmen codetext dalam mode Auto |
| [AddBinary](./addbinary/)(System::String) | Menambahkan fragmen codetext dalam mode Binary |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Menambahkan fragmen codetext dalam [Common](../../aspose.barcode.common/) mode Chinese Region One |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Menambahkan fragmen codetext dalam [Common](../../aspose.barcode.common/) mode Chinese Region Two |
| [AddECI](./addeci/)(System::String, int32_t) | Menambahkan fragmen codetext dalam mode ECI |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Menambahkan fragmen codetext dalam mode GB18030 Four Byte |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Menambahkan fragmen codetext dalam mode GB18030 Two Byte |
| [AddNumeric](./addnumeric/)(System::String) | Menambahkan fragmen codetext dalam mode Numeric |
| [AddText](./addtext/)(System::String) | Menambahkan fragmen codetext dalam mode Text |
| [AddUnicode](./addunicode/)(System::String) | Menambahkan fragmen codetext dalam mode Unicode |
| [AddURI](./adduri/)(System::String) | Menambahkan fragmen codetext dalam mode URI |
| [GetExtendedCodetext](./getextendedcodetext/)() | Mengembalikan codetext dari pembuat codetext mode Ekstensi |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Catatan


Generator codetext ekstensi untuk Han Xin Code untuk Mode Ekstensi dari EncodeMode


```cpp
[C#]
//Mode teks kode yang diperluas
//buat codetext
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

//hasilkan codetext
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

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
