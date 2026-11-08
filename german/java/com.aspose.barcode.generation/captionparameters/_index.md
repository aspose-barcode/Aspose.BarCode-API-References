---
title: "CaptionParameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Caption-Parameter."
type: docs
weight: 20
url: /de/java/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Caption-Parameter.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Horizontale Ausrichtung des Beschriftungstests. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Beschriftungsschriftart. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Geben Sie Wortumbrüche (Zeilenumbrüche) im Text an.
``` |
| [getPadding()](#getPadding--) | Captions paddings. |
| [getText()](#getText--) | Caption text. |
| [getTextColor()](#getTextColor--) | Caption text color. |
| [getVisible()](#getVisible--) | Caption text visibility. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Caption test horizontal alignment. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | Abstände der Beschriftungen. |
| [setText(String value)](#setText-java.lang.String-) | Beschriftungstext. |
| [setTextColor(Color value)](#setTextColor-java.awt.Color-) | Farbe des Beschriftungstextes. |
| [setVisible(boolean value)](#setVisible-boolean-) | Sichtbarkeit des Beschriftungstextes. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionParameters() {#CaptionParameters--}
```
public CaptionParameters()
```


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


Horizontale Ausrichtung des Beschriftungstests. Standardwert: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Beschriftungsschriftart. Standardwert: Arial 8pt regular.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolesch
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


Abstände der Beschriftungen. Standardwert für CaptionAbove: 5pt 5pt 0 5pt. Standardwert für CaptionBelow: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


Beschriftungstext. Standardwert: leere Zeichenkette.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Farbe des Beschriftungstextes. Standardwert: Color.BLACK.

**Returns:**
java.awt.Color
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Sichtbarkeit des Beschriftungstextes. Standardwert: false.

**Returns:**
boolesch
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


Horizontale Ausrichtung des Beschriftungstests. Standardwert: StringAlignment.Center.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


Abstände der Beschriftungen. Standardwert für CaptionAbove: 5pt 5pt 0 5pt. Standardwert für CaptionBelow: 0 5pt 5pt 5pt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Beschriftungstext. Standardwert: leere Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color value)
```


Farbe des Beschriftungstextes. Standardwert: Color.BLACK.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.awt.Color |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Sichtbarkeit des Beschriftungstextes. Standardwert: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolesch |  |

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

