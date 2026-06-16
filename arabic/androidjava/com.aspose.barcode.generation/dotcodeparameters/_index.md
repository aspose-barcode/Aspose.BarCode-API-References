---
title: DotCodeParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات DotCode.
type: docs
weight: 36
url: /ar/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

معلمات DotCode.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد. |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
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
### getColumns() {#getColumns--}
```
public final int getColumns()
```


يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


يحدد معرف (ID) الباركود في وضع الإلحاق الهيكلي لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


يحدد عدد الباركودات في وضع الإلحاق الهيكلي لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


يحدد معرف (ID) الباركود في وضع الإلحاق الهيكلي لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


يحدد عدد الباركودات في وضع الإلحاق الهيكلي لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

**Returns:**
int
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public final void setAspectRatio(float value)
```


نسبة الارتفاع إلى العرض لوحدة الباركود ثنائية الأبعاد.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


يحدد عدد الأعمدة. يجب أن يكون مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الأعمدة على الأقل 5. القيمة الافتراضية: -1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


يحدد معرف (ID) الباركود في وضع الإلحاق الهيكلي لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


يحدد عدد الباركودات في وضع الإلحاق الهيكلي لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


يحدد ترميز ECI. يُستخدم عندما يكون DotCodeEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


يحدد وضع ترميز DotCode. القيمة الافتراضية: Auto.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


يشير إلى ما إذا كان يتم استخدام الشيفرة لتوجيه القارئ لتفسير البيانات التالية كتعليمات للتهيئة أو إعادة برمجة قارئ الباركود. القيمة الافتراضية هي false.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


يحدد عدد الصفوف. يجب أن يكون مجموع عدد الصفوف زائد عدد الأعمدة لرمز DotCode عددًا فرديًا. يجب أن يكون عدد الصفوف على الأقل 5. القيمة الافتراضية: -1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


يحدد معرف (ID) الباركود في وضع الإلحاق الهيكلي لـ DotCode. يبدأ المعرف من 1 ويجب أن يكون أقل أو يساوي عدد الباركودات. القيمة الافتراضية هي -1.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


يحدد عدد الباركودات في وضع الإلحاق الهيكلي لـ DotCode. القيمة الافتراضية هي -1. يجب أن يكون العدد قيمة من 1 إلى 35.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).
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

