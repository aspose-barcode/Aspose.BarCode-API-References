---
title: USADriveIdJurisdSubfile
second_title: Aspose.BarCode for Android via Java API Reference
description: USA DL の管轄固有フィールド用クラス
type: docs
weight: 39
url: /ja/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

USA DL の管轄固有フィールド用クラス
## Constructors

| Constructor | Description |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | ElementID が既に存在する場合は、新しい DataElement を追加するか置き換えます。 |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | 指定された識別子と値で新しい DataElement を追加するか、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。 |
| [clear()](#clear--) | すべてのデータ要素をクリアします |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | 3文字のIDでデータ要素を検索します |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | データ要素の数を返します |
| [get_Item(int index)](#get-Item-int-) | インデックス番号でインデックス付けします |
| [get_Item(String id)](#get-Item-java.lang.String-) | 3文字の要素IDでインデックス付けします |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 指定された DataElement を指定されたインデックスに挿入します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | インデックス位置の要素を削除しようとします |
| [removeAt(String id)](#removeAt-java.lang.String-) | 3文字のIDを持つ要素を削除しようとします |
| [set_Item(int index, USADriveIdJurisdSubfile.DataElement value)](#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | インデックス番号でインデックス付けします |
| [set_Item(String id, USADriveIdJurisdSubfile.DataElement value)](#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 3文字の要素IDでインデックス付けします |
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


ElementID が既に存在する場合は、新しい DataElement を追加するか置き換えます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 追加する DataElement |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


指定された識別子と値で新しい DataElement を追加するか、同じ ElementID のエントリが既に存在する場合は既存の要素を置き換えます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 管轄関連データ要素を一意に指定する3文字の識別子です。 |
| 値 | java.lang.String | データ要素に割り当てられたテキスト値です。要素が既に存在する場合、この値は既存のものを上書きします。 |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


すべてのデータ要素をクリアします

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
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


3文字のIDでデータ要素を検索します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3文字のID |
| isOpenOrCreate | boolean | true の場合、見つからなければ作成されます |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Found data element
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public final int getCount()
```


データ要素の数を返します

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(int index)
```


インデックス番号でインデックス付けします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素インデックス (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get_Item(String id) {#get-Item-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(String id)
```


3文字の要素IDでインデックス付けします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3文字の要素ID |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
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


指定された DataElement を指定されたインデックスに挿入します。同じ ElementID を持つ DataElement が既に存在する場合、置き換えられます。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素を挿入すべきゼロベースのインデックスです。 |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 対象位置に挿入または置き換える DataElement インスタンスです。 |

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




### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


インデックス位置の要素を削除しようとします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | インデックス番号 |

**Returns:**
boolean - 成功した場合は true、範囲外の場合は false
### removeAt(String id) {#removeAt-java.lang.String-}
```
public final boolean removeAt(String id)
```


3文字のIDを持つ要素を削除しようとします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3文字のID |

**Returns:**
boolean - 成功した場合は true、該当する ID がない場合は false
### set_Item(int index, USADriveIdJurisdSubfile.DataElement value) {#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(int index, USADriveIdJurisdSubfile.DataElement value)
```


インデックス番号でインデックス付けします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素インデックス (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set_Item(String id, USADriveIdJurisdSubfile.DataElement value) {#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(String id, USADriveIdJurisdSubfile.DataElement value)
```


3文字の要素IDでインデックス付けします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | 3文字の要素ID |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

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

