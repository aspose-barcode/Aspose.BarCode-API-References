---
title: "Classe AztecExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.AztecExtCodetextBuilder. Générateur de texte de code étendu pour les codes-barres Aztec en mode ExtendedCodetext du AztecEncodeMode"
type: docs
weight: 950
url: /fr/net/aspose.barcode.generation/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

Générateur de texte de code étendu pour les codes-barres Aztec en mode ExtendedCodetext du AztecEncodeMode

Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion.

```csharp
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AztecExtCodetextBuilder](aztecextcodetextbuilder/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Ajoute du texte de code avec l'Identifiant de Canal Étendu |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| virtual [Clear](../../aspose.barcode.generation/extcodetextbuilder/clear/)() | Efface les éléments de texte de code étendu |
| override [GetExtendedCodetext](../../aspose.barcode.generation/aztecextcodetextbuilder/getextendedcodetext/)() | Génère le texte de code étendu à partir de la liste de texte de code étendu. |

## Exemples

Cet exemple montre comment utiliser AztecExtCodetextBuilder en mode Étendu.

```csharp
[C#]
//créer du codetext
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//générer du codetext
string codetext = textBuilder.GetExtendedCodetext();    

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Voir aussi

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


