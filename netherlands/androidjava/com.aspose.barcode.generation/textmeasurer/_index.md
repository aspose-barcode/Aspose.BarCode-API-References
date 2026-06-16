---
title: TextMeasurer
second_title: Aspose.BarCode for Android via Java API-referentie
description: Stelt tekstmeetinstrument voor.
type: docs
weight: 68
url: /nl/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Stelt tekstmeasurer voor. Volledige Framework-implementatie. TODO: Cache bitmap en graphics
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | Initialiseert een nieuw exemplaar van de klasse TextMeasurer. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | Disposeert de measurer en interne bronnen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Haalt tekens, teken‑rechthoeken, resolutie en AntiAlias-modus op die in de constructor zijn ingesteld. |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Meet string met opgegeven breedte, lettertype. |
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


Initialiseert een nieuw exemplaar van de klasse TextMeasurer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dpi | float | DPI van het doelcanvas |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Tekst‑antialiasingmodus |

### dispose() {#dispose--}
```
public void dispose()
```


Disposeert de measurer en interne bronnen.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt tekens, teken‑rechthoeken, resolutie en AntiAlias-modus op die in de constructor zijn ingesteld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | tekst meten |
| lettertype | android.text.TextPaint | lettertype meten |
| rechthoek | com.aspose.ms.System.Drawing.RectangleF | begrenzende rechthoek |
| tekstopties | com.aspose.barcode.drawing.TextOptions | tekstuitlijning |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF[] - tekens rechthoeken
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Meet tekenreeks met opgegeven breedte, lettertype. Resolutie en AntiAlias-modus ingesteld in constructor

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | java.lang.String | Een tekenreeks |
| breedte | float | Een breedte |
| lettertype | android.text.TextPaint | Een lettertype |

**Returns:**
com.aspose.ms.System.Drawing.SizeF - Grootte van een tekenreeks
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nativeRechthoek | com.aspose.ms.System.Drawing.RectangleF |  |
| isGeenWrap | boolean |  |
| verticaleUitlijning | int |  |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF
### reOffsetRectangle(System.Drawing.RectangleF symbolArea, System.Drawing.RectangleF nativeRectangle, System.Drawing.RectangleF offsetRectangle, int horisontalAlignment) {#reOffsetRectangle-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-com.aspose.ms.System.Drawing.RectangleF-int-}
```
public static void reOffsetRectangle(System.Drawing.RectangleF symbolArea, System.Drawing.RectangleF nativeRectangle, System.Drawing.RectangleF offsetRectangle, int horisontalAlignment)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| symboolGebied | com.aspose.ms.System.Drawing.RectangleF |  |
| nativeRechthoek | com.aspose.ms.System.Drawing.RectangleF |  |
| offsetRechthoek | com.aspose.ms.System.Drawing.RectangleF |  |
| horizontaleUitlijning | int |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

