---
title: QRExtendedParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يخزن معلومات QR Structured Append لباركود معترف به
type: docs
weight: 42
url: /ar/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

يخزن معلومات QR Structured Append لباركود معترف به

يعرض هذا المثال كيفية الحصول على بيانات QR Structured Append

```
{
```
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) المحددة. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. |
| [getMicroQRVersion()](#getMicroQRVersion--) | إصدار MicroQR Code المعترف به. |
| [getQRErrorLevel()](#getQRErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | يحصل على فهرس الباركود في وضع QR structured append. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | يحصل على عدد الباركودات في وضع QR structured append. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | يحصل على بيانات التوازن لوضع الإلحاق المهيكل للـ QR. |
| [getQRVersion()](#getQRVersion--) | إصدار رمز QR المعترف به. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | إصدار رمز RectMicroQR المعترف به. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | يحصل على فهرس الباركود في وضع QR structured append. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | يحصل على عدد الباركودات في وضع QR structured append. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | يحصل على بيانات التوازن لوضع الإلحاق المهيكل للـ QR. |
| [getVersion()](#getVersion--) | إصدار رمز QR المعترف به. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [isEmpty()](#isEmpty--) | يفحص ما إذا كانت جميع المعلمات لها القيم الافتراضية فقط. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | يعيد قيمة تشير إلى ما إذا كانت قيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) الأولى مساوية للثانية. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | يعيد قيمة تشير إلى ما إذا كانت قيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) الأولى مختلفة عن الثانية. |
| [toString()](#toString--) | يعيد تمثيلاً نصيًا مقروءًا للإنسان لهذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يعيد قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) المحددة.

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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ، LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


إصدار رمز MicroQR المعترف به. من M1 إلى M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon للباركود المعترف به. من الأقل إلى الأعلى: LevelL، LevelM، LevelQ، LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


يحصل على فهرس الباركود في وضع الإلحاق المهيكل للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1.

القيمة: عدد الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - فهرس الباركود في وضع الإلحاق المهيكل للـ QR.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل للـ QR. القيمة الافتراضية هي -1.

القيمة: عدد الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - عدد الباركودات في وضع الإلحاق المهيكل للـ QR.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


يحصل على بيانات التوازن لوضع الإلحاق المهيكل للـ QR. القيمة الافتراضية هي -1.

القيمة: فهرس الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - بيانات التوازن لوضع الإلحاق المهيكل للـ QR.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


إصدار رمز QR المعترف به. من Version1 إلى Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


إصدار رمز RectMicroQR المعترف به. من R7x43 إلى R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


يحصل على فهرس الباركود في وضع الإلحاق المهيكل للـ QR. يبدأ الفهرس من 0. القيمة الافتراضية هي -1.

القيمة: عدد الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - فهرس الباركود في وضع الإلحاق المهيكل للـ QR.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


يحصل على عدد الباركودات في وضع الإلحاق المهيكل للـ QR. القيمة الافتراضية هي -1.

القيمة: عدد الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - عدد الباركودات في وضع الإلحاق المهيكل للـ QR.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


يحصل على بيانات التوازن لوضع الإلحاق المهيكل للـ QR. القيمة الافتراضية هي -1.

القيمة: فهرس الباركود في وضع الإلحاق المهيكل للـ QR.

**Returns:**
int - بيانات التوازن لوضع الإلحاق المهيكل للـ QR.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


إصدار رمز QR المعترف به. من Version1 إلى Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


يعيد قيمة تشير إلى ما إذا كانت قيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) الأولى مساوية للثانية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | قيمة أولى للمقارنة |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | قيمة ثانية للمقارنة |

**Returns:**
boolean -  **true**  إذا كان الأول له نفس القيمة كالثاني؛ وإلا،  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


يعيد قيمة تشير إلى ما إذا كانت قيمة [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) الأولى مختلفة عن الثانية.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | قيمة أولى للمقارنة |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | قيمة ثانية للمقارنة |

**Returns:**
boolean -  **true**  إذا كان الأول له قيمة مختلفة عن الثاني؛ وإلا،  **false** .
### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلاً نصيًا مقروءًا للإنسان لهذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - نص يمثل هذا [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

