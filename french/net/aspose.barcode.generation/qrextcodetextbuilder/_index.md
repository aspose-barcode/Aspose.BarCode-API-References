---
title: "Classe QrExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.QrExtCodetextBuilder. Générateur de texte de code étendu pour les codes-barres QR 2D pour le mode ExtendedCodetext de EncodeMode"
type: docs
weight: 1630
url: /fr/net/aspose.barcode.generation/qrextcodetextbuilder/
---
## QrExtCodetextBuilder class

Générateur de texte codé étendu pour les codes-barres 2D QR en mode ExtendedCodetext Mode de EncodeMode.

Utilisez la propriété TwoDDisplayText de BarcodeGenerator pour définir le texte visible en supprimant les caractères de gestion.

```csharp
public class QrExtCodetextBuilder : ExtCodetextBuilder
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [QrExtCodetextBuilder](qrextcodetextbuilder/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddCodetextWithCompactionMode](../../aspose.barcode.generation/qrextcodetextbuilder/addcodetextwithcompactionmode/)(QrExtCompactionMode, string) | Ajoute du texte de code avec le mode de compaction QR spécifié aux éléments de texte de code étendu. |
| [AddECICodetext](../../aspose.barcode.generation/extcodetextbuilder/addecicodetext/)(ECIEncodings, string) | Ajoute du texte de code avec l'Identifiant de Canal Étendu |
| [AddFNC1FirstPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1firstposition/)() | Définit FNC1 à la première position. Si un autre mode FNC1 avait été défini auparavant, il est remplacé. |
| [AddFNC1GroupSeparator](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1groupseparator/)() | Ajoute le séparateur de groupe (GS - '\\u001D') aux éléments de texte de code étendu |
| [AddFNC1SecondPosition](../../aspose.barcode.generation/qrextcodetextbuilder/addfnc1secondposition/)(string) | Définit FNC1 à la deuxième position. Si un autre mode FNC1 avait été défini auparavant, il est remplacé. |
| [AddPlainCodetext](../../aspose.barcode.generation/extcodetextbuilder/addplaincodetext/)(string) | Ajoute du texte de code simple aux éléments de texte de code étendu |
| override [Clear](../../aspose.barcode.generation/qrextcodetextbuilder/clear/)() | Efface les éléments de texte de code étendu |
| override [GetExtendedCodetext](../../aspose.barcode.generation/qrextcodetextbuilder/getextendedcodetext/)() | Génère le texte de code étendu à partir de la liste de texte de code étendu. |

## Exemples

Cet exemple montre comment utiliser la première position FNC1 en mode étendu.

```csharp
[C#]
//créer du codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1FirstPosition();
TextBuilder.AddPlainCodetext("000%89%%0");
TextBuilder.AddFNC1GroupSeparator();
TextBuilder.AddPlainCodetext("12345<FNC1>");

//générer du codetext
string codetext = TextBuilder.GetExtendedCodetext();

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Cet exemple montre comment utiliser la deuxième position FNC1 en mode étendu.

```csharp
[C#]
//créer du codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddFNC1SecondPosition("12");
TextBuilder.AddPlainCodetext("TRUE3456"); 

//générer du codetext
string codetext = TextBuilder.GetExtendedCodetext();

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

Cet exemple montre comment utiliser le mode multi‑ECI en mode étendu.

```csharp
[C#]
//créer du codetext
QrExtCodetextBuilder TextBuilder = new QrExtCodetextBuilder();
TextBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
TextBuilder.AddECICodetext(ECIEncodings.UTF8, "Right");
TextBuilder.AddECICodetext(ECIEncodings.UTF16BE, "Power");
TextBuilder.AddPlainCodetext(@"t\e\\st");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.AlphaNumeric, @"ASPOSE2001");
TextBuilder.AddCodetextWithCompactionMode(QrExtCompactionMode.Numeric, @"20012026");

//générer du codetext
string codetext = TextBuilder.GetExtendedCodetext();

//générer
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
{
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ExtendedCodetext;
    generator.Parameters.Barcode.QR.ErrorLevel = QRErrorLevel.LevelL;
	generator.CodeText = codetext;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### Voir aussi

* class [ExtCodetextBuilder](../extcodetextbuilder/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


