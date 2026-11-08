---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "UI-Wrapper für die Klasse com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /de/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI-Wrapper für die Klasse com.aspose.barcode.generation.CodetextParameters.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ermittelt die Ausrichtung des Code-Texts. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Geben Sie die anzuzeigende Farbe des CodeText an. |
| [getFont()](#getFont--) | Geben Sie die anzuzeigende Schriftart des CodeText an. |
| [getFontMode()](#getFontMode--) | Geben Sie den FontMode an. |
| [getLocation()](#getLocation--) | Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um den CodeText auszublenden. |
| [getSpace()](#getSpace--) | Abstand zwischen dem CodeText und dem BarCode im Wert. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text, der anstelle des Codetexts in 2D-Barcodes angezeigt wird. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Legt die Ausrichtung des Code-Textes fest. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Geben Sie die anzuzeigende Farbe des CodeText an. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Geben Sie die anzuzeigende Schriftart des CodeText an. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Geben Sie den FontMode an. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um den CodeText auszublenden. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text, der anstelle des Codetexts in 2D-Barcodes angezeigt wird. |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser CodetextParameters zurück . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolesch
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Ermittelt die Ausrichtung des Code-Textes. Standardwert: StringAlignment.Center.

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


Geben Sie die Farbe des angezeigten CodeText an. Standardwert: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Wird ignoriert, wenn FontMode auf FontMode.AUTO gesetzt ist.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Geben Sie den FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.AUTO zu verwenden, insbesondere in AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION. Standardwert: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um den CodeText auszublenden. Standardwert: CodeLocation.BELOW für 1D-Barcodes und CodeLocation.None für 2D-Barcodes.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Abstand zwischen dem CodeText und dem BarCode im Wert. Standardwert: 2pt. Wird ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

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


Legt die Ausrichtung des Code-Textes fest. Standardwert: StringAlignment.Center.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Geben Sie die Farbe des angezeigten CodeText an. Standardwert: Color.BLACK.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Geben Sie die Schriftart des angezeigten CodeText an. Standardwert: Arial 5pt regular. Wird ignoriert, wenn FontMode auf FontMode.AUTO gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Geben Sie den FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, FontMode.AUTO zu verwenden, insbesondere in AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION. Standardwert: FontMode.AUTO.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Geben Sie den Anzeigestandort des CodeText an, setzen Sie ihn auf CodeLocation.None, um den CodeText auszublenden. Standardwert: CodeLocation.BELOW für 1D-Barcodes und CodeLocation.None für 2D-Barcodes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Text, der anstelle des Codetexts in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser CodetextParameters zurück .

**Returns:**
java.lang.String – Eine Zeichenkette, die diese CodetextParameters darstellt .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

