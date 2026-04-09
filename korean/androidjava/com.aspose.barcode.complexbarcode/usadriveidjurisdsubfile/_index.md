---
title: USADriveIdJurisdSubfile
second_title: Aspose.BarCode for Android via Java API Reference
description: USA DL에 대한 관할 구역별 필드용 클래스
type: docs
weight: 39
url: /ko/androidjava/com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile/
---
**Inheritance:**
java.lang.Object
```
public class USADriveIdJurisdSubfile
```

USA DL에 대한 관할 구역별 필드용 클래스
## Constructors

| Constructor | 설명 |
| --- | --- |
| [USADriveIdJurisdSubfile()](#USADriveIdJurisdSubfile--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [addOrReplace(USADriveIdJurisdSubfile.DataElement node)](#addOrReplace-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | ElementID가 이미 존재하면 새 DataElement를 추가하거나 교체합니다. |
| [addOrReplace(String id, String value)](#addOrReplace-java.lang.String-java.lang.String-) | 지정된 식별자와 값을 가진 새 DataElement를 추가하거나, 동일한 ElementID가 이미 존재하면 기존 요소를 교체합니다. |
| [clear()](#clear--) | 모든 데이터 요소를 지웁니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findDataElement(String id, boolean isOpenOrCreate)](#findDataElement-java.lang.String-boolean-) | 3자리 ID로 데이터 요소를 검색합니다 |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | 데이터 요소의 개수를 반환합니다 |
| [get_Item(int index)](#get-Item-int-) | 인덱스 번호로 인덱싱합니다 |
| [get_Item(String id)](#get-Item-java.lang.String-) | 3자리 요소 ID로 인덱싱합니다 |
| [hashCode()](#hashCode--) |  |
| [insert(int index, USADriveIdJurisdSubfile.DataElement node)](#insert-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 지정된 DataElement를 주어진 인덱스에 삽입합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeAt(int index)](#removeAt-int-) | 인덱스에서 요소를 제거하려 시도합니다 |
| [removeAt(String id)](#removeAt-java.lang.String-) | 3자리 ID를 가진 요소를 제거하려 시도합니다 |
| [set_Item(int index, USADriveIdJurisdSubfile.DataElement value)](#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 인덱스 번호로 인덱싱합니다 |
| [set_Item(String id, USADriveIdJurisdSubfile.DataElement value)](#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-) | 3자리 요소 ID로 인덱싱합니다 |
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


ElementID가 이미 존재하면 새 DataElement를 추가하거나 교체합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 추가할 DataElement |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Added/replaced data element
### addOrReplace(String id, String value) {#addOrReplace-java.lang.String-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement addOrReplace(String id, String value)
```


지정된 식별자와 값을 가진 새 DataElement를 추가하거나, 동일한 ElementID가 이미 존재하면 기존 요소를 교체합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| id | java.lang.String | 관할 관련 데이터 요소를 고유하게 지정하는 3자리 식별자입니다. |
| 값 | java.lang.String | 데이터 요소에 할당된 텍스트 값; 요소가 이미 존재하면 이 값이 기존 값을 덮어씁니다. |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - The DataElement instance that was added to the collection or updated in place.
### clear() {#clear--}
```
public final void clear()
```


모든 데이터 요소를 지웁니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findDataElement(String id, boolean isOpenOrCreate) {#findDataElement-java.lang.String-boolean-}
```
public final USADriveIdJurisdSubfile.DataElement findDataElement(String id, boolean isOpenOrCreate)
```


3자리 ID로 데이터 요소를 검색합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| id | java.lang.String | 3자리 id |
| isOpenOrCreate | boolean | true이면, 찾지 못했을 때 생성됩니다 |

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


데이터 요소의 개수를 반환합니다

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(int index)
```


인덱스 번호로 인덱싱합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| index | int | 요소 인덱스 (int) |

**Returns:**
[DataElement](../../com.aspose.barcode.complexbarcode/dataelement) - Corresponding DataElement
### get_Item(String id) {#get-Item-java.lang.String-}
```
public final USADriveIdJurisdSubfile.DataElement get_Item(String id)
```


3자리 요소 ID로 인덱싱합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| id | java.lang.String | 3자리 요소 id |

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


지정된 DataElement를 주어진 인덱스에 삽입합니다. 동일한 ElementID를 가진 DataElement가 이미 존재하면 교체됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| index | int | 요소를 삽입해야 하는 0부터 시작하는 인덱스입니다. |
| node | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) | 대상 위치에 삽입하거나 교체할 DataElement 인스턴스입니다. |

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


인덱스에서 요소를 제거하려 시도합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| index | int | 인덱스 번호 |

**Returns:**
boolean - 성공하면 true, 범위를 벗어나면 false
### removeAt(String id) {#removeAt-java.lang.String-}
```
public final boolean removeAt(String id)
```


3자리 ID를 가진 요소를 제거하려 시도합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| id | java.lang.String | 3자리 id |

**Returns:**
boolean - 성공하면 true, 해당 id가 없으면 false
### set_Item(int index, USADriveIdJurisdSubfile.DataElement value) {#set-Item-int-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(int index, USADriveIdJurisdSubfile.DataElement value)
```


인덱스 번호로 인덱싱합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| index | int | 요소 인덱스 (int) |
| value | [DataElement](../../com.aspose.barcode.complexbarcode/dataelement) |  |

### set_Item(String id, USADriveIdJurisdSubfile.DataElement value) {#set-Item-java.lang.String-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile.DataElement-}
```
public final void set_Item(String id, USADriveIdJurisdSubfile.DataElement value)
```


3자리 요소 ID로 인덱싱합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| id | java.lang.String | 3자리 요소 id |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

