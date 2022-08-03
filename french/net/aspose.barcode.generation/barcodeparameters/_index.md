---
title: BarcodeParameters
second_title: Référence de l'API Aspose.BarCode pour .NET
description: Paramètres de génération de code-barres.
type: docs
weight: 500
url: /fr/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Paramètres de génération de code-barres.

```csharp
public class BarcodeParameters
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | Paramètres de code-barres AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Paramètres aztèques. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Couleur des barres. Valeur par défaut : Couleur.Noir. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Hauteur des barres des codes-barres 1D dans[`Unit`](../unit) value. Ignoré siAutoSizeMode la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Obtient ou définit la valeur de réduction des barres utilisée pour compenser la propagation de l'encre lors de l'impression. Valeur par défaut : 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Toujours afficher le chiffre de la somme de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Paramètres Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Paramètres Codablock. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Paramètres Code16K. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Paramètres de texte de code. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Paramètres de la barre de données. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | Paramètres DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | Paramètres DotCode. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Indique si explique le caractère "\" comme un caractère d'échappement dans la propriété CodeText. Utilisé pour Pdf417, DataMatrix, Code128 uniquement Si EnableEscape est vrai, "\" sera expliqué comme un caractère d'échappement spécial. Sinon, "\" agit comme des caractères normaux. Aspose.BarCode prend en charge la saisie de code ascii décimal et de mnémonique pour les caractères de code de contrôle ASCII. Par exemple, \013 et \\CR signifie CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Obtient ou définit une valeur indiquant si les barres sont remplies. Uniquement pour les codes-barres 1D. Valeur par défaut : true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | Paramètres de la barre composite GS1. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Activer la somme de contrôle lors de la génération de codes-barres 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | Paramètres ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | Paramètres MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Rembourrages de code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | Paramètres PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | Paramètres PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Paramètres postaux. Utilisé pour Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | Paramètres QR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Paramètres supplémentaires. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Uniquement pour les codes-barres 1D. Si le texte du code est incorrect et que la valeur est définie sur true - une exception sera levée. Sinon, le texte de code sera corrigé pour correspondre à la spécification du code-barres. L'exception sera toujours levée pour : la symbologie de la barre de données si le texte de code est incorrect. L'exception ne sera toujours pas levée pour : AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, la symbologie Code128 si le texte de code est incorrect . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Rapport barres larges/barres étroites. Valeur par défaut : 3, c'est-à-dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | la dimension x est la plus petite largeur de l'unité de barres ou d'espaces du code-barres. Augmenter ceci augmentera la largeur de l'image du code-barres. Ignoré siAutoSizeMode la propriété est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |

### Voir également

* espace de noms [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Assemblée [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
