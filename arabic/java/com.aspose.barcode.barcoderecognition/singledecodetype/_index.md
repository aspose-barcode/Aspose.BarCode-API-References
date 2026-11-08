---
title: "SingleDecodeType"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "نوع فك الترميز الفردي."
type: docs
weight: 44
url: /ar/java/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

نوع فك الترميز الفردي. راجع نوع فك الترميز للحصول على المثيل.

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## الدوال

| دالة | الوصف |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | يعيد قيمة تشير إلى ما إذا كان هذا المثيل مدرجًا في القائمة المحددة. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) المحددة. |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | يقوم بتحويل مثيل SingleDecodeType إلى تمثيله النصي المكافئ، باستخدام الصيغة التالية: "Index:-1; Name:None". |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يقوم بتحويل مثيل SingleDecodeType إلى تمثيله النصي المكافئ، باستخدام الصيغة التالية: "Index:-1; Name:None". |
| [getTypeIndex()](#getTypeIndex--) | يحصل على فهرس نوع فك الترميز |
| [getTypeName()](#getTypeName--) | يحصل على اسم نوع فك الترميز |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لاسم SingleDecodeType إلى مثيله. |
| [toString()](#toString--) | طريقة مُعاد تعريفها تمثل SingleDecodeType كسلسلة الاسم. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ BaseDecodeType إلى مثيله، بعد تحديد النوع الفعلي. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ MultiDecodeType إلى مثيله. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ SingleDecodeType إلى مثيله. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


يعيد قيمة تشير إلى ما إذا كان هذا المثيل مدرجًا في القائمة المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | مصفوفة من أنواع فك الترميز الفردية والمتعددة |

**Returns:**
boolean - القيمة صحيحة إذا تم تضمين أي نوع في
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كان هذا المثيل مساويًا لقيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean - صحيح إذا كان obj له نفس القيمة كما هذه المثيلة؛ وإلا، خطأ.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


يقوم بتحويل مثيل SingleDecodeType إلى تمثيله النصي المكافئ، باستخدام الصيغة التالية: "Index:-1; Name:None".

**Returns:**
java.lang.String - سلسلة تمثل القيمة الكاملة لنوع فك الترميز الفردي
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


يقوم بتحويل مثيل SingleDecodeType إلى تمثيله النصي المكافئ، باستخدام الصيغة التالية: "Index:-1; Name:None".

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | مثيلة SingleDecodeType للتحويل |

**Returns:**
java.lang.String - سلسلة تمثل القيمة الكاملة لنوع فك الترميز الفردي المعطى
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


يحصل على فهرس نوع فك الترميز

**Returns:**
short - فهرس نوع فك الترميز
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


يحصل على اسم نوع فك الترميز

**Returns:**
java.lang.String - اسم نوع فك الترميز
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




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


يقوم بتحويل التمثيل النصي لاسم SingleDecodeType إلى مثيله.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| stringDecodeType | java.lang.String | سلسلة تحتوي على اسم SingleDecodeType للتحويل. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


طريقة مُعاد تعريفها تمثل SingleDecodeType كسلسلة الاسم.

**Returns:**
java.lang.String - سلسلة تمثل اسم نوع فك الترميز الفردي
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ BaseDecodeType إلى مثيلتها، بعد تحديد النوع الفعلي. قيمة الإرجاع تشير إلى ما إذا كان التحويل نجح أم فشل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على تمثيل MultiDecodeType للتحويل. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

وإلا فإنه يعيد نوعًا غير محدد. أو MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ MultiDecodeType إلى مثيلتها. قيمة الإرجاع تشير إلى ما إذا كان التحويل نجح أم فشل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على تمثيل MultiDecodeType للتحويل. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

وإلا فإنه يعيد نوعًا غير محدد. أو MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ SingleDecodeType إلى مثيلتها. قيمة الإرجاع تشير إلى ما إذا كان التحويل نجح أم فشل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على SingleDecodeType بالتنسيق مثل \"EAN8\" أو \"EAN13\" أو \"CodaBar\"... للتحويل. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

وإلا فإنه يعيد نوعًا غير محدد. أو SingleDecodeType (-1, \"None\").
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

