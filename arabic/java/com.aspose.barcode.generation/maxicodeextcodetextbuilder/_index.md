---
title: "MaxiCodeExtCodetextBuilder"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "مولد النص المشفر الموسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص المرئي وإزالة الأحرف الإدارية."
type: docs
weight: 54
url: /ar/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

مولد نص مشفر موسع لباركودات MaxiCode لوضع ExtendedCodetext في MaxiCodeEncodeMode. استخدم خاصية TwoDDisplayText في BarcodeGenerator لتعيين النص الظاهر وإزالة الأحرف الإدارية. يوضح هذا المثال كيفية استخدام MaxiCodeExtCodetextBuilder في الوضع الموسع.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | يضيف codetext مع Extended Channel Identifier |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | يضيف codetext عادي إلى عناصر codetext الموسعة |
| [clear()](#clear--) | يمسح عناصر codetext الموسعة |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | ينشئ codetext الموسع من قائمة codetext الموسعة. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
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
public String getExtendedCodetext()
```


ينشئ codetext الموسع من قائمة codetext الموسعة.

**Returns:**
java.lang.String - نص ترميز ممتد كسلسلة
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

