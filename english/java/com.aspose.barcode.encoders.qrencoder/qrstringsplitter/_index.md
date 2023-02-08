---
title: QRStringSplitter
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.encoders.qrencoder/qrstringsplitter/
---
**Inheritance:**
java.lang.Object
```
public class QRStringSplitter
```
## Constructors

| Constructor | Description |
| --- | --- |
| [QRStringSplitter()](#QRStringSplitter--) |  |
## Fields

| Field | Description |
| --- | --- |
| [FNC1AsText](#FNC1AsText) |  |
| [FNC1FistPosTag](#FNC1FistPosTag) |  |
| [FNC1SecondPosTag](#FNC1SecondPosTag) |  |
| [MinimalECINonIgnored](#MinimalECINonIgnored) |  |
## Methods

| Method | Description |
| --- | --- |
| [GetCharacterType(char symbol)](#GetCharacterType-char-) |  |
| [SplitStringToECIPieces(String aString)](#SplitStringToECIPieces-java.lang.String-) |  |
| [SplitStringToFNC1(String aString)](#SplitStringToFNC1-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### QRStringSplitter() {#QRStringSplitter--}
```
public QRStringSplitter()
```


### FNC1AsText {#FNC1AsText}
```
public static final String FNC1AsText
```


### FNC1FistPosTag {#FNC1FistPosTag}
```
public static final String FNC1FistPosTag
```


### FNC1SecondPosTag {#FNC1SecondPosTag}
```
public static final String FNC1SecondPosTag
```


### MinimalECINonIgnored {#MinimalECINonIgnored}
```
public static final int MinimalECINonIgnored
```


### GetCharacterType(char symbol) {#GetCharacterType-char-}
```
public static QRCompactionType GetCharacterType(char symbol)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| symbol | char |  |

**Returns:**
com.aspose.barcode.encoders.qrencoder.QRCompactionType
### SplitStringToECIPieces(String aString) {#SplitStringToECIPieces-java.lang.String-}
```
public static System.Collections.Generic.List<ECIPiece> SplitStringToECIPieces(String aString)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aString | java.lang.String |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
### SplitStringToFNC1(String aString) {#SplitStringToFNC1-java.lang.String-}
```
public static System.Collections.Generic.List<FNC1Piece> SplitStringToFNC1(String aString)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| aString | java.lang.String |  |

**Returns:**
[List](../../com.aspose.ms.system.collections.generic/list)
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

