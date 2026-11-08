---
title: "معلمات Aztec"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات Aztec."
type: docs
weight: 12
url: /ar/java/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

معلمات Aztec.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | يحصل على ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحصل على وضع تشفير Aztec. |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [getLayersCount()](#getLayersCount--) | يحصل على عدد الطبقات لرمز Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | معرّف الباركود لوضع الإلحاق الهيكلي لباركود Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | عدد الباركودات لوضع الإلحاق الهيكلي لباركود Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | معرّف الملف لوضع الإلحاق الهيكلي لباركود Aztec (حقل اختياري). |
| [getSymbolMode()](#getSymbolMode--) | يحصل على وضع رمز Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | يضبط وضع تشفير Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | يضبط عدد الطبقات لرمز Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | معرّف الباركود لوضع الإلحاق الهيكلي لباركود Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | عدد الباركودات لوضع الإلحاق الهيكلي لباركود Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | معرّف الملف لوضع الإلحاق الهيكلي لباركود Aztec (حقل اختياري). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | يضبط وضع رمز Aztec. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا قابلاً للقراءة لهذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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


يحصل على ترميز ECI. يُستخدم عندما يكون AztecEncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1.

**Returns:**
int - ترميز ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - وضع ترميز Aztec.
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


يحصل على عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المضغوط ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي).

**Returns:**
int - عدد الطبقات لرمز Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


معرّف الباركود لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


عدد الباركودات لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


معرّف الملف لوضع الإلحاق المُنظم لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


يحصل على وضع رمز أزتك. القيمة الافتراضية: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

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


يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode تلقائيًا. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.generation.AztecEncodeMode | وضع ترميز Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 و 95.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


يضبط عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المضغوط ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي).

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد الطبقات لرمز Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


معرّف الباركود لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


عدد الباركودات لوضع الإلحاق المُنظم لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


معرّف الملف لوضع الإلحاق المُنظم لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


يضبط وضع رمز أزتك. القيمة الافتراضية: AztecSymbolMode.Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | وضع رمز أزتك. |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا قابلاً للقراءة لهذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

