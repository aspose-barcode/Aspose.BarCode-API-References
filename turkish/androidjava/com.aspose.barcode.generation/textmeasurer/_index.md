---
title: "TextMeasurer"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "Metin ölçümcüsünü temsil eder."
type: docs
weight: 66
url: /tr/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Metin ölçümcüyü temsil eder. Tam Framework uygulaması. TODO: Bitmap ve grafik önbelleklemesi
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | TextMeasurer sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose()](#dispose--) | Ölçümcüyü ve iç kaynakları serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Yapıcıda ayarlanan karakter çizim dikdörtgenleri, çözünürlük ve AntiAlias modunu alır. |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Belirtilen genişlik ve yazı tipi ile dizeyi ölç. |
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


TextMeasurer sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpi | float | Hedef tuvalin DPI'sı |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Metin anti-aliasing modu |

### dispose() {#dispose--}
```
public void dispose()
```


Ölçümcüyü ve iç kaynakları serbest bırakır.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Yapıcıda ayarlanan karakter çizim dikdörtgenleri, çözünürlük ve AntiAlias modunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | metni ölçme |
| yazı tipi | android.text.TextPaint | yazı tipini ölçme |
| dikdörtgen | com.aspose.ms.System.Drawing.RectangleF | sınırlayıcı dikdörtgen |
| textOptions | com.aspose.barcode.drawing.TextOptions | metin hizalaması |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF[] - karakter dikdörtgenleri
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Belirtilen genişlik ve yazı tipi ile dizeyi ölç. Çözünürlük ve AntiAlias Modu yapıcıda ayarlanır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | java.lang.String | Bir dize |
| genişlik | float | Bir genişlik |
| yazı tipi | android.text.TextPaint | Bir yazı tipi |

**Returns:**
com.aspose.ms.System.Drawing.SizeF - Bir dize boyutu
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

