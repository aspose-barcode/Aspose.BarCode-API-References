---
title: MultiDecodeType
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: نوع فك الترميز المركب.
type: docs
weight: 37
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

نوع فك الترميز المركب.

يعرض هذا المثال كيفية إنشاء أنواع MultiDecode مركبة تجمع بين SingleDecodeType و MultiDecode.

```

```
## Constructors

| Constructor | الوصف |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | يُهيئ مثالًا جديدًا من فئة MultiDecodeType. |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | يُهيئ مثالًا جديدًا من فئة MultiDecodeType. |
## Methods

| Method | الوصف |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يضيف نوعًا آخر من [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) إلى MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | تحقق مما إذا كان يحتوي هذا على جميع الأنواع من أنواع الباركود. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | هل يحتوي على أي من الأنواع. |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة MultiDecodeType المحددة. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يرجع قيمة تشير إلى ما إذا كانت مجموعة أنواع الفك تحتوي فقط على القيمة المحددة لـ [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة MultiDecodeType المحددة. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يستثني [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) من MultiDecodeType ويعيد نسخة جديدة من MultiDecodeType. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | يمثل قائمة من الأنواع الفردية. |
| [getSingleTypesCount()](#getSingleTypesCount--) | يرجع عددًا من الأنواع الفردية. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | طريقة مُعاد تعريفها تمثل MultiDecodeType كسلسلة نصية. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ BaseDecodeType إلى كائنه، بعد تحديد النوع المحدد. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ MultiDecodeType إلى كائنه. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | تحويل التمثيل النصي لـ SingleDecodeType إلى كائنه. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


يُهيئ مثالًا جديدًا من فئة MultiDecodeType.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | مصفوفة من أنواع الفك الفردية. |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


يُهيئ مثالًا جديدًا من فئة MultiDecodeType.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | مصفوفة من أنواع الفك المتعددة والفردية. |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


يضيف نوعًا آخر من [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) إلى MultiDecodeType.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع DecodeType فردي ليُضاف إلى القائمة. |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


تحقق مما إذا كان يحتوي هذا على جميع الأنواع من أنواع الباركود.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | إدخال أنواع الباركود الفردية أو المتعددة. |

**Returns:**
قيمة منطقية - تكون true إذا تم تضمين جميع الأنواع في.
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


هل يحتوي على أي من الأنواع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع الفك. |

**Returns:**
منطقي - القيمة صحيحة إذا تم تضمين أي نوع في
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة MultiDecodeType المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| أخرى | com.aspose.barcode.barcoderecognition.MultiDecodeType | قيمة MultiDecodeType للمقارنة مع هذه النسخة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


يرجع قيمة تشير إلى ما إذا كانت مجموعة أنواع الفك تحتوي فقط على القيمة المحددة لـ [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | قيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) للمقارنة مع مجموعة أنواع الفك هذه. |

**Returns:**
منطقي - **true** إذا كان هذا التجميع يحتوي فقط على نوع فك الترميز المحدد؛ وإلا، **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه النسخة مساوية لقيمة MultiDecodeType المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


يستثني [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) من MultiDecodeType ويعيد نسخة جديدة من MultiDecodeType.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع فك الترميز الفردي لاستثنائه. |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - كائن MultiDecodeType جديد مع استبعاد SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


يمثل قائمة من الأنواع الفردية.

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - قائمة بالأنواع الفردية
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


يرجع عددًا من الأنواع الفردية.

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


طريقة مُعاد تعريفها تمثل MultiDecodeType كسلسلة نصية.

**Returns:**
java.lang.String - سلسلة تمثل كائن MultiDecodeType كـ "singleDecodeType1, singleDecodeType2, ..."

 **"AllSupportedTypes"**  returns when all types are included.
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

