---
title: "Klasse MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.MaxiCodeExtCodetextBuilder klasse. Uitgebreide codetextgenerator voor MaxiCode-barcodes voor de ExtendedCodetext-modus van MaxiCodeEncodeMode"
type: docs
weight: 1470
url: /nl/net/aspose.barcode.generation/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Uitgebreide codetekstgenerator voor MaxiCode-barcodes voor ExtendedCodetext Mode van MaxiCodeEncodeMode

Gebruik de TwoDDisplayText-eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen door beheertekens te verwijderen.

```csharp
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](maxicodeextcodetextbuilder/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Voegt codetext toe met Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Voegt platte codetext toe aan de uitgebreide codetextitems |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Leegt uitgebreide codetextitems |
| override [GetExtendedCodetext](../../aspose.barcode.generation/maxicodeextcodetextbuilder/getextendedcodetext/)() | Genereert Extended codetext uit de uitgebreide codetextlijst. |

## Voorbeelden

Dit voorbeeld toont hoe MaxiCodeExtCodetextBuilder te gebruiken in de Extended-modus.

```csharp
[C#]
//codetext maken
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();    

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Zie ook

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


