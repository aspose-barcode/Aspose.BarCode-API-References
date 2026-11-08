---
title: "QrParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات QR."
type: docs
weight: 62
url: /ar/java/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

معلمات QR.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | معرفات تفسير القناة الموسعة. |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) |  |
| [getEncodeMode()](#getEncodeMode--) | نوع ترميز QR لوضع ترميز الباركود. |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء Reed-Solomon لباركود QR وMicroQR وRectMicroQR. |
| [getMicroQRVersion()](#getMicroQRVersion--) | إصدار MicroQR Code. |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | إصدار RectMicroQR Code. |
| [getStructuredAppend()](#getStructuredAppend--) | معلمات الإلحاق الهيكلي لـ QR. |
| [getVersion()](#getVersion--) | إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | معرفات تفسير القناة الموسعة. |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) |  |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | نوع ترميز QR لوضع ترميز الباركود. |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | مستوى تصحيح الأخطاء Reed-Solomon لباركود QR وMicroQR وRectMicroQR. |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | إصدار MicroQR Code. |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | إصدار RectMicroQR Code. |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | معلمات الإلحاق الهيكلي لـ QR. |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلًا للقراءة لهذا [QrParameters](../../com.aspose.barcode.generation/qrparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

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


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR.

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public final boolean getEncodeGS1SeparatorInByteMode()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة GS1 في وضع البايت للباركودات QR وRectMicroQR.

إذا كان false، قد يتم ترميز فواصل GS1 كـ '%' في الوضع الأبجدي الرقمي وفقًا لمواصفات QR.

إذا كان true، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، وتُرمّز أحرف '%' أيضًا في وضع البايت للحفاظ عليها كبيانات.

قد يحسن هذا الخيار التوافق مع المفككات التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

**Returns:**
منطقي - قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة GS1 في وضع البايت لباركودات QR وRectMicroQR.
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


مستوى تصحيح الأخطاء Reed-Solomon لباركود QR وMicroQR وRectMicroQR. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH. راجع QERrrorLevel.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
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


معلمات الإلحاق المُنظم لرمز QR. وضع الإلحاق المُنظم غير مدعوم من قبل باركودات MicroQR وRectMicroQR.

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. القيمة الافتراضية هي QRVersion.Auto.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public final int hashCode()
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


نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


معرفات تفسير القناة الموسعة. تُستخدم لإبلاغ قارئ الباركود بتفاصيل حول المراجع المستخدمة لترميز البيانات في الرمز. التنفيذ الحالي يتضمن جميع ترميزات مجموعة الأحرف المعروفة. غير مدعوم من قبل MicroQR.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public final void setEncodeGS1SeparatorInByteMode(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة GS1 في وضع البايت للباركودات QR وRectMicroQR.

إذا كان false، قد يتم ترميز فواصل GS1 كـ '%' في الوضع الأبجدي الرقمي وفقًا لمواصفات QR.

إذا كان true، يتم ترميز فواصل مجموعة GS1 في وضع البايت كحرف 0x1D، وتُرمّز أحرف '%' أيضًا في وضع البايت للحفاظ عليها كبيانات.

قد يحسن هذا الخيار التوافق مع المفككات التي تتوقع فواصل مجموعة GS1 على مستوى البايت ويمنع تفسير أحرف البيانات '%' كفواصل GS1.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كان يجب ترميز الأحرف الخاصة GS1 في وضع البايت لباركودات QR وRectMicroQR. |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


نوع ترميز QR لوضع ترميز الباركود. القيمة الافتراضية: QREncodeMode.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


مستوى تصحيح الأخطاء Reed-Solomon لباركود QR وMicroQR وRectMicroQR. من منخفض إلى عالي: LevelL، LevelM، LevelQ، LevelH. راجع QERrrorLevel.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


إصدار رمز MicroQR. من الإصدار M1 إلى الإصدار M4. القيمة الافتراضية هي MicroQRVersion.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


إصدار رمز RectMicroQR. من الإصدار R7x59 إلى الإصدار R17x139. القيمة الافتراضية هي RectMicroQRVersion.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


معلمات الإلحاق المُنظم لرمز QR. وضع الإلحاق المُنظم غير مدعوم من قبل باركودات MicroQR وRectMicroQR.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


إصدار رمز QR. من الإصدار 1 إلى الإصدار 40. القيمة الافتراضية هي QRVersion.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا قابلًا للقراءة لهذا [QrParameters](../../com.aspose.barcode.generation/qrparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [QrParameters](../../com.aspose.barcode.generation/qrparameters).
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

