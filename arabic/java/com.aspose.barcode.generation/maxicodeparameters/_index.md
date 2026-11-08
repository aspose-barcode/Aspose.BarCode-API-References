---
title: "MaxiCodeParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات MaxiCode."
type: docs
weight: 55
url: /ar/java/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

معلمات MaxiCode.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | يحصل على ترميز ECI. |
| [getEncodeMode()](#getEncodeMode--) | يحصل على وضع ترميز MaxiCode. |
| [getMode()](#getMode--) | يحصل على وضع ترميز MaxiCode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | يحصل على معرف الباركود MaxiCode في وضع الإلحاق المُنظم. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | يحصل على عدد باركودات MaxiCode في وضع الإلحاق المُنظم. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | نسبة الارتفاع/العرض لوحدة الباركود ثنائي الأبعاد. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | يضبط ترميز ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | يضبط وضع ترميز MaxiCode. |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | يضبط وضع ترميز MaxiCode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | يضبط معرف الباركود MaxiCode في وضع الإلحاق المُنظم. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | يضبط عدد باركودات MaxiCode في وضع الإلحاق المُنظم. |
| [toString()](#toString--) | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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


يحصل على ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode على الوضع التلقائي. القيمة الافتراضية: ISO-8859-1

**Returns:**
int - ترميز ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


يحصل على وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


يحصل على وضع ترميز MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


يحصل على معرف باركود MaxiCode في وضع الإلحاق المُنظم. يجب أن يكون المعرف قيمة بين 1 و 8. القيمة الافتراضية: 0

**Returns:**
int - معرف باركود MaxiCode في وضع الإلحاق المُنظم.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


يحصل على عدد باركودات MaxiCode في وضع الإلحاق المُنظم. يجب أن يكون عدد العد قيمة بين 2 و 8 (الحد الأقصى لعدد الباركودات). القيمة الافتراضية: -1

**Returns:**
int - عدد باركودات MaxiCode في وضع الإلحاق المُنظم.
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


يضبط ترميز ECI. يُستخدم عندما يكون MaxiCodeEncodeMode هو Auto. القيمة الافتراضية: ISO-8859-1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | ترميز ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


يضبط وضع ترميز MaxiCode. القيمة الافتراضية: Auto.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | وضع ترميز MaxiCode. |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


يضبط وضع ترميز MaxiCode.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | وضع ترميز MaxiCode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


يضبط معرف باركود MaxiCode في وضع الإلحاق المُنظم. يجب أن يكون المعرف قيمة بين 1 و 8. القيمة الافتراضية: 0

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | معرف الباركود MaxiCode في وضع الإلحاق المهيكل. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


يضبط عدد باركودات MaxiCode في وضع الإلحاق المهيكل. يجب أن يكون رقم العدد قيمة بين 2 و 8 (الحد الأقصى لعدد الباركودات). القيمة الافتراضية: -1

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int | عدد باركودات MaxiCode في وضع الإلحاق المهيكل. |

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - سلسلة تمثل هذا [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

