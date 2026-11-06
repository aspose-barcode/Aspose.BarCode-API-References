---
title: "BarcodeParameters"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Parametri di generazione del codice a barre."
type: docs
weight: 14
url: /it/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parametri di generazione del codice a barre.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | Parametri del codice a barre AustralianPost. |
| [getAztec()](#getAztec--) | Parametri Aztec. |
| [getBarColor()](#getBarColor--) | Colore delle barre. |
| [getBarHeight()](#getBarHeight--) | Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Ottieni il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Parametri Codabar. |
| [getCodablock()](#getCodablock--) | Parametri Codablock. |
| [getCode128()](#getCode128--) | Parametri Code128. |
| [getCode16K()](#getCode16K--) | Parametri Code16K. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Parametri del testo del codice. |
| [getCoupon()](#getCoupon--) | Parametri del coupon. |
| [getDataBar()](#getDataBar--) | Parametri Databar. |
| [getDataMatrix()](#getDataMatrix--) | Parametri DataMatrix. |
| [getDotCode()](#getDotCode--) | Parametri DotCode. |
| [getFilledBars()](#getFilledBars--) | Ottiene un valore che indica se le barre sono riempite. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Parametri della barra composita GS1. |
| [getHanXin()](#getHanXin--) | Parametri HanXin. |
| [getITF()](#getITF--) | Parametri ITF. |
| [getMaxiCode()](#getMaxiCode--) | Parametri MaxiCode. |
| [getPadding()](#getPadding--) | Spaziatura del codice a barre. |
| [getPatchCode()](#getPatchCode--) | Parametri PatchCode. |
| [getPdf417()](#getPdf417--) | Parametri PDF417. |
| [getPostal()](#getPostal--) | Parametri postali. |
| [getQR()](#getQR--) | Parametri QR, MicroQR e RectMicroQR. |
| [getSupplement()](#getSupplement--) | Parametri supplementari. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Solo per codici a barre 1D. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Rapporto tra barre larghe e barre strette. |
| [getXDimension()](#getXDimension--) | La x-dimension è la larghezza minima dell'unità delle barre o degli spazi del codice a barre. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Colore delle barre. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Imposta un valore che indica se le barre sono riempite. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Parametri della barra composita GS1. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Solo per codici a barre 1D. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Rapporto tra barre larghe e barre strette. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | La x-dimension è la larghezza minima dell'unità delle barre o degli spazi del codice a barre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


Parametri del codice a barre AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Parametri Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Colore delle barre. Valore predefinito: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Altezza delle barre dei codici a barre 1D nel valore [Unit](../../com.aspose.barcode.generation/unit). Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Ottieni il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

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


Parametri Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Parametri Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Parametri Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Parametri Code16K.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Parametri del testo del codice.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Parametri del coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Parametri Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


Parametri DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


Parametri DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Restituisce un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true.

**Returns:**
boolean - un valore che indica se le barre sono riempite.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Parametri della barra composita GS1.

Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il testo codificato 1D e quello 2D sono separati dal simbolo '|'.

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


Parametri HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


Parametri ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


Parametri MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Spaziatura del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


Parametri PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


Parametri PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Parametri postali. Utilizzato per Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Parametri QR, MicroQR e RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Solo per codici a barre 1D. Se il testo codificato è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il testo codificato verrà corretto per corrispondere alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il testo codificato è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il testo codificato è errato.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


La x-dimension è la larghezza minima dell'unità delle barre o spazi del codice a barre. Incrementare questo aumenterà la larghezza dell'intera immagine del codice a barre. Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

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


Abilita il checksum durante la generazione dei codici a barre 1D.

Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale.

Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum sempre utilizzato: resto delle simbologie

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




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


Colore delle barre. Valore predefinito: Color.Black.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Altezza delle barre dei codici a barre 1D nel valore [Unit](../../com.aspose.barcode.generation/unit). Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Abilita il checksum durante la generazione dei codici a barre 1D.

Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale.

Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum sempre utilizzato: resto delle simbologie

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Imposta un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se le barre sono riempite. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Parametri della barra composita GS1.

Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il testo codificato 1D e quello 2D sono separati dal simbolo '|'.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Solo per codici a barre 1D. Se il testo codificato è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il testo codificato verrà corretto per corrispondere alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il testo codificato è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il testo codificato è errato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


La x-dimension è la larghezza minima dell'unità delle barre o spazi del codice a barre. Incrementare questo aumenterà la larghezza dell'intera immagine del codice a barre. Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

