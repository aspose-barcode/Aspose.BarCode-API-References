---
title: "HanXinParametersUI"
second_title: "Aspose.BarCode for Java API リファレンス"
description: 
type: docs
weight: 15
url: /ja/java/com.aspose.barcode.barcodecontrol/hanxinparametersui/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParametersUI
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | 拡張チャネル解釈識別子。 |
| [getEncodeMode()](#getEncodeMode--) | BarCode のエンコードモードの HanXin シンボロジータイプです。 |
| [getErrorLevel()](#getErrorLevel--) | HanXin バーコードの Reed-Solomon 誤り訂正レベルです。 |
| [getVersion()](#getVersion--) | HanXin コードのバージョンです。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | 拡張チャネル解釈識別子。 |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | BarCode のエンコードモードの HanXin シンボロジータイプです。 |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | HanXin バーコードの Reed-Solomon 誤り訂正レベルです。 |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin コードのバージョンです。 |
| [toString()](#toString--) | この [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) の人間が読める文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


拡張チャネル解釈識別子です。シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


BarCode のエンコードモードの HanXin シンボロジータイプです。デフォルト値: EncodeMode.Auto。

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


HanXin バーコードの Reed-Solomon 誤り訂正レベルです。低から高: L1 - L4。ErrorLevel を参照してください。

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXinコードのバージョン。HanXinコードはVersion01からVersion84までです。デフォルト値はVersion.Autoです。

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


拡張チャネル解釈識別子です。シンボル内のデータをエンコードするために使用された参照に関する詳細をバーコードリーダーに伝えるために使用されます。現在の実装は、すべてのよく知られた文字セットエンコーディングで構成されています。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


BarCode のエンコードモードの HanXin シンボロジータイプです。デフォルト値: EncodeMode.Auto。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


HanXin バーコードの Reed-Solomon 誤り訂正レベルです。低から高: L1 - L4。ErrorLevel を参照してください。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXinコードのバージョン。HanXinコードはVersion01からVersion84までです。デフォルト値はVersion.Autoです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


この [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) の人間が読める文字列表現を返します。

**Returns:**
java.lang.String - この[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)を表す文字列です。
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

