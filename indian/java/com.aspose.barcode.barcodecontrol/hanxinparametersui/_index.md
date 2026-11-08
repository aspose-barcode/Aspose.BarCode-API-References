---
title: "HanXinParametersUI"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 15
url: /hi/java/com.aspose.barcode.barcodecontrol/hanxinparametersui/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParametersUI
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getEncodeMode()](#getEncodeMode--) | BarCode के एन्कोडिंग मोड का HanXin प्रतीक प्रकार। |
| [getErrorLevel()](#getErrorLevel--) | HanXin बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। |
| [getVersion()](#getVersion--) | HanXin कोड का संस्करण। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | BarCode के एन्कोडिंग मोड का HanXin प्रतीक प्रकार। |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | HanXin बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin कोड का संस्करण। |
| [toString()](#toString--) | इस [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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


विस्तारित चैनल व्याख्या पहचानकर्ता। यह बारकोड रीडर को डेटा को प्रतीक में एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टर सेट एन्कोडिंग्स को सम्मिलित करता है।

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


BarCode के एन्कोडिंग मोड का HanXin प्रतीक प्रकार। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


HanXin बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: L1 - L4। देखें ErrorLevel।

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin कोड का संस्करण। HanXin कोड के लिए Version01 से Version84 तक। डिफ़ॉल्ट मान Version.Auto है।

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




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


विस्तारित चैनल व्याख्या पहचानकर्ता। यह बारकोड रीडर को डेटा को प्रतीक में एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टर सेट एन्कोडिंग्स को सम्मिलित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


BarCode के एन्कोडिंग मोड का HanXin प्रतीक प्रकार। डिफ़ॉल्ट मान: EncodeMode.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


HanXin बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: L1 - L4। देखें ErrorLevel।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin कोड का संस्करण। HanXin कोड के लिए Version01 से Version84 तक। डिफ़ॉल्ट मान Version.Auto है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


इस [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) का प्रतिनिधित्व करती है।
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

