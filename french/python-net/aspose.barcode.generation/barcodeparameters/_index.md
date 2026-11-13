---
title: "BarcodeParameters"
second_title: "Référence de l'API Aspose.BarCode pour Python via .NET"
description: 
type: docs
url: /fr/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Paramètres de génération de codes-barres.

Le type BarcodeParameters expose les membres suivants :
## Properties
| Name | Description |
| :- | :- |
| x_dimension | x-dimension est la largeur minimale de l'unité des barres ou espaces du code-barres.<br/>            L'augmenter augmentera la largeur totale de l'image du code-barres.<br/>            Ignoré si la propriété [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| bar_height | Hauteur des barres des codes-barres 1D en valeur [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Ignoré si la propriété [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation. |
| bar_color | Couleur des barres.<br/>            Valeur par défaut : Color.Black. |
| padding | Marges du code-barres.<br/>            Valeur par défaut : 5pt 5pt 5pt 5pt. |
| checksum_always_show | Afficher toujours le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Uniquement pour les codes-barres 1D.<br/>            Si le texte du code est incorrect et que la valeur est définie sur true, une exception sera levée. Sinon le texte du code sera corrigé pour correspondre à la spécification du code-barres.<br/>            Une exception sera toujours levée pour : Databar symbology si le texte du code est incorrect.<br/>            Une exception ne sera jamais levée pour : AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology si le texte du code est incorrect. |
| wide_narrow_ratio | Ratio des barres larges aux barres étroites.<br/>            Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites.<br/>            Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Paramètres Codetext. |
| filled_bars | Obtient ou définit une valeur indiquant si les barres sont remplies.<br/>            Uniquement pour les codes-barres 1D.<br/>            Valeur par défaut : true. |
| bar_width_reduction | Obtient ou définit la valeur de réduction des barres utilisée pour compenser la diffusion d’encre lors de l’impression.<br/>            Valeur par défaut : 0 |
| postal | Paramètres postaux. Utilisé pour Postnet, Planet. |
| patch_code | Paramètres PatchCode. |
| australian_post | Paramètres du code-barres AustralianPost. |
| data_bar | Paramètres Databar. |
| gs1_composite_bar | Paramètres de la barre composite GS1. |
| codablock | Paramètres Codablock. |
| data_matrix | Paramètres DataMatrix. |
| code_16k | Paramètres Code16K. |
| dot_code | Paramètres DotCode. |
| itf | Paramètres ITF. |
| pdf417 | Paramètres PDF417. |
| qr | Paramètres QR, MicroQR et RectMicroQR. |
| supplément | Paramètres de supplément. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Paramètres MaxiCode. |
| aztec | Paramètres Aztec. |
| code128 | Paramètres Code128. |
| codabar | Paramètres Codabar. |
| coupon | Paramètres Coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | Paramètres HanXin. |
| gs1 | Paramètres GS1. |

### Voir aussi

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

