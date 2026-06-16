---
title: BarcodeParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Parámetros de generación de códigos de barras.
type: docs
weight: 14
url: /es/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parámetros de generación de códigos de barras.
## Methods

| Method | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | Parámetros del código de barras AustralianPost. |
| [getAztec()](#getAztec--) | Parámetros de Aztec. |
| [getBarColor()](#getBarColor--) | Color de las barras. |
| [getBarHeight()](#getBarHeight--) | Altura de las barras de códigos de barras 1D en valor de [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | Obtiene el valor de reducción de barras que se usa para compensar la difusión de tinta al imprimir. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Parámetros de Codabar. |
| [getCodablock()](#getCodablock--) | Parámetros de Codablock. |
| [getCode128()](#getCode128--) | Parámetros de Code128. |
| [getCode16K()](#getCode16K--) | Parámetros de Code16K. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Parámetros de Codetext. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Parámetros de cupón. |
| [getDataBar()](#getDataBar--) | Parámetros de Databar. |
| [getDataMatrix()](#getDataMatrix--) | Parámetros de DataMatrix. |
| [getDotCode()](#getDotCode--) | Parámetros de DotCode. |
| [getEnableEscape()](#getEnableEscape--) | Indica si se interpreta el carácter "\\" como un carácter de escape en la propiedad CodeText. |
| [getFilledBars()](#getFilledBars--) | Obtiene un valor que indica si las barras están rellenas. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | Parámetros de GS1 Composite Bar. |
| [getHanXin()](#getHanXin--) | Parámetros de HanXin. |
| [getITF()](#getITF--) | Parámetros de ITF. |
| [getMaxiCode()](#getMaxiCode--) | Parámetros de MaxiCode. |
| [getPadding()](#getPadding--) | Rellenos del código de barras. |
| [getPatchCode()](#getPatchCode--) | Parámetros de PatchCode. |
| [getPdf417()](#getPdf417--) | Parámetros de PDF417. |
| [getPostal()](#getPostal--) | Parámetros postales. |
| [getQR()](#getQR--) | Parámetros de QR, MicroQR y RectMicroQR. |
| [getSupplement()](#getSupplement--) | Parámetros de suplemento. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Solo para códigos de barras 1D. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Relación de barras anchas a barras estrechas. |
| [getXDimension()](#getXDimension--) | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del código de barras. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Color de las barras. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Altura de las barras de códigos de barras 1D en valor de [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Establece el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Indica si se interpreta el carácter "\\" como un carácter de escape en la propiedad CodeText. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Establece un valor que indica si las barras están rellenas. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | Parámetros de GS1 Composite Bar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Solo para códigos de barras 1D. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Relación de barras anchas a barras estrechas. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | La x-dimensión es el ancho más pequeño de la unidad de barras o espacios del código de barras. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
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


Parámetros del código de barras AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Parámetros de Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Color de las barras. Valor predeterminado: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Altura de las barras de los códigos de barras 1D en unidades de [Unit](../../com.aspose.barcode.generation/unit). Se ignora si la propiedad BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) está establecida en AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Obtiene el valor de reducción de barras que se usa para compensar la difusión de tinta durante la impresión. Valor predeterminado: 0

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


Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128.

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


Parámetros de Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Parámetros de Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Parámetros de Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Parámetros de Code16K.

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


Parámetros de Codetext.

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


Parámetros de cupón. Usado para UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Parámetros de Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


Parámetros de DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


Parámetros de DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Indica si se interpreta el carácter "\\" como un carácter de escape en la propiedad CodeText. Usado solo para Pdf417, DataMatrix y Code128. Si EnableEscape es verdadero, "\\" se interpretará como un carácter de escape especial. De lo contrario, "\\" actúa como caracteres normales.

Aspose.BarCode admite la entrada de códigos ASCII decimales y mnemónicos para caracteres de código de control ASCII. Por ejemplo, \\013 y \\\\CR representan CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Obtiene un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true.

**Returns:**
boolean - un valor que indica si las barras están rellenas.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


Parámetros de GS1 Composite Bar.

Este ejemplo muestra cómo crear y guardar una imagen de GS1 Composite Bar. Tenga en cuenta que el codetext 1D y el codetext 2D están separados por el símbolo '|'

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


Parámetros de HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


Parámetros de ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


Parámetros de MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Rellenos del código de barras. Valor predeterminado: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


Parámetros de PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


Parámetros de PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Parámetros postales. Usado para Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


Parámetros de QR, MicroQR y RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Parámetros suplementarios. Usado para Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Solo para códigos de barras 1D. Si el codetext es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el codetext se corregirá para cumplir con la especificación del código de barras. La excepción siempre se lanzará para: la simbología Databar si el codetext es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbología Code128 si el codetext es incorrecto.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las barras estrechas. Usado para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension es el ancho más pequeño de la unidad de barras o espacios del código de barras. Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

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


Habilitar suma de verificación durante la generación de códigos de barras 1D.

El valor predeterminado se trata como Sí para la simbología que debe contener suma de verificación, y como No donde la suma de verificación solo es posible.

La suma de verificación es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Suma de verificación siempre usada: Resto de la simbología

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


Color de las barras. Valor predeterminado: Color.Black.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Altura de las barras de los códigos de barras 1D en unidades de [Unit](../../com.aspose.barcode.generation/unit). Se ignora si la propiedad BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) está establecida en AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Establece el valor de reducción de barras que se usa para compensar la difusión de tinta al imprimir. Valor predeterminado: 0

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | valor de reducción de barras que se usa para compensar la difusión de tinta al imprimir. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Mostrar siempre el dígito de suma de verificación en el texto legible para humanos de los códigos de barras Code128 y GS1Code128.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Habilitar suma de verificación durante la generación de códigos de barras 1D.

El valor predeterminado se trata como Sí para la simbología que debe contener suma de verificación, y como No donde la suma de verificación solo es posible.

La suma de verificación es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Suma de verificación siempre usada: Resto de la simbología

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Indica si se interpreta el carácter "\\" como un carácter de escape en la propiedad CodeText. Usado solo para Pdf417, DataMatrix y Code128. Si EnableEscape es verdadero, "\\" se interpretará como un carácter de escape especial. De lo contrario, "\\" actúa como caracteres normales.

Aspose.BarCode admite la entrada de códigos ASCII decimales y mnemónicos para caracteres de código de control ASCII. Por ejemplo, \\013 y \\\\CR representan CR.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Establece un valor que indica si las barras están rellenas. Solo para códigos de barras 1D. Valor predeterminado: true.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si las barras están rellenas. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


Parámetros de GS1 Composite Bar.

Este ejemplo muestra cómo crear y guardar una imagen de GS1 Composite Bar. Tenga en cuenta que el codetext 1D y el codetext 2D están separados por el símbolo '|'

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Solo para códigos de barras 1D. Si el codetext es incorrecto y el valor se establece en true, se lanzará una excepción. De lo contrario, el codetext se corregirá para cumplir con la especificación del código de barras. La excepción siempre se lanzará para: la simbología Databar si el codetext es incorrecto. La excepción nunca se lanzará para: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbología Code128 si el codetext es incorrecto.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Relación de barras anchas a barras estrechas. Valor predeterminado: 3, es decir, las barras anchas son 3 veces más anchas que las barras estrechas. Usado para ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension es el ancho más pequeño de la unidad de barras o espacios del código de barras. Incrementar esto aumentará el ancho total de la imagen del código de barras. Se ignora si la propiedad BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) está configurada a AutoSizeMode.Nearest o AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Descripción |
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

