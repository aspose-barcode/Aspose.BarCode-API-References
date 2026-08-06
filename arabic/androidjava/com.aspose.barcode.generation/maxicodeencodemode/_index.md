---
title: MaxiCodeEncodeMode
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: وضع الترميز لباركودات MaxiCode.
type: docs
weight: 95
url: /ar/androidjava/com.aspose.barcode.generation/maxicodeencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeEncodeMode extends Enum<MaxiCodeEncodeMode>
```

وضع الترميز لباركودات MaxiCode.

```
//Auto mode
 String codetext = "\u72acRight\u72d7";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 {
     generator.getParameters().getBarcode().getMaxiCode().setECIEncoding(ECIEncodings.UTF8);
     generator.save("test.bmp");
 }

 //Bytes mode
 byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE);
 generator.setCodetext(encodedArr);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.BINARY);
 generator.save("test.bmp");

 //Extended codetext mode
 //create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 // generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext);
 generator.getParameters().getBarcode().getMaxiCode().setMaxiCodeEncodeMode(MaxiCodeEncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | في الوضع التلقائي، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. |
| [BINARY](#BINARY) | في الوضع الثنائي، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. |
| [BYTES](#BYTES) | تشفير codetext كبايتات عادية. |
| [ECI](#ECI) | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final MaxiCodeEncodeMode AUTO
```


في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم إعادة ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار لـ ECI، يتم إلقاء استثناء.

### BINARY {#BINARY}
```
public static final MaxiCodeEncodeMode BINARY
```


في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء.

### BYTES {#BYTES}
```
public static final MaxiCodeEncodeMode BYTES
```


تشفير codetext كبايتات عادية. إذا تم اكتشاف أي حرف Unicode، سيتم تشفير الحرف كبايتين، البايت الأقل أولاً.

### ECI {#ECI}
```
public static final MaxiCodeEncodeMode ECI
```


في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز المختار لـ ECI، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع.

### EXTENDED {#EXTENDED}
```
public static final MaxiCodeEncodeMode EXTENDED
```


الوضع الموسع الذي يدعم أوضاع ECI المتعددة.

من الأفضل استخدام MaxiCodeExtCodetextBuilder لتوليد codetext الموسع.

استخدم الخاصية Display2DText لتعيين النص الظاهر وإزالة الأحرف الإدارية.

معرفات ECI تُحدد كشرطة مائلة واحدة ومعرف مكون من ستة أرقام "\\000026" - معرف ECI UTF8

جميع أحرف Unicode بعد معرف ECI يتم ترميزها تلقائيًا إلى مجموعة الأحرف الصحيحة.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final MaxiCodeEncodeMode EXTENDED_CODETEXT
```


الوضع الموسع الذي يدعم أوضاع ECI المتعددة.

من الأفضل استخدام MaxiCodeExtCodetextBuilder لتوليد codetext الموسع.

استخدم الخاصية Display2DText لتعيين النص الظاهر وإزالة الأحرف الإدارية.

معرفات ECI تُحدد كشرطة مائلة واحدة ومعرف مكون من ستة أرقام "\\000026" - معرف ECI UTF8

جميع أحرف Unicode بعد معرف ECI يتم ترميزها تلقائيًا إلى مجموعة الأحرف الصحيحة.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MaxiCodeEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
### values() {#values--}
```
public static MaxiCodeEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeEncodeMode[]
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

