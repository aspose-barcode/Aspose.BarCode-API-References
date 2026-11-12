---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Parámetros de generación de códigos de barras."
type: docs
weight: 140
url: /es/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Parámetros de generación de códigos de barras.

```js
new BarcodeParameters()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | Parámetros del código de barras AustralianPost. |
| [getAztec()](#getaztec) | Parámetros de Aztec. |
| [getBarColor()](#getbarcolor) | Color de las barras. |
| [getBarHeight()](#getbarheight) | Altura de las barras de códigos de barras 1D en valor Unit. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Obtenga el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Mostrar siempre el dígito de suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128. |
| [getCodabar()](#getcodabar) | Parámetros de Codabar. |
| [getCodablock()](#getcodablock) | Parámetros de Codablock. |
| [getCode16K()](#getcode16k) | Parámetros de Code16K. |
| [getCode128()](#getcode128) | Parámetros de Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | Parámetros de Codetext. |
| [getCoupon()](#getcoupon) | Parámetros de cupón. Utilizado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Parámetros de Databar. |
| [getDataMatrix()](#getdatamatrix) | Parámetros de DataMatrix. |
| [getDotCode()](#getdotcode) | Parámetros de DotCode. |
| [getEnableEscape()](#getenableescape) | Indica si explica el carácter "\" como carácter de escape en la propiedad CodeText. Usado para Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Obtiene un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | Parámetros de GS1 Composite Bar. Esta muestra muestra cómo crear y guardar una imagen GS1 Composite Bar. Note que 1D codetext |
| [getHanXin()](#gethanxin) | Parámetros de HanXin. |
| [getITF()](#getitf) | Parámetros de ITF. |
| [getMaxiCode()](#getmaxicode) | Parámetros de MaxiCode. |
| [getPadding()](#getpadding) | Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | Parámetros de PatchCode. |
| [getPdf417()](#getpdf417) | Parámetros PDF417. |
| [getPostal()](#getpostal) | Parámetros postales. Usado para Postnet, Planet. |
| [getQR()](#getqr) | Parámetros QR. |
| [getSupplement()](#getsupplement) | Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Usado para ITF, |
| [getXDimension()](#getxdimension) | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del BarCode. Incrementar esto aumentará todo el código de barras i |
| [isChecksumEnabled()](#ischecksumenabled) | Habilitar suma de verificación durante la generación de códigos de barras 1D. Por defecto se trata como Sí para simbología que debe contener suma de verificación, como N |
| [setBarColor(value)](#setbarcolor) | Color de las barras. |
| [setBarHeight()](#setbarheight) | Altura de las barras de códigos de barras 1D en valor Unit. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Establece el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Mostrar siempre el dígito de suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | Habilitar suma de verificación durante la generación de códigos de barras 1D. Por defecto se trata como Sí para simbología que debe contener suma de verificación, como N |
| [setEnableEscape()](#setenableescape) | Indica si explica el carácter "\" como carácter de escape en la propiedad CodeText. Usado para Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | Parámetros de GS1 Composite Bar. Esta muestra muestra cómo crear y guardar una imagen GS1 Composite Bar. Note que 1D codetext |
| [setPadding()](#setpadding) | Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Usado para ITF, P |
| [setXDimension()](#setxdimension) | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del BarCode. Incrementar esto aumentará todo el código de barras i |

### getAustralianPost() {#getaustralianpost}

Parámetros del código de barras AustralianPost.

### getAztec() {#getaztec}

Parámetros de Aztec.

### getBarColor() {#getbarcolor}

Color de las barras.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Altura de las barras de códigos de barras 1D en valor Unit. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Obtenga el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Mostrar siempre el dígito de suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128.

### getCodabar() {#getcodabar}

Parámetros de Codabar.

### getCodablock() {#getcodablock}

Parámetros de Codablock.

### getCode16K() {#getcode16k}

Parámetros de Code16K.

### getCode128() {#getcode128}

Parámetros de Code128.

### getCodeTextParameters() {#getcodetextparameters}

Parámetros de Codetext.

### getCoupon() {#getcoupon}

Parámetros de cupón. Utilizado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Parámetros de Databar.

### getDataMatrix() {#getdatamatrix}

Parámetros de DataMatrix.

### getDotCode() {#getdotcode}

Parámetros de DotCode.

### getEnableEscape() {#getenableescape}

Indica si explica el carácter "\" como carácter de escape en la propiedad CodeText. Usado para Pdf417, DataMatrix, Code128 solo. Si EnableEscape es true, "\" se interpretará como un carácter de escape especial. De lo contrario, "\" actúa como caracteres normales. Aspose.BarCode soporta la entrada de códigos ascii decimales y mnemónicos para caracteres de control ASCII. Por ejemplo, \013 y \\CR representan a CR.

### getFilledBars() {#getfilledbars}

Obtiene un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true.

### getGS1CompositeBar() {#getgs1compositebar}

Parámetros de GS1 Composite Bar. Esta muestra muestra cómo crear y guardar una imagen GS1 Composite Bar. Note que el codetext 1D y el codetext 2D están separados por el símbolo '/'

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

Parámetros de HanXin.

### getITF() {#getitf}

Parámetros de ITF.

### getMaxiCode() {#getmaxicode}

Parámetros de MaxiCode.

### getPadding() {#getpadding}

Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

Parámetros de PatchCode.

### getPdf417() {#getpdf417}

Parámetros PDF417.

### getPostal() {#getpostal}

Parámetros postales. Usado para Postnet, Planet.

### getQR() {#getqr}

Parámetros QR.

### getSupplement() {#getsupplement}

Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Usado para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. El valor del parámetro WideNarrowRatio es menor o igual a 0.

### getXDimension() {#getxdimension}

La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del BarCode. Incrementar esto aumentará el ancho total de la imagen del código de barras. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Habilitar checksum durante la generación de códigos de barras 1D. Por defecto se trata como Sí para la simbología que debe contener checksum, y como No donde el checksum solo es posible. El checksum es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Checksum siempre usado: Resto de simbología

### setBarColor(value) {#setbarcolor}

Color de las barras.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | String | para el color de la barra Valor predeterminado: #000000. |

### setBarHeight() {#setbarheight}

Altura de las barras de códigos de barras 1D en valor Unit. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Establece el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Mostrar siempre el dígito de suma de verificación en el texto legible por humanos para los códigos de barras Code128 y GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

Habilitar checksum durante la generación de códigos de barras 1D. Por defecto se trata como Sí para la simbología que debe contener checksum, y como No donde el checksum solo es posible. El checksum es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Checksum siempre usado: Resto de simbología

### setEnableEscape() {#setenableescape}

Indica si se interpreta el carácter "\\" como carácter de escape en la propiedad CodeText. Se usa solo para Pdf417, DataMatrix, Code128. Si EnableEscape es verdadero, "\\" se interpretará como un carácter de escape especial. De lo contrario, "\\" actúa como caracteres normales. Aspose.BarCode admite el código ascii decimal y mnemónico para los caracteres de control ASCII. Por ejemplo, \\013 y \\\\CR representan a CR.

### setFilledBars() {#setfilledbars}

Establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true.

### setGS1CompositeBar() {#setgs1compositebar}

Parámetros de GS1 Composite Bar. Esta muestra muestra cómo crear y guardar una imagen GS1 Composite Bar. Note que el codetext 1D y el codetext 2D están separados por el símbolo '/'

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

Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las estrechas. Se usa para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. El valor del parámetro WideNarrowRatio es menor o igual a 0.

### setXDimension() {#setxdimension}

La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del BarCode. Incrementar esto aumentará el ancho total de la imagen del código de barras. Ignorado si la propiedad AutoSizeMode está establecida en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
