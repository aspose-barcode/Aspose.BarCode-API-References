---
title: HanXinParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Han Xin parameters.
type: docs
weight: 50
url: /androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | Extended Channel Interpretation Identifiers. |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin encoding mode. |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Level of Reed-Solomon error correction for Han Xin barcode. |
| [getHanXinVersion()](#getHanXinVersion--) | Version of HanXin Code. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHanXinECIEncoding(int value)](#setHanXinECIEncoding-int-) | Extended Channel Interpretation Identifiers. |
| [setHanXinEncodeMode(HanXinEncodeMode value)](#setHanXinEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin encoding mode. |
| [setHanXinErrorLevel(HanXinErrorLevel value)](#setHanXinErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Level of Reed-Solomon error correction for Han Xin barcode. |
| [setHanXinVersion(HanXinVersion value)](#setHanXinVersion-com.aspose.barcode.generation.HanXinVersion-) | Version of HanXin Code. |
| [toString()](#toString--) | Returns a human-readable string representation of this  HanXinParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public int getHanXinECIEncoding()
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public HanXinEncodeMode getHanXinEncodeMode()
```


HanXin encoding mode. Default value: HanXinEncodeMode.Mixed.

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public HanXinErrorLevel getHanXinErrorLevel()
```


Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see HanXinErrorLevel.

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public HanXinVersion getHanXinVersion()
```


Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is HanXinVersion.Auto.

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
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




### setHanXinECIEncoding(int value) {#setHanXinECIEncoding-int-}
```
public void setHanXinECIEncoding(int value)
```


Extended Channel Interpretation Identifiers. It is used to tell the barcode reader details about the used references for encoding the data in the symbol. Current implementation consists all well known charset encodings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHanXinEncodeMode(HanXinEncodeMode value) {#setHanXinEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public void setHanXinEncodeMode(HanXinEncodeMode value)
```


HanXin encoding mode. Default value: HanXinEncodeMode.Mixed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setHanXinErrorLevel(HanXinErrorLevel value) {#setHanXinErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public void setHanXinErrorLevel(HanXinErrorLevel value)
```


Level of Reed-Solomon error correction for Han Xin barcode. From low to high: L1, L2, L3, L4. see HanXinErrorLevel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setHanXinVersion(HanXinVersion value) {#setHanXinVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public void setHanXinVersion(HanXinVersion value)
```


Version of HanXin Code. From Version01 to Version84 for Han Xin code. Default value is HanXinVersion.Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  HanXinParameters .

**Returns:**
java.lang.String - A string that represents this  HanXinParameters .
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

