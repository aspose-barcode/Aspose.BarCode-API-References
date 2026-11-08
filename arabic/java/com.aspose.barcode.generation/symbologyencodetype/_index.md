---
title: "SymbologyEncodeType"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "نوع ترميز الرموز."
type: docs
weight: 66
url: /ar/java/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
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
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BaseEncodeType المحددة. |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | يحصل على تصنيف هذا الترميز. |
| [getString()](#getString--) | يقوم بتحويل نسخة BaseEncodeType إلى تمثيلها النصي المكافئ. |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | يقوم بتحويل نسخة BaseEncodeType إلى تمثيلها النصي المكافئ. |
| [getTypeIndex()](#getTypeIndex--) | يحصل على فهرس نوع الترميز |
| [getTypeName()](#getTypeName--) | يحصل على اسم نوع الترميز |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | يقوم بتحويل التمثيل النصي لاسم BaseEncodeType إلى نسخة منه. |
| [toString()](#toString--) | يعيد اسم BaseEncodeType المعطى كسلسلة نصية. |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخة منه. |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخة منه. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة BaseEncodeType المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | java.lang.Object | قيمة BaseEncodeType للمقارنة مع هذه النسخة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
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


يقوم بتحويل نسخة BaseEncodeType إلى تمثيلها النصي المكافئ. تنسيق السلسلة هو: "Index:0; Name:Codabar".

**Returns:**
java.lang.String - سلسلة تمثل القيمة الكاملة لنوع الترميز
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


يقوم بتحويل نسخة BaseEncodeType إلى تمثيلها النصي المكافئ. تنسيق السلسلة هو: "Index:-1; Name:None".

**Parameters:**
| معامل | النوع | الوصف |
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


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
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


يقوم بتحويل التمثيل النصي لاسم BaseEncodeType إلى نسخة منه.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| stringEncodeType | java.lang.String | سلسلة تحتوي على اسم BaseEncodeType للتحويل. |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


يعيد اسم BaseEncodeType المعطى كسلسلة نصية.

**Returns:**
java.lang.String - سلسلة تمثل اسم نوع الترميز
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخة منه. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة بالتنسيق "Index:-1; Name:None" للتحويل. |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | يُرجع SingleEncodeType الفعلي عندما يكتمل التحويل بنجاح؛ |

وإلا فإنه يُرجع null. |

**Returns:**
boolean -  **true**  إذا تم تحويل s بنجاح؛ وإلا،  **false** .
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


يقوم بتحويل التمثيل النصي لـ BaseEncodeType إلى نسخة منه. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة بالتنسيق "Index:-1; Name:None" للتحويل. |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | يُرجع SingleEncodeType الفعلي عندما يكتمل التحويل بنجاح؛ |

وإلا فإنه يُرجع null. |

**Returns:**
boolean -  **true**  إذا تم تحويل s بنجاح؛ وإلا،  **false** .
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

