---
title: "SwissQRCodetext"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "SwissQRコードに埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 36
url: /ja/androidjava/com.aspose.barcode.complexbarcode/swissqrcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class SwissQRCodetext implements IComplexCodetext
```

SwissQRコードに埋め込まれたテキストをエンコードおよびデコードするクラス。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SwissQRCodetext(SwissQRBill bill)](#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-) | SwissQRCodetext のインスタンスを作成します。 |
| [SwissQRCodetext()](#SwissQRCodetext--) | SwissQRCodetext のインスタンスを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | バーコードの種類を取得します。 |
| [getBill()](#getBill--) | SwissQR請求書データ |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | SwissQR 請求書データからコードテキストを構築します。 |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 構築されたコードテキストで Bill を初期化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SwissQRCodetext(SwissQRBill bill) {#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-}
```
public SwissQRCodetext(SwissQRBill bill)
```


SwissQRCodetext のインスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| bill | [SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill) | SwissQR請求書データ |

### SwissQRCodetext() {#SwissQRCodetext--}
```
public SwissQRCodetext()
```


SwissQRCodetext のインスタンスを作成します。

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


バーコードの種類を取得します。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getBill() {#getBill--}
```
public SwissQRBill getBill()
```


SwissQR請求書データ

**Returns:**
[SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


SwissQR 請求書データからコードテキストを構築します。

**Returns:**
java.lang.String - 構築されたコードテキスト
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


構築されたコードテキストで Bill を初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 構築されたコードテキスト。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

