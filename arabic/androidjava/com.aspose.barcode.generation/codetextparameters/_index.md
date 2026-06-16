---
title: CodetextParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات Codetext.
type: docs
weight: 27
url: /ar/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

معلمات Codetext.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Gets the alignment of the code text. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specify the displaying CodeText's Color. |
| [getFont()](#getFont--) | Specify the displaying CodeText's font. |
| [getFontMode()](#getFontMode--) | Specify FontMode. |
| [getLocation()](#getLocation--) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specify word wraps (line breaks) within text.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Space between the CodeText and the BarCode in  Unit  value. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Text that will be displayed instead of codetext in 2D barcodes. |
| [toString()](#toString--) | Returns a human-readable string representation of this  CodetextParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Gets the alignment of the code text. Default value: TextAlignment.CENTER.

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
public int getColor()
```


حدد لون عرض CodeText. القيمة الافتراضية: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


حدد موقع عرض CodeText، عيّن إلى CodeLocation.None لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW للباركودات أحادية الأبعاد و CodeLocation.None للباركودات ثنائية الأبعاد.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
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
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


المسافة بين CodeText و BarCode بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها للأنواع EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


النص الذي سيُعرض بدلاً من codetext في الباركودات ثنائية الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode.

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


يضبط محاذاة نص الكود. القيمة الافتراضية: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


حدد لون عرض CodeText. القيمة الافتراضية: Color.BLACK.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt regular. يتم تجاهلها إذا تم تعيين FontMode إلى FontMode.AUTO.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام FontMode.AUTO خاصةً في AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION. القيمة الافتراضية: FontMode.AUTO.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


حدد موقع عرض CodeText، عيّن إلى CodeLocation.None لإخفاء CodeText. القيمة الافتراضية: CodeLocation.BELOW للباركودات أحادية الأبعاد و CodeLocation.None للباركودات ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


المسافة بين CodeText و BarCode بوحدة القيمة. القيمة الافتراضية: 2pt. يتم تجاهلها للأنواع EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


النص الذي سيُعرض بدلاً من codetext في الباركودات ثنائية الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  CodetextParameters .

**Returns:**
java.lang.String - سلسلة تمثل هذا  CodetextParameters .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

