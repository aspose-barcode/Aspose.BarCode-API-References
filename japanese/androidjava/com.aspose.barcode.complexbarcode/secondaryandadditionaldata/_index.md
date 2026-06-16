---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode for Android via Java API Reference
description: HIBC LIC の二次および追加データを格納するクラス。
type: docs
weight: 35
url: /ja/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

HIBC LIC の二次および追加データを格納するクラス。
## Constructors

| Constructor | Description |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  SecondaryAndAdditionalData  値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | 製造日を識別します。 |
| [getExpiryDate()](#getExpiryDate--) | 有効期限を識別します。 |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | 有効期限の形式を識別します。 |
| [getLotNumber()](#getLotNumber--) | ロットまたはバッチ番号を識別します。 |
| [getQuantity()](#getQuantity--) | 数量を識別します。0 から 500 までの整数値である必要があります。 |
| [getSerialNumber()](#getSerialNumber--) | シリアル番号を識別します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC 仕様に従った文字列形式から二次および追加の補足データをインスタンス化します。 |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | 製造日を識別します。 |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | 有効期限を識別します。 |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | 有効期限の形式を識別します。 |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | ロットまたはバッチ番号を識別します。 |
| [setQuantity(int value)](#setQuantity-int-) | 数量を識別します。0 から 500 までの整数値である必要があります。 |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | シリアル番号を識別します。 |
| [toString()](#toString--) | データを HIBC LIC 仕様に従った文字列形式に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  SecondaryAndAdditionalData  値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための  SecondaryAndAdditionalData  値です。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。デフォルト値: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


有効期限を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


有効期限の形式を識別します。

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


数量を識別します。0 から 500 までの整数値である必要があります。このフィールドを使用しない場合は数量を -1 に設定できます。デフォルト値: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - 32 ビット符号付き整数のハッシュコード。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


HIBC LIC 仕様に従った文字列形式から二次および追加の補足データをインスタンス化します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | フォーマットされた文字列。 |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


製造日を識別します。製造日はこのフィールドを使用しないようにするために DateTime.MinValue に設定できます。デフォルト値: DateTime.MinValue

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


有効期限を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


有効期限の形式を識別します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


ロットまたはバッチ番号を識別します。ロット/バッチ番号は最大 18 文字の英数字文字列である必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


数量を識別します。0 から 500 までの整数値である必要があります。このフィールドを使用しない場合は数量を -1 に設定できます。デフォルト値: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


シリアル番号を識別します。シリアル番号は最大 18 文字の英数字文字列である必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


データを HIBC LIC 仕様に従った文字列形式に変換します。

**Returns:**
java.lang.String - フォーマットされた文字列。
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

