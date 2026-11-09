---
title: "CodetextParameters"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Parámetros de Codetext."
type: docs
weight: 26
url: /es/java/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Parámetros de Codetext.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtiene la alineación del texto del código. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Especifique el color del CodeText que se muestra. |
| [getFont()](#getFont--) | Especifique la fuente del CodeText que se muestra. |
| [getFontMode()](#getFontMode--) | Especifique FontMode. |
| [getLocation()](#getLocation--) | Especifique la ubicación del CodeText que se muestra, establezca CodeLocation.None para ocultar el CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Especifique los ajustes de línea (saltos de línea) dentro del texto.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Espacio entre el CodeText y el BarCode en valor de Unit. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Texto que se mostrará en lugar del codetext en códigos de barras 2D. |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este CodetextParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Obtiene la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Especifique el color del CodeText que se muestra. Valor predeterminado: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Especifique la fuente del CodeText que se muestra. Valor predeterminado: Arial 5pt regular. Ignorado si FontMode está configurado a FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor xDimension. Se recomienda usar FontMode.AUTO especialmente en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valor predeterminado: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Especifique la ubicación del CodeText que se muestra, establezca CodeLocation.None para ocultar el CodeText. Valor predeterminado: CodeLocation.BELOW para códigos de barras 1D y CodeLocation.None para códigos de barras 2D.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Espacio entre el CodeText y el BarCode en valor de Unit. Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Establece la alineación del texto del código. Valor predeterminado: TextAlignment.CENTER.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Especifique el color del CodeText que se muestra. Valor predeterminado: Color.BLACK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Color |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Especifique la fuente del CodeText que se muestra. Valor predeterminado: Arial 5pt regular. Ignorado si FontMode está configurado a FontMode.AUTO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Especifique FontMode. Si FontMode está configurado a Auto, el tamaño de fuente se calculará automáticamente en función del valor xDimension. Se recomienda usar FontMode.AUTO especialmente en AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valor predeterminado: FontMode.AUTO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Especifique la ubicación del CodeText que se muestra, establezca CodeLocation.None para ocultar el CodeText. Valor predeterminado: CodeLocation.BELOW para códigos de barras 1D y CodeLocation.None para códigos de barras 2D.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Espacio entre el CodeText y el BarCode en valor de Unit. Valor predeterminado: 2pt. Ignorado para EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Texto que se mostrará en lugar del codetext en códigos de barras 2D. Usado para: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este CodetextParameters.

**Returns:**
java.lang.String - Una cadena que representa este CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

