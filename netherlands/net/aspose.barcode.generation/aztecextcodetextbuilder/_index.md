---
title: "Klasse AztecExtCodetextBuilder"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.AztecExtCodetextBuilder klasse. Uitgebreide codetextgenerator voor Aztec-streepjescodes voor de ExtendedCodetext-modus van AztecEncodeMode"
type: docs
weight: 950
url: /nl/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Uitgebreide codetext‑generator voor Aztec‑barcodes voor de ExtendedCodetext‑modus van AztecEncodeMode

Gebruik de TwoDDisplayText-eigenschap van BarcodeGenerator om de zichtbare tekst in te stellen door beheertekens te verwijderen.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | De standaardconstructor. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Voegt codetext toe met Extended Channel Identifier |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Voegt platte codetext toe aan de uitgebreide codetextitems |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Leegt uitgebreide codetextitems |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Genereert Extended codetext uit de uitgebreide codetextlijst. |

## Voorbeelden

Dit voorbeeld toont hoe AztecExtCodetextBuilder te gebruiken in Extended-modus.

```csharp
[C#]
//codetext maken
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//codetext genereren
string codetext = textBuilder.GetExtendedCodetext();    

//genereren
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Zie ook

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


