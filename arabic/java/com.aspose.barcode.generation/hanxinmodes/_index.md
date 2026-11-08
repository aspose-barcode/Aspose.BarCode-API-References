---
title: "HanXinModes"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "وضع الترميز لـ Han Xin Code."
type: docs
weight: 89
url: /ar/java/com.aspose.barcode.generation/hanxinmodes/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinModes extends Enum<HanXinModes>
```

وضع ترميز Han Xin Code. يُنصح باستخدام Auto مع أحرف ASCII / الصينية أو Unicode للأحرف Unicode.
## الحقول

| حقل | الوصف |
| --- | --- |
| [AUTO](#AUTO) | تسلسل أوضاع Numeric وText وECI وBinary Bytes و4 GB18030 يتغير تلقائيًا. |
| [BINARY](#BINARY) | وضع البايت الثنائي يشفّر البيانات الثنائية بأي شكل ويشفّرها في بايتها الثنائي. |
| [COMMON_CHINESE_REGION_ONE](#COMMON-CHINESE-REGION-ONE) | كل حرف صيني شائع في المنطقة الأولى يُمثَّل بـ 12 بت. |
| [COMMON_CHINESE_REGION_TWO](#COMMON-CHINESE-REGION-TWO) | كل حرف صيني شائع في المنطقة الثانية يُمثَّل بـ 12 بت. |
| [ECI](#ECI) | وضع تفسير القناة الموسّعة (ECI) |
| [GB_18030_FOUR_BYTE](#GB-18030-FOUR-BYTE) | كل حرف من منطقة GB18030 المكوّن من 4 بايت يُمثَّل بـ 21 بت. |
| [GB_18030_TWO_BYTE](#GB-18030-TWO-BYTE) | كل حرف من منطقة GB18030 المكوّن من 2 بايت يُمثَّل بـ 15 بت. |
| [GS_1](#GS-1) | يشير وضع GS1 إلى أن البيانات الممثَّلة في Han Xin Code هي بيانات GS1 لنظام GS1 المحددة في مواصفة GS1 العامة. |
| [NUMERIC](#NUMERIC) | وضع Numeric يشفّر البيانات من مجموعة الأرقام العشرية (الأرقام 0-9، قيم البايت من 30HEX إلى 39HEX). |
| [TEXT](#TEXT) | وضع النص يشفّر البيانات من الرموز الشائعة المعرفة في ISO/IEC 646، أي. |
| [UNICODE](#UNICODE) | وضع Unicode يصمم طريقة لتمثيل أي بيانات نصية تشير إلى ترميز/مجموعة أحرف UTF8 في رمز Han Xin. |
| [URI](#URI) | وضع URI يشير إلى أن البيانات الممثلة في رمز Han Xin هي معرف مورد موحد (URI) وفقًا للمرجع RFC 3986. |
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
### AUTO {#AUTO}
```
public static final HanXinModes AUTO
```


تسلسل أوضاع Numeric وText وECI وBinary Bytes و4 GB18030 يتغير تلقائيًا.

### BINARY {#BINARY}
```
public static final HanXinModes BINARY
```


وضع البايت الثنائي يشفّر البيانات الثنائية بأي شكل ويشفّرها في بايتها الثنائي. كل بايت في وضع البايت الثنائي يُمثَّل بـ 8 بتات.

### COMMON_CHINESE_REGION_ONE {#COMMON-CHINESE-REGION-ONE}
```
public static final HanXinModes COMMON_CHINESE_REGION_ONE
```


كل حرف صيني شائع في المنطقة الأولى يُمثَّل بـ 12 بتًا. تشمل الأحرف الصينية الشائعة في المنطقة الأولى الأحرف التي تكون قيمة البايت الأول لها في النطاق من B0HEX إلى D7HEX والقيمة الثانية في النطاق من A1HEX إلى FEHEX (3760 حرفًا)، والأحرف التي تكون قيمة البايت الأول لها في النطاق من A1HEX إلى A3HEX والقيمة الثانية في النطاق من A1HEX إلى FEHEX (282 حرفًا)، والأحرف التي قيم البايت لها في النطاق من A8A1HEX إلى A8C0HEX (32 حرفًا).

### COMMON_CHINESE_REGION_TWO {#COMMON-CHINESE-REGION-TWO}
```
public static final HanXinModes COMMON_CHINESE_REGION_TWO
```


كل حرف صيني شائع في المنطقة الثانية يُمثَّل بـ 12 بتًا. تشمل الأحرف الصينية الشائعة في المنطقة الثانية الأحرف التي تكون قيمة البايت الأول لها في النطاق من D8HEX إلى F7HEX والقيمة الثانية في النطاق من A1HEX إلى FEHEX.

### ECI {#ECI}
```
public static final HanXinModes ECI
```


وضع تفسير القناة الموسّعة (ECI)

### GB_18030_FOUR_BYTE {#GB-18030-FOUR-BYTE}
```
public static final HanXinModes GB_18030_FOUR_BYTE
```


كل حرف في منطقة GB18030 ذات 4 بايت يُمثَّل بـ 21 بتًا. منطقة GB18030 ذات 4 بايت تشفّر البيانات من جميع الأحرف في منطقة GB18030 ذات الأربعة بايت (أي الأحرف التي تكون قيمة البايت الأول لها في النطاق من 81HEX إلى FEHEX، والقيمة الثانية في النطاق من 30HEX إلى 39HEX، والبايت الثالث في النطاق من 81HEX إلى FEHEX، والبايت الرابع في النطاق من 30HEX إلى 39HEX).

### GB_18030_TWO_BYTE {#GB-18030-TWO-BYTE}
```
public static final HanXinModes GB_18030_TWO_BYTE
```


كل حرف في منطقة GB18030 ذات 2 بايت يُمثَّل بـ 15 بتًا. منطقة GB18030 ذات 2 بايت تشفّر البيانات من جميع الأحرف (بما في ذلك الأحرف الصينية الشائعة في المنطقتين الأولى والثانية) في منطقة GB18030 ذات البايتين، (أي الأحرف الصينية التي تكون قيمة البايت الأول لها في النطاق من 81HEX إلى FEHEX والقيمة الثانية في النطاق من 40HEX إلى 7EHEX أو 80HEX إلى FEHEX).

### GS_1 {#GS-1}
```
public static final HanXinModes GS_1
```


وضع GS1 يشير إلى أن البيانات الممثلة في رمز Han Xin هي بيانات GS1 لنظام GS1 المعرفة بمواصفة GS1 العامة. مثال على سلسلة الإدخال: "(01)03453120000011(17)191125(10)ABCD1234(21)10".

### NUMERIC {#NUMERIC}
```
public static final HanXinModes NUMERIC
```


وضع الأرقام يشفّر البيانات من مجموعة الأرقام العشرية (الأرقام 0-9، قيم البايت من 30HEX إلى 39HEX). عادةً، يُمثَّل 3 أحرف بيانات بـ 10 بت.

### TEXT {#TEXT}
```
public static final HanXinModes TEXT
```


وضع النص يشفّر البيانات من الرموز الشائعة المعرفة في ISO/IEC 646، أي قيم البايت من 00 HEX إلى 1B HEX ومن 20 HEX إلى 7F HEX.

### UNICODE {#UNICODE}
```
public static final HanXinModes UNICODE
```


وضع Unicode يصمم طريقة لتمثيل أي بيانات نصية تشير إلى ترميز/مجموعة أحرف UTF8 في رمز Han Xin.

### URI {#URI}
```
public static final HanXinModes URI
```


وضع URI يشير إلى أن البيانات الممثلة في رمز Han Xin هي معرف مورد موحد (URI) وفقًا للمرجع RFC 3986.

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
public static HanXinModes fromValue(int value)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
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
public static HanXinModes valueOf(String name)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.HanXinModes
### values() {#values--}
```
public static HanXinModes[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinModes[]
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

