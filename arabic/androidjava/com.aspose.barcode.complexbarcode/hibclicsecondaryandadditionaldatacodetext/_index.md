---
title: HIBCLICSecondaryAndAdditionalDataCodetext
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الثانوية.
type: docs
weight: 17
url: /ar/androidjava/com.aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICSecondaryAndAdditionalDataCodetext extends HIBCLICComplexCodetext
```

فئة لتشفير وفك تشفير النص المضمن في رمز HIBC LIC الذي يخزن البيانات الثانوية.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext()](#HIBCLICSecondaryAndAdditionalDataCodetext--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة HIBCLICSecondaryAndAdditionalDataCodetext المحددة. |
| [getBarcodeType()](#getBarcodeType--) | يحصل على أو يعيّن نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | يبني codetext. |
| [getData()](#getData--) | يحدد البيانات الثانوية والإضافية المكملة. |
| [getLinkCharacter()](#getLinkCharacter--) | يحدد حرف الرابط. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يُهيئ المثيلة من codetext المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | يحصل على أو يعيّن نوع الباركود. |
| [setData(SecondaryAndAdditionalData value)](#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | يحدد البيانات الثانوية والإضافية المكملة. |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | يحدد حرف الرابط. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICSecondaryAndAdditionalDataCodetext() {#HIBCLICSecondaryAndAdditionalDataCodetext--}
```
public HIBCLICSecondaryAndAdditionalDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة HIBCLICSecondaryAndAdditionalDataCodetext المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة  HIBCLICSecondaryAndAdditionalDataCodetext  للمقارنة مع هذه الحالة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC LIC باستخدام الأنواع HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


يبني codetext.

**Returns:**
java.lang.String - نص الرمز المُنشأ
### getData() {#getData--}
```
public SecondaryAndAdditionalData getData()
```


يحدد البيانات الثانوية والإضافية المكملة.

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### getLinkCharacter() {#getLinkCharacter--}
```
public char getLinkCharacter()
```


يحدد حرف الرابط.

**Returns:**
char
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


يُهيئ المثيلة من codetext المُنشأ.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| constructedCodetext | java.lang.String | نص الرمز المُنشأ. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


يحصل أو يعيّن نوع الباركود. يمكن ترميز نص رمز HIBC LIC باستخدام الأنواع HIBCCode39LIC، HIBCCode128LIC، HIBCAztecLIC، HIBCDataMatrixLIC و HIBCQRLIC. القيمة الافتراضية: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(SecondaryAndAdditionalData value) {#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setData(SecondaryAndAdditionalData value)
```


يحدد البيانات الثانوية والإضافية المكملة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public void setLinkCharacter(char value)
```


يحدد حرف الرابط.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | char |  |

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

