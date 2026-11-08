---
title: "MailmarkCodetext"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "فئة لتشفير وفك تشفير النص المدمج في رمز Royal Mailmark ذو الأربع حالات."
type: docs
weight: 24
url: /ar/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

فئة لتشفير وفك تشفير النص المدمج في رمز Royal Mailmark ذو الأربع حالات.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | ينشئ مثيلًا جديدًا من الفئة MailmarkCodetext. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | يحصل على نوع الباركود. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | \"0\" - فارغ أو اختبار \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - ممتاز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) \"5\" - مؤجل (Retail) \"6\" - هواء (Retail) (للاستخدام المستقبلي المحتمل) \"7\" - سطح (Retail) (للاستخدام المستقبلي المحتمل) \"8\" - ممتاز (Network Access) \"9\" - قياسي (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | إنشاء نص رمز من بيانات Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. |
| [getFormat()](#getFormat--) | \"0\" \\u2013 فارغ أو اختبار \"1\" \\u2013 حرف \"2\" \\u2013 حرف كبير |
| [getItemID()](#getItemID--) | القيمة القصوى هي 99999999. |
| [getSupplychainID()](#getSupplychainID--) | القيم القصوى هي 99 للباركود C و 999999 للباركود L. |
| [getVersionID()](#getVersionID--) | حاليًا "1" \\u2013 لباركود Mailmark (0 و 2 إلى 9 و A إلى Z احتياطي للاستخدام المستقبلي) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | يقوم بتهيئة بيانات Mailmark من النص المشفر المُنشأ. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | \"0\" - فارغ أو اختبار \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - ممتاز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) \"5\" - مؤجل (Retail) \"6\" - هواء (Retail) (للاستخدام المستقبلي المحتمل) \"7\" - سطح (Retail) (للاستخدام المستقبلي المحتمل) \"8\" - ممتاز (Network Access) \"9\" - قياسي (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. |
| [setFormat(int value)](#setFormat-int-) | \"0\" \\u2013 فارغ أو اختبار \"1\" \\u2013 حرف \"2\" \\u2013 حرف كبير |
| [setItemID(int value)](#setItemID-int-) | القيمة القصوى هي 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | القيم القصوى هي 99 للباركود C و 999999 للباركود L. |
| [setVersionID(int value)](#setVersionID-int-) | حاليًا "1" \\u2013 لباركود Mailmark (0 و 2 إلى 9 و A إلى Z احتياطي للاستخدام المستقبلي) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


ينشئ مثيلًا جديدًا من الفئة MailmarkCodetext.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


يحصل على نوع الباركود.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


\"0\" - فارغ أو اختبار \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - ممتاز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) \"5\" - مؤجل (Retail) \"6\" - هواء (Retail) (للاستخدام المستقبلي المحتمل) \"7\" - سطح (Retail) (للاستخدام المستقبلي المحتمل) \"8\" - ممتاز (Network Access) \"9\" - قياسي (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


إنشاء نص رمز من بيانات Mailmark.

**Returns:**
java.lang.String - نص الكود المُنشأ
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكوّنة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ وجود 5 مسافات في النهاية) أو نمط من الأحرف يمثل رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريد خارجي، رمز بريد داخلي، وملحق نقطة التسليم.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


\"0\" \\u2013 فارغ أو اختبار \"1\" \\u2013 حرف \"2\" \\u2013 حرف كبير

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


القيمة القصوى هي 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


القيم القصوى هي 99 للباركود C و 999999 للباركود L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


حاليًا "1" \\u2013 لباركود Mailmark (0 و 2 إلى 9 و A إلى Z احتياطي للاستخدام المستقبلي)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


يقوم بتهيئة بيانات Mailmark من النص المشفر المُنشأ.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| constructedCodetext | java.lang.String | نص الكود المُنشأ. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


\"0\" - فارغ أو اختبار \"1\" - 1C (Retail) \"2\" - 2C (Retail) \"3\" - 3C (Retail) \"4\" - ممتاز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) \"5\" - مؤجل (Retail) \"6\" - هواء (Retail) (للاستخدام المستقبلي المحتمل) \"7\" - سطح (Retail) (للاستخدام المستقبلي المحتمل) \"8\" - ممتاز (Network Access) \"9\" - قياسي (Network Access)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكوّنة من تسعة أحرف تمثل "XY11 " دوليًا (لاحظ وجود 5 مسافات في النهاية) أو نمط من الأحرف يمثل رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريد خارجي، رمز بريد داخلي، وملحق نقطة التسليم.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


\"0\" \\u2013 فارغ أو اختبار \"1\" \\u2013 حرف \"2\" \\u2013 حرف كبير

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


القيمة القصوى هي 99999999.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


القيم القصوى هي 99 للباركود C و 999999 للباركود L.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


حاليًا "1" \\u2013 لباركود Mailmark (0 و 2 إلى 9 و A إلى Z احتياطي للاستخدام المستقبلي)

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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

