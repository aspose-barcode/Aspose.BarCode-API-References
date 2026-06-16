---
title: HanXinParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin パラメータ。
type: docs
weight: 50
url: /ja/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin パラメータ。
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getEncodeMode()](#getEncodeMode--) | HanXin エンコーディングモード。 |
| [getErrorLevel()](#getErrorLevel--) | Han Xin バーコードのリード・ソロモン誤り訂正レベル。 |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin エンコーディングモード。 |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Han Xin バーコードのリード・ソロモン誤り訂正レベル。 |
| [getHanXinVersion()](#getHanXinVersion--) | HanXin コードのバージョン。 |
| [getVersion()](#getVersion--) | HanXin コードのバージョン。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin エンコーディングモード。 |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Han Xin バーコードのリード・ソロモン誤り訂正レベル。 |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin コードのバージョン。 |
| [toString()](#toString--) | この [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装には、すべてのよく知られた文字セットエンコーディングが含まれています。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin エンコーディングモード。デフォルト値: EncodeMode.Mixed。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Han Xin バーコードのリード・ソロモン誤り訂正レベル。低から高: L1、L2、L3、L4。ErrorLevel を参照してください。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装には、すべてのよく知られた文字セットエンコーディングが含まれています。

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


HanXin エンコーディングモード。デフォルト値: EncodeMode.Mixed。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Han Xin バーコードのリード・ソロモン誤り訂正レベル。低から高: L1、L2、L3、L4。ErrorLevel を参照してください。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


HanXin コードのバージョン。Han Xin コードは Version01 から Version84 まであります。デフォルト値は Version.Auto です。

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin コードのバージョン。Han Xin コードは Version01 から Version84 まであります。デフォルト値は Version.Auto です。

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


拡張チャネル解釈識別子。シンボル内のデータエンコードに使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装には、すべてのよく知られた文字セットエンコーディングが含まれています。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin エンコーディングモード。デフォルト値: EncodeMode.Mixed。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Han Xin バーコードのリード・ソロモン誤り訂正レベル。低から高: L1、L2、L3、L4。ErrorLevel を参照してください。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin コードのバージョン。Han Xin コードは Version01 から Version84 まであります。デフォルト値は Version.Auto です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


この [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) を表す文字列です。
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

