---
title: Pdf417EncodeMode
second_title: Aspose.BarCode for Android via Java API Reference
description: Pdf417 バーコードのエンコードモード
type: docs
weight: 99
url: /ja/androidjava/com.aspose.barcode.generation/pdf417encodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Pdf417EncodeMode extends Enum<Pdf417EncodeMode>
```

Pdf417 バーコードのエンコードモード
## フィールド

| フィールド | Description |
| --- | --- |
| [AUTO](#AUTO) | Auto モードでは、CodeText が最大のデータ圧縮でエンコードされます。 |
| [BINARY](#BINARY) | Binary モードでは、CodeText が最大のデータ圧縮でエンコードされます。 |
| [ECI](#ECI) | ECIモードでは、メッセージ全体がECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。 |
| [EXTENDED](#EXTENDED) |  |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
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
public static final Pdf417EncodeMode AUTO
```


Autoモードでは、CodeTextが最大限のデータ圧縮でエンコードされます。Unicode文字はECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。

### BINARY {#BINARY}
```
public static final Pdf417EncodeMode BINARY
```


Binaryモードでは、CodeTextが最大限のデータ圧縮でエンコードされます。Unicode文字が見つかった場合、例外がスローされます。

### ECI {#ECI}
```
public static final Pdf417EncodeMode ECI
```


ECIモードでは、メッセージ全体がECIEncodingで指定されたエンコーディングで再エンコードされ、ECI識別子が挿入されます。選択されたECIエンコーディングでサポートされていない文字が見つかった場合、例外がスローされます。なお、2006年以前の古いスキャナーはこのモードをサポートしない場合があります。

### EXTENDED {#EXTENDED}
```
public static final Pdf417EncodeMode EXTENDED
```


複数の ECI モードをサポートする拡張モードです。

拡張コードテキスト生成には Pdf417ExtCodetextBuilder を使用する方が良いです。

Display2DTextプロパティを使用して、表示テキストを設定し、管理文字を除去します。

ECI識別子はスラッシュ1つと6桁の識別子 "\\000026"（UTF8 ECI識別子）として設定されます。

ECI識別子の後のすべてのUnicode文字は自動的に正しい文字コードセットにエンコードされます。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static Pdf417EncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
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
public static Pdf417EncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Pdf417EncodeMode](../../com.aspose.barcode.generation/pdf417encodemode)
### values() {#values--}
```
public static Pdf417EncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.Pdf417EncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

