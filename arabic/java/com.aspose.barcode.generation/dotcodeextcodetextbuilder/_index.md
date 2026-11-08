---
title: "DotCodeExtCodetextBuilder"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: 
type: docs
weight: 33
url: /ar/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

مولد النص الموسع لباركودات DotCode ثنائية الأبعاد لوضع ExtendedCodetext في DotCodeEncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## الدوال

| دالة | الوصف |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | يضيف codetext مع Extended Channel Identifier |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | يضيف معرف تنسيق FNC1 إلى عناصر النص الموسع. |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | يضيف تهيئة قارئ FNC3 إلى عناصر النص الموسع. |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | يضيف فاصل رمز FNC3 إلى عناصر النص الموسع. |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | يضيف codetext عادي إلى عناصر codetext الموسعة |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | يضيف وضع الإلحاق الهيكلي إلى عناصر النص الموسع. |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


يضيف معرف تنسيق FNC1 إلى عناصر النص الموسع.

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


يضيف تهيئة قارئ FNC3 إلى عناصر النص الموسع.

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


يضيف فاصل رمز FNC3 إلى عناصر النص الموسع.

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


يضيف codetext عادي إلى عناصر codetext الموسعة

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| codetext | java.lang.String | نص الترميز في Unicode للإضافة كعنصر نص ترميز ممتد |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


يضيف وضع الإلحاق الهيكلي إلى عناصر النص الموسع.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| barcodeId | int | معرّف الباركود |
| barcodesCount | int | عدد الباركودات |

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

