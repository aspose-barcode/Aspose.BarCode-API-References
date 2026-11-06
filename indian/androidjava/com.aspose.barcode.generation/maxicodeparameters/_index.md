---
title: "MaxiCodeParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "MaxiCode पैरामीटर।"
type: docs
weight: 55
url: /hi/androidjava/com.aspose.barcode.generation/maxicodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class MaxiCodeParameters
```

MaxiCode पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग प्राप्त करता है। |
| [getEncodeMode()](#getEncodeMode--) | एक MaxiCode एन्कोड मोड प्राप्त करता है। |
| [getMode()](#getMode--) | एक MaxiCode एन्कोड मोड प्राप्त करता है। |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | संरचित अपेंड मोड में एक MaxiCode बारकोड आईडी प्राप्त करता है। |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | संरचित अपेंड मोड में MaxiCode बारकोड की संख्या प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग सेट करता है। |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode एन्कोड मोड सेट करता है। |
| [setMode(MaxiCodeMode value)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | MaxiCode एन्कोड मोड सेट करता है। |
| [setStructuredAppendModeBarcodeId(int value)](#setStructuredAppendModeBarcodeId-int-) | संरचित एपेंड मोड में एक MaxiCode बारकोड आईडी सेट करता है। |
| [setStructuredAppendModeBarcodesCount(int value)](#setStructuredAppendModeBarcodesCount-int-) | संरचित एपेंड मोड में MaxiCode बारकोड की गिनती सेट करता है। |
| [toString()](#toString--) | इस [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Returns:**
int - ECI एन्कोडिंग।
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: ऑटो।

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public final MaxiCodeMode getMode()
```


एक MaxiCode एन्कोड मोड प्राप्त करता है।

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - a MaxiCode encode mode.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


संरचित एपेंड मोड में MaxiCode बारकोड आईडी प्राप्त करता है। आईडी 1 से 8 के बीच का मान होना चाहिए। डिफ़ॉल्ट मान: 0

**Returns:**
int - संरचित अपेंड मोड में एक MaxiCode बारकोड आईडी।
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


संरचित एपेंड मोड में MaxiCode बारकोड की गिनती प्राप्त करता है। गिनती संख्या 2 से 8 के बीच का मान होना चाहिए (अधिकतम बारकोड गिनती)। डिफ़ॉल्ट मान: -1

**Returns:**
int - संरचित अपेंड मोड में MaxiCode बारकोड की संख्या।
### hashCode() {#hashCode--}
```
public final int hashCode()
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


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | ECI एन्कोडिंग। |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | एक MaxiCode एन्कोड मोड। |

### setMode(MaxiCodeMode value) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public final void setMode(MaxiCodeMode value)
```


MaxiCode एन्कोड मोड सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) | एक MaxiCode एन्कोड मोड। |

### setStructuredAppendModeBarcodeId(int value) {#setStructuredAppendModeBarcodeId-int-}
```
public final void setStructuredAppendModeBarcodeId(int value)
```


संरचित एपेंड मोड में MaxiCode बारकोड आईडी सेट करता है। आईडी 1 से 8 के बीच का मान होना चाहिए। डिफ़ॉल्ट मान: 0

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | संरचित एपेंड मोड में एक MaxiCode बारकोड आईडी। |

### setStructuredAppendModeBarcodesCount(int value) {#setStructuredAppendModeBarcodesCount-int-}
```
public final void setStructuredAppendModeBarcodesCount(int value)
```


संरचित एपेंड मोड में MaxiCode बारकोड की गिनती सेट करता है। गिनती संख्या 2 से 8 के बीच का मान होना चाहिए (अधिकतम बारकोड गिनती)। डिफ़ॉल्ट मान: -1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int | संरचित एपेंड मोड में MaxiCode बारकोड की गिनती। |

### toString() {#toString--}
```
public String toString()
```


इस [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters) का प्रतिनिधित्व करती है।
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
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

