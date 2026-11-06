---
title: "CodetextParameters"
second_title: "Aspose.BarCode för Android via Java API-referens"
description: "Codetext-parametrar."
type: docs
weight: 26
url: /sv/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetext-parametrar.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Hämtar justeringen av kodtexten. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Ange färgen för den visade CodeText. |
| [getFont()](#getFont--) | Ange teckensnittet för den visade CodeText. |
| [getFontMode()](#getFontMode--) | Ange FontMode. |
| [getLocation()](#getLocation--) | Ange platsen för den visade CodeText, sätt till CodeLocation.None för att dölja CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Ange radbrytningar (linjeskift) i texten.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Avstånd mellan CodeText och BarCode i  Unit  värde. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text som kommer att visas istället för kodtext i 2D-streckkoder. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av dessa  CodetextParameters . |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Hämtar justeringen av kodtexten. Standardvärde: TextAlignment.CENTER.

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
public int getColor()
```


Ange färgen för den visade CodeText. Standardvärde: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension-värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Ange platsen för den visade CodeText, sätt till CodeLocation.None för att dölja CodeText. Standardvärde: CodeLocation.BELOW för 1D-streckkoder och CodeLocation.None för 2D-streckkoder.

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


Avstånd mellan CodeText och BarCode i  Unit  värde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Ställer in justeringen av kodtexten. Standardvärde: TextAlignment.CENTER.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Ange färgen för den visade CodeText. Standardvärde: Color.BLACK.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är satt till FontMode.AUTO.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Ange FontMode. Om FontMode är satt till Auto beräknas teckenstorleken automatiskt baserat på xDimension-värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Ange platsen för den visade CodeText, sätt till CodeLocation.None för att dölja CodeText. Standardvärde: CodeLocation.BELOW för 1D-streckkoder och CodeLocation.None för 2D-streckkoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Avstånd mellan CodeText och BarCode i  Unit  värde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Text som kommer att visas istället för kodtext i 2D-streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av dessa  CodetextParameters .

**Returns:**
java.lang.String - En sträng som representerar detta CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

