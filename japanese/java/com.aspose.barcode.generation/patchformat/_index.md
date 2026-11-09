---
title: "PatchFormat"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "PatchCode フォーマット。"
type: docs
weight: 96
url: /ja/java/com.aspose.barcode.generation/patchformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchFormat extends Enum<PatchFormat>
```

PatchCode の形式です。単一の PatchCode を生成するには PATCH\_ONLY を選択してください。ページ形式を使用すると、PatchCodes を境界として Patch ページを生成します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [A4](#A4) | PatchCodes を境界として、センターにオプションの QR を配置した A4 形式のページを生成します。 |
| [A4_LANDSCAPE](#A4-LANDSCAPE) | PatchCodes を境界として、センターにオプションの QR を配置した A4 横向き形式のページを生成します。 |
| [PATCH_ONLY](#PATCH-ONLY) | PatchCode のみを生成します。 |
| [US_LETTER](#US-LETTER) | PatchCodes を境界として、センターにオプションの QR を配置した US レター形式のページを生成します。 |
| [US_LETTER_LANDSCAPE](#US-LETTER-LANDSCAPE) | PatchCodes を境界として、センターにオプションの QR を配置した US レター横向き形式のページを生成します。 |
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
### A4 {#A4}
```
public static final PatchFormat A4
```


PatchCodes を境界として、センターにオプションの QR を配置した A4 形式のページを生成します。

### A4_LANDSCAPE {#A4-LANDSCAPE}
```
public static final PatchFormat A4_LANDSCAPE
```


PatchCodes を境界として、センターにオプションの QR を配置した A4 横向き形式のページを生成します。

### PATCH_ONLY {#PATCH-ONLY}
```
public static final PatchFormat PATCH_ONLY
```


PatchCode のみを生成します。

### US_LETTER {#US-LETTER}
```
public static final PatchFormat US_LETTER
```


PatchCodes を境界として、センターにオプションの QR を配置した US レター形式のページを生成します。

### US_LETTER_LANDSCAPE {#US-LETTER-LANDSCAPE}
```
public static final PatchFormat US_LETTER_LANDSCAPE
```


PatchCodes を境界として、センターにオプションの QR を配置した US レター横向き形式のページを生成します。

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
public static PatchFormat fromValue(int value)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

**Returns:**
[PatchFormat](../../com.aspose.barcode.generation/patchformat)
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
public static PatchFormat valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[PatchFormat](../../com.aspose.barcode.generation/patchformat)
### values() {#values--}
```
public static PatchFormat[] values()
```




**Returns:**
com.aspose.barcode.generation.PatchFormat[]
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

