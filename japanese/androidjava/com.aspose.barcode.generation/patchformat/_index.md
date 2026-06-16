---
title: PatchFormat
second_title: Aspose.BarCode for Android via Java API Reference
description: PatchCode フォーマット。
type: docs
weight: 97
url: /ja/androidjava/com.aspose.barcode.generation/patchformat/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PatchFormat extends Enum<PatchFormat>
```

PatchCode の形式です。単一の PatchCode を生成するには PatchOnly を選択してください。ページ形式を使用すると、PatchCode を枠として持つ Patch ページを生成します。
## フィールド

| フィールド | Description |
| --- | --- |
| [A4](#A4) | A4 形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。 |
| [A4_LANDSCAPE](#A4-LANDSCAPE) | A4 横向き形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。 |
| [PATCH_ONLY](#PATCH-ONLY) | PatchCode のみを生成します。 |
| [US_LETTER](#US-LETTER) | US レター形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。 |
| [US_LETTER_LANDSCAPE](#US-LETTER-LANDSCAPE) | US レター横向き形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。 |
## Methods

| Method | Description |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
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


A4 形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。

### A4_LANDSCAPE {#A4-LANDSCAPE}
```
public static final PatchFormat A4_LANDSCAPE
```


A4 横向き形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。

### PATCH_ONLY {#PATCH-ONLY}
```
public static final PatchFormat PATCH_ONLY
```


PatchCode のみを生成します。

### US_LETTER {#US-LETTER}
```
public static final PatchFormat US_LETTER
```


US レター形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。

### US_LETTER_LANDSCAPE {#US-LETTER-LANDSCAPE}
```
public static final PatchFormat US_LETTER_LANDSCAPE
```


US レター横向き形式のページを生成し、枠として PatchCode を配置し、中央にオプションで QR を配置します。

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
| Parameter | Type | Description |
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

