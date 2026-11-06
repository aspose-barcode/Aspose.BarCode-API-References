---
title: "住所"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "債権者または債務者の住所です。"
type: docs
weight: 10
url: /ja/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

債権者または債務者の住所です。

ストリート、番地、郵便番号、町（タイプ *structured address*）のいずれか、または住所行1と2（タイプ *combined address elements*）を設定できます。これらのフィールドのいずれかが設定されると、タイプは自動的に設定されます。フィールドを設定する前は、住所タイプは *undetermined* です。両方のタイプのフィールドが設定されると、住所タイプは *conflicting* になります。すべてのフィールドが空でない限り、名前と国コードは常に設定する必要があります。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Address()](#Address--) | Address のインスタンスを作成します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clear()](#clear--) | すべてのフィールドをクリアし、タイプを AddressType.Undetermined に設定します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。 |
| [getAddressLine1()](#getAddressLine1--) | 住所行1を取得します。 |
| [getAddressLine2()](#getAddressLine2--) | 住所行2を取得します。 |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | 2文字のISO国コードを取得します。 |
| [getHouseNo()](#getHouseNo--) | 住宅番号を取得します。 |
| [getName()](#getName--) | 名前を取得します。自然人の場合は姓と名、法人の場合は会社名です。 |
| [getPostalCode()](#getPostalCode--) | 郵便番号を取得します。 |
| [getStreet()](#getStreet--) | 通り名を取得します。 |
| [getTown()](#getTown--) | 町または市を取得します。 |
| [getType()](#getType--) | 住所タイプを取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 住所行1を設定します。 |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 住所行2を設定します。 |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 2文字のISO国コードを設定します。 |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 住宅番号を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。自然人の場合は姓と名、法人の場合は会社名です。 |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 郵便番号を設定します。 |
| [setStreet(String value)](#setStreet-java.lang.String-) | 通り名を設定します。 |
| [setTown(String value)](#setTown-java.lang.String-) | 町または市を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Address のインスタンスを作成します

### clear() {#clear--}
```
public void clear()
```


すべてのフィールドをクリアし、タイプを AddressType.Undetermined に設定します。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定されたオブジェクトが現在のオブジェクトと等しいかどうかを判断します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 現在のオブジェクトと比較するオブジェクトです。 |

**Returns:**
boolean - 指定されたオブジェクトが現在のオブジェクトと等しい場合は true、そうでない場合は false。
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


住所行1を取得します。

住所行1には通り名、住宅番号、または私書箱が含まれます。

このフィールドを設定すると、住所タイプが  AddressType.CombinedElements  に設定されます。ただし、既に  AddressType.Structured  の場合は  AddressType.Conflicting  になります。

このフィールドは結合要素住所でのみ使用され、オプションです。

値: 住所行1。

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


住所行2を取得します。

住所行2には郵便番号と町が含まれます。

このフィールドを設定すると、住所タイプが  AddressType.CombinedElements  に設定されます。ただし、既に  AddressType.Structured  の場合は  AddressType.Conflicting  になります。

このフィールドは結合要素住所でのみ使用されます。このタイプでは必須です。

値: 住所行2。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


2文字のISO国コードを取得します。

国コードは、住所全体に  null  または空の値が含まれていない限り必須です。

値: ISO国コード。

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


住宅番号を取得します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

値: 番地。

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


名前を取得します。自然人の場合は姓と名、法人の場合は会社名です。

値: 名前。

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


郵便番号を取得します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用されます。このタイプでは必須です。

値: 郵便番号。

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


通り名を取得します。

通りは住宅番号なしで指定する必要があります。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

値: 通り。

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


町または市を取得します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用されます。このタイプでは必須です。

値: 町または市。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


住所タイプを取得します。

住所タイプは、通り/住宅番号を設定するか、住所行1と2を設定することで自動的に決定されます。フィールドを設定する前は住所タイプは *Undetermined* です。両方のタイプのフィールドが設定されると、住所タイプは *Conflicting* になります。

値: 住所タイプ。

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを取得します。

**Returns:**
int - 現在のオブジェクトのハッシュコードです。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


住所行1を設定します。

住所行1には通り名、住宅番号、または私書箱が含まれます。

このフィールドを設定すると、住所タイプが  AddressType.CombinedElements  に設定されます。ただし、既に  AddressType.Structured  の場合は  AddressType.Conflicting  になります。

このフィールドは結合要素住所でのみ使用され、オプションです。

値: 住所行1。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


住所行2を設定します。

住所行2には郵便番号と町が含まれます。

このフィールドを設定すると、住所タイプが  AddressType.CombinedElements  に設定されます。ただし、既に  AddressType.Structured  の場合は  AddressType.Conflicting  になります。

このフィールドは結合要素住所でのみ使用されます。このタイプでは必須です。

値: 住所行2。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


2文字のISO国コードを設定します。

国コードは、住所全体に  null  または空の値が含まれていない限り必須です。

値: ISO国コード。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


住宅番号を設定します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

値: 番地。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。自然人の場合は姓と名、法人の場合は会社名です。

値: 名前。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


郵便番号を設定します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用されます。このタイプでは必須です。

値: 郵便番号。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


通り名を設定します。

通りは住宅番号なしで指定する必要があります。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用され、オプションです。

値: 通り。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


町または市を設定します。

このフィールドを設定すると、住所タイプが  AddressType.Structured  に設定されます。ただし、既に  AddressType.CombinedElements  の場合は  AddressType.Conflicting  になります。

このフィールドは構造化された住所でのみ使用されます。このタイプでは必須です。

値: 町または市。

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

