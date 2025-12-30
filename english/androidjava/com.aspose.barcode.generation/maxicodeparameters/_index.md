---
title: MaxiCodeParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: MaxiCode parameters.
type: docs
weight: 57
url: /androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | Height/Width ratio of 2D BarCode module. |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | Gets ECI encoding. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Gets a MaxiCode barcode id in structured append mode. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Gets a MaxiCode barcodes count in structured append mode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setECIEncoding(int ECIEncoding)](#setECIEncoding-int-) | Sets ECI encoding. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode maxiCodeEncodeMode)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeMode(int maxiCodeMode)](#setMaxiCodeMode-int-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int maxiCodeStructuredAppendModeBarcodeId)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Sets a MaxiCode barcode id in structured append mode. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int maxiCodeStructuredAppendModeBarcodesCount)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Sets a MaxiCode barcodes count in structured append mode. |
| [toString()](#toString--) | Returns a human-readable string representation of this  MaxiCodeParameters . |
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
### getAspectRatio() {#getAspectRatio--}
```
public float getAspectRatio()
```


Height/Width ratio of 2D BarCode module.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getECIEncoding() {#getECIEncoding--}
```
public int getECIEncoding()
```


Gets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. Default value: ISO-8859-1

**Returns:**
int
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Gets a MaxiCode encode mode. Default value: AUTO.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode)
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public int getMaxiCodeMode()
```


Gets a MaxiCode encode mode.

**Returns:**
int
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public int getMaxiCodeStructuredAppendModeBarcodeId()
```


Gets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Returns:**
int
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Gets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Returns:**
int
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




### setAspectRatio(float value) {#setAspectRatio-float-}
```
public void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int ECIEncoding) {#setECIEncoding-int-}
```
public void setECIEncoding(int ECIEncoding)
```


Sets ECI encoding. Used when MaxiCodeEncodeMode is AUTO. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ECIEncoding | int |  |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode maxiCodeEncodeMode) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public void setMaxiCodeEncodeMode(MaxiCodeEncodeMode maxiCodeEncodeMode)
```


Sets a MaxiCode encode mode. Default value: AUTO.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxiCodeEncodeMode | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) |  |

### setMaxiCodeMode(int maxiCodeMode) {#setMaxiCodeMode-int-}
```
public void setMaxiCodeMode(int maxiCodeMode)
```


Sets a MaxiCode encode mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxiCodeMode | int |  |

### setMaxiCodeStructuredAppendModeBarcodeId(int maxiCodeStructuredAppendModeBarcodeId) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public void setMaxiCodeStructuredAppendModeBarcodeId(int maxiCodeStructuredAppendModeBarcodeId)
```


Sets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxiCodeStructuredAppendModeBarcodeId | int |  |

### setMaxiCodeStructuredAppendModeBarcodesCount(int maxiCodeStructuredAppendModeBarcodesCount) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public void setMaxiCodeStructuredAppendModeBarcodesCount(int maxiCodeStructuredAppendModeBarcodesCount)
```


Sets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxiCodeStructuredAppendModeBarcodesCount | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  MaxiCodeParameters .

**Returns:**
java.lang.String - A string that represents this  MaxiCodeParameters .
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

