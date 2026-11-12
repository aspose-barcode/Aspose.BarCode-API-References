---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri di generazione del Barcode."
type: docs
weight: 140
url: /it/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Parametri di generazione del Barcode.

```js
new BarcodeParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Parametri del codice a barre AustralianPost. |
| [getAztec()](#getaztec) | Parametri Aztec. |
| [getBarColor()](#getbarcolor) | Colore delle barre. |
| [getBarHeight()](#getbarheight) | Altezza delle barre dei codici a barre 1D in valore Unit. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Ottieni il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [getCodabar()](#getcodabar) | Parametri Codabar. |
| [getCodablock()](#getcodablock) | Parametri Codablock. |
| [getCode16K()](#getcode16k) | Parametri Code16K. |
| [getCode128()](#getcode128) | Parametri Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Parametri Codetext. |
| [getCoupon()](#getcoupon) | Parametri Coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Parametri Databar. |
| [getDataMatrix()](#getdatamatrix) | Parametri DataMatrix. |
| [getDotCode()](#getdotcode) | Parametri DotCode. |
| [getEnableEscape()](#getenableescape) | Indica se il carattere "\" viene interpretato come carattere di escape nella proprietà CodeText. Utilizzato per Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Ottiene un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Parametri GS1 Composite Bar. Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D |
| [getHanXin()](#gethanxin) | Parametri HanXin. |
| [getITF()](#getitf) | Parametri ITF. |
| [getMaxiCode()](#getmaxicode) | Parametri MaxiCode. |
| [getPadding()](#getpadding) | Padding del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Parametri PatchCode. |
| [getPdf417()](#getpdf417) | Parametri PDF417. |
| [getPostal()](#getpostal) | Parametri postali. Utilizzati per Postnet, Planet. |
| [getQR()](#getqr) | Parametri QR. |
| [getSupplement()](#getsupplement) | Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, |
| [getXDimension()](#getxdimension) | La x-dimension è la larghezza minima dell'unità delle barre o spazi del BarCode. Incrementare questo aumenterà l'intero barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Abilita il checksum durante la generazione dei codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, come N |
| [setBarColor(value)](#setbarcolor) | Colore delle barre. |
| [setBarHeight()](#setbarheight) | Altezza delle barre dei codici a barre 1D in valore Unit. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Abilita il checksum durante la generazione dei codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, come N |
| [setEnableEscape()](#setenableescape) | Indica se il carattere "\" viene interpretato come carattere di escape nella proprietà CodeText. Utilizzato per Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Imposta un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Parametri GS1 Composite Bar. Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D |
| [setPadding()](#setpadding) | Padding del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, P |
| [setXDimension()](#setxdimension) | La x-dimension è la larghezza minima dell'unità delle barre o spazi del BarCode. Incrementare questo aumenterà l'intero barcode i |

### getAustralianPost() {#getaustralianpost}

Parametri del codice a barre AustralianPost.

### getAztec() {#getaztec}

Parametri Aztec.

### getBarColor() {#getbarcolor}

Colore delle barre.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Altezza delle barre dei codici a barre 1D in valore Unit. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Ottieni il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

### getCodabar() {#getcodabar}

Parametri Codabar.

### getCodablock() {#getcodablock}

Parametri Codablock.

### getCode16K() {#getcode16k}

Parametri Code16K.

### getCode128() {#getcode128}

Parametri Code128.

### getCodeTextParameters() {#getcodetextparameters}

Parametri Codetext.

### getCoupon() {#getcoupon}

Parametri Coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Parametri Databar.

### getDataMatrix() {#getdatamatrix}

Parametri DataMatrix.

### getDotCode() {#getdotcode}

Parametri DotCode.

### getEnableEscape() {#getenableescape}

Indica se il carattere "\" viene interpretato come carattere di escape nella proprietà CodeText. Utilizzato per Pdf417, DataMatrix, Code128 solo Se EnableEscape è true, "\" sarà interpretato come un carattere di escape speciale. Altrimenti, "\" agisce come caratteri normali. Aspose.BarCode supporta l'inserimento di codici ascii decimali e mnemonici per i caratteri di controllo ASCII. Per esempio, \013 e \\CR rappresentano CR.

### getFilledBars() {#getfilledbars}

Ottiene un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true.

### getGS1CompositeBar() {#getgs1compositebar}

Parametri GS1 Composite Bar. Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

Parametri HanXin.

### getITF() {#getitf}

Parametri ITF.

### getMaxiCode() {#getmaxicode}

Parametri MaxiCode.

### getPadding() {#getpadding}

Padding del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Parametri PatchCode.

### getPdf417() {#getpdf417}

Parametri PDF417.

### getPostal() {#getpostal}

Parametri postali. Utilizzati per Postnet, Planet.

### getQR() {#getqr}

Parametri QR.

### getSupplement() {#getsupplement}

Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Il valore del parametro WideNarrowRatio è minore o uguale a 0.

### getXDimension() {#getxdimension}

La x-dimension è la larghezza minima dell'unità delle barre o spazi del BarCode. Incrementare questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Abilita il checksum durante la generazione di codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale. Il checksum è possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Il checksum è sempre usato: resto delle simbologie

### setBarColor(value) {#setbarcolor}

Colore delle barre.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | String | per il colore della barra Valore predefinito: #000000. |

### setBarHeight() {#setbarheight}

Altezza delle barre dei codici a barre 1D in valore Unit. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Visualizza sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Abilita il checksum durante la generazione di codici a barre 1D. Il valore predefinito è considerato Sì per le simbologie che devono contenere il checksum, e No dove il checksum è solo opzionale. Il checksum è possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Il checksum è sempre usato: resto delle simbologie

### setEnableEscape() {#setenableescape}

Indica se spiega il carattere "\" come carattere di escape nella proprietà CodeText. Utilizzato solo per Pdf417, DataMatrix, Code128. Se EnableEscape è true, "\" verrà interpretato come un carattere di escape speciale. Altrimenti, "\" agisce come caratteri normali. Aspose.BarCode supporta il codice ascii decimale e le mnemoniche per i caratteri di controllo ASCII. Per esempio, \013 e \\CR rappresentano CR.

### setFilledBars() {#setfilledbars}

Imposta un valore che indica se le barre sono riempite. Solo per codici a barre 1D. Valore predefinito: true.

### setGS1CompositeBar() {#setgs1compositebar}

Parametri GS1 Composite Bar. Questo esempio mostra come creare e salvare un'immagine GS1 Composite Bar. Nota che il codetext 1D e il codetext 2D sono separati dal simbolo '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Padding del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Il valore del parametro WideNarrowRatio è minore o uguale a 0.

### setXDimension() {#setxdimension}

La x-dimension è la larghezza minima dell'unità delle barre o spazi del BarCode. Incrementare questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorata se la proprietà AutoSizeMode è impostata su AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
