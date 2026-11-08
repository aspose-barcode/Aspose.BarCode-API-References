---
title: "QRExtendedParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "يخزن معلومات إلحاق منظم QR لرمز الباركود المعترف به"
type: docs
weight: 38
url: /ar/java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

يخزن معلومات إلحاق منظم QR لرمز الباركود المعترف به

يعرض هذا المثال كيفية الحصول على بيانات QR Structured Append

```
{
```
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) المحددة. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. |
| [getMicroQRVersion()](#getMicroQRVersion--) | إصدار MicroQR Code المعترف به. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | إصدار RectMicroQR Code المعترف به. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | يحصل على فهرس الباركود في وضع الإلحاق الهيكلي QR. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | يحصل على عدد الباركودات في وضع الإلحاق الهيكلي QR. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | يحصل على بيانات التماثل في وضع الإلحاق الهيكلي QR. |
| [getVersion()](#getVersion--) | إصدار QR Code المعترف به. |
| [hashCode()](#hashCode--) | يعيد رمز التجزئة لهذه المثيلة. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) المحددة.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة System.Object للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كهذه المثيلة؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


إصدار MicroQR Code المعترف به. من M1 إلى M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


إصدار RectMicroQR Code المعترف به. من R7x43 إلى R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


يحصل على فهرس الباركود في وضع الإلحاق الهيكلي QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1.

القيمة: عدد الباركودات في وضع الإلحاق الهيكلي QR.

**Returns:**
int - فهرس الباركود في وضع الإلحاق الهيكلي QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


يحصل على عدد الباركودات في وضع الإلحاق الهيكلي QR. القيمة الافتراضية هي -1.

القيمة: عدد الباركودات في وضع الإلحاق الهيكلي QR.

**Returns:**
int - عدد الباركودات في وضع الإلحاق الهيكلي QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


يحصل على بيانات التماثل في وضع الإلحاق الهيكلي QR. القيمة الافتراضية هي -1.

القيمة: فهرس الباركود في وضع الإلحاق الهيكلي QR.

**Returns:**
int - بيانات التماثل في وضع الإلحاق الهيكلي QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


إصدار QR Code المعترف به. من Version1 إلى Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز التجزئة لهذه المثيلة.

**Returns:**
int - رمز تجزئة عدد صحيح موقع 32-بت.
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


يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

