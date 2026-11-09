---
title: "USADriveIdCodetext.SubfileProperties"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "USA DL サブファイルプロパティのオフセットと長さは自動的に設定されます。"
type: docs
weight: 12
url: /ja/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.SubfileProperties
```

米国運転免許証サブファイルのプロパティ、オフセットおよび長さは自動的に設定されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SubfileProperties(String type)](#SubfileProperties-java.lang.String-) |  |
| [SubfileProperties()](#SubfileProperties--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。 |
| [getOffset()](#getOffset--) | 4桁の数値で、ファイルの先頭または開始位置から特定のサブファイルに関連するデータがある位置までのバイト数を指定します。ファイルの最初のバイトはオフセット0にあります。 |
| [getType()](#getType--) | 「DL」のようなサブファイルのタイプを示す2バイト |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLength(int value)](#setLength-int-) | 4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。 |
| [setOffset(int value)](#setOffset-int-) | 4桁の数値で、ファイルの先頭または開始位置から特定のサブファイルに関連するデータがある位置までのバイト数を指定します。ファイルの最初のバイトはオフセット0にあります。 |
| [setType(String value)](#setType-java.lang.String-) | 「DL」のようなサブファイルのタイプを示す2バイト |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SubfileProperties(String type) {#SubfileProperties-java.lang.String-}
```
public SubfileProperties(String type)
```


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| タイプ | java.lang.String |  |

### SubfileProperties() {#SubfileProperties--}
```
public SubfileProperties()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
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


4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは2文字のサブファイルタイプで開始し、これら2文字も長さに含める必要があります。

**Returns:**
int
### getOffset() {#getOffset--}
```
public final int getOffset()
```


4桁の数値で、ファイルの先頭または開始位置から特定のサブファイルに関連するデータがある位置までのバイト数を指定します。ファイルの最初のバイトはオフセット0にあります。

**Returns:**
int
### getType() {#getType--}
```
public final String getType()
```


「DL」のようなサブファイルのタイプを示す2バイト

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


4 これらのバイトは、サブファイルの長さ（バイト単位）を指定する4桁の数値を含みます。セグメントターミネータはサブファイルの長さ計算に含める必要があります。セグメントターミネータ = 1。各サブファイルは2文字のサブファイルタイプで開始し、これら2文字も長さに含める必要があります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOffset(int value) {#setOffset-int-}
```
public final void setOffset(int value)
```


4桁の数値で、ファイルの先頭または開始位置から特定のサブファイルに関連するデータがある位置までのバイト数を指定します。ファイルの最初のバイトはオフセット0にあります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setType(String value) {#setType-java.lang.String-}
```
public final void setType(String value)
```


「DL」のようなサブファイルのタイプを示す2バイト

**Parameters:**
| パラメータ | 型 | 説明 |
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

