---
title: DotCodeExtendedParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن بيانات خاصة لباركود DotCode المعترف به
type: docs
weight: 33
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

يخزن بيانات خاصة لباركود DotCode المعترف به

يعرض هذا المثال كيفية الحصول على القيم الخام لـ DotCode.

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) المحددة. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | يحصل على معرف DotCode في وضع الإلحاق المهيكل للباركود. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | يحصل على معرف DotCode في وضع الإلحاق المهيكل للباركود. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط. |
| [isReaderInitialization()](#isReaderInitialization--) | يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | يعيد قيمة تشير إلى ما إذا كانت قيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) الأولى مساوية للثانية. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | يعيد قيمة تشير إلى ما إذا كانت قيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) الأولى مختلفة عن الثانية. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كان هذا الكائن مساويًا لقيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) المحددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذا الكائن. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


يحصل على معرف DotCode في وضع الإلحاق المهيكل للباركود. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

القيمة: معرف DotCode في وضع الإلحاق المهيكل للباركود.

**Returns:**
int - معرف DotCode في وضع الإلحاق المهيكل للباركود.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

القيمة: عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode.

**Returns:**
int - عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


يحصل على معرف DotCode في وضع الإلحاق المهيكل للباركود. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

القيمة: معرف DotCode في وضع الإلحاق المهيكل للباركود.

**Returns:**
int - معرف DotCode في وضع الإلحاق المهيكل للباركود.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

القيمة: عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode.

**Returns:**
int - عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط.

القيمة: يعيد  **true**  إذا كانت جميع المعلمات لها القيم الافتراضية فقط؛ وإلا،  **false** .

**Returns:**
boolean
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


يعيد قيمة تشير إلى ما إذا كانت قيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) الأولى مساوية للثانية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | قيمة أولى للمقارنة |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | قيمة ثانية للمقارنة |

**Returns:**
boolean -  **true**  إذا كان الأول له نفس القيمة كالثاني؛ وإلا،  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


يعيد قيمة تشير إلى ما إذا كانت قيمة [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) الأولى مختلفة عن الثانية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | قيمة أولى للمقارنة |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | قيمة ثانية للمقارنة |

**Returns:**
boolean -  **true**  إذا كان الأول له قيمة مختلفة عن الثاني؛ وإلا،  **false** .
### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

