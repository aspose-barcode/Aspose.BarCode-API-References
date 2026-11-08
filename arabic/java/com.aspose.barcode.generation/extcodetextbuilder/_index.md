---
title: "ExtCodetextBuilder"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "فئة المساعدة لإنشاء النص المشفر تلقائيًا في وضع النص المشفر الموسع"
type: docs
weight: 38
url: /ar/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

فئة المساعدة لإنشاء النص المشفر تلقائيًا في وضع النص المشفر الموسع
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | يضيف codetext مع Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | يضيف codetext عادي إلى عناصر codetext الموسعة |
| [clear()](#clear--) | يمسح عناصر codetext الموسعة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | إنشاء نص رمزي موسع من قائمة عناصر الإنشاء |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


يضيف codetext مع Extended Channel Identifier

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | codetext في Unicode لإضافته كعنصر codetext موسع مع Extended Channel Identifier |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


يضيف codetext عادي إلى عناصر codetext الموسعة

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | نص الترميز في Unicode للإضافة كعنصر نص ترميز ممتد |

### clear() {#clear--}
```
public void clear()
```


يمسح عناصر codetext الموسعة

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


إنشاء نص رمزي موسع من قائمة عناصر الإنشاء

**Returns:**
java.lang.String - إرجاع سلسلة النص الرمزي الموسع
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

