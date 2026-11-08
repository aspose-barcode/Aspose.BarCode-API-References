---
title: "DotCodeParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات DotCode."
type: docs
weight: 34
url: /ar/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

معلمات DotCode.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | يحدد عدد الأعمدة. |
| [getECIEncoding()](#getECIEncoding--) | يحدد ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحدد وضع ترميز DotCode. |
| [getRows()](#getRows--) | يحدد عدد الصفوف. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | يحدد معرف الباركود في وضع الإلحاق المهيكل لـ DotCode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | يحدد عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setColumns(int value)](#setColumns-int-) | يحدد عدد الأعمدة. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يحدد ترميز ECI. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | يحدد وضع ترميز DotCode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يشير إلى ما إذا كان الرمز يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [setRows(int value)](#setRows-int-) | يحدد عدد الصفوف. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | يحدد معرف الباركود في وضع الإلحاق المهيكل لـ DotCode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | يحدد عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode وضعًا تلقائيًا. القيمة الافتراضية: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: تلقائي.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


يحدد معرف الباركود في وضع الإلحاق المهيكل لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


يحدد عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35.

**Returns:**
int
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


يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

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

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode وضعًا تلقائيًا. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: تلقائي.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يشير إلى ما إذا كان الكود يُستخدم لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف وعدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


يحدد معرف الباركود في وضع الإلحاق المهيكل لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


يحدد عدد الباركودات في وضع الإلحاق المهيكل لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة بين 1 و 35.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

