---
title: QRExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores a QR Structured Append information of recognized barcode
type: docs
weight: 42
url: /ja/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stores a QR Structured Append information of recognized barcode

このサンプルは QR Structured Append データの取得方法を示しています

```
{
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | 認識されたバーコードの Reed-Solomon エラー訂正レベル。 |
| [getMicroQRVersion()](#getMicroQRVersion--) | 認識された MicroQR Code のバージョン。 |
| [getQRErrorLevel()](#getQRErrorLevel--) | 認識されたバーコードの Reed-Solomon エラー訂正レベル。 |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | QR Structured Append モードのバーコードのインデックスを取得します。 |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | QR Structured Append モードのバーコード数を取得します。 |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | QR構造付加モードのパリティデータを取得します。 |
| [getQRVersion()](#getQRVersion--) | 認識されたQRコードのバージョン。 |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | 認識されたRectMicroQRコードのバージョン。 |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR Structured Append モードのバーコードのインデックスを取得します。 |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR Structured Append モードのバーコード数を取得します。 |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR構造付加モードのパリティデータを取得します。 |
| [getVersion()](#getVersion--) | 認識されたQRコードのバージョン。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEmpty()](#isEmpty--) | すべてのパラメーターがデフォルト値のみであるかどうかをテストします。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | 最初の[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の値が2番目と等しいかどうかを示す値を返します。 |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | 最初の[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の値が2番目と異なるかどうかを示す値を返します。 |
| [toString()](#toString--) | この[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の人間が読みやすい文字列表現を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) 値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための System.Object 値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
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


認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


認識されたMicroQRコードのバージョン。M1からM4まで。

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


認識されたバーコードのリード・ソロモン誤り訂正レベル。低から高へ: LevelL、LevelM、LevelQ、LevelH。

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


QR構造付加モードバーコードのインデックスを取得します。インデックスは0から始まります。デフォルト値は-1です。

値: QR構造付加モードバーコードの数量。

**Returns:**
int - QR構造付加モードバーコードのインデックス。
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


QR構造付加モードバーコードの数量を取得します。デフォルト値は-1です。

値: QR構造付加モードバーコードの数量。

**Returns:**
int - QR構造付加モードバーコードの数量。
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


QR構造付加モードのパリティデータを取得します。デフォルト値は-1です。

値: QR構造付加モードバーコードのインデックス。

**Returns:**
int - QR構造付加モードのパリティデータ。
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


認識されたQRコードのバージョン。Version1からVersion40まで。

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


認識されたRectMicroQRコードのバージョン。R7x43からR17x139まで。

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


QR構造付加モードバーコードのインデックスを取得します。インデックスは0から始まります。デフォルト値は-1です。

値: QR構造付加モードバーコードの数量。

**Returns:**
int - QR構造付加モードバーコードのインデックス。
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR構造付加モードバーコードの数量を取得します。デフォルト値は-1です。

値: QR構造付加モードバーコードの数量。

**Returns:**
int - QR構造付加モードバーコードの数量。
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR構造付加モードのパリティデータを取得します。デフォルト値は-1です。

値: QR構造付加モードバーコードのインデックス。

**Returns:**
int - QR構造付加モードのパリティデータ。
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


認識されたQRコードのバージョン。Version1からVersion40まで。

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


すべてのパラメーターがデフォルト値のみであるかどうかをテストします。

値: すべてのパラメーターがデフォルト値のみである場合 **true** を返し、そうでない場合は **false** を返します。

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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


最初の[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の値が2番目と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 最初の比較対象の値 |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 2 番目の比較対象の値 |

**Returns:**
boolean -  **true**  最初の値が2番目と同じ場合; それ以外は **false** 。
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


最初の[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の値が2番目と異なるかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 最初の比較対象の値 |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | 2 番目の比較対象の値 |

**Returns:**
boolean -  **true**  最初の値が2番目と異なる場合; それ以外は **false** 。
### toString() {#toString--}
```
public String toString()
```


この[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)の人間が読みやすい文字列表現を返します。

**Returns:**
java.lang.String - この[QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters)を表す文字列。
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

