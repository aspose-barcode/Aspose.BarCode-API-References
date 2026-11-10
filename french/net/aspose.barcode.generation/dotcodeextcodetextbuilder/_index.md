---
title: "Classe DotCodeExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.DotCodeExtCodetextBuilder. Générateur de texte de code étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext de DotCodeEncodeMode"
type: docs
weight: 1250
url: /fr/net/aspose.barcode.generation/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Générateur de texte codé étendu pour les codes-barres 2D DotCode en mode ExtendedCodetext Mode de DotCodeEncodeMode.

```csharp
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DotCodeExtCodetextBuilder](dotcodeextcodetextbuilder/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Ajoute du texte de code avec l'Identifiant de Canal Étendu |
| [AddFNC1FormatIdentifier](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc1formatidentifier/)() | Ajoute l'identifiant de format FNC1 aux éléments de texte de code étendu |
| [AddFNC3ReaderInitialization](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3readerinitialization/)() | Ajoute l'initialisation du lecteur FNC3 aux éléments de texte de code étendu |
| [AddFNC3SymbolSeparator](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addfnc3symbolseparator/)() | Ajoute le séparateur de symbole FNC3 aux éléments de texte de code étendu |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| [AddStructuredAppendMode](../../aspose.barcode.generation/dotcodeextcodetextbuilder/addstructuredappendmode/)(int, int) | Ajoute le mode d'ajout structuré aux éléments de texte de code étendu |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Efface les éléments de texte de code étendu |
| override [GetExtendedCodetext](../../aspose.barcode.generation/dotcodeextcodetextbuilder/getextendedcodetext/)() | Génère le texte de code étendu à partir de la liste de texte de code étendu. |

## Exemples

```csharp
[C#]
//Mode codetext Étendu
//créer du codetext
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC3ReaderInitialization();
textBuilder.AddPlainCodetext("Reader initialization info");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.ExtendedCodetext;
	generator.Save("test.bmp");
}
```

### Voir aussi

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


