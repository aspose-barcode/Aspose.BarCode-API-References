---
title: العنوان
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: عنوان الدائن أو المدين.
type: docs
weight: 10
url: /ar/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

عنوان الدائن أو المدين.

يمكنك إما تعيين الشارع، رقم المنزل، الرمز البريدي والمدينة (type  *structured address* ) أو سطر العنوان 1 و2 (type  *combined address elements* ). يتم تعيين النوع تلقائيًا بمجرد تعيين أي من هذه الحقول. قبل تعيين الحقول، يكون نوع العنوان *undetermined*. إذا تم تعيين حقول من كلا النوعين، يصبح نوع العنوان *conflicting*. يجب دائمًا تعيين الاسم ورمز الدولة ما لم تكن جميع الحقول فارغة.
## Constructors

| Constructor | الوصف |
| --- | --- |
| [Address()](#Address--) | ينشئ نسخة من Address |
## Methods

| Method | الوصف |
| --- | --- |
| [clear()](#clear--) | يمسح جميع الحقول ويضبط النوع إلى AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [getAddressLine1()](#getAddressLine1--) | يحصل على سطر العنوان 1. |
| [getAddressLine2()](#getAddressLine2--) | يحصل على سطر العنوان 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | يحصل على رمز البلد ISO المكوّن من حرفين. |
| [getHouseNo()](#getHouseNo--) | يحصل على رقم المنزل. |
| [getName()](#getName--) | يحصل على الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [getPostalCode()](#getPostalCode--) | يحصل على الرمز البريدي. |
| [getStreet()](#getStreet--) | يحصل على الشارع. |
| [getTown()](#getTown--) | يحصل على البلدة أو المدينة. |
| [getType()](#getType--) | يحصل على نوع العنوان. |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | يضبط سطر العنوان 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | يضبط سطر العنوان 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | يضبط رمز البلد ISO المكوّن من حرفين. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | يضبط رقم المنزل. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | يضبط الرمز البريدي. |
| [setStreet(String value)](#setStreet-java.lang.String-) | يضبط الشارع. |
| [setTown(String value)](#setTown-java.lang.String-) | يضبط البلدة أو المدينة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


ينشئ نسخة من Address

### clear() {#clear--}
```
public void clear()
```


يمسح جميع الحقول ويضبط النوع إلى AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع الكائن الحالي. |

**Returns:**
منطقي -  true  إذا كان الكائن المحدد مساويًا للكائن الحالي؛ وإلا،  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


يحصل على سطر العنوان 1.

سطر العنوان 1 يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد.

ضبط هذا الحقل يضبط نوع العنوان إلى AddressType.CombinedElements ما لم يكن بالفعل AddressType.Structured، وفي هذه الحالة يصبح AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: سطر العنوان 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


يحصل على سطر العنوان 2.

سطر العنوان 2 يحتوي على الرمز البريدي والبلدة.

ضبط هذا الحقل يضبط نوع العنوان إلى AddressType.CombinedElements ما لم يكن بالفعل AddressType.Structured، وفي هذه الحالة يصبح AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

القيمة: سطر العنوان 2.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


يحصل على رمز البلد ISO المكوّن من حرفين.

رمز البلد إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.

القيمة: رمز البلد ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


يحصل على رقم المنزل.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


يحصل على الرمز البريدي.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


يحصل على الشارع.

يجب تحديد الشارع بدون رقم المنزل.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


يحصل على البلدة أو المدينة.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: المدينة أو البلدة.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


يحصل على نوع العنوان.

يتم ضبط نوع العنوان تلقائيًا إما بتحديد الشارع / رقم المنزل أو سطر العنوان 1 و2. قبل ضبط الحقول، يكون نوع العنوان  *Undetermined* . إذا تم ضبط حقول من كلا النوعين، يصبح نوع العنوان  *Conflicting* .

القيمة: نوع العنوان.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لهذا الكائن.

**Returns:**
int - رمز تجزئة للكائن الحالي.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


يضبط سطر العنوان 1.

سطر العنوان 1 يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد.

ضبط هذا الحقل يضبط نوع العنوان إلى AddressType.CombinedElements ما لم يكن بالفعل AddressType.Structured، وفي هذه الحالة يصبح AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: سطر العنوان 1.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


يضبط سطر العنوان 2.

سطر العنوان 2 يحتوي على الرمز البريدي والبلدة.

ضبط هذا الحقل يضبط نوع العنوان إلى AddressType.CombinedElements ما لم يكن بالفعل AddressType.Structured، وفي هذه الحالة يصبح AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

القيمة: سطر العنوان 2.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


يضبط رمز البلد ISO المكوّن من حرفين.

رمز البلد إلزامي ما لم يحتوي العنوان بالكامل على قيم فارغة أو null.

القيمة: رمز البلد ISO.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


يضبط رقم المنزل.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


يضبط الرمز البريدي.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


يضبط الشارع.

يجب تحديد الشارع بدون رقم المنزل.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


يضبط البلدة أو المدينة.

تعيين هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: المدينة أو البلدة.

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

