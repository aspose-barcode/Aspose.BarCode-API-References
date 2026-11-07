---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder klasse"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je Aspose::BarCode::Generation::HanXinExtCodetextBuilder klasse in C++."
type: docs
weight: 2800
url: /nl/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Voegt codetextfragment toe in Auto-modus |
| [AddBinary](./addbinary/)(System::String) | Voegt codetextfragment toe in Binaire modus |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Voegt codetextfragment toe in [Gemeenschappelijk](../../aspose.barcode.common/) Chinese Region One-modus |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Voegt codetextfragment toe in [Gemeenschappelijk](../../aspose.barcode.common/) Chinese Region Two-modus |
| [AddECI](./addeci/)(System::String, int32_t) | Voegt codetextfragment toe in ECI-modus |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Voegt codetextfragment toe in GB18030 Vier-Byte-modus |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Voegt codetextfragment toe in GB18030 Twee-Byte-modus |
| [AddNumeric](./addnumeric/)(System::String) | Voegt codetextfragment toe in Numerieke modus |
| [AddText](./addtext/)(System::String) | Voegt codetextfragment toe in Tekstmodus |
| [AddUnicode](./addunicode/)(System::String) | Voegt codetextfragment toe in Unicode-modus |
| [AddURI](./adduri/)(System::String) | Voegt codetextfragment toe in URI-modus |
| [GetExtendedCodetext](./getextendedcodetext/)() | Retourneert codetext van Extended-modus codetext builder |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Opmerkingen


Extended codetextgenerator voor Han Xin Code voor Extended-modus van EncodeMode


```cpp
[C#]
//Uitgebreide codetext-modus
//codetext maken
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

//codetext genereren
var str = codeTextBuilder.GetExtendedCodetext();

//genereren
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

## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
