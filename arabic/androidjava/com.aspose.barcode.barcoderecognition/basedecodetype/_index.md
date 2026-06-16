---
title: BaseDecodeType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: الفئة الأساسية لـ MultiDecodeType و SingleDecodeType.
type: docs
weight: 23
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

الفئة الأساسية لـ MultiDecodeType و SingleDecodeType.

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | الوصف |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | يحدد ما إذا كان أي من أنواع فك الترميز المعطاة مدرجًا في |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [equals(Object other)](#equals-java.lang.Object-) | إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype). |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ BaseDecodeType إلى كائنه، بعد تحديد النوع المحدد. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ MultiDecodeType إلى كائنه. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ SingleDecodeType إلى كائنه. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


يحدد ما إذا كان أي من أنواع فك الترميز المعطاة مدرجًا في

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | الأنواع للتحقق منها. |

**Returns:**
boolean - القيمة صحيحة إذا كان أي من الأنواع مدرجًا في.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| أخرى | com.aspose.barcode.barcoderecognition.MultiDecodeType | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
منطقي - صحيح إذا كان الكائن يحتوي على نفس القيمة كما هذا الكائن؛ وإلا، خطأ.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
منطقي - صحيح إذا كان الكائن يحتوي على نفس القيمة كما هذا الكائن؛ وإلا، خطأ.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


إرجاع قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| أخرى | java.lang.Object | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
منطقي - صحيح إذا كان الكائن يحتوي على نفس القيمة كما هذا الكائن؛ وإلا، خطأ.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ BaseDecodeType إلى مثاله، بعد تحديد النوع الفعلي. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على تمثيل MultiDecodeType للتحويل. |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

إلا فإنه يُعيد نوعًا غير محدد أو MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ MultiDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على تمثيل MultiDecodeType للتحويل. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - يتم إرجاع MultiDecodeType فعلي عندما يكتمل التحويل بنجاح؛

إلا فإنه يُعيد نوعًا غير محدد أو MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


يقوم بتحويل تمثيل السلسلة لـ SingleDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parsingType | java.lang.String | سلسلة تحتوي على SingleDecodeType بالتنسيق مثل "EAN8" أو "EAN13" أو "CodaBar"... للتحويل. |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

إلا فإنه يُعيد نوعًا غير محدد أو SingleDecodeType (-1, "None").
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

