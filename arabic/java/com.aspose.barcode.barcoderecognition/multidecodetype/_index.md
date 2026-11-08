---
title: "MultiDecodeType"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "نوع فك الترميز المركب."
type: docs
weight: 34
url: /ar/java/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

نوع فك الترميز المركب.

يوضح هذا المثال كيفية إنشاء أنواع MultiDecode مركبة تجمع بين SingleDecodeType وأنواع MultiDecode.

```

```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | يُنشئ مثيلاً جديدًا للفئة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | يُنشئ مثيلاً جديدًا للفئة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype). |
## الدوال

| دالة | الوصف |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يضيف نوعًا آخر من [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) إلى MultiDecodeType. |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | تحقق مما إذا كان هذا يحتوي على جميع الأنواع من أنواع الباركود. |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | هل يحتوي على أي من الأنواع |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) محددة. |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | إرجاع قيمة تشير إلى ما إذا كانت مجموعة أنواع فك الترميز هذه تحتوي فقط على قيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) المحددة. |
| [equals(Object obj)](#equals-java.lang.Object-) | إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) محددة. |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | يستثني [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) من الـ MultiDecodeType ويُرجع كائن MultiDecodeType جديد. |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | يمثل قائمة من الأنواع الفردية. |
| [getSingleTypesCount()](#getSingleTypesCount--) | إرجاع عدد من الأنواع الفردية. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | طريقة مُعاد تعريفها تمثل MultiDecodeType كسلسلة نصية. |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ BaseDecodeType إلى مثيله، بعد تحديد النوع الفعلي. |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ MultiDecodeType إلى مثيله. |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | يقوم بتحويل التمثيل النصي لـ SingleDecodeType إلى مثيله. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


يُنشئ مثيلاً جديدًا للفئة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | مصفوفة من أنواع فك الترميز الفردية |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


يُنشئ مثيلاً جديدًا للفئة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | مصفوفة من أنواع فك الترميز المتعددة والفردية |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


يضيف نوعًا آخر من [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) إلى MultiDecodeType.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع فك ترميز فردي يُضاف إلى القائمة |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


تحقق مما إذا كان هذا يحتوي على جميع الأنواع من أنواع الباركود.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع باركود فردية أو متعددة كمدخل |

**Returns:**
منطقي - القيمة تكون true إذا تم تضمين جميع الأنواع في
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


هل يحتوي على أي من الأنواع

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | أنواع فك الترميز |

**Returns:**
boolean - القيمة صحيحة إذا تم تضمين أي نوع في
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | قيمة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


إرجاع قيمة تشير إلى ما إذا كانت مجموعة أنواع فك الترميز هذه تحتوي فقط على قيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | قيمة [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) للمقارنة مع مجموعة أنواع فك الترميز هذه. |

**Returns:**
منطقي -  **true**  إذا كانت هذه المجموعة تحتوي فقط على نوع فك الترميز المحدد؛ وإلا،  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


إرجاع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) محددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


يستثني [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) من الـ MultiDecodeType ويُرجع كائن MultiDecodeType جديد.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | نوع فك ترميز فردي يُستثنى. |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
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


إرجاع عدد من الأنواع الفردية.

**Returns:**
int
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

