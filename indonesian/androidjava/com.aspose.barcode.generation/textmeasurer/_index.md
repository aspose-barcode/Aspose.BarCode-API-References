---
title: TextMeasurer
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Mewakili pengukur teks.
type: docs
weight: 68
url: /id/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Mewakili pengukur teks. Implementasi Full Framework. TODO: Cache bitmap dan grafik
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | Menginisialisasi instance baru dari kelas TextMeasurer. |
## Methods

| Method | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Membuang (dispose) pengukur dan sumber daya internal. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Mendapatkan resolusi menggambar persegi panjang karakter dan mode AntiAlias yang ditetapkan di konstruktor. |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Mengukur string dengan lebar dan font yang ditentukan. |
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


Menginisialisasi instance baru dari kelas TextMeasurer.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dpi | float | DPI kanvas target |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Mode antialising teks |

### dispose() {#dispose--}
```
public void dispose()
```


Membuang (dispose) pengukur dan sumber daya internal.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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


Mendapatkan resolusi menggambar persegi panjang karakter dan mode AntiAlias yang ditetapkan di konstruktor.

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | mengukur teks |
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

