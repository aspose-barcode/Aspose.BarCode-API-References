---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode för Java API-referens"
description: "UI-omslag för klassen com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /sv/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI-omslag för klassen com.aspose.barcode.generation.CodetextParameters.
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
| [getSpace()](#getSpace--) | Mellanrum mellan CodeText och BarCode i värde. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text som kommer att visas istället för kodtext i 2D-streckkoder. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Ställer in justeringen av kodtexten. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Ange färgen för den visade CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Ange teckensnittet för den visade CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Ange FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Ange platsen för den visade CodeText, sätt till CodeLocation.None för att dölja CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text som kommer att visas istället för kodtext i 2D-streckkoder. |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta CodetextParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Hämtar justeringen av kodtexten. Standardvärde: StringAlignment.Center.

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


Ange färgen för den visade CodeText. Standardvärde: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Ange det visade CodeText:ens teckensnitt. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är inställt på FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Ange FontMode. Om FontMode är inställt på Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Ange den visade CodeText‑platsen, sätt till CodeLocation.None för att dölja CodeText. Standardvärde: CodeLocation.BELOW för 1D‑streckkoder och CodeLocation.None för 2D‑streckkoder.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Avstånd mellan CodeText och BarCode i  värde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Text som kommer att visas i stället för codetext i 2D‑streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
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


Ställer in justeringen av kodtexten. Standardvärde: StringAlignment.Center.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Ange färgen för den visade CodeText. Standardvärde: Color.BLACK.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Ange det visade CodeText:ens teckensnitt. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är inställt på FontMode.AUTO.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Ange FontMode. Om FontMode är inställt på Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda FontMode.AUTO särskilt i AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION. Standardvärde: FontMode.AUTO.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Ange den visade CodeText‑platsen, sätt till CodeLocation.None för att dölja CodeText. Standardvärde: CodeLocation.BELOW för 1D‑streckkoder och CodeLocation.None för 2D‑streckkoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Text som kommer att visas i stället för codetext i 2D‑streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returnerar en människoläsbar strängrepresentation av detta CodetextParameters .

**Returns:**
java.lang.String - En sträng som representerar dessa CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

