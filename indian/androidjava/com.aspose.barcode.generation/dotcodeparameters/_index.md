---
title: DotCodeParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: DotCode पैरामीटर।
type: docs
weight: 36
url: /hi/androidjava/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | Identifies columns count. |
| [getDotCodeEncodeMode()](#getDotCodeEncodeMode--) | Identifies DotCode encode mode. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [getECIEncoding()](#getECIEncoding--) | Identifies ECI encoding. |
| [getEncodeMode()](#getEncodeMode--) | Identifies DotCode encode mode. |
| [getRows()](#getRows--) | Identifies rows count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Identifies the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Identifies DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setColumns(int value)](#setColumns-int-) | Identifies columns count. |
| [setDotCodeEncodeMode(DotCodeEncodeMode value)](#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setDotCodeStructuredAppendModeBarcodeId(int value)](#setDotCodeStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setDotCodeStructuredAppendModeBarcodesCount(int value)](#setDotCodeStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Identifies ECI encoding. |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | Identifies DotCode encode mode. |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [setRows(int value)](#setRows-int-) | Identifies rows count. |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | Identifies the ID of the DotCode structured append mode barcode. |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | Identifies DotCode structured append mode barcodes count. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColumns() {#getColumns--}
```
public final int getColumns()
```


कॉलम की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Returns:**
int
### getDotCodeEncodeMode() {#getDotCodeEncodeMode--}
```
public final DotCodeEncodeMode getDotCodeEncodeMode()
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


DotCode संरचित एपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान: -1।

**Returns:**
int
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


DotCode संरचित एपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान: -1। संख्या 1 से 35 के बीच होनी चाहिए।

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto.

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


पंक्तियों की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode संरचित एपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान: -1।

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode संरचित एपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान: -1। संख्या 1 से 35 के बीच होनी चाहिए।

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

**Returns:**
boolean
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


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


कॉलम की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDotCodeEncodeMode(DotCodeEncodeMode value) {#setDotCodeEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setDotCodeEncodeMode(DotCodeEncodeMode value)
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setDotCodeStructuredAppendModeBarcodeId(int value) {#setDotCodeStructuredAppendModeBarcodeId-int-}
```
public final void setDotCodeStructuredAppendModeBarcodeId(int value)
```


DotCode संरचित एपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान: -1।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setDotCodeStructuredAppendModeBarcodesCount(int value) {#setDotCodeStructuredAppendModeBarcodesCount-int-}
```
public final void setDotCodeStructuredAppendModeBarcodesCount(int value)
```


DotCode संरचित एपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान: -1। संख्या 1 से 35 के बीच होनी चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: Auto.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


पंक्तियों की संख्या की पहचान करता है। एक DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode संरचित एपेंड मोड बारकोड का ID पहचानता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान: -1।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode संरचित एपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान: -1। संख्या 1 से 35 के बीच होनी चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters).

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) को दर्शाती है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

