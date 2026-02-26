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
| [getEncodeMode()](#getEncodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeMode()](#getMaxiCodeMode--) | Gets a MaxiCode encode mode. |
| [getMaxiCodeStructuredAppendModeBarcodeId()](#getMaxiCodeStructuredAppendModeBarcodeId--) | Gets a MaxiCode barcode id in structured append mode. |
| [getMaxiCodeStructuredAppendModeBarcodesCount()](#getMaxiCodeStructuredAppendModeBarcodesCount--) | Gets a MaxiCode barcodes count in structured append mode. |
| [getMode()](#getMode--) | Gets a MaxiCode encode mode. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Gets a MaxiCode barcode id in structured append mode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Gets a MaxiCode barcodes count in structured append mode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | Height/Width ratio of 2D BarCode module. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Sets ECI encoding. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeMode(int value)](#setMaxiCodeMode-int-) | Sets a MaxiCode encode mode. |
| [setMaxiCodeStructuredAppendModeBarcodeId(int value)](#setMaxiCodeStructuredAppendModeBarcodeId-int-) | Sets a MaxiCode barcode id in structured append mode. |
| [setMaxiCodeStructuredAppendModeBarcodesCount(int value)](#setMaxiCodeStructuredAppendModeBarcodesCount-int-) | Sets a MaxiCode barcodes count in structured append mode. |
| [setMode(int value)](#setMode-int-) | Sets a MaxiCode encode mode. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Sets a MaxiCode barcode id in structured append mode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Sets a MaxiCode barcodes count in structured append mode. |
| [toString()](#toString--) | Returns a human-readable string representation of this [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters). |
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
public final float getAspectRatio()
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
public final int getECIEncoding()
```


Gets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1

**Returns:**
int - ECI encoding.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Gets a MaxiCode encode mode. Default value: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


Gets a MaxiCode encode mode. Default value: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeMode() {#getMaxiCodeMode--}
```
public final int getMaxiCodeMode()
```


Gets a MaxiCode encode mode.

**Returns:**
int - a MaxiCode encode mode.
### getMaxiCodeStructuredAppendModeBarcodeId() {#getMaxiCodeStructuredAppendModeBarcodeId--}
```
public final int getMaxiCodeStructuredAppendModeBarcodeId()
```


Gets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Returns:**
int - a MaxiCode barcode id in structured append mode.
### getMaxiCodeStructuredAppendModeBarcodesCount() {#getMaxiCodeStructuredAppendModeBarcodesCount--}
```
public final int getMaxiCodeStructuredAppendModeBarcodesCount()
```


Gets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Returns:**
int - a MaxiCode barcodes count in structured append mode.
### getMode() {#getMode--}
```
public final int getMode()
```


Gets a MaxiCode encode mode.

**Returns:**
int - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Gets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Returns:**
int - a MaxiCode barcode id in structured append mode.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Gets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Returns:**
int - a MaxiCode barcodes count in structured append mode.
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
public final void setAspectRatio(float value)
```


Height/Width ratio of 2D BarCode module.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Sets ECI encoding. Used when MaxiCodeEncodeMode is Auto. Default value: ISO-8859-1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ECI encoding. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Sets a MaxiCode encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | a MaxiCode encode mode. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


Sets a MaxiCode encode mode. Default value: Auto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | a MaxiCode encode mode. |

### setMaxiCodeMode(int value) {#setMaxiCodeMode-int-}
```
public final void setMaxiCodeMode(int value)
```


Sets a MaxiCode encode mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode encode mode. |

### setMaxiCodeStructuredAppendModeBarcodeId(int value) {#setMaxiCodeStructuredAppendModeBarcodeId-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodeId(int value)
```


Sets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode barcode id in structured append mode. |

### setMaxiCodeStructuredAppendModeBarcodesCount(int value) {#setMaxiCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setMaxiCodeStructuredAppendModeBarcodesCount(int value)
```


Sets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode barcodes count in structured append mode. |

### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Sets a MaxiCode encode mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode encode mode. |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


Sets a MaxiCode barcode id in structured append mode. ID must be a value between 1 and 8. Default value: 0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode barcode id in structured append mode. |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


Sets a MaxiCode barcodes count in structured append mode. Count number must be a value between 2 and 8 (maximum barcodes count). Default value: -1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | a MaxiCode barcodes count in structured append mode. |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).

**Returns:**
java.lang.String - A string that represents this [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters).
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

