---
title: PrimaryData
second_title: Aspose.BarCode for Android via Java API Reference
description: HIBC LIC の一次データを格納するクラス。
type: docs
weight: 34
url: /ja/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

HIBC LIC の一次データを格納するクラス。
## Constructors

| Constructor | Description |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | このインスタンスが指定された  PrimaryData  値と等しいかどうかを示す値を返します。 |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | ラベラー識別コードの日付を識別します。 |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 製品またはカタログ番号を識別します。 |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 測定単位 ID を識別します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC 仕様に従って文字列形式からプライマリデータをインスタンス化します。 |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | ラベラー識別コードの日付を識別します。 |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 製品またはカタログ番号を識別します。 |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 測定単位 ID を識別します。 |
| [toString()](#toString--) | データを HIBC LIC 仕様に従った文字列形式に変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


このインスタンスが指定された  PrimaryData  値と等しいかどうかを示す値を返します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較するための PrimaryData 値。 |

**Returns:**
boolean -  **true**  obj がこのインスタンスと同じ値を持つ場合; それ以外の場合は **false** 。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


ラベラー識別コードの日付を識別します。ラベラー識別コードは 4 文字の英数字文字列で、最初の文字は必ずアルファベットでなければなりません。

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


製品またはカタログ番号を識別します。製品またはカタログ番号は最大 18 文字の英数字文字列である必要があります。

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


測定単位 ID を識別します。測定単位 ID は 0 から 9 の整数値でなければなりません。

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


HIBC LIC 仕様に従って文字列形式からプライマリデータをインスタンス化します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | フォーマットされた文字列。 |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


ラベラー識別コードの日付を識別します。ラベラー識別コードは 4 文字の英数字文字列で、最初の文字は必ずアルファベットでなければなりません。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


製品またはカタログ番号を識別します。製品またはカタログ番号は最大 18 文字の英数字文字列である必要があります。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


測定単位 ID を識別します。測定単位 ID は 0 から 9 の整数値でなければなりません。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | int |  |

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

