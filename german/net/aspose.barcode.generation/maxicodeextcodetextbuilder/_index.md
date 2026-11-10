---
title: "Klasse MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder Klasse. Erweiterter Codetext-Generator für MaxiCode‑Strichcodes für den ExtendedCodetext‑Modus von MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /de/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Erweiterter Codetext-Generator für MaxiCode-Barcodes für ExtendedCodetext Mode von MaxiCodeEncodeMode

Verwenden Sie die Eigenschaft TwoDDisplayText von BarcodeGenerator, um den sichtbaren Text festzulegen, indem verwaltende Zeichen entfernt werden.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Fügt Codetext mit Extended Channel Identifier hinzu |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Löscht erweiterte Codetext-Elemente |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Erzeugt erweiterten Codetext aus der erweiterten Codetext-Liste. |

## Beispiele

Dieses Beispiel zeigt, wie man MaxiCodeExtCodetextBuilder im erweiterten Modus verwendet.

```csharp
[C#]
//Codetext erstellen
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//Codetext generieren
string codetext = textBuilder.GetExtendedCodetext();    

//generieren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Siehe auch

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


