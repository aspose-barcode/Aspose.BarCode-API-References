---
title: BarcodeParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri di generazione del barcode.
type: docs
weight: 14
url: /it/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parametri di generazione del barcode.
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | Parametri del codice a barre AustralianPost. |
| [getAztec()](#getAztec--) | Parametri Aztec. |
| [getBarColor()](#getBarColor--) | Colore delle barre. |
| [getBarHeight()](#getBarHeight--) | Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Ottieni il valore di riduzione delle barre che viene usato per compensare la diffusione dell'inchiostro durante la stampa. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Visualizza sempre il carattere di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Parametri Codabar. |
| [getCodablock()](#getCodablock--) | Parametri Codablock. |
| [getCode128()](#getCode128--) | Parametri Code128. |
| [getCode16K()](#getCode16K--) | Parametri Code16K. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Parametri Codetext. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Parametri Coupon. |
| [getDataBar()](#getDataBar--) | Parametri Databar. |
| [getDataMatrix()](#getDataMatrix--) | Parametri DataMatrix. |
| [getDotCode()](#getDotCode--) | Parametri DotCode. |
| [getEnableEscape()](#getEnableEscape--) | Indica se spiega il carattere "\\" come carattere di escape nella proprietà CodeText. |
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
| [getXDimension()](#getXDimension--) | La dimensione x è la larghezza minima dell'unità delle barre o degli spazi del codice a barre. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Colore delle barre. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Visualizza sempre il carattere di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Indica se spiega il carattere "\\" come carattere di escape nella proprietà CodeText. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Imposta un valore che indica se le barre sono riempite. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Parametri della barra composita GS1. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Solo per codici a barre 1D. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Rapporto tra barre larghe e barre strette. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | La dimensione x è la larghezza minima dell'unità delle barre o degli spazi del codice a barre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```




**Returns:**
float
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


Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Ottiene il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Visualizza sempre il carattere di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

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
### getCodeText() {#getCodeText--}
```
public final String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Parametri Codetext.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getComplexBarcode() {#getComplexBarcode--}
```
public final ComplexBarcode getComplexBarcode()
```




**Returns:**
[ComplexBarcode](../../com.aspose.barcode.generation/complexbarcode)
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
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Indica se spiega il carattere "\\" come carattere di escape nella proprietà CodeText. Utilizzato solo per Pdf417, DataMatrix e Code128. Se EnableEscape è true, "\\" verrà interpretato come un carattere di escape speciale. Altrimenti, "\\" agirà come caratteri normali.

Aspose.BarCode supporta l'inserimento di codici ASCII decimali e mnemonici per i caratteri di controllo ASCII. Ad esempio, \\013 e \\\\CR rappresentano CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Ottiene un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true.

**Returns:**
boolean - un valore che indica se le barre sono riempite.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Parametri della barra composita GS1.

Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
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


Solo per codici a barre 1D. Se il codetext è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il codetext verrà corretto per conformarsi alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il codetext è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il codetext è errato.

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


La x-dimension è la larghezza minima dell'unità delle barre o spazi del codice a barre. Incrementare questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorato se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


Abilita il checksum durante la generazione di codici a barre 1D.

Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale.

Il checksum è possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum sempre usato: Altre simbologie

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Altezza delle barre dei codici a barre 1D in valore [Unit](../../com.aspose.barcode.generation/unit). Ignorata se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Visualizza sempre il carattere di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Abilita il checksum durante la generazione di codici a barre 1D.

Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale.

Il checksum è possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum sempre usato: Altre simbologie

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Indica se spiega il carattere "\\" come carattere di escape nella proprietà CodeText. Utilizzato solo per Pdf417, DataMatrix e Code128. Se EnableEscape è true, "\\" verrà interpretato come un carattere di escape speciale. Altrimenti, "\\" agirà come caratteri normali.

Aspose.BarCode supporta l'inserimento di codici ASCII decimali e mnemonici per i caratteri di controllo ASCII. Ad esempio, \\013 e \\\\CR rappresentano CR.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Imposta un valore che indica se le barre sono riempite. Solo per i codici a barre 1D. Valore predefinito: true.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se le barre sono riempite. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Parametri della barra composita GS1.

Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Solo per codici a barre 1D. Se il codetext è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il codetext verrà corretto per conformarsi alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il codetext è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il codetext è errato.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


La x-dimension è la larghezza minima dell'unità delle barre o spazi del codice a barre. Incrementare questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorato se la proprietà BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

