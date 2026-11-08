---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder class"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder klassen Aspose::BarCode::Generation::HanXinExtCodetextBuilder i C++."
type: docs
weight: 2800
url: /sv/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Lägger till kodtextfragment i Auto-läge |
| [AddBinary](./addbinary/)(System::String) | Lägger till kodtextfragment i Binärt läge |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Lägger till kodtextfragment i [Common](../../aspose.barcode.common/) kinesisk region ett läge |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Lägger till kodtextfragment i [Common](../../aspose.barcode.common/) kinesisk region två läge |
| [AddECI](./addeci/)(System::String, int32_t) | Lägger till kodtextfragment i ECI-läge |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Lägger till kodtextfragment i GB18030 Four Byte‑läge |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Lägger till kodtextfragment i GB18030 Two Byte‑läge |
| [AddNumeric](./addnumeric/)(System::String) | Lägger till kodtextfragment i numeriskt läge |
| [AddText](./addtext/)(System::String) | Lägger till kodtextfragment i textläge |
| [AddUnicode](./addunicode/)(System::String) | Lägger till kodtextfragment i Unicode‑läge |
| [AddURI](./adduri/)(System::String) | Lägger till kodtextfragment i URI-läge |
| [GetExtendedCodetext](./getextendedcodetext/)() | Returnerar kodtext från Extended-läge kodtextbyggare |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Anmärkningar


Utökad kodtextgenerator för Han Xin Code för Extended-läge av EncodeMode


```cpp
[C#]
//Utökad kodtextläge
//skapa kodtext
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

//generera kodtext
var str = codeTextBuilder.GetExtendedCodetext();

//generera
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

## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
