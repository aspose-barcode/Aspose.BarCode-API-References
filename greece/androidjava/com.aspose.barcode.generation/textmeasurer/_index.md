---
title: TextMeasurer
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Αντιπροσωπεύει το εργαλείο μέτρησης κειμένου.
type: docs
weight: 68
url: /el/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Represents text measurer. Full Framework implementation. TODO: Cache bitmap and graphics
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | Initializes new instance of class  TextMeasurer . |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Disposes measurer and internal resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Gets characters drawing Rectangles Resolution and AntiAlias Mode set in constructor |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Measure string with specified width, font. |
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


Initializes new instance of class  TextMeasurer .

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| dpi | float | Dpi of target canvas |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Text antialising mode |

### dispose() {#dispose--}
```
public void dispose()
```


Disposes measurer and internal resources.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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


Gets characters drawing Rectangles Resolution and AntiAlias Mode set in constructor

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | java.lang.String | measuring text |
| γραμματοσειρά | android.text.TextPaint | μέτρηση γραμματοσειράς |
| ορθογώνιο | com.aspose.ms.System.Drawing.RectangleF | περιβάλλουσα ορθογώνιο |
| textOptions | com.aspose.barcode.drawing.TextOptions | στοίχιση κειμένου |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF[] - ορθογώνια χαρακτήρων
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Μετρήστε τη συμβολοσειρά με καθορισμένο πλάτος, γραμματοσειρά. Η ανάλυση και η λειτουργία AntiAlias ορίζονται στον κατασκευαστή

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| str | java.lang.String | Μια συμβολοσειρά |
| πλάτος | float | Ένα πλάτος |
| γραμματοσειρά | android.text.TextPaint | Μια γραμματοσειρά |

**Returns:**
com.aspose.ms.System.Drawing.SizeF - Μέγεθος μιας συμβολοσειράς
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
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

