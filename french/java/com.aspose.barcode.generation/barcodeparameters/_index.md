---
title: "BarcodeParameters"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Paramètres de génération de code-barres."
type: docs
weight: 14
url: /fr/java/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Paramètres de génération de code-barres.
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | Paramètres du code-barres AustralianPost. |
| [getAztec()](#getAztec--) | Paramètres Aztec. |
| [getBarColor()](#getBarColor--) | Couleur des barres. |
| [getBarHeight()](#getBarHeight--) | Hauteur des barres des codes-barres 1D en valeur [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Obtient la valeur de réduction des barres utilisée pour compenser la diffusion d’encre lors de l’impression. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Paramètres Codabar. |
| [getCodablock()](#getCodablock--) | Paramètres Codablock. |
| [getCode128()](#getCode128--) | Paramètres Code128. |
| [getCode16K()](#getCode16K--) | Paramètres Code16K. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Paramètres Codetext. |
| [getCoupon()](#getCoupon--) | Paramètres Coupon. |
| [getDataBar()](#getDataBar--) | Paramètres Databar. |
| [getDataMatrix()](#getDataMatrix--) | Paramètres DataMatrix. |
| [getDotCode()](#getDotCode--) | Paramètres DotCode. |
| [getFilledBars()](#getFilledBars--) | Obtient une valeur indiquant si les barres sont remplies. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Paramètres du GS1 Composite Bar. |
| [getHanXin()](#getHanXin--) | Paramètres HanXin. |
| [getITF()](#getITF--) | Paramètres ITF. |
| [getMaxiCode()](#getMaxiCode--) | Paramètres MaxiCode. |
| [getPadding()](#getPadding--) | Marges du code-barres. |
| [getPatchCode()](#getPatchCode--) | Paramètres PatchCode. |
| [getPdf417()](#getPdf417--) | Paramètres PDF417. |
| [getPostal()](#getPostal--) | Paramètres postaux. |
| [getQR()](#getQR--) | Paramètres QR, MicroQR et RectMicroQR. |
| [getSupplement()](#getSupplement--) | Paramètres de supplément. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Uniquement pour les codes-barres 1D. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Rapport entre les barres larges et les barres étroites. |
| [getXDimension()](#getXDimension--) | La x-dimension est la plus petite largeur de l’unité des barres ou espaces du code-barres. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | Couleur des barres. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Hauteur des barres des codes-barres 1D en valeur [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Définit la valeur de réduction des barres utilisée pour compenser la diffusion d’encre lors de l’impression. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Définit une valeur indiquant si les barres sont remplies. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Paramètres du GS1 Composite Bar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Uniquement pour les codes-barres 1D. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Rapport entre les barres larges et les barres étroites. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | La x-dimension est la plus petite largeur de l’unité des barres ou espaces du code-barres. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


Paramètres du code-barres AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Paramètres Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final Color getBarColor()
```


Couleur des barres. Valeur par défaut : Color.Black.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Hauteur des barres des codes-barres 1D en valeur [Unit](../../com.aspose.barcode.generation/unit). Ignorée si la propriété BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Obtient la valeur de réduction des barres utilisée pour compenser la diffusion d’encre lors de l’impression. Valeur par défaut : 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


Paramètres Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Paramètres Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Paramètres Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Paramètres Code16K.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Paramètres Codetext.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Paramètres du coupon. Utilisé pour UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Paramètres Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


Paramètres DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


Paramètres DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Obtient une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true.

**Returns:**
booléen - une valeur indiquant si les barres sont remplies.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Paramètres du GS1 Composite Bar.

Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le texte de code 1D et le texte de code 2D sont séparés par le symbole '|'.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


Paramètres HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


Paramètres ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


Paramètres MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Marges du code-barres. Valeur par défaut : 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


Paramètres PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


Paramètres PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Paramètres postaux. Utilisés pour Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Paramètres QR, MicroQR et RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Paramètres de supplément. Utilisé pour Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Seulement pour les codes-barres 1D. Si le texte du code est incorrect et que la valeur est définie sur true, une exception sera levée. Sinon le texte du code sera corrigé pour correspondre à la spécification du code-barres. Une exception sera toujours levée pour : la symbologie Databar si le texte du code est incorrect. Une exception ne sera jamais levée pour : AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la symbologie Code128 si le texte du code est incorrect.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Rapport entre barres larges et barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


La x-dimension est la plus petite largeur de l’unité des barres ou espaces du code-barres. L’augmenter augmentera la largeur de l’image du code-barres complet. Ignorée si la propriété BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


Active le chiffre de contrôle lors de la génération des codes-barres 1D.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que.

Le checksum est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum toujours utilisé : le reste des symbologies

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(Color value) {#setBarColor-java.awt.Color-}
```
public final void setBarColor(Color value)
```


Couleur des barres. Valeur par défaut : Color.Black.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.awt.Color |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Hauteur des barres des codes-barres 1D en valeur [Unit](../../com.aspose.barcode.generation/unit). Ignorée si la propriété BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Définit la valeur de réduction des barres utilisée pour compenser la diffusion de l'encre lors de l'impression. Valeur par défaut : 0

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Valeur de réduction des barres utilisée pour compenser la diffusion de l'encre lors de l'impression. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Toujours afficher le chiffre de contrôle dans le texte lisible par l'homme pour les codes-barres Code128 et GS1Code128.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Active le chiffre de contrôle lors de la génération des codes-barres 1D.

Par défaut, il est considéré comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que.

Le checksum est possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum toujours utilisé : le reste des symbologies

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Définit une valeur indiquant si les barres sont remplies. Seulement pour les codes-barres 1D. Valeur par défaut : true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si les barres sont remplies. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Paramètres du GS1 Composite Bar.

Cet exemple montre comment créer et enregistrer une image GS1 Composite Bar. Notez que le texte de code 1D et le texte de code 2D sont séparés par le symbole '|'.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Seulement pour les codes-barres 1D. Si le texte du code est incorrect et que la valeur est définie sur true, une exception sera levée. Sinon le texte du code sera corrigé pour correspondre à la spécification du code-barres. Une exception sera toujours levée pour : la symbologie Databar si le texte du code est incorrect. Une exception ne sera jamais levée pour : AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la symbologie Code128 si le texte du code est incorrect.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Rapport entre barres larges et barres étroites. Valeur par défaut : 3, c’est‑à‑dire que les barres larges sont 3 fois plus larges que les barres étroites. Utilisé pour ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


La x-dimension est la plus petite largeur de l’unité des barres ou espaces du code-barres. L’augmenter augmentera la largeur de l’image du code-barres complet. Ignorée si la propriété BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) est définie sur AutoSizeMode.Nearest ou AutoSizeMode.Interpolation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

