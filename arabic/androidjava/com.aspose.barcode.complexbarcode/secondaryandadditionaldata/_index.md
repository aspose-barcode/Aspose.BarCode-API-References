---
title: SecondaryAndAdditionalData
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC.
type: docs
weight: 35
url: /ar/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

فئة لتخزين البيانات الثانوية والإضافية لـ HIBC LIC.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  SecondaryAndAdditionalData  محددة. |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | يحدد تاريخ الصنع. |
| [getExpiryDate()](#getExpiryDate--) | يحدد تاريخ الانتهاء. |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | يحدد تنسيق تاريخ الانتهاء. |
| [getLotNumber()](#getLotNumber--) | يحدد رقم الدفعة أو اللوط. |
| [getQuantity()](#getQuantity--) | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. |
| [getSerialNumber()](#getSerialNumber--) | يحدد الرقم التسلسلي. |
| [hashCode()](#hashCode--) | يعيد قيمة تجزئة (hash code) لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | ينشئ البيانات الثانوية والإضافية التكميلية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | يحدد تاريخ الصنع. |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | يحدد تاريخ الانتهاء. |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | يحدد تنسيق تاريخ الانتهاء. |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | يحدد رقم الدفعة أو اللوط. |
| [setQuantity(int value)](#setQuantity-int-) | يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | يحدد الرقم التسلسلي. |
| [toString()](#toString--) | يحوّل البيانات إلى تنسيق السلسلة وفقًا لمواصفات HIBC LIC. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يرجع قيمة تشير إلى ما إذا كانت هذه المثيلة مساوية لقيمة  SecondaryAndAdditionalData  محددة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | قيمة  SecondaryAndAdditionalData  للمقارنة مع هذه المثيلة. |

**Returns:**
boolean -  **true**  إذا كان obj له نفس القيمة كما هذا الكائن؛ وإلا،  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


يحدد تاريخ الصنع. يمكن تعيين تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم تعيين ExpiryDateFormat إلى None.

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


يحدد تنسيق تاريخ الانتهاء.

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول أقصى 18 رمزًا.

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن تعيين الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول أقصى 18 رمزًا.

**Returns:**
java.lang.String
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




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


ينشئ البيانات الثانوية والإضافية التكميلية من تنسيق السلسلة وفقًا لمواصفات HIBC LIC.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | سلسلة منسقة. |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


يحدد تاريخ الصنع. يمكن تعيين تاريخ الصنع إلى DateTime.MinValue لعدم استخدام هذا الحقل. القيمة الافتراضية: DateTime.MinValue

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


يحدد تاريخ الانتهاء. سيُستخدم إذا لم يتم تعيين ExpiryDateFormat إلى None.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


يحدد تنسيق تاريخ الانتهاء.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


يحدد رقم الدفعة أو اللوط. يجب أن يكون رقم الدفعة/اللوط سلسلة أبجدية رقمية بطول أقصى 18 رمزًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


يحدد الكمية، يجب أن تكون قيمة صحيحة من 0 إلى 500. يمكن تعيين الكمية إلى -1 لعدم استخدام هذا الحقل. القيمة الافتراضية: -1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


يحدد الرقم التسلسلي. يجب أن يكون الرقم التسلسلي سلسلة أبجدية رقمية بطول أقصى 18 رمزًا.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

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

