---
title: "BaseDecodeType"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "الفئة الأساسية لـ MultiDecodeType و SingleDecodeType."
type: docs
weight: 22
url: /ar/java/com.aspose.barcode.barcoderecognition/basedecodetype/
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
## الدوال

| دالة | الوصف |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | يحدد ما إذا كان أي من أنواع فك الترميز المعطاة مدرجًا في |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة. |
| [equals(Object other)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ BaseDecodeType إلى مثيله، بعد تحديد النوع الفعلي. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ MultiDecodeType إلى مثيله. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ SingleDecodeType إلى مثيله. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


يحدد ما إذا كان أي من أنواع فك الترميز المعطاة مدرجًا في

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | الأنواع للتحقق منها. |

**Returns:**
boolean - القيمة صحيحة إذا كان أي نوع مدرجًا في.
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean - صحيح إذا كان obj له نفس القيمة كما هذه المثيلة؛ وإلا، خطأ.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean - صحيح إذا كان obj له نفس القيمة كما هذه المثيلة؛ وإلا، خطأ.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | java.lang.Object | قيمة java.lang.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean - صحيح إذا كان obj له نفس القيمة كما هذه المثيلة؛ وإلا، خطأ.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
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

