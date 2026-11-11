---
title: "Class HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder class. Uitgebreide codetekstgenerator voor Han Xin Code voor de Extended-modus van EncodeMode."
type: docs
weight: 1380
url: /nl/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Uitgebreide codetekstgenerator voor Han Xin Code voor Extended Mode van EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Voegt codetekstfragment toe in Auto-modus |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Voegt codetekstfragment toe in Binaire modus |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Voegt codetekstfragment toe in Common Chinese Region One-modus |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Voegt codetekstfragment toe in Common Chinese Region Two-modus |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Voegt codetekstfragment toe in ECI-modus |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Voegt codetekstfragment toe in GB18030 Four Byte-modus |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Voegt codetekstfragment toe in GB18030 Two Byte-modus |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Voegt codetekstfragment toe in Numerieke modus |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Voegt codetekstfragment toe in Tekstmodus |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Voegt codetekstfragment toe in Unicode-modus |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Voegt codetekstfragment toe in URI-modus |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Retourneert codetekst van de Extended-modus codetekstbouwer |

## Voorbeelden

```csharp
[C#]
//Extended codetext-modus
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

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


