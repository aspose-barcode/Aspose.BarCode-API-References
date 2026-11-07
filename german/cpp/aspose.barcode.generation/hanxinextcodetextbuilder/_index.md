---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder Klasse"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "So verwenden Sie die Klasse Aspose::BarCode::Generation::HanXinExtCodetextBuilder in C++."
type: docs
weight: 2800
url: /de/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Fügt Codetext-Fragment im Auto-Modus hinzu |
| [AddBinary](./addbinary/)(System::String) | Fügt Codetext-Fragment im Binärmodus hinzu |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Fügt Codetext-Fragment im [Common](../../aspose.barcode.common/) Chinese Region One-Modus hinzu |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Fügt Codetext-Fragment im [Common](../../aspose.barcode.common/) Chinese Region Two-Modus hinzu |
| [AddECI](./addeci/)(System::String, int32_t) | Fügt Codetext-Fragment im ECI-Modus hinzu |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Fügt Codetext-Fragment im GB18030 Four Byte-Modus hinzu |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Fügt Codetext-Fragment im GB18030 Two Byte-Modus hinzu |
| [AddNumeric](./addnumeric/)(System::String) | Fügt Codetext-Fragment im Numerischen Modus hinzu |
| [AddText](./addtext/)(System::String) | Fügt Codetext-Fragment im Textmodus hinzu |
| [AddUnicode](./addunicode/)(System::String) | Fügt Codetext-Fragment im Unicode-Modus hinzu |
| [AddURI](./adduri/)(System::String) | Fügt Codetext-Fragment im URI-Modus hinzu |
| [GetExtendedCodetext](./getextendedcodetext/)() | Gibt Codetext vom Codetext-Builder im erweiterten Modus zurück |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Hinweise


Erweiterter Codetext-Generator für Han Xin Code für den erweiterten Modus von EncodeMode


```cpp
[C#]
//Erweiterter Codetext-Modus
//Codetext erstellen
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

//Codetext generieren
var str = codeTextBuilder.GetExtendedCodetext();

//generieren
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

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
