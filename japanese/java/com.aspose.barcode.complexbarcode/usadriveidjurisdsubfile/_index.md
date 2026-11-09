---
title: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode for Java API リファレンス"
description: "米国運転免許証の管轄別フィールド用クラス"
type: docs
weight: 38
url: /ja/java/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

米国運転免許証の管轄別フィールド用クラス
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | ElementID が既に存在する場合は置き換え、存在しない場合は新しい DataElement を追加します。 |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | 指定された識別子と値で新しい DataElement を追加するか、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。 |
| [clear()](#clear--) | すべてのデータ要素をクリアします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | 3文字の ID でデータ要素を検索します。 |
| [get(int index)](#get-int-) | インデックス番号によるインデックス付け |
| [get(String id)](#get-java.lang.String-) | 3文字の要素 ID によるインデックス付け |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 指定された DataElement を指定されたインデックスに挿入します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(int index)](#remove-int-) | インデックス位置の要素を削除しようとします。 |
| [remove(String id)](#remove-java.lang.String-) | 3文字のIDを持つ要素の削除を試みます |
| [set(int index, USADriveIdJurisdSubfile.DataElement value)](#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | インデックス番号によるインデックス付け |
| [set(String id, USADriveIdJurisdSubfile.DataElement value)](#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 3文字の要素 ID によるインデックス付け |
| [size()](#size--) | データ要素の数を返します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdJurisdSubfile() {#USADriveIdJurisdSubfile--}
```
public USADriveIdJurisdSubfile()
```


### addOrReplace(USADriveIdJurisdSubfile.DataElement node) {#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(USADriveIdJurisdSubfile.DataElement node)
```


ElementID が既に存在する場合は置き換え、存在しない場合は新しい DataElement を追加します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 追加するDataElement |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


指定された識別子と値で新しい DataElement を追加するか、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 管轄関連データ要素を一意に指定する3文字の識別子です。 |
| 値 | java.lang.String | データ要素に割り当てられたテキスト値です。要素が既に存在する場合、この値は既存のものを上書きします。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


すべてのデータ要素をクリアします。

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
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


3文字の ID でデータ要素を検索します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 3文字のid |
| isOpenOrCreate | boolean | true の場合、見つからなければ作成されます |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### get(int index) {#get-int-}
```
public final USADriveIdJurisdSubfile.DataElement get(int index)
```


インデックス番号によるインデックス付け

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素インデックス (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get(String id) {#get-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get(String id)
```


3文字の要素 ID によるインデックス付け

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 3文字の要素id |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### insert(int index, USADriveIdJurisdSubfile.DataElement node) {#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final USADriveIdJurisdSubfile.DataElement insert(int index, USADriveIdJurisdSubfile.DataElement node)
```


指定されたDataElementを指定されたインデックスに挿入します。同じElementIDを持つDataElementが既に存在する場合、置き換えられます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素を挿入すべきゼロベースのインデックスです。 |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 対象位置に挿入または置き換えるDataElementインスタンスです。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement that was inserted or used to replace an existing entry.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(int index) {#remove-int-}
```
public final boolean remove(int index)
```


インデックス位置の要素を削除しようとします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | インデックス番号 |

**Returns:**
boolean - 成功した場合はtrue、範囲外の場合はfalse
### remove(String id) {#remove-java.lang.String-}
```
public final boolean remove(String id)
```


3文字のIDを持つ要素の削除を試みます

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 3文字のid |

**Returns:**
boolean - 成功した場合はtrue、該当するidがない場合はfalse
### set(int index, USADriveIdJurisdSubfile.DataElement value) {#set-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(int index, USADriveIdJurisdSubfile.DataElement value)
```


インデックス番号によるインデックス付け

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素インデックス (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set(String id, USADriveIdJurisdSubfile.DataElement value) {#set-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set(String id, USADriveIdJurisdSubfile.DataElement value)
```


3文字の要素 ID によるインデックス付け

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | java.lang.String | 3文字の要素id |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### size() {#size--}
```
public final int size()
```


データ要素の数を返します

**Returns:**
int
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

