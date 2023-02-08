---
title: pdf417DataGrid
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417datagrid/
---
**Inheritance:**
java.lang.Object
```
public class pdf417DataGrid
```
## Constructors

| Constructor | Description |
| --- | --- |
| [pdf417DataGrid(int aColumns, int aRows)](#pdf417DataGrid-int-int-) |  |
| [pdf417DataGrid(int aColumns, int aRows, pdf417DataCell aInit)](#pdf417DataGrid-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-) |  |
| [pdf417DataGrid(pdf417DataGrid aGrid)](#pdf417DataGrid-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataGrid-) |  |
## Fields

| Field | Description |
| --- | --- |
| [Columns](#Columns) |  |
| [Data](#Data) |  |
| [Rows](#Rows) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [extractRawData()](#extractRawData--) | Returns recognized values in correct order |
| [extractRawData(int aWipedWordDefVal)](#extractRawData-int-) | Returns recognized values in correct order with wiped values replacement |
| [extractRawDataSafe(pdf417DataGrid aGrid)](#extractRawDataSafe-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataGrid-) | Null safe codewords list extraction |
| [getAverageQuality()](#getAverageQuality--) | Calculates average quality of codewords |
| [getClass()](#getClass--) |  |
| [getValue(int aColumn, int aRow)](#getValue-int-int-) | Returns value or null if we out of the grid. |
| [getWipedWordsCount()](#getWipedWordsCount--) | Detects count of not recognized codewords(Value is -1) in datacolumns grid |
| [get_Item(int c, int r)](#get-Item-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [isCellExists(int aColumn, int aRow)](#isCellExists-int-int-) | Checks if current column+row position exists |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBestByQualityValue(int aColumn, int aRow, pdf417DataCell aItem)](#setBestByQualityValue-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-) | Set new value the call if it has better quality. |
| [set_Item(int c, int r, pdf417DataCell value)](#set-Item-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### pdf417DataGrid(int aColumns, int aRows) {#pdf417DataGrid-int-int-}
```
public pdf417DataGrid(int aColumns, int aRows)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aColumns | int |  |
| aRows | int |  |

### pdf417DataGrid(int aColumns, int aRows, pdf417DataCell aInit) {#pdf417DataGrid-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-}
```
public pdf417DataGrid(int aColumns, int aRows, pdf417DataCell aInit)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aColumns | int |  |
| aRows | int |  |
| aInit | com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell |  |

### pdf417DataGrid(pdf417DataGrid aGrid) {#pdf417DataGrid-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataGrid-}
```
public pdf417DataGrid(pdf417DataGrid aGrid)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [pdf417DataGrid](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417datagrid) |  |

### Columns {#Columns}
```
public int Columns
```


### Data {#Data}
```
public pdf417DataCell[] Data
```


### Rows {#Rows}
```
public int Rows
```


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
### extractRawData() {#extractRawData--}
```
public System.Collections.Generic.List<Integer> extractRawData()
```


Returns recognized values in correct order

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - codewords list
### extractRawData(int aWipedWordDefVal) {#extractRawData-int-}
```
public System.Collections.Generic.List<Integer> extractRawData(int aWipedWordDefVal)
```


Returns recognized values in correct order with wiped values replacement

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aWipedWordDefVal | int | value which replace not recognized cells |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - codewords list
### extractRawDataSafe(pdf417DataGrid aGrid) {#extractRawDataSafe-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataGrid-}
```
public static System.Collections.Generic.List<Integer> extractRawDataSafe(pdf417DataGrid aGrid)
```


Null safe codewords list extraction

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aGrid | [pdf417DataGrid](../../com.aspose.barcode.barcoderecognition.pdf417.codeword/pdf417datagrid) | datagrid |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list) - recognized values in correct order or null
### getAverageQuality() {#getAverageQuality--}
```
public float getAverageQuality()
```


Calculates average quality of codewords

**Returns:**
float - average codewords quality
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getValue(int aColumn, int aRow) {#getValue-int-int-}
```
public pdf417DataCell getValue(int aColumn, int aRow)
```


Returns value or null if we out of the grid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aColumn | int | X |
| aRow | int | Y |

**Returns:**
com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell - value from cell or null
### getWipedWordsCount() {#getWipedWordsCount--}
```
public int getWipedWordsCount()
```


Detects count of not recognized codewords(Value is -1) in datacolumns grid

**Returns:**
int - not recognized codewords in datacell
### get_Item(int c, int r) {#get-Item-int-int-}
```
public pdf417DataCell get_Item(int c, int r)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | int |  |
| r | int |  |

**Returns:**
com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCellExists(int aColumn, int aRow) {#isCellExists-int-int-}
```
public boolean isCellExists(int aColumn, int aRow)
```


Checks if current column+row position exists

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aColumn | int | X |
| aRow | int | Y |

**Returns:**
boolean - hitting grid area
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBestByQualityValue(int aColumn, int aRow, pdf417DataCell aItem) {#setBestByQualityValue-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-}
```
public void setBestByQualityValue(int aColumn, int aRow, pdf417DataCell aItem)
```


Set new value the call if it has better quality. If new value is null or we misshit the grid, just pass it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aColumn | int | X |
| aRow | int | Y |
| aItem | com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell | new item, can be null |

### set_Item(int c, int r, pdf417DataCell value) {#set-Item-int-int-com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell-}
```
public void set_Item(int c, int r, pdf417DataCell value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | int |  |
| r | int |  |
| value | com.aspose.barcode.barcoderecognition.pdf417.codeword.pdf417DataCell |  |

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

