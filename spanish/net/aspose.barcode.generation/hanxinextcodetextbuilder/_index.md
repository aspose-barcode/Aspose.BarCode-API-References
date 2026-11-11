---
title: "Clase HanXinExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder class. Generador de codetexto extendido para Han Xin Code en el Modo Extendido de EncodeMode."
type: docs
weight: 1380
url: /es/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Generador de codetexto extendido para Han Xin Code para Extended Mode de EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Agrega fragmento de codetexto en modo Auto |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Agrega fragmento de codetexto en modo Binario |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Agrega fragmento de codetexto en modo Common Chinese Region One |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Agrega fragmento de codetexto en modo Common Chinese Region Two |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Agrega fragmento de codetexto en modo ECI |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Agrega fragmento de codetexto en modo GB18030 Four Byte |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Agrega fragmento de codetexto en modo GB18030 Two Byte |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Agrega fragmento de codetexto en modo Numérico |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Agrega fragmento de texto de código en modo Texto |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Agrega fragmento de texto de código en modo Unicode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Agrega fragmento de texto de código en modo URI |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Devuelve el texto de código del generador de texto de código en modo Extendido |

## Ejemplos

```csharp
[C#]
//Modo codetext Extendido
//crear codetext
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

//generar codetext
var str = codeTextBuilder.GetExtendedCodetext();

//generar
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

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


