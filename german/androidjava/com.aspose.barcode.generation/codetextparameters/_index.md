---
title: CodetextParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Codetext-Parameter.
type: docs
weight: 27
url: /de/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetext-Parameter.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ermittelt die Ausrichtung des Codetextes. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Geben Sie die Farbe des angezeigten CodeText an. |
| [getFont()](#getFont--) | Geben Sie die Schriftart des angezeigten CodeText an. |
| [getFontMode()](#getFontMode--) | Geben Sie den FontMode an. |
| [getLocation()](#getLocation--) | Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um CodeText zu verbergen. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Geben Sie Zeilenumbrüche (Wortumbrüche) im Text an.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Abstand zwischen CodeText und BarCode im Einheit-Wert. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text, der anstelle von Codetext in 2D-Barcodes angezeigt wird. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser CodetextParameters zurück. |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Ermittelt die Ausrichtung des Codetextes. Standardwert: TextAlignment.CENTER.

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


Geben Sie die Anzeigefarbe des CodeText an. Standardwert: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Ignoriert, wenn FontMode auf FontMode.AUTO gesetzt ist.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.AUTO zu verwenden, insbesondere in AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION. Standardwert: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um CodeText auszublenden. Standardwert: CodeLocation.BELOW für 1D-Barcodes und CodeLocation.None für 2D-Barcodes.

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


Abstand zwischen CodeText und BarCode in Einheit. Standardwert: 2pt. Ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Text, der anstelle des Codetexts in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Legt die Ausrichtung des Code-Textes fest. Standardwert: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Geben Sie die Anzeigefarbe des CodeText an. Standardwert: Color.BLACK.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Ignoriert, wenn FontMode auf FontMode.AUTO gesetzt ist.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.AUTO zu verwenden, insbesondere in AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION. Standardwert: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um CodeText auszublenden. Standardwert: CodeLocation.BELOW für 1D-Barcodes und CodeLocation.None für 2D-Barcodes.

**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Abstand zwischen CodeText und BarCode in Einheit. Standardwert: 2pt. Ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Text, der anstelle des Codetexts in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser CodetextParameters zurück.

**Returns:**
java.lang.String - Eine Zeichenkette, die diese CodetextParameters darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

