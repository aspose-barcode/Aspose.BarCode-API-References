---
title: CaptionParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Beschriftungsparameter.
type: docs
weight: 20
url: /de/androidjava/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Beschriftungsparameter.
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Horizontale Ausrichtung des Caption-Tests. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Caption-Schriftart. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Geben Sie Zeilenumbrüche (Wortumbrüche) im Text an.
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
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | Abstände der Captions. |
| [setText(String value)](#setText-java.lang.String-) | Caption-Text. |
| [setTextColor(int value)](#setTextColor-int-) | Caption-Textfarbe. |
| [setVisible(boolean value)](#setVisible-boolean-) | Sichtbarkeit des Caption-Textes. |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Horizontale Ausrichtung des Caption-Tests. Standardwert: StringAlignment.Center.

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


Caption-Schriftart. Standardwert: Arial 8pt regular.

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
boolean
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


Abstände der Captions. Standardwert für CaptionAbove: 5pt 5pt 0 5pt. Standardwert für CaptionBelow: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


Caption-Text. Standardwert: leere Zeichenkette.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public int getTextColor()
```


Caption-Textfarbe. Standardwert: Color.BLACK.

**Returns:**
int
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Sichtbarkeit des Caption-Textes. Standardwert: false.

**Returns:**
boolean
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


Horizontale Ausrichtung des Caption-Tests. Standardwert: StringAlignment.Center.

**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


Abstände der Captions. Standardwert für CaptionAbove: 5pt 5pt 0 5pt. Standardwert für CaptionBelow: 0 5pt 5pt 5pt.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Caption-Text. Standardwert: leere Zeichenkette.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setTextColor(int value) {#setTextColor-int-}
```
public void setTextColor(int value)
```


Caption-Textfarbe. Standardwert: Color.BLACK.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Sichtbarkeit des Caption-Textes. Standardwert: false.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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

