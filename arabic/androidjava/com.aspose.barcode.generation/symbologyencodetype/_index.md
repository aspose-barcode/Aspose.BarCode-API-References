---
title: SymbologyEncodeType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: نوع ترميز الرموز.
type: docs
weight: 67
url: /ar/androidjava/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object، [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

نوع ترميز الرموز. راجع EncodeTypes للحصول على نسخة.

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة BaseEncodeType المحددة. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | يحصل على تصنيف هذا الترميز. |
| [getString()](#getString--) | يحوّل كائن BaseEncodeType إلى تمثيله النصي المكافئ. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | يحوّل كائن BaseEncodeType إلى تمثيله النصي المكافئ. |
| [getTypeIndex()](#getTypeIndex--) | يحصل على فهرس نوع الترميز |
| [getTypeName()](#getTypeName--) | يحصل على اسم نوع الترميز |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | يحوّل التمثيل النصي لاسم BaseEncodeType إلى كائنه. |
| [toString()](#toString--) | يرجع اسم BaseEncodeType المعطى كسلسلة نصية. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | يحوّل التمثيل النصي لـ BaseEncodeType إلى كائنه. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | يحوّل التمثيل النصي لـ BaseEncodeType إلى كائنه. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يرجع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة BaseEncodeType المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| أخرى | java.lang.Object | قيمة BaseEncodeType للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


يحصل على تصنيف هذا الترميز.

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


يقوم بتحويل نسخة من BaseEncodeType إلى تمثيلها النصي المكافئ. تنسيق السلسلة هو: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - سلسلة تمثل القيمة الكاملة لنوع الترميز
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


يقوم بتحويل نسخة من BaseEncodeType إلى تمثيلها النصي المكافئ. تنسيق السلسلة هو: "Index:-1; Name:None".

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | نسخة BaseEncodeType المراد تحويلها |

**Returns:**
java.lang.String - سلسلة تمثل القيمة الكاملة لنوع الترميز المعطى
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


يحصل على فهرس نوع الترميز

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


يحصل على اسم نوع الترميز

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


يحوّل التمثيل النصي لاسم BaseEncodeType إلى كائنه.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| stringEncodeType | java.lang.String | سلسلة تحتوي على اسم BaseEncodeType للتحويل. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


يرجع اسم BaseEncodeType المعطى كسلسلة نصية.

**Returns:**
java.lang.String - سلسلة تمثل اسم نوع الترميز
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخته. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة بالتنسيق "Index:-1; Name:None" للتحويل. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | يُرجع SingleEncodeType فعلي عندما يكتمل التحويل بنجاح؛ |

وإلا فإنه يُرجع null. |

**Returns:**
boolean -  **true**  إذا تم تحويل s بنجاح؛ وإلا،  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخته. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة بالتنسيق "Index:-1; Name:None" للتحويل. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | يُرجع SingleEncodeType فعلي عندما يكتمل التحويل بنجاح؛ |

وإلا فإنه يُرجع null. |

**Returns:**
boolean -  **true**  إذا تم تحويل s بنجاح؛ وإلا،  **false** .
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

