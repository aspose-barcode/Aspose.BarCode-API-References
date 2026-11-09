---
title: "MaxiCodeMode"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "MaxiCode のエンコードモードを含みます。"
type: docs
weight: 94
url: /ja/java/com.aspose.barcode.generation/maxicodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MaxiCodeMode extends Enum<MaxiCodeMode>
```

MaxiCode のエンコードモードを含みます。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [MODE_2](#MODE-2) | モード2は、最初のメッセージに郵便情報を、2番目のメッセージにデータをエンコードします。 |
| [MODE_3](#MODE-3) | モード3は、最初のメッセージに郵便情報を、2番目のメッセージにデータをエンコードします。 |
| [MODE_4](#MODE-4) | モード4は、短いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。 |
| [MODE_5](#MODE-5) | モード5は、長いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。 |
| [MODE_6](#MODE-6) | モード6は、短いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。 |
## メソッド

| メソッド | 説明 |
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
### MODE_2 {#MODE-2}
```
public static final MaxiCodeMode MODE_2
```


モード2は、最初のメッセージに郵便情報を、2番目のメッセージにデータをエンコードします。9桁の郵便番号を持ち、米国でのみ使用されます。

### MODE_3 {#MODE-3}
```
public static final MaxiCodeMode MODE_3
```


モード3は、最初のメッセージに郵便情報を、2番目のメッセージにデータをエンコードします。6文字の英数字郵便番号を持ち、全世界で使用されます。

### MODE_4 {#MODE-4}
```
public static final MaxiCodeMode MODE_4
```


モード4は、短いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。

### MODE_5 {#MODE-5}
```
public static final MaxiCodeMode MODE_5
```


モード5は、長いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。

### MODE_6 {#MODE-6}
```
public static final MaxiCodeMode MODE_6
```


モード6は、短いECC訂正を使用して、最初と2番目のメッセージにデータをエンコードします。デバイスのエンコードに使用されます。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static MaxiCodeMode fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
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
public static MaxiCodeMode valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode)
### values() {#values--}
```
public static MaxiCodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.MaxiCodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

