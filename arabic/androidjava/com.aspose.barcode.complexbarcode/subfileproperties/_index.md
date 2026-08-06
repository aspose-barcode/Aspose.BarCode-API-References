---
title: USADriveIdCodetext.SubfileProperties
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: يتم ضبط إزاحة وطول خصائص ملف فرعي رخصة القيادة الأمريكية تلقائيًا.
type: docs
weight: 12
url: /ar/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

خصائص ملف فرعي لرخصة القيادة الأمريكية، الإزاحة والطول يتم ضبطها تلقائيًا.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 تحتوي هذه البايتات على قيمة رقمية مكوّنة من 4 أرقام تحدد طول الملف الفرعي بالبايت. يجب تضمين محدد القطعة عند حساب طول الملف الفرعي. محدد القطعة = 1. |
| [getOffset()](#getOffset--) | قيمة رقمية مكوّنة من 4 أرقام تحدد عدد البايتات من بداية الملف إلى الموقع الذي توجد فيه البيانات المتعلقة بالملف الفرعي المحدد. البايت الأول في الملف يقع عند الإزاحة 0. |
| [getType()](#getType--) | نوع الملف الفرعي من 2 بايت، مثل "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 تحتوي هذه البايتات على قيمة رقمية مكوّنة من 4 أرقام تحدد طول الملف الفرعي بالبايت. يجب تضمين محدد القطعة عند حساب طول الملف الفرعي. محدد القطعة = 1. |
| [setOffset(int value)](#setOffset-int-) | قيمة رقمية مكوّنة من 4 أرقام تحدد عدد البايتات من بداية الملف إلى الموقع الذي توجد فيه البيانات المتعلقة بالملف الفرعي المحدد. البايت الأول في الملف يقع عند الإزاحة 0. |
| [setType(String value)](#setType-java.lang.String-) | نوع الملف الفرعي من 2 بايت، مثل "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| نوع | java.lang.String |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


4 تحتوي هذه البايتات على قيمة رقمية مكوّنة من 4 أرقام تحدد طول الملف الفرعي بالبايت. يجب تضمين محدد القطعة عند حساب طول الملف الفرعي. محدد القطعة = 1. يجب أن يبدأ كل ملف فرعي بنوع الملف الفرعي المكوّن من حرفين ويجب أيضًا تضمين هذين الحرفين في الطول.

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


قيمة رقمية مكوّنة من 4 أرقام تحدد عدد البايتات من بداية الملف إلى الموقع الذي توجد فيه البيانات المتعلقة بالملف الفرعي المحدد. البايت الأول في الملف يقع عند الإزاحة 0.

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


نوع الملف الفرعي من 2 بايت، مثل "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 تحتوي هذه البايتات على قيمة رقمية مكوّنة من 4 أرقام تحدد طول الملف الفرعي بالبايت. يجب تضمين محدد القطعة عند حساب طول الملف الفرعي. محدد القطعة = 1. يجب أن يبدأ كل ملف فرعي بنوع الملف الفرعي المكوّن من حرفين ويجب أيضًا تضمين هذين الحرفين في الطول.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


قيمة رقمية مكوّنة من 4 أرقام تحدد عدد البايتات من بداية الملف إلى الموقع الذي توجد فيه البيانات المتعلقة بالملف الفرعي المحدد. البايت الأول في الملف يقع عند الإزاحة 0.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


نوع الملف الفرعي من 2 بايت، مثل "DL"

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

