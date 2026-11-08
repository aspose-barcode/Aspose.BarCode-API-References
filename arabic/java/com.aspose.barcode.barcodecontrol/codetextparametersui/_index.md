---
title: "CodetextParametersUI"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "غلاف واجهة المستخدم لفئة com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /ar/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

غلاف واجهة المستخدم لفئة com.aspose.barcode.generation.CodetextParameters.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | يحصل على محاذاة نص الرمز. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | حدد لون عرض CodeText. |
| [getFont()](#getFont--) | حدد خط عرض CodeText. |
| [getFontMode()](#getFontMode--) | حدد FontMode. |
| [getLocation()](#getLocation--) | حدد موقع عرض CodeText، اضبطه على CodeLocation.None لإخفاء CodeText. |
| [getSpace()](#getSpace--) | المسافة بين CodeText و BarCode في القيمة. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | يضبط محاذاة نص الرمز. |
| [setColor(Color value)](#setColor-java.awt.Color-) | حدد لون عرض CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | حدد خط عرض CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | حدد FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | حدد موقع عرض CodeText، اضبطه على CodeLocation.None لإخفاء CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا CodetextParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


يحصل على محاذاة نص الرمز. القيمة الافتراضية: StringAlignment.Center.

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


حدد لون عرض CodeText. القيمة الافتراضية: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهله إذا تم ضبط FontMode على FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


حدد FontMode. إذا تم ضبط FontMode على Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


حدد موقع عرض CodeText، اضبطه على CodeLocation.None لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW للباركود أحادي الأبعاد و CodeLocation.None للباركود ثنائي الأبعاد.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


المسافة بين CodeText و BarCode في القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها لـ EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode

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


يضبط محاذاة نص الرمز. القيمة الافتراضية: StringAlignment.Center.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


حدد لون عرض CodeText. القيمة الافتراضية: Color.BLACK.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهله إذا تم ضبط FontMode على FontMode.AUTO.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


حدد FontMode. إذا تم ضبط FontMode على Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


حدد موقع عرض CodeText، اضبطه على CodeLocation.None لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW للباركود أحادي الأبعاد و CodeLocation.None للباركود ثنائي الأبعاد.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


النص الذي سيُعرض بدلاً من codetext في الباركود ثنائي الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا CodetextParameters.

**Returns:**
java.lang.String - سلسلة تمثل هذا CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

