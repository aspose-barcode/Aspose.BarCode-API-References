---
title: AztecParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات Aztec.
type: docs
weight: 12
url: /ar/androidjava/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

معلمات Aztec.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [getAztecEncodeMode()](#getAztecEncodeMode--) | يحصل على وضع ترميز Aztec. |
| [getAztecErrorLevel()](#getAztecErrorLevel--) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [getAztecSymbolMode()](#getAztecSymbolMode--) | يحصل على وضع رمز Aztec. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | يسترجع ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحصل على وضع ترميز Aztec. |
| [getErrorLevel()](#getErrorLevel--) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [getLayersCount()](#getLayersCount--) | يحصل على عدد الطبقات لرمز Aztec. |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | عدد الباركودات لوضع الإلحاق المهيكل لباركود Aztec. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). |
| [getSymbolMode()](#getSymbolMode--) | يحصل على وضع رمز Aztec. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [setAztecEncodeMode(AztecEncodeMode value)](#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | يضبط وضع ترميز Aztec. |
| [setAztecErrorLevel(int value)](#setAztecErrorLevel-int-) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [setAztecSymbolMode(AztecSymbolMode value)](#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | يضبط وضع رمز Aztec. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | يضبط وضع ترميز Aztec. |
| [setErrorLevel(int value)](#setErrorLevel-int-) | مستوى تصحيح الأخطاء لأنواع باركود Aztec. |
| [setLayersCount(int value)](#setLayersCount-int-) | يضبط عدد الطبقات لرمز Aztec. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ. |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | عدد الباركودات لوضع الإلحاق المهيكل لباركود Aztec. |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | يضبط وضع رمز Aztec. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters). |
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
### getAztecEncodeMode() {#getAztecEncodeMode--}
```
public final AztecEncodeMode getAztecEncodeMode()
```


يحصل على وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - وضع ترميز Aztec.
### getAztecErrorLevel() {#getAztecErrorLevel--}
```
public final int getAztecErrorLevel()
```


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 إلى 95.

**Returns:**
int
### getAztecSymbolMode() {#getAztecSymbolMode--}
```
public final AztecSymbolMode getAztecSymbolMode()
```


يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


يحصل على ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Returns:**
عدد صحيح - ترميز ECI.
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


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 إلى 95.

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


يحصل على عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المدمج ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي).

**Returns:**
int - عدد الطبقات لرمز Aztec.
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


عدد الباركودات لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


يحصل على وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
### hashCode() {#hashCode--}
```
public native int hashCode()
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


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setAztecEncodeMode(AztecEncodeMode value) {#setAztecEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setAztecEncodeMode(AztecEncodeMode value)
```


يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.generation.AztecEncodeMode | وضع ترميز Aztec. |

### setAztecErrorLevel(int value) {#setAztecErrorLevel-int-}
```
public final void setAztecErrorLevel(int value)
```


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 إلى 95.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setAztecSymbolMode(AztecSymbolMode value) {#setAztecSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setAztecSymbolMode(AztecSymbolMode value)
```


يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | وضع رمز Aztec. |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يضبط ترميز ECI. يُستخدم عندما يكون AztecEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


يضبط وضع ترميز Aztec. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.barcode.generation.AztecEncodeMode | وضع ترميز Aztec. |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


مستوى تصحيح الأخطاء لأنواع باركود Aztec. يجب أن تكون القيمة بين 5 إلى 95.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


يضبط عدد الطبقات لرمز Aztec. يجب أن يكون عدد الطبقات في النطاق من 1 إلى 3 للوضع المدمج ومن 1 إلى 32 للوضع الكامل. القيمة الافتراضية: 0 (تلقائي).

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int | عدد الطبقات لرمز Aztec. |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يُستخدم لإرشاد القارئ لتفسير البيانات الموجودة داخل الرمز كبرمجة لتهيئة القارئ.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


معرّف الباركود لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون معرّف الباركود في النطاق من 1 إلى عدد الباركودات. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


عدد الباركودات لوضع الإلحاق المهيكل لباركود Aztec. يجب أن يكون عدد الباركودات في النطاق من 1 إلى 26. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


معرّف الملف لوضع الإلحاق المهيكل لباركود Aztec (حقل اختياري). يجب ألا يحتوي معرّف الملف على مسافات. القيمة الافتراضية: سلسلة فارغة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


يضبط وضع رمز Aztec. القيمة الافتراضية: AztecSymbolMode.Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | وضع رمز Aztec. |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا قابلًا للقراءة البشرية لهذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [AztecParameters](../../com.aspose.barcode.generation/aztecparameters).
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

