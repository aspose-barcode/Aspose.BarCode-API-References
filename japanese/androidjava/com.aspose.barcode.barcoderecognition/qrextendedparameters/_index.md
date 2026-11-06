---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "認識されたバーコードの QR Structured Append 情報を保存します"
type: docs
weight: 40
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

認識されたバーコードの QR Structured Append 情報を保存します

このサンプルは QR Structured Append データの取得方法を示します。

```
{
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) の値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | 認識されたバーコードの Reed-Solomon エラー訂正レベル。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | 認識された MicroQR Code のバージョン。 |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | 認識された RectMicroQR Code のバージョン。 |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR structured append モードのバーコードのインデックスを取得します。 |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR structured append モードのバーコードの数量を取得します。 |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR structured append モードのパリティデータを取得します。 |
| [getVersion()](#getVersion--) | 認識された QR Code のバージョン。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかテストします |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | この [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) の値と等しいかどうかを示す値を返します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は、  **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


認識されたバーコードの Reed-Solomon エラー訂正レベル。低から高へ: LevelL, LevelM, LevelQ, LevelH。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


認識された MicroQR Code のバージョン。M1 から M4 まで。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


認識された RectMicroQR Code のバージョン。R7x43 から R17x139 まで。

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


QR structured append モードのバーコードのインデックスを取得します。インデックスは 0 から開始します。デフォルト値は -1 です。

値: QR structured append モードのバーコードの数量。

**Returns:**
int - QR structured append モードのバーコードのインデックス。
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR structured append モードのバーコードの数量を取得します。デフォルト値は -1 です。

値: QR structured append モードのバーコードの数量。

**Returns:**
int - QR structured append モードのバーコードの数量。
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR structured append モードのパリティデータを取得します。デフォルト値は -1 です。

値: QR structured append モードのバーコードのインデックス。

**Returns:**
int - QR structured append モードのパリティデータ。
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


認識された QR コードのバージョン。Version1 から Version40 まで。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


すべてのパラメーターがデフォルト値のみであるかテストします

値: すべてのパラメーターがデフォルト値のみである場合は  **true**  を返し、そうでない場合は  **false** を返します。

**Returns:**
boolean
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


この [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) を表す文字列です。
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

