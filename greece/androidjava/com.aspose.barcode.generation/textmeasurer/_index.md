---
title: "TextMeasurer"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αντιπροσωπεύει το εργαλείο μέτρησης κειμένου."
type: docs
weight: 66
url: /el/androidjava/com.aspose.barcode.generation/textmeasurer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.barcode.internal.ITextMeasurer
```
public class TextMeasurer implements ITextMeasurer
```

Αναπαριστά το μετρητή κειμένου. Πλήρης υλοποίηση Framework. TODO: Cache bitmap and graphics
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextMeasurer(float dpi, AntiAliasMode antiAliasMode)](#TextMeasurer-float-com.aspose.barcode.drawing.AntiAliasMode-) | Αρχικοποιεί νέα παρουσία της κλάσης TextMeasurer. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Αποδεσμεύει τον μετρητή και τους εσωτερικούς πόρους. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [measureCharacterRanges(String text, TextPaint font, System.Drawing.RectangleF rectangle, TextOptions textOptions)](#measureCharacterRanges-java.lang.String-android.text.TextPaint-com.aspose.ms.System.Drawing.RectangleF-com.aspose.barcode.drawing.TextOptions-) | Λαμβάνει τα χαρακτηριστικά σχεδίασης χαρακτήρων, ανάλυση και λειτουργία AntiAlias που ορίστηκαν στον κατασκευαστή. |
| [measureString(String str, float width, TextPaint font)](#measureString-java.lang.String-float-android.text.TextPaint-) | Μετρήστε τη συμβολοσειρά με καθορισμένο πλάτος, γραμματοσειρά. |
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


Αρχικοποιεί νέα παρουσία της κλάσης TextMeasurer.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpi | float | DPI του στόχου καμβά |
| antiAliasMode | com.aspose.barcode.drawing.AntiAliasMode | Λειτουργία αντι-αποθώμισης κειμένου |

### dispose() {#dispose--}
```
public void dispose()
```


Αποδεσμεύει τον μετρητή και τους εσωτερικούς πόρους.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Λαμβάνει τα χαρακτηριστικά σχεδίασης χαρακτήρων, ανάλυση και λειτουργία AntiAlias που ορίστηκαν στον κατασκευαστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κείμενο | java.lang.String | μέτρηση κειμένου |
| γραμματοσειρά | android.text.TextPaint | μέτρηση γραμματοσειράς |
| ορθογώνιο | com.aspose.ms.System.Drawing.RectangleF | περιβάλλον ορθογώνιο |
| textOptions | com.aspose.barcode.drawing.TextOptions | στοίχιση κειμένου |

**Returns:**
com.aspose.ms.System.Drawing.RectangleF[] - ορθογώνια χαρακτήρων
### measureString(String str, float width, TextPaint font) {#measureString-java.lang.String-float-android.text.TextPaint-}
```
public System.Drawing.SizeF measureString(String str, float width, TextPaint font)
```


Μετρήστε τη συμβολοσειρά με καθορισμένο πλάτος, γραμματοσειρά. Η ανάλυση και η λειτουργία AntiAlias ορίζονται στον κατασκευαστή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

