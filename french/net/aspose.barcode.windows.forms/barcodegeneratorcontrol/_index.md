---
title: "Classe BarCodeGeneratorControl"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl. Contrôle Windows BarCode allez dans votre panneau boîte à outils et ajoutez Aspose.BarCode.dll et vous verrez apparaître BarcodeGeneratorControl. Il suffit de le faire glisser et de le déposer sur votre formulaire Windows. voir  voir"
type: docs
weight: 1800
url: /fr/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

Contrôle BarCode Windows, allez à votre panneau de boîte à outils et ajoutez Aspose.BarCode.dll, et vous verrez apparaître BarcodeGeneratorControl. Il suffit de le faire glisser et de le déposer sur votre formulaire Windows. see  see

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Obtient ou définit le mode selon lequel le code-barres redimensionne automatiquement. La valeur par défaut est AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Couleur d'arrière-plan de l'image du code-barres. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | Hauteur de l’image BarCode lorsque la propriété [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Obtient ou définit les paramètres de remplissage du code-barres [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | Type d’encodage du BarCode (symbologie). Utilisez [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) pour obtenir la symbologie actuelle. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | Largeur de l’image BarCode lorsque la propriété [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Couleur des barres. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | Hauteur des barres des codes-barres 1D. Ignorée si la propriété [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Obtient ou définit les paramètres de bordure [`BorderParameters`](../../aspose.barcode.generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | Légende au-dessus de l’image BarCode. Voir [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | Légende en dessous de l’image BarCode. Voir [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Données à encoder, différents types de BarCode peuvent avoir des restrictions de longueur de CodeText différentes. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | Obtient ou définit les paramètres CodeText [`CodetextParametersUI`](../codetextparametersui/). |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | Type d’encodage du BarCode (symbologie). Utilisez [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) pour obtenir la symbologie actuelle. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Obtient ou définit une valeur indiquant si les barres sont remplies. Uniquement pour les codes-barres 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | Activer la somme de contrôle lors de la génération des codes-barres 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | Obtient ou définit la résolution de l’image BarCode. Une valeur pour les deux dimensions. Valeur par défaut : 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | Angle de rotation de l'image BarCode, mesuré en degrés, par ex. RotationAngle = 0 ou RotationAngle = 360 signifie aucune rotation. Si RotationAngle n'est PAS égal à 90, 180, 270 ou 0, cela peut augmenter la difficulté pour le scanner de lire l'image. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Paramètres spécifiques |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Uniquement pour les codes-barres 1D. Si le codetext est incorrect et que la valeur est définie sur true, une exception sera levée. Sinon le codetext sera corrigé pour correspondre à la spécification du code-barres. Une exception sera toujours levée pour : la symbologie Databar si le codetext est incorrect. Une exception ne sera jamais levée pour : AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, la symbologie Code128 si le codetext est incorrect. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Obtient ou définit une valeur indiquant si le mode anti-aliasing est utilisé pour rendre l'image. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Ratio des barres larges aux barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | La X-dimension est la plus petite largeur de l’unité des barres ou espaces du BarCode. L’augmenter augmentera la largeur de l’image du code-barres complet. Ignoré si la propriété [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |

### Voir aussi

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


