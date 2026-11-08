---
title: "DataMatrixEncodeMode"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "وضع ترميز محولات DataMatrix افتراضيًا إلى تلقائي"
type: docs
weight: 81
url: /ar/java/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

وضع الترميز لمشفّر DataMatrix، الافتراضي Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## الحقول

| حقل | الوصف |
| --- | --- |
| [ANSIX12](#ANSIX12) | يستخدم ترميز ANSI X12. |
| [ASCII](#ASCII) | يقوم بترميز حرف أبجدي رقمي واحد أو رقمين لكل بايت |
| [AUTO](#AUTO) | في الوضع التلقائي، يتم ترميز نص الكود بأقصى درجة من ضغط البيانات. |
| [BASE_256](#BASE-256) | ترميز قيم 8 بت |
| [BINARY](#BINARY) | في الوضع الثنائي، يتم ترميز نص الكود بأقصى درجة من ضغط البيانات. |
| [C40](#C40) | يستخدم ترميز C40. |
| [ECI](#ECI) | في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. |
| [EDIFACT](#EDIFACT) | يستخدم ترميز EDIFACT. |
| [EXTENDED](#EXTENDED) | وضع ExtendedCodetext يتيح التبديل يدويًا بين مخططات الترميز وترميزات ECI في codetext. |
| [TEXT](#TEXT) | يستخدم ترميز Text. |
## الدوال

| دالة | الوصف |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


يستخدم ترميز ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


يقوم بترميز حرف أبجدي رقمي واحد أو رقمين لكل بايت

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


في وضع Auto، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. يتم إعادة ترميز أحرف Unicode باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المحدد، يتم إلقاء استثناء.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


ترميز قيم 8 بت

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


في وضع Binary، يتم ترميز CodeText بأقصى درجة من ضغط البيانات. إذا تم العثور على حرف Unicode، يتم إلقاء استثناء.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


يستخدم ترميز C40. يرمز الأحرف الأبجدية الرقمية الكبيرة، الأحرف الصغيرة والرموز الخاصة.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


في وضع ECI، يتم إعادة ترميز الرسالة بالكامل باستخدام الترميز المحدد في ECIEncoding مع إدراج معرف ECI. إذا تم العثور على حرف غير مدعوم من قبل الترميز ECI المحدد، يتم إلقاء استثناء. يرجى ملاحظة أن بعض الماسحات الضوئية القديمة (قبل 2006) قد لا تدعم هذا الوضع.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


يستخدم ترميز EDIFACT. يستخدم ست بتات لكل حرف، يرمز الأرقام، الأحرف الكبيرة، والعديد من علامات الترقيم، لكنه لا يدعم الأحرف الصغيرة.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


وضع ExtendedCodetext يتيح التبديل يدويًا بين مخططات الترميز وترميزات ECI في codetext. من الأفضل استخدام DataMatrixExtCodetextBuilder لإنشاء codetext موسع. استخدم الخاصية Display2DText لتعيين النص الظاهر وإزالة الأحرف الإدارية. يتم تعيين معرفات ECI كشرطة مائلة واحدة ومعرف مكون من ستة أرقام \"\\\\000026\" - معرف ECI UTF8. جميع أحرف Unicode بعد معرف ECI يتم ترميزها تلقائيًا إلى مجموعة الأحرف الصحيحة. يتم تعيين مخططات الترميز بالتنسيق التالي: \"\\\\Encodation\\_scheme\\_name:text\\\\Encodation\\_scheme\\_name:text\". المخططات المسموح بها هي: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. يجب أن تكون جميع الشرطات المائلة العكسية (\\) مضاعفة في النص.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


يستخدم ترميز Text. يرمز الأحرف الأبجدية الرقمية الصغيرة، الأحرف الكبيرة والرموز الخاصة.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
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
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

