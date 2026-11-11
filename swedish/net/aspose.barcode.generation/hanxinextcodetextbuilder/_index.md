---
title: "Klass HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder-klass. Utökad kodtextgenerator för Han Xin Code för Utökat läge av EncodeMode"
type: docs
weight: 1380
url: /sv/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Utökad kodtextgenerator för Han Xin Code för Utökat läge av EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Lägger till kodtextfragment i Auto-läge |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Lägger till kodtextfragment i Binärt läge |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Lägger till kodtextfragment i Common Chinese Region One-läge |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Lägger till kodtextfragment i Common Chinese Region Two-läge |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Lägger till kodtextfragment i ECI-läge |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Lägger till kodtextfragment i GB18030 Four Byte-läge |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Lägger till kodtextfragment i GB18030 Two Byte-läge |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Lägger till kodtextfragment i Numeriskt läge |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Lägger till kodtextfragment i Textläge |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Lägger till kodtextfragment i Unicode-läge |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Lägger till kodtextfragment i URI-läge |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Returnerar kodtext från Extended-läge kodtextbyggare |

## Exempel

```csharp
[C#]
//Extended kodtextläge
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

### Se även

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


