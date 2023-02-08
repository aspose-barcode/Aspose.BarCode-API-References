---
title: AztecDatas
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 11
url: /java/com.aspose.barcode.encoders.aztec/aztecdatas/
---
**Inheritance:**
java.lang.Object
```
public class AztecDatas
```
## Constructors

| Constructor | Description |
| --- | --- |
| [AztecDatas()](#AztecDatas--) |  |
## Fields

| Field | Description |
| --- | --- |
| [AztecRuneSymbolSize](#AztecRuneSymbolSize) |  |
| [CharSiz](#CharSiz) | The 6x1 matrix CharSiz[State] indicates the Character Size, namely how many bits are required for each data character within each state. |
| [Inf](#Inf) | Large value for empty element in FromTo tables |
| [LatLen](#LatLen) | This is a 6x6 matrix LatLen[From][To] of the Latch Lengths, namely how many bits it takes to latch from one state to another. |
| [LatchTable](#LatchTable) | Latch table for latch from one state to another. |
| [ShftLen](#ShftLen) | This is a 5x5 matrix ShftLen[From][To] of the Shift Lengths, namely how many bits it takes to shift from one state into another for a single entries. |
| [ShiftTable](#ShiftTable) | Shift table for shift from one state to another. |
| [s_CharSetDigit](#s-CharSetDigit) |  |
| [s_CharSetLower](#s-CharSetLower) |  |
| [s_CharSetMixed](#s-CharSetMixed) |  |
| [s_CharSetPunct](#s-CharSetPunct) |  |
| [s_CharSetPunctDoubles](#s-CharSetPunctDoubles) |  |
| [s_CharSetUpper](#s-CharSetUpper) |  |
| [s_VersionInfo](#s-VersionInfo) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [versionInfo(int versionIndex)](#versionInfo-int-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AztecDatas() {#AztecDatas--}
```
public AztecDatas()
```


### AztecRuneSymbolSize {#AztecRuneSymbolSize}
```
public static final int AztecRuneSymbolSize
```


### CharSiz {#CharSiz}
```
public static final int[] CharSiz
```


The 6x1 matrix CharSiz[State] indicates the Character Size, namely how many bits are required for each data character within each state.

### Inf {#Inf}
```
public static int Inf
```


Large value for empty element in FromTo tables

### LatLen {#LatLen}
```
public static final int[][] LatLen
```


This is a 6x6 matrix LatLen[From][To] of the Latch Lengths, namely how many bits it takes to latch from one state to another.

### LatchTable {#LatchTable}
```
public static final Token[][][] LatchTable
```


Latch table for latch from one state to another.

### ShftLen {#ShftLen}
```
public static final int[][] ShftLen
```


This is a 5x5 matrix ShftLen[From][To] of the Shift Lengths, namely how many bits it takes to shift from one state into another for a single entries.

### ShiftTable {#ShiftTable}
```
public static final Token[][][] ShiftTable
```


Shift table for shift from one state to another.

### s_CharSetDigit {#s-CharSetDigit}
```
public static final int[] s_CharSetDigit
```


### s_CharSetLower {#s-CharSetLower}
```
public static final int[] s_CharSetLower
```


### s_CharSetMixed {#s-CharSetMixed}
```
public static final int[] s_CharSetMixed
```


### s_CharSetPunct {#s-CharSetPunct}
```
public static final int[] s_CharSetPunct
```


### s_CharSetPunctDoubles {#s-CharSetPunctDoubles}
```
public static final Token[] s_CharSetPunctDoubles
```


### s_CharSetUpper {#s-CharSetUpper}
```
public static final int[] s_CharSetUpper
```


### s_VersionInfo {#s-VersionInfo}
```
public static final int[][] s_VersionInfo
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
### versionInfo(int versionIndex) {#versionInfo-int-}
```
public static AztecSymbolData versionInfo(int versionIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| versionIndex | int |  |

**Returns:**
[AztecSymbolData](../../com.aspose.barcode.encoders.aztec/aztecsymboldata)
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

