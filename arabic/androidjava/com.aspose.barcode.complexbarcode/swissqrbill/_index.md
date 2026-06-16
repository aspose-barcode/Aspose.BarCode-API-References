---
title: SwissQRBill
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: بيانات فاتورة SwissQR
type: docs
weight: 36
url: /ar/androidjava/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

بيانات فاتورة SwissQR
## Methods

| Method | الوصف |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [getAccount()](#getAccount--) | Gets the creditor's account number. |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | يحصل أو يضبط مخططات الدفع البديلة. |
| [getAmount()](#getAmount--) | يحصل على مبلغ الدفع. |
| [getBillInformation()](#getBillInformation--) | يحصل على معلومات الفاتورة المهيكلة الإضافية. |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | يحصل على عنوان الدائن. |
| [getCurrency()](#getCurrency--) | يحصل على عملة الدفع. |
| [getDebtor()](#getDebtor--) | يحصل على عنوان المدين. |
| [getReference()](#getReference--) | يحصل على مرجع دفع الدائن. |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | يحصل على الرسالة غير المهيكلة الإضافية. |
| [getVersion()](#getVersion--) | يحصل على نسخة معيار الفاتورة SwissQR. |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا الكائن. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | يضبط رقم حساب الدائن. |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | يحصل أو يضبط مخططات الدفع البديلة. |
| [setAmount(double value)](#setAmount-double-) | يضبط مبلغ الدفع. |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | يضبط معلومات الفاتورة المهيكلة الإضافية. |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | يضبط عنوان الدائن. |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | يضبط عملة الدفع. |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | يضبط عنوان المدين. |
| [setReference(String value)](#setReference-java.lang.String-) | يضبط مرجع دفع الدائن. |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | يضبط الرسالة غير المهيكلة الإضافية. |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | يضبط نسخة معيار الفاتورة SwissQR. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum.

يتم إزالة المسافات البيضاء من المرجع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| rawReference | java.lang.String | المرجع الخام. |

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
### getAccount() {#getAccount--}
```
public String getAccount()
```


Gets the creditor's account number.

يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

القيمة: رقم حساب الدائن.

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


يحصل أو يضبط مخططات الدفع البديلة.

يسمح بحد أقصى مخططين مع المعلمات.

القيمة: مخططات الدفع البديلة.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


يحصل على مبلغ الدفع.

القيم الصالحة بين 0.01 و 999,999,999.99.

القيمة: مبلغ الدفع.

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


يحصل على معلومات الفاتورة المهيكلة الإضافية.

القيمة: معلومات الفاتورة المهيكلة.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


يحصل على عنوان الدائن.

القيمة: عنوان الدائن.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


يحصل على عملة الدفع.

القيم الصالحة هي "CHF" و "EUR".

القيمة: عملة الدفع.

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


يحصل على عنوان المدين.

المدين اختياري. إذا تم حذفه، فإن تعيين هذا الحقل إلى  null  أو تعيين عنوان يحتوي على جميع القيم  null  أو الفارغة مقبول.

القيمة: عنوان المدين.

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


يحصل على مرجع دفع الدائن.

المرجع إلزامي لرموز SwissQR IBAN، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx.

إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا لـ ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

القيمة: مرجع دفع الدائن.

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


يحصل على الرسالة غير المهيكلة الإضافية.

القيمة: الرسالة غير المهيكلة.

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


يحصل على نسخة معيار الفاتورة SwissQR.

القيمة: نسخة معيار الفاتورة SwissQR.

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
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




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


يضبط رقم حساب الدائن.

يجب أن تكون أرقام الحسابات IBAN صالحة لبنك في سويسرا أو ليختنشتاين. يُسمح بالمسافات في رقم الحساب.

القيمة: رقم حساب الدائن.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


يحصل أو يضبط مخططات الدفع البديلة.

يسمح بحد أقصى مخططين مع المعلمات.

القيمة: مخططات الدفع البديلة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


يضبط مبلغ الدفع.

القيم الصالحة بين 0.01 و 999,999,999.99.

القيمة: مبلغ الدفع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


يضبط معلومات الفاتورة المهيكلة الإضافية.

القيمة: معلومات الفاتورة المهيكلة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


يضبط عنوان الدائن.

القيمة: عنوان الدائن.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


يضبط عملة الدفع.

القيم الصالحة هي "CHF" و "EUR".

القيمة: عملة الدفع.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


يضبط عنوان المدين.

المدين اختياري. إذا تم حذفه، فإن تعيين هذا الحقل إلى  null  أو تعيين عنوان يحتوي على جميع القيم  null  أو الفارغة مقبول.

القيمة: عنوان المدين.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


يضبط مرجع دفع الدائن.

المرجع إلزامي لرموز SwissQR IBAN، أي IBANs في النطاق CHxx30000xxxxxx إلى CHxx31999xxxxx.

إذا تم تحديده، يجب أن يكون المرجع إما مرجع SwissQR صالح (مطابق لنموذج مرجع ISR) أو مرجع دائن صالح وفقًا لـ ISO 11649 ("RFxxxx"). كلاهما قد يحتوي على مسافات للتنسيق.

القيمة: مرجع دفع الدائن.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


يضبط الرسالة غير المهيكلة الإضافية.

القيمة: الرسالة غير المهيكلة.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


يضبط نسخة معيار الفاتورة SwissQR.

القيمة: نسخة معيار الفاتورة SwissQR.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

