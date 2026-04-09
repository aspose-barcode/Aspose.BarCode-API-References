---
title: PrimaryData
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتخزين البيانات الأولية لـ HIBC LIC.
type: docs
weight: 34
url: /ar/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

فئة لتخزين البيانات الأولية لـ HIBC LIC.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  PrimaryData  محددة. |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | يحدد تاريخ رمز تعريف الملصق. |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | يحدد رقم المنتج أو الكتالوج. |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | يحدد معرف وحدة القياس. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | ينشئ البيانات الأولية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | يحدد تاريخ رمز تعريف الملصق. |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | يحدد رقم المنتج أو الكتالوج. |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | يحدد معرف وحدة القياس. |
| [toString()](#toString--) | يحوّل البيانات إلى تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  PrimaryData  محددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة PrimaryData للمقارنة مع هذه الحالة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق سلسلة أبجدية رقمية مكوّنة من 4 رموز، مع أن الحرف الأول يجب أن يكون أبجديًا دائمًا.

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


يحدد رقم المنتج أو الكتالوج. يجب أن يكون رقم المنتج أو الكتالوج سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة صحيحة من 0 إلى 9.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة تجزئة (hash code) لهذا الكائن.

**Returns:**
int - رمز تجزئة (hash code) عدد صحيح موقع 32 بت.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


ينشئ البيانات الأولية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | سلسلة منسقة. |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


يحدد تاريخ رمز تعريف الملصق. يجب أن يكون رمز تعريف الملصق سلسلة أبجدية رقمية مكوّنة من 4 رموز، مع أن الحرف الأول يجب أن يكون أبجديًا دائمًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


يحدد رقم المنتج أو الكتالوج. يجب أن يكون رقم المنتج أو الكتالوج سلسلة أبجدية رقمية بطول يصل إلى 18 رمزًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


يحدد معرف وحدة القياس. يجب أن يكون معرف وحدة القياس قيمة صحيحة من 0 إلى 9.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### toString() {#toString--}
```
public String toString()
```


يحوّل البيانات إلى تنسيق السلسلة وفقًا لمواصفات HIBC LIC.

**Returns:**
java.lang.String - سلسلة منسقة.
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

