---
title: BarCodeGeneratorControl
second_title: Référence de l'API Aspose.BarCode pour .NET
description: BarCode Windows Control accédez au panneau de votre boîte à outils et ajoutez Aspose.BarCode.dll et vous verrez BarcodeGeneratorControl apparaître. Faites-le simplement glisser et déposez-le sur votre formulaire Windows. voir voir
type: docs
weight: 1050
url: /fr/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, accédez au panneau de votre boîte à outils et ajoutez Aspose.BarCode.dll, et vous verrez BarcodeGeneratorControl apparaître. Faites-le simplement glisser et déposez-le sur votre formulaire Windows. voir voir

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Obtient ou définit le mode par lequel le code-barres se redimensionne automatiquement. La valeur par défaut est AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Couleur de fond de l'image du code-barres. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | Hauteur de l'image du code-barres lorsque[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Obtient ou définit les paramètres de rembourrage de code-barres[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Type d'encodage de BarCode (symbologie). Utilisation[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) pour obtenir la symbologie actuelle. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Largeur de l'image du code-barres lorsque[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Couleur des barres. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Hauteur des barres des codes-barres 1D. Ignoré si[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Obtient ou définit les paramètres de bordure[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Légende Au-dessus de l'image du code-barres. Voir[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Légende Sous l'image du code-barres. Voir[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Toujours afficher le chiffre de la somme de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Données à encoder, différents types de BarCode peuvent avoir différentes restrictions de longueur de CodeText. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Obtient ou définit les paramètres CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Indique si explique le caractère "\" comme un caractère d'échappement dans la propriété CodeText. Utilisé pour Pdf417, DataMatrix, Code128 uniquement Si EnableEscape est vrai, "\" sera expliqué comme un caractère d'échappement spécial. Sinon, "\" agit comme des caractères normaux. Aspose.BarCode prend en charge la saisie de code ascii décimal et de mnémonique pour les caractères de code de contrôle ASCII. Par exemple, \013 et \\CR signifie CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Type d'encodage de BarCode (symbologie). Utilisation[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) pour obtenir la symbologie actuelle. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Obtient ou définit une valeur indiquant si les barres sont remplies. Uniquement pour les codes-barres 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Activer la somme de contrôle lors de la génération de codes-barres 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Obtient ou définit la résolution de l'image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | Angle de rotation de l'image du code-barres, mesuré en degrés, par exemple RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle N'EST PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Paramètres spécifiques |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Uniquement pour les codes-barres 1D. Si le texte du code est incorrect et que la valeur est définie sur true - une exception sera levée. Sinon, le texte de code sera corrigé pour correspondre à la spécification du code-barres. L'exception sera toujours levée pour : la symbologie de la barre de données si le texte de code est incorrect. L'exception ne sera toujours pas levée pour : AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, la symbologie Code128 si le texte de code est incorrect . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Rapport barres larges/barres étroites. Valeur par défaut : 3, c'est-à-dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | La dimension X est la plus petite largeur de l'unité de barres ou d'espaces de code-barres. Augmenter ceci augmentera la largeur totale de l'image du code-barres. Ignoré si[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |

### Voir également

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* espace de noms [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
