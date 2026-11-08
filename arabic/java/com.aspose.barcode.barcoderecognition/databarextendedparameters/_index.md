---
title: "DataBarExtendedParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن معلومات إضافية لـ DataBar للباركود المُعترف به BarCodeReader reader  new BarCodeReaderctest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity"
type: docs
weight: 28
url: /ar/java/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

يخزن معلومات إضافية لرمز DataBar المعترف به BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة DataBarExtendedParameters المحددة. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | يحصل على علم المكوّن المركب لـ DataBar ثنائي الأبعاد. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلاً نصيًا مقروءًا للإنسان لهذا الكائن DataBarExtendedParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه الحالة مساوية لقيمة DataBarExtendedParameters المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
منطقي - **true** إذا كان obj له نفس القيمة كما هذه الحالة؛ وإلا، **false**.
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


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


يحصل على علم المكوّن المركب لـ DataBar ثنائي الأبعاد. القيمة الافتراضية هي false.

**Returns:**
منطقي - علم المكوّن المركب لـ DataBar ثنائي الأبعاد.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية.

القيمة: تُعيد  **true**  إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية؛ وإلا،  **false** .

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




### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلاً نصيًا مقروءًا للإنسان لهذا الكائن DataBarExtendedParameters.

**Returns:**
java.lang.String - سلسلة تمثل هذا الكائن DataBarExtendedParameters.
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

