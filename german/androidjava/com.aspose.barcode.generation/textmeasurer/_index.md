---
title: TextMeasurer
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Stellt einen Textmesswert dar.
type: docs
weight: 68
url: /de/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Stellt den Textmessgerät dar. Vollständige Framework‑Implementierung. TODO: Bitmap und Grafiken zwischenspeichern
## Constructors

| Constructor | Beschreibung |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | Initialisiert eine neue Instanz der Klasse TextMeasurer. |
## Methods

| Method | Beschreibung |
| --- | --- |
| [dispose()](#dispose--) | Gibt den Messgerät und interne Ressourcen frei. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Liest Zeichen, Zeichenrechtecke, Auflösung und AntiAlias‑Modus, die im Konstruktor festgelegt wurden. |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Misst eine Zeichenkette mit angegebener Breite und Schriftart. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offsetRectangle(System.Drawing.RectangleF nativeRectangle, boolean isNoWrap, int verticalAlignment)](#offsetRectangle-com.aspose.ms.System.Drawing.RectangleF-boolean-int-) |  |
| [reOffsetRectangle(System.Drawing.RectangleF symbolArea, System.Drawing.RectangleF nativeRectangle, System.Drawing.RectangleF offsetRectangle, int horisontalAlignment)](#reOffsetRectangle-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextMeasurer(float dpi, AntiAliasMode antiAliasMode) {#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-}
```
public TextMeasurer(float dpi, AntiAliasMode antiAliasMode)
```


Initialisiert eine neue Instanz der Klasse TextMeasurer.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| dpi | float | DPI der Ziel‑Canvas |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Text-Antialiasing‑Modus |

### dispose() {#dispose--}
```
public void dispose()
```


Gibt den Messgerät und interne Ressourcen frei.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions) {#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-}
```
public System.Drawing.RectangleF[] measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)
```


Liest Zeichen, Zeichenrechtecke, Auflösung und AntiAlias‑Modus, die im Konstruktor festgelegt wurden.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Messung von Text |
| font | android.text.TextPaint | measuring font |
| rectangle | com.aspose.ms.System.Drawing.RectangleF | bounding rectangle |
| textOptions | com.aspose.barcode.drawing.TextOptions | text alignment |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF[] - characters rectangles
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Measure string with specified width, font. Resolution and AntiAlias Mode set in constructor

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| str | java.lang.String | A string |
| width | float | A width |
| font | android.text.TextPaint | A font |

**Returns:**
com.aspose.ms.System.Drawing.SizeF - Size of a string
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offsetRectangle(System.Drawing.RectangleF nativeRectangle, boolean isNoWrap, int verticalAlignment) {#offsetRectangle-com.aspose.ms.System.Drawing.RectangleF-boolean-int-}
```
public static System.Drawing.RectangleF offsetRectangle(System.Drawing.RectangleF nativeRectangle, boolean isNoWrap, int verticalAlignment)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| nativeRectangle | com.aspose.ms.System.Drawing.RectangleF |  |
| isNoWrap | boolean |  |
| verticalAlignment | int |  |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF
### reOffsetRectangle(System.Drawing.RectangleF symbolArea, System.Drawing.RectangleF nativeRectangle, System.Drawing.RectangleF offsetRectangle, int horisontalAlignment) {#reOffsetRectangle-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-int-}
```
public static void reOffsetRectangle(System.Drawing.RectangleF symbolArea, System.Drawing.RectangleF nativeRectangle, System.Drawing.RectangleF offsetRectangle, int horisontalAlignment)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| symbolArea | com.aspose.ms.System.Drawing.RectangleF |  |
| nativeRectangle | com.aspose.ms.System.Drawing.RectangleF |  |
| offsetRectangle | com.aspose.ms.System.Drawing.RectangleF |  |
| horisontalAlignment | int |  |

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

