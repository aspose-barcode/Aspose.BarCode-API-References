---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "بيانات الفاتورة SwissQR"
type: docs
weight: 920
url: /ar/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

بيانات الفاتورة SwissQR

```js
new SwissQRBill()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | ينشئ ويضبط مرجع الدائن ISO11649 من سلسلة خام عن طريق إضافة البادئة \"RF\" إلى السلسلة وتطبيق عملية modulo 97. |
| [equals(obj)](#equals) | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [getAccount()](#getaccount) | يحصل على رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | يحصل أو يضبط أنظمة الدفع البديلة. يُسمح بحد أقصى نظامين مع معلمات. |
| [getAmount()](#getamount) | يحصل على مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99. |
| [getBillInformation()](#getbillinformation) | يحصل على معلومات الفاتورة الهيكلية الإضافية. |
| [getCreditor()](#getcreditor) | يحصل على عنوان الدائن. |
| [getCurrency()](#getcurrency) | يحصل على عملة الدفع. القيم الصالحة هي \"CHF\" و \"EUR\". |
| [getDebtor()](#getdebtor) | يحصل على عنوان المدين. المدين اختياري. إذا تم حذفه، يمكن إما تعيين هذا الحقل إلى null أو تعيين عنوان |
| [getReference()](#getreference) | يحصل على مرجع دفع الدائن. المرجع إلزامي لـ IBANs الخاصة بـ SwissQR، أي IBANs في النطاق CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | يحصل على الرسالة غير المهيكلة الإضافية. |
| [getVersion()](#getversion) | يحصل على نسخة معيار الفاتورة SwissQR. |
| [hashCode()](#hashcode) | يحصل على رمز التجزئة لهذا المثيل. |
| [setAccount(value:)](#setaccount) | يضبط رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. Space |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | يحصل أو يضبط مخططات الدفع البديلة. يُسمح بحد أقصى مخططين مع معلمات. |
| [setAmount(value)](#setamount) | يضبط مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | يضبط معلومات الفاتورة المهيكلة الإضافية. |
| [setCreditor(value:)](#setcreditor) | يضبط عنوان الدائن. |
| [setCurrency(value)](#setcurrency) | يضبط عملة الدفع. |
| [setDebtor(value:)](#setdebtor) | يضبط عنوان المدين. المدين اختياري. إذا تم حذفه، يمكن إما تعيين هذا الحقل إلى null أو تعيين عنوان. |
| [setReference(value)](#setreference) | يضبط مرجع دفع الدائن. المرجع إلزامي لـ IBANs الخاصة بـ SwissQR، أي IBANs في النطاق CHxx30000xxxxx. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | يضبط الرسالة غير المهيكلة الإضافية. |
| [setVersion(value)](#setversion) | يضبط نسخة معيار الفاتورة SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

ينشئ ويضبط مرجع دائن ISO11649 من سلسلة خام عن طريق إضافة البادئة "RF" إلى السلسلة وحساب اختبار modulo 97. يتم إزالة المسافات البيضاء من المرجع.

| معامل | الوصف |
| --- | --- |
| rawReference | المرجع الخام. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي.

| معامل | الوصف |
| --- | --- |
| obj | الكائن للمقارنة مع الكائن الحالي. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

يحصل على رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

يحصل أو يضبط أنظمة الدفع البديلة. يُسمح بحد أقصى نظامين مع معلمات.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

يحصل على مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

يحصل على معلومات الفاتورة الهيكلية الإضافية.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

يحصل على عنوان الدائن.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

يحصل على عملة الدفع. القيم الصالحة هي \"CHF\" و \"EUR\".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

يحصل على عنوان المدين. المدين اختياري. إذا تم حذفه، يمكن إما تعيين هذا الحقل إلى null أو تعيين عنوان بجميع القيم null أو الفارغة.

**Returns:** The debtor address.

### getReference() {#getreference}

يحصل على مرجع دفع الدائن. المرجع إلزامي لـ IBANs الخاصة بـ SwissQR، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx. إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفق ISO 11649 ("RFxxxx"). يمكن لكليهما احتواء مسافات للتنسيق.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

يحصل على الرسالة غير المهيكلة الإضافية.

**Returns:** The unstructured message.

### getVersion() {#getversion}

يحصل على نسخة معيار الفاتورة SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

يحصل على رمز التجزئة لهذا المثيل.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

يضبط رقم حساب الدائن. يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

| معامل | الوصف |
| --- | --- |
| القيمة: | رقم حساب الدائن. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

يحصل أو يضبط مخططات الدفع البديلة. يُسمح بحد أقصى مخططين مع معلمات.

| معامل | الوصف |
| --- | --- |
| القيمة: | مخططات الدفع البديلة. |

### setAmount(value) {#setamount}

يضبط مبلغ الدفع. القيم الصالحة بين 0.01 و 999,999,999.99.

| معامل | الوصف |
| --- | --- |
| القيمة | مبلغ الدفع. |

### setBillInformation(value:) {#setbillinformation}

يضبط معلومات الفاتورة المهيكلة الإضافية.

| معامل | الوصف |
| --- | --- |
| القيمة: | معلومات الفاتورة المهيكلة. |

### setCreditor(value:) {#setcreditor}

يضبط عنوان الدائن.

| معامل | الوصف |
| --- | --- |
| القيمة: | عنوان الدائن. |

### setCurrency(value) {#setcurrency}

يضبط عملة الدفع.

| معامل | الوصف |
| --- | --- |
| القيمة | القيم الصالحة هي "CHF" و "EUR". |

### setDebtor(value:) {#setdebtor}

يضبط عنوان المدين. المدين اختياري. إذا تم حذفه، فإن تعيين هذا الحقل إلى null أو تعيين عنوان يحتوي على جميع القيم null أو فارغة مقبول.

| معامل | الوصف |
| --- | --- |
| القيمة: | عنوان المدين. |

### setReference(value) {#setreference}

يضبط مرجع دفع الدائن. المرجع إلزامي لرموز IBAN الخاصة بـ SwissQR، أي IBANs في النطاق CHxx30000xxxxxx حتى CHxx31999xxxxx. إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا للمعيار ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

| معامل | الوصف |
| --- | --- |
| القيمة | مرجع دفع الدائن. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

يضبط الرسالة غير المهيكلة الإضافية.

| معامل | الوصف |
| --- | --- |
| القيمة: | الرسالة غير المهيكلة. |

### setVersion(value) {#setversion}

يضبط نسخة معيار الفاتورة SwissQR.

| معامل | الوصف |
| --- | --- |
| القيمة | إصدار معيار فاتورة SwissQR. |
