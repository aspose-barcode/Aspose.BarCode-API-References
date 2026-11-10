---
title: "Classe HanXinExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder class. Générateur de texte de code étendu pour le Han Xin Code en mode étendu d'EncodeMode."
type: docs
weight: 1380
url: /fr/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Générateur de texte codé étendu pour le code Han Xin en mode Extended Mode de EncodeMode.

```csharp
public class HanXinExtCodetextBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Ajoute un fragment de texte de code en mode Auto |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Ajoute un fragment de texte de code en mode Binaire |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Ajoute un fragment de texte de code en mode Common Chinese Region One |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Ajoute un fragment de texte de code en mode Common Chinese Region Two |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Ajoute un fragment de texte de code en mode ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Ajoute un fragment de texte de code en mode GB18030 Four Byte |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Ajoute un fragment de texte de code en mode GB18030 Two Byte |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Ajoute un fragment de texte de code en mode Numérique |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Ajoute un fragment de codetext en mode texte |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Ajoute un fragment de codetext en mode Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Ajoute un fragment de codetext en mode URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Renvoie le codetext du générateur de codetext en mode Étendu |

## Exemples

```csharp
[C#]
//Mode codetext Étendu
//créer du codetext
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

//générer du codetext
var str = codeTextBuilder.GetExtendedCodetext();

//générer
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

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


