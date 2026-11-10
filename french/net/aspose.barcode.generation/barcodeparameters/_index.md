---
title: "Classe BarcodeParameters"
second_title: "Référence de l'API Aspose.BarCode pour .NET"
description: "Classe Aspose.BarCode.Generation.BarcodeParameters. Paramètres de génération de code-barres"
type: docs
weight: 1010
url: /fr/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Paramètres de génération de code-barres.

```csharp
public class BarcodeParameters
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | Paramètres du code-barres AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Paramètres Aztec. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Couleur des barres. Valeur par défaut : Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | Hauteur des barres des codes-barres 1D en valeur [`Unit`](../unit/). Ignorée si la propriété [`AutoSizeMode`](../basegenerationparameters/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Obtient ou définit la valeur de réduction des barres qui est utilisée pour compenser la diffusion de l'encre lors de l'impression. Valeur par défaut : 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Paramètres Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Paramètres Codablock. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Paramètres Code128. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Paramètres Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Paramètres du texte de code. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Paramètres de coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Paramètres Databar. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | Paramètres DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | Paramètres DotCode. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Obtient ou définit une valeur indiquant si les barres sont remplies. Uniquement pour les codes-barres 1D. Valeur par défaut : true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | Paramètres GS1. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | Paramètres de la barre composite GS1. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | Paramètres HanXin. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | Activer la somme de contrôle lors de la génération des codes-barres 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | Paramètres ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | Paramètres MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | Paramètres PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | Paramètres PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Paramètres postaux. Utilisé pour Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | Paramètres QR, MicroQR et RectMicroQR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Paramètres supplémentaires. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Uniquement pour les codes-barres 1D. Si le texte du code est incorrect et que la valeur est définie sur true, une exception sera levée. Sinon, le texte du code sera corrigé pour correspondre à la spécification du code-barres. Une exception sera toujours levée pour : la symbologie Databar si le texte du code est incorrect. Une exception ne sera jamais levée pour : AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la symbologie Code128 si le texte du code est incorrect. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Ratio des barres larges aux barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | La x-dimension est la plus petite largeur de l'unité des barres ou espaces du code-barres. L'augmenter augmentera la largeur totale de l'image du code-barres. Ignorée si la propriété [`AutoSizeMode`](../basegenerationparameters/autosizemode/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |

### Voir aussi

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


