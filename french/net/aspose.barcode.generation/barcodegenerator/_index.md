---
title: "Classe BarcodeGenerator"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.BarcodeGenerator. BarcodeGenerator pour la génération d'images de codes-barres côté serveur"
type: docs
weight: 1000
url: /fr/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator pour la génération d'images de codes-barres côté serveur.

symbologies prises en charge: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Crée une instance de BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Crée une instance de BarcodeGenerator. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Type de symbologie du code-barres. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Texte à encoder. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Paramètres de génération. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Importe les propriétés BarCode depuis le flux XML spécifié et crée une instance de BarcodeGenerator. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Importe les propriétés BarCode depuis le fichier XML spécifié et crée une instance de BarcodeGenerator. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Dessine l'image du code-barres sur le canvas WPF. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Exporte les propriétés BarCode vers le flux XML spécifié |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Exporte les propriétés BarCode vers le fichier XML spécifié |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Génère l'image du code-barres avec les paramètres actuels. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Enregistre l'image du code-barres dans un fichier spécifique. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Enregistre l'image du code-barres dans un flux dans un format spécifique. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Définit le texte du code comme une séquence d'octets. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge, la fonction insère automatiquement un [marque d'ordre d'octet (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Encode le texte Unicode **codeText** en une séquence d'octets en utilisant l'**encoding** spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le prend en charge et que **insertBOM** est défini sur `true`, la fonction inclut un [marque d'ordre d'octet (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |

## Exemples

Cet exemple montre comment créer et enregistrer une image de code-barres.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


