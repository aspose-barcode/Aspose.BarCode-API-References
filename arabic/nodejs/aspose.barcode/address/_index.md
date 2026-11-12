---
title: "العنوان"
linktitle: "العنوان"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "عنوان الدائن أو المدين."
type: docs
weight: 10
url: /ar/nodejs/aspose.barcode/address/
---

## Address class

عنوان الدائن أو المدين. يمكنك إما تعيين الشارع، رقم المنزل، الرمز البريدي والمدينة (نوع عنوان منظم) أو السطر الأول والثاني للعنوان (نوع عناصر عنوان مجمعة). يتم تعيين النوع تلقائيًا بمجرد تعيين أي من هذه الحقول. قبل تعيين الحقول، يكون نوع العنوان غير محدد. إذا تم تعيين حقول من كلا النوعين، يصبح نوع العنوان متعارضًا. يجب دائمًا تعيين الاسم ورمز الدولة ما لم تكن جميع الحقول فارغة.

```js
new Address()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [clear()](#clear) | يمسح جميع الحقول ويعيّن النوع إلى AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [getAddressLine1()](#getaddressline1) | يحصل على السطر الأول للعنوان. السطر الأول للعنوان يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد. تعيين هذا الحقل يعيّن الـ addr |
| [getAddressLine2()](#getaddressline2) | يحصل على السطر الثاني للعنوان. السطر الثاني للعنوان يحتوي على الرمز البريدي والمدينة. تعيين هذا الحقل يعيّن نوع العنوان إلى Addre |
| [getCountryCode()](#getcountrycode) | يحصل على رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على قيمة فارغة أو null |
| [getHouseNo()](#gethouseno) | يحصل على رقم المنزل. تعيين هذا الحقل يعيّن نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressTyp |
| [getName()](#getname) | يحصل على الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [getPostalCode()](#getpostalcode) | يحصل على الرمز البريدي. تعيين هذا الحقل يعيّن نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType |
| [getStreet()](#getstreet) | يحصل على الشارع. يجب تحديد الشارع دون رقم المنزل. تعيين هذا الحقل يعيّن نوع العنوان إلى AddressT |
| [getTown()](#gettown) | يحصل على المدينة أو البلدة. تعيين هذا الحقل يعيّن نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressTyp |
| [getType()](#gettype) | يحصل على نوع العنوان. يتم تعيين نوع العنوان تلقائيًا إما بتعيين الشارع / رقم المنزل أو السطر الأول للعنوان أ |
| [hashCode()](#hashcode) | يحصل على رمز التجزئة لهذا المثيل. |
| [setAddressLine1(value:)](#setaddressline1) | يعين السطر الأول للعنوان. السطر الأول للعنوان يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد. تعيين هذا الحقل يعيّن الـ addr |
| [setAddressLine2(value:)](#setaddressline2) | يضبط السطر الثاني للعنوان. السطر الثاني للعنوان يحتوي على الرمز البريدي والمدينة. ضبط هذا الحقل يحدد نوع العنوان إلى Addre |
| [setCountryCode(value)](#setcountrycode) | يضبط رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على null أو emtpy val |
| [setHouseNo(value:)](#sethouseno) | يضبط رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressTyp |
| [setName(value:)](#setname) | يضبط الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني. |
| [setPostalCode(value)](#setpostalcode) | يضبط الرمز البريدي. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType |
| [setStreet(value:)](#setstreet) | يضبط الشارع. يجب تحديد الشارع بدون رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressT |
| [setTown(value)](#settown) | يضبط المدينة أو البلدة. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressTyp |

### clear() {#clear}

يمسح جميع الحقول ويعيّن النوع إلى AddressType.UNDETERMINED.

### equals(obj) {#equals}

يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي.

| معامل | الوصف |
| --- | --- |
| obj | الكائن للمقارنة مع الكائن الحالي. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

يحصل على السطر الأول للعنوان. السطر الأول للعنوان يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.COMBINED_ELEMENTS ما لم يكن بالفعل AddressType.STRUCTURED، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة وهو اختياري.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

يحصل على السطر الثاني للعنوان. السطر الثاني للعنوان يحتوي على الرمز البريدي والمدينة. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.COMBINED_ELEMENTS ما لم يكن بالفعل AddressType.STRUCTURED، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

يحصل على رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على null أو emtpy values.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

يحصل على رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين مُنظمة وهو اختياري.

**Returns:** The house number.

### getName() {#getname}

يحصل على الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

يحصل على الرمز البريدي. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين مُنظمة. لهذا النوع، هو إلزامي.

**Returns:** The postal code.

### getStreet() {#getstreet}

يحصل على الشارع. يجب تحديد الشارع بدون رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين مُنظمة وهو اختياري.

**Returns:** The street.

### getTown() {#gettown}

يحصل على المدينة أو البلدة. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين مُنظمة. لهذا النوع، هو إلزامي.

**Returns:** The town or city.

### getType() {#gettype}

يحصل على نوع العنوان. يتم تعيين نوع العنوان تلقائيًا إما بضبط الشارع / رقم المنزل أو السطرين الأول والثاني للعنوان. قبل ضبط الحقول، يكون نوع العنوان غير محدد (Undetermined). إذا تم ضبط حقول من كلا النوعين، يصبح نوع العنوان متعارضًا (Conflicting).

**Returns:** The address type.

### hashCode() {#hashcode}

يحصل على رمز التجزئة لهذا المثيل.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

يضبط السطر الأول للعنوان. السطر الأول للعنوان يحتوي على اسم الشارع، رقم المنزل أو صندوق البريد. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.COMBINED_ELEMENTS ما لم يكن بالفعل AddressType.STRUCTURED، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة وهو اختياري.

| معامل | الوصف |
| --- | --- |
| القيمة: | السطر الأول للعنوان. |

### setAddressLine2(value:) {#setaddressline2}

يضبط السطر الثاني للعنوان. السطر الثاني للعنوان يحتوي على الرمز البريدي والمدينة. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.COMBINED_ELEMENTS ما لم يكن بالفعل AddressType.STRUCTURED، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط لعناوين العناصر المدمجة. لهذا النوع، هو إلزامي.

| معامل | الوصف |
| --- | --- |
| القيمة: | السطر الثاني للعنوان. |

### setCountryCode(value) {#setcountrycode}

يضبط رمز الدولة ISO المكوّن من حرفين. رمز الدولة إلزامي ما لم يحتوي العنوان بالكامل على null أو emtpy values.

| معامل | الوصف |
| --- | --- |
| القيمة | رمز الدولة ISO. |

### setHouseNo(value:) {#sethouseno}

يضبط رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

| معامل | الوصف |
| --- | --- |
| القيمة: | رقم المنزل. |

### setName(value:) {#setname}

يضبط الاسم، إما الاسم الأول والاسم الأخير لشخص طبيعي أو اسم الشركة لشخص قانوني.

| معامل | الوصف |
| --- | --- |
| القيمة: | الاسم. |

### setPostalCode(value) {#setpostalcode}

يضبط الرمز البريدي. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

| معامل | الوصف |
| --- | --- |
| القيمة | الرمز البريدي. |

### setStreet(value:) {#setstreet}

يضبط الشارع. يجب تحديد الشارع بدون رقم المنزل. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط للعناوين المهيكلة وهو اختياري.

| معامل | الوصف |
| --- | --- |
| القيمة: | الشارع. |

### setTown(value) {#settown}

يضبط المدينة أو البلدة. ضبط هذا الحقل يحدد نوع العنوان إلى AddressType.STRUCTURED ما لم يكن بالفعل AddressType.COMBINED_ELEMENTS، وفي هذه الحالة يصبح AddressType.CONFLICTING. يُستخدم هذا الحقل فقط للعناوين المهيكلة. لهذا النوع، هو إلزامي.

| معامل | الوصف |
| --- | --- |
| القيمة | المدينة أو البلدة. |
