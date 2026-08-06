---
title: HanXinParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Han Xin पैरामीटर।
type: docs
weight: 50
url: /hi/androidjava/com.aspose.barcode.generation/hanxinparameters/
---
**Inheritance:**
java.lang.Object
```
public class HanXinParameters
```

Han Xin पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getEncodeMode()](#getEncodeMode--) | HanXin एन्कोडिंग मोड। |
| [getErrorLevel()](#getErrorLevel--) | Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। |
| [getHanXinECIEncoding()](#getHanXinECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getHanXinEncodeMode()](#getHanXinEncodeMode--) | HanXin एन्कोडिंग मोड। |
| [getHanXinErrorLevel()](#getHanXinErrorLevel--) | Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। |
| [getHanXinVersion()](#getHanXinVersion--) | HanXin कोड का संस्करण। |
| [getVersion()](#getVersion--) | HanXin कोड का संस्करण। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setEncodeMode(HanXinEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-) | HanXin एन्कोडिंग मोड। |
| [setErrorLevel(HanXinErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-) | Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। |
| [setVersion(HanXinVersion value)](#setVersion-com.aspose.barcode.generation.HanXinVersion-) | HanXin कोड का संस्करण। |
| [toString()](#toString--) | इसका मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)। |
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


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा को एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं। वर्तमान कार्यान्वयन में सभी ज्ञात कैरेक्टरसेट एन्कोडिंग शामिल हैं।

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final HanXinEncodeMode getEncodeMode()
```


HanXin एन्कोडिंग मोड। डिफ़ॉल्ट मान: EncodeMode.Mixed।

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final HanXinErrorLevel getErrorLevel()
```


Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: L1, L2, L3, L4। देखें ErrorLevel।

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinECIEncoding() {#getHanXinECIEncoding--}
```
public final int getHanXinECIEncoding()
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा को एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं। वर्तमान कार्यान्वयन में सभी ज्ञात कैरेक्टरसेट एन्कोडिंग शामिल हैं।

**Returns:**
int
### getHanXinEncodeMode() {#getHanXinEncodeMode--}
```
public final HanXinEncodeMode getHanXinEncodeMode()
```


HanXin एन्कोडिंग मोड। डिफ़ॉल्ट मान: EncodeMode.Mixed।

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### getHanXinErrorLevel() {#getHanXinErrorLevel--}
```
public final HanXinErrorLevel getHanXinErrorLevel()
```


Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: L1, L2, L3, L4। देखें ErrorLevel।

**Returns:**
[HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel)
### getHanXinVersion() {#getHanXinVersion--}
```
public final HanXinVersion getHanXinVersion()
```


HanXin कोड का संस्करण। Han Xin कोड के लिए Version01 से Version84 तक। डिफ़ॉल्ट मान है Version.Auto।

**Returns:**
[HanXinVersion](../../com.aspose.barcode.generation/hanxinversion)
### getVersion() {#getVersion--}
```
public final HanXinVersion getVersion()
```


HanXin कोड का संस्करण। Han Xin कोड के लिए Version01 से Version84 तक। डिफ़ॉल्ट मान है Version.Auto।

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


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा को एन्कोड करने के लिए कौन से संदर्भ उपयोग किए गए हैं। वर्तमान कार्यान्वयन में सभी ज्ञात कैरेक्टरसेट एन्कोडिंग शामिल हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(HanXinEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.HanXinEncodeMode-}
```
public final void setEncodeMode(HanXinEncodeMode value)
```


HanXin एन्कोडिंग मोड। डिफ़ॉल्ट मान: EncodeMode.Mixed।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode) |  |

### setErrorLevel(HanXinErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.HanXinErrorLevel-}
```
public final void setErrorLevel(HanXinErrorLevel value)
```


Han Xin बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: L1, L2, L3, L4। देखें ErrorLevel।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [HanXinErrorLevel](../../com.aspose.barcode.generation/hanxinerrorlevel) |  |

### setVersion(HanXinVersion value) {#setVersion-com.aspose.barcode.generation.HanXinVersion-}
```
public final void setVersion(HanXinVersion value)
```


HanXin कोड का संस्करण। Han Xin कोड के लिए Version01 से Version84 तक। डिफ़ॉल्ट मान है Version.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [HanXinVersion](../../com.aspose.barcode.generation/hanxinversion) |  |

### toString() {#toString--}
```
public String toString()
```


इसका मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters) को दर्शाती है।
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

