---
title: QrParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات QR.
type: docs
weight: 64
url: /ar/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

معلمات QR.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getEncodeMode()](#getEncodeMode--) | نوع ترميز QR في وضع ترميز الباركود. |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon لباركودات QR وMicroQR وRectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | إصدار MicroQR Code. |
| [getQrECIEncoding()](#getQrECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getQrEncodeMode()](#getQrEncodeMode--) | نوع ترميز QR في وضع ترميز الباركود. |
| [getQrEncodeType()](#getQrEncodeType--) | وضع اختيار QR / MicroQR. |
| [getQrErrorLevel()](#getQrErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon لباركودات QR وMicroQR وRectMicroQR. |
| [getQrVersion()](#getQrVersion--) | إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | إصدار RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | معلمات الإلحاق الهيكلي ل QR. |
| [getVersion()](#getVersion--) | إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | نوع ترميز QR في وضع ترميز الباركود. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | مستوى تصحيح الأخطاء Reed-Solomon لباركودات QR وMicroQR وRectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | إصدار MicroQR Code. |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | وضع اختيار QR / MicroQR. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | إصدار RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | معلمات الإلحاق الهيكلي ل QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يشمل جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم بواسطة MicroQR.

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


نوع ترميز QR في وضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


مستوى تصحيح الأخطاء Reed‑Solomon للباركود QR و MicroQR و RectMicroQR. من منخفض إلى مرتفع: LevelL، LevelM، LevelQ، LevelH. راجع QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يشمل جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم بواسطة MicroQR.

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


نوع ترميز QR في وضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR.

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


مستوى تصحيح الأخطاء Reed‑Solomon للباركود QR و MicroQR و RectMicroQR. من منخفض إلى مرتفع: LevelL، LevelM، LevelQ، LevelH. راجع QRErrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


إصدار رمز QR. من الإصدار Version1 إلى الإصدار Version40. القيمة الافتراضية هي QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


معلمات الإلحاق المهيكل QR. وضع الإلحاق المهيكل غير مدعوم من قبل باركودات MicroQR و RectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


إصدار رمز QR. من الإصدار Version1 إلى الإصدار Version40. القيمة الافتراضية هي QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يشمل جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم بواسطة MicroQR.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


نوع ترميز QR في وضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


مستوى تصحيح الأخطاء Reed‑Solomon للباركود QR و MicroQR و RectMicroQR. من منخفض إلى مرتفع: LevelL، LevelM، LevelQ، LevelH. راجع QRErrorLevel.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


وضع محدد QR / MicroQR. اختر ForceQR للرموز القياسية QR، Auto لـ MicroQR.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


معلمات الإلحاق المهيكل QR. وضع الإلحاق المهيكل غير مدعوم من قبل باركودات MicroQR و RectMicroQR.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


إصدار رمز QR. من الإصدار Version1 إلى الإصدار Version40. القيمة الافتراضية هي QRVersion.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

