---
title: "AztecParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "अज़्टेक पैरामीटर."
type: docs
weight: 12
url: /hi/java/com.aspose.barcode.generation/aztecparameters/
---
**Inheritance:**
java.lang.Object
```
public class AztecParameters
```

अज़्टेक पैरामीटर.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | ECI एन्कोडिंग प्राप्त करता है। |
| [getEncodeMode()](#getEncodeMode--) | एक Aztec एन्कोड मोड प्राप्त करता है। |
| [getErrorLevel()](#getErrorLevel--) | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। |
| [getLayersCount()](#getLayersCount--) | Aztec प्रतीक की परतों की संख्या प्राप्त करता है। |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec बारकोड के Structured Append मोड के लिए बारकोड ID। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec बारकोड के Structured Append मोड के लिए फ़ाइल ID (वैकल्पिक फ़ील्ड)। |
| [getSymbolMode()](#getSymbolMode--) | एक Aztec Symbol मोड प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isReaderInitialization()](#isReaderInitialization--) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI एन्कोडिंग सेट करता है। |
| [setEncodeMode(AztecEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-) | एक Aztec एन्कोड मोड सेट करता है। |
| [setErrorLevel(int value)](#setErrorLevel-int-) | Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। |
| [setLayersCount(int value)](#setLayersCount-int-) | Aztec प्रतीक की परतों की संख्या सेट करता है। |
| [setReaderInitialization(boolean value)](#setReaderInitialization-boolean-) | रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे। |
| [setStructuredAppendBarcodeId(int value)](#setStructuredAppendBarcodeId-int-) | Aztec बारकोड के Structured Append मोड के लिए बारकोड ID। |
| [setStructuredAppendBarcodesCount(int value)](#setStructuredAppendBarcodesCount-int-) | Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। |
| [setStructuredAppendFileId(String value)](#setStructuredAppendFileId-java.lang.String-) | Aztec बारकोड के Structured Append मोड के लिए फ़ाइल ID (वैकल्पिक फ़ील्ड)। |
| [setSymbolMode(AztecSymbolMode value)](#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-) | एक Aztec Symbol मोड सेट करता है। |
| [toString()](#toString--) | इस [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI एन्कोडिंग प्राप्त करता है। जब AztecEncodeMode Auto हो तब उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Returns:**
int - ECI एन्कोडिंग।
### getEncodeMode() {#getEncodeMode--}
```
public final AztecEncodeMode getEncodeMode()
```


Aztec एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: Auto.

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode - एक Aztec एन्कोड मोड।
### getErrorLevel() {#getErrorLevel--}
```
public final int getErrorLevel()
```


Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

**Returns:**
int
### getLayersCount() {#getLayersCount--}
```
public final int getLayersCount()
```


Aztec प्रतीक की परतों की संख्या प्राप्त करता है। कॉम्पैक्ट मोड के लिए परतों की संख्या 1 से 3 के बीच और फुल रेंज मोड के लिए 1 से 32 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 (auto)।

**Returns:**
int - Aztec प्रतीक की परतों की संख्या।
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public final int getStructuredAppendBarcodeId()
```


Aztec बारकोड के Structured Append मोड के लिए बारकोड ID। बारकोड ID 1 से बारकोड की कुल संख्या के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public final int getStructuredAppendBarcodesCount()
```


Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public final String getStructuredAppendFileId()
```


Aztec बारकोड के Structured Append मोड के लिए फ़ाइल ID (वैकल्पिक फ़ील्ड)। फ़ाइल ID में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग

**Returns:**
java.lang.String
### getSymbolMode() {#getSymbolMode--}
```
public final AztecSymbolMode getSymbolMode()
```


Aztec Symbol मोड प्राप्त करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

**Returns:**
[AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) - a Aztec Symbol mode.
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


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

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

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI एन्कोडिंग सेट करता है। जब AztecEncodeMode Auto हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | ECI एन्कोडिंग। |

### setEncodeMode(AztecEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.AztecEncodeMode-}
```
public final void setEncodeMode(AztecEncodeMode value)
```


Aztec एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.barcode.generation.AztecEncodeMode | एक Aztec एन्कोड मोड। |

### setErrorLevel(int value) {#setErrorLevel-int-}
```
public final void setErrorLevel(int value)
```


Aztec प्रकार के बारकोड की त्रुटि सुधार स्तर। मान 5 से 95 के बीच होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLayersCount(int value) {#setLayersCount-int-}
```
public final void setLayersCount(int value)
```


Aztec प्रतीक की परतों की संख्या सेट करता है। कॉम्पैक्ट मोड के लिए परतों की संख्या 1 से 3 के बीच और फुल रेंज मोड के लिए 1 से 32 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0 (auto)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | Aztec प्रतीक की परतों की संख्या। |

### setReaderInitialization(boolean value) {#setReaderInitialization-boolean-}
```
public final void setReaderInitialization(boolean value)
```


रीडर को यह निर्देश देने के लिए उपयोग किया जाता है कि वह प्रतीक के भीतर मौजूद डेटा को रीडर इनिशियलाइज़ेशन के लिए प्रोग्रामिंग के रूप में व्याख्या करे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStructuredAppendBarcodeId(int value) {#setStructuredAppendBarcodeId-int-}
```
public final void setStructuredAppendBarcodeId(int value)
```


Aztec बारकोड के Structured Append मोड के लिए बारकोड ID। बारकोड ID 1 से बारकोड की कुल संख्या के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendBarcodesCount(int value) {#setStructuredAppendBarcodesCount-int-}
```
public final void setStructuredAppendBarcodesCount(int value)
```


Aztec बारकोड के Structured Append मोड के लिए बारकोड की संख्या। बारकोड की संख्या 1 से 26 के बीच होनी चाहिए। डिफ़ॉल्ट मान: 0

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStructuredAppendFileId(String value) {#setStructuredAppendFileId-java.lang.String-}
```
public final void setStructuredAppendFileId(String value)
```


Aztec बारकोड के Structured Append मोड के लिए फ़ाइल ID (वैकल्पिक फ़ील्ड)। फ़ाइल ID में स्पेस नहीं होना चाहिए। डिफ़ॉल्ट मान: खाली स्ट्रिंग

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSymbolMode(AztecSymbolMode value) {#setSymbolMode-com.aspose.barcode.generation.AztecSymbolMode-}
```
public final void setSymbolMode(AztecSymbolMode value)
```


Aztec Symbol मोड सेट करता है। डिफ़ॉल्ट मान: AztecSymbolMode.Auto.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [AztecSymbolMode](../../com.aspose.barcode.generation/aztecsymbolmode) | एक Aztec Symbol मोड। |

### toString() {#toString--}
```
public String toString()
```


इस [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [AztecParameters](../../com.aspose.barcode.generation/aztecparameters) को दर्शाती है।
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

