---
title: USADriveIdCodetext.SubfileProperties
second_title: Aspose.BarCode for Android via Java API Reference
description: USA DL サブファイルプロパティのオフセットと長さは自動的に設定されます。
type: docs
weight: 12
url: /ja/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

USA DL サブファイルのプロパティ、オフセットおよび長さは自動的に設定されます。
## Constructors

| Constructor | Description |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する 4 桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。 |
| [getOffset()](#getOffset--) | 4 桁の数値で、ファイルの先頭から特定のサブファイルに関連するデータが位置するバイト数を指定します。ファイルの最初のバイトはオフセット 0 にあります。 |
| [getType()](#getType--) | サブファイルのタイプ（2 バイト）、例: "DL" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する 4 桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。 |
| [setOffset(int value)](#setOffset-int-) | 4 桁の数値で、ファイルの先頭から特定のサブファイルに関連するデータが位置するバイト数を指定します。ファイルの最初のバイトはオフセット 0 にあります。 |
| [setType(String value)](#setType-java.lang.String-) | サブファイルのタイプ（2 バイト）、例: "DL" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| タイプ | java.lang.String |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getLength() {#getLength--}
```
public final int getLength()
```


4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する 4 桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは 2 文字のサブファイルタイプで開始する必要があり、これら 2 文字も長さに含める必要があります。

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4 桁の数値で、ファイルの先頭から特定のサブファイルに関連するデータが位置するバイト数を指定します。ファイルの最初のバイトはオフセット 0 にあります。

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


サブファイルのタイプ（2 バイト）、例: "DL"

**Returns:**
java.lang.String
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




### setLength(int value) {#setLength-int-}
```
public final void setLength(int value)
```


4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する 4 桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは 2 文字のサブファイルタイプで開始する必要があり、これら 2 文字も長さに含める必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4 桁の数値で、ファイルの先頭から特定のサブファイルに関連するデータが位置するバイト数を指定します。ファイルの最初のバイトはオフセット 0 にあります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


サブファイルのタイプ（2 バイト）、例: "DL"

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

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

