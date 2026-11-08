---
title: "DotCodeParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "DotCode पैरामीटर।"
type: docs
weight: 34
url: /hi/java/com.aspose.barcode.generation/dotcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class DotCodeParameters
```

DotCode पैरामीटर।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getColumns()](#getColumns--) | कॉलम की संख्या की पहचान करता है। |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग की पहचान करता है। |
| [getEncodeMode()](#getEncodeMode--) | DotCode एन्कोड मोड की पहचान करता है। |
| [getRows()](#getRows--) | पंक्तियों की संख्या की पहचान करता है। |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की ID की पहचान करता है। |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | संकेत देता है कि कोड का उपयोग रीडर को निम्नलिखित डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setColumns(int value)](#setColumns-int-) | कॉलम की संख्या की पहचान करता है। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग की पहचान करता है। |
| [setEncodeMode(DotCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-) | DotCode एन्कोड मोड की पहचान करता है। |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | संकेत देता है कि कोड का उपयोग रीडर को निम्नलिखित डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [setRows(int value)](#setRows-int-) | पंक्तियों की संख्या की पहचान करता है। |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की ID की पहचान करता है। |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। |
| [toString()](#toString--) | इस [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


कॉलम की संख्या की पहचान करता है। DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Returns:**
int
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final DotCodeEncodeMode getEncodeMode()
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: ऑटो।

**Returns:**
[DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode)
### getRows() {#getRows--}
```
public final int getRows()
```


पंक्तियों की संख्या की पहचान करता है। DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Returns:**
int
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की ID की पहचान करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

**Returns:**
int
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान -1 है। संख्या 1 से 35 के बीच होनी चाहिए।

**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setColumns(int value) {#setColumns-int-}
```
public final void setColumns(int value)
```


कॉलम की संख्या की पहचान करता है। DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। कॉलम की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग की पहचान करता है। जब DotCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(DotCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.DotCodeEncodeMode-}
```
public final void setEncodeMode(DotCodeEncodeMode value)
```


DotCode एन्कोड मोड की पहचान करता है। डिफ़ॉल्ट मान: ऑटो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DotCodeEncodeMode](../../com.aspose.barcode.generation/dotcodeencodemode) |  |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRows(int value) {#setRows-int-}
```
public final void setRows(int value)
```


पंक्तियों की संख्या की पहचान करता है। DotCode प्रतीक की पंक्तियों की संख्या प्लस कॉलम की संख्या का योग विषम होना चाहिए। पंक्तियों की संख्या कम से कम 5 होनी चाहिए। डिफ़ॉल्ट मान: -1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की ID की पहचान करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


DotCode स्ट्रक्चर्ड अपेंड मोड बारकोड की संख्या की पहचान करता है। डिफ़ॉल्ट मान -1 है। संख्या 1 से 35 के बीच होनी चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


इस [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters) का प्रतिनिधित्व करती है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

