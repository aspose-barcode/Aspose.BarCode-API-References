---
title: "العنوان"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "عنوان الدائن أو المدين."
type: docs
weight: 10
url: /ar/java/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

عنوان الدائن أو المدين.

يمكنك إما تعيين الشارع، رقم المنزل، الرمز البريدي والمدينة (النوع *structured address*) أو سطر العنوان 1 و2 (النوع *combined address elements*). يتم تعيين النوع تلقائيًا بمجرد تعيين أي من هذه الحقول. قبل تعيين الحقول، يكون نوع العنوان *undetermined*. إذا تم تعيين حقول من كلا النوعين، يصبح نوع العنوان *conflicting*. يجب دائمًا تعيين الاسم ورمز الدولة ما لم تكن جميع الحقول فارغة.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Address()](#Address--) | إنشاء كائن من Address |
## الدوال

| دالة | الوصف |
| --- | --- |
| [clear()](#clear--) | يمسح جميع الحقول ويضبط النوع إلى  AddressType.Undetermined . |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [getAddressLine1()](#getAddressLine1--) | يحصل على سطر العنوان 1. |
| [getAddressLine2()](#getAddressLine2--) | يحصل على سطر العنوان 2. |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | يحصل على رمز الدولة ISO المكوّن من حرفين. |
| [getHouseNo()](#getHouseNo--) | يحصل على رقم المنزل. |
| [getName()](#getName--) | يحصل على الاسم، إما الاسم الأول والأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [getPostalCode()](#getPostalCode--) | يحصل على الرمز البريدي. |
| [getStreet()](#getStreet--) | يحصل على الشارع. |
| [getTown()](#getTown--) | يحصل على المدينة أو البلدة. |
| [getType()](#getType--) | يحصل على نوع العنوان. |
| [hashCode()](#hashCode--) | يحصل على قيمة التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | يضبط سطر العنوان 1. |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | يضبط سطر العنوان 2. |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | يضبط رمز الدولة ISO المكوّن من حرفين. |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | يضبط رقم المنزل. |
| [setName(String value)](#setName-java.lang.String-) | يضبط الاسم، إما الاسم الأول والأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | يضبط الرمز البريدي. |
| [setStreet(String value)](#setStreet-java.lang.String-) | يضبط الشارع. |
| [setTown(String value)](#setTown-java.lang.String-) | يضبط المدينة أو البلدة. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


إنشاء كائن من Address

### clear() {#clear--}
```
public void clear()
```


يمسح جميع الحقول ويضبط النوع إلى  AddressType.Undetermined .

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع الكائن الحالي. |

**Returns:**
boolean -  true  إذا كان الكائن المحدد يساوي الكائن الحالي؛ وإلا،  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


يحصل على سطر العنوان 1.

سطر العنوان 1 يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.CombinedElements  ما لم يكن بالفعل  AddressType.Structured ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: سطر العنوان 1.

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


يحصل على سطر العنوان 2.

سطر العنوان 2 يحتوي على الرمز البريدي والمدينة.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.CombinedElements  ما لم يكن بالفعل  AddressType.Structured ، وفي هذه الحالة يصبح  AddressType.Conflicting .

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


يحصل على رمز الدولة ISO المكوّن من حرفين.

رمز الدولة إلزامي ما لم يحتوي العنوان الكامل على  null  أو قيم فارغة.

القيمة: رمز الدولة ISO.

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


يحصل على رقم المنزل.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


يحصل على الاسم، إما الاسم الأول والأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


يحصل على الرمز البريدي.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


يحصل على الشارع.

يجب تحديد الشارع بدون رقم المنزل.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


يحصل على المدينة أو البلدة.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: البلدة أو المدينة.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


يحصل على نوع العنوان.

يتم تعيين نوع العنوان تلقائيًا إما عن طريق ضبط الشارع / رقم المنزل أو سطر العنوان 1 و 2. قبل ضبط الحقول، يكون نوع العنوان  *Undetermined* . إذا تم ضبط حقول من كلا النوعين، يصبح نوع العنوان  *Conflicting* .

القيمة: نوع العنوان.

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على قيمة التجزئة لهذا الكائن.

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

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.CombinedElements  ما لم يكن بالفعل  AddressType.Structured ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة وهو اختياري.

القيمة: سطر العنوان 1.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


يضبط سطر العنوان 2.

سطر العنوان 2 يحتوي على الرمز البريدي والمدينة.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.CombinedElements  ما لم يكن بالفعل  AddressType.Structured ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

القيمة: سطر العنوان 2.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


يضبط رمز الدولة ISO المكوّن من حرفين.

رمز الدولة إلزامي ما لم يحتوي العنوان الكامل على  null  أو قيم فارغة.

القيمة: رمز الدولة ISO.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


يضبط رقم المنزل.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.

القيمة: رقم المنزل.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


يضبط الاسم، إما الاسم الأول والأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

القيمة: الاسم.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


يضبط الرمز البريدي.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: الرمز البريدي.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


يضبط الشارع.

يجب تحديد الشارع بدون رقم المنزل.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة وهو اختياري.

القيمة: الشارع.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


يضبط المدينة أو البلدة.

ضبط هذا الحقل يضبط نوع العنوان إلى  AddressType.Structured  ما لم يكن بالفعل  AddressType.CombinedElements ، وفي هذه الحالة يصبح  AddressType.Conflicting .

هذا الحقل يُستخدم فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

القيمة: البلدة أو المدينة.

**Parameters:**
| معامل | النوع | الوصف |
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

