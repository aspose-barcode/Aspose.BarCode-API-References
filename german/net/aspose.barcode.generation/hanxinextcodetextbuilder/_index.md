---
title: "Klasse HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder Klasse. Erweiterter Codetext‑Generator für Han‑Xin‑Code im erweiterten Modus von EncodeMode"
type: docs
weight: 1380
url: /de/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Erweiterter Codetext-Generator für Han Xin Code für Extended Mode von EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Fügt Codetext‑Fragment im Auto‑Modus hinzu |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Fügt Codetext‑Fragment im Binär‑Modus hinzu |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Fügt Codetext‑Fragment im Modus Common Chinese Region One hinzu |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Fügt Codetext‑Fragment im Modus Common Chinese Region Two hinzu |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Fügt Codetext‑Fragment im ECI‑Modus hinzu |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Fügt Codetext-Fragment im GB18030 Vier-Byte-Modus hinzu |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Fügt Codetext-Fragment im GB18030 Zwei-Byte-Modus hinzu |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Fügt Codetext-Fragment im numerischen Modus hinzu |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Fügt Codetext-Fragment im Textmodus hinzu |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Fügt Codetext-Fragment im Unicode-Modus hinzu |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Fügt Codetext-Fragment im URI-Modus hinzu |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Gibt den Codetext vom Codetext-Builder im erweiterten Modus zurück |

## Beispiele

```csharp
[C#]
//Extended-Codetext-Modus
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

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


