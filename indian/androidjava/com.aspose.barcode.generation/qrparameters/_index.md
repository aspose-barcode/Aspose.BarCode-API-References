---
title: QrParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: QR पैरामीटर।
type: docs
weight: 64
url: /hi/androidjava/com.aspose.barcode.generation/qrparameters/
---
**Inheritance:**
java.lang.Object
```
public class QrParameters
```

QR पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getEncodeMode()](#getEncodeMode--) | बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। |
| [getErrorLevel()](#getErrorLevel--) | QR, माइक्रोQR और रेक्टमाइक्रोQR बारकोड के लिए रीड़-सोमन त्रुटि सुधार का स्तर। |
| [getMicroQRVersion()](#getMicroQRVersion--) | MicroQR कोड का संस्करण। |
| [getQrECIEncoding()](#getQrECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getQrEncodeMode()](#getQrEncodeMode--) | बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। |
| [getQrEncodeType()](#getQrEncodeType--) | QR / MicroQR चयनकर्ता मोड। |
| [getQrErrorLevel()](#getQrErrorLevel--) | QR, माइक्रोQR और रेक्टमाइक्रोQR बारकोड के लिए रीड़-सोमन त्रुटि सुधार का स्तर। |
| [getQrVersion()](#getQrVersion--) | QR कोड का संस्करण। संस्करण1 से संस्करण40 तक। |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR कोड का संस्करण। |
| [getStructuredAppend()](#getStructuredAppend--) | QR संरचित एपेंड पैरामीटर। |
| [getVersion()](#getVersion--) | QR कोड का संस्करण। संस्करण1 से संस्करण40 तक। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, माइक्रोQR और रेक्टमाइक्रोQR बारकोड के लिए रीड़-सोमन त्रुटि सुधार का स्तर। |
| [setMicroQRVersion(MicroQRVersion value)](#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR कोड का संस्करण। |
| [setQrEncodeType(QREncodeType value)](#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-) | QR / MicroQR चयनकर्ता मोड। |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR कोड का संस्करण। |
| [setStructuredAppend(QrStructuredAppendParameters value)](#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-) | QR संरचित एपेंड पैरामीटर। |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR कोड का संस्करण। संस्करण1 से संस्करण40 तक। |
| [toString()](#toString--) | इस [QrParameters](../../com.aspose.barcode.generation/qrparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। माइक्रोQR द्वारा समर्थित नहीं है।

**Returns:**
int
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto।

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel।

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है MicroQRVersion.Auto।

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQrECIEncoding() {#getQrECIEncoding--}
```
public final int getQrECIEncoding()
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। माइक्रोQR द्वारा समर्थित नहीं है।

**Returns:**
int
### getQrEncodeMode() {#getQrEncodeMode--}
```
public final QREncodeMode getQrEncodeMode()
```


बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto।

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getQrEncodeType() {#getQrEncodeType--}
```
public final QREncodeType getQrEncodeType()
```


QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto।

**Returns:**
[QREncodeType](../../com.aspose.barcode.generation/qrencodetype)
### getQrErrorLevel() {#getQrErrorLevel--}
```
public final QRErrorLevel getQrErrorLevel()
```


QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel।

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQrVersion() {#getQrVersion--}
```
public final QRVersion getQrVersion()
```


QR कोड का संस्करण। संस्करण Version1 से Version40 तक। डिफ़ॉल्ट मान है QRVersion.Auto।

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है RectMicroQRVersion.Auto।

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppend() {#getStructuredAppend--}
```
public final QrStructuredAppendParameters getStructuredAppend()
```


QR संरचित जोड़ पैरामीटर। संरचित जोड़ मोड MicroQR और RectMicroQR बारकोड द्वारा समर्थित नहीं है।

**Returns:**
[QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR कोड का संस्करण। संस्करण Version1 से Version40 तक। डिफ़ॉल्ट मान है QRVersion.Auto।

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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


2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। यह बारकोड रीडर को यह बताने के लिए उपयोग किया जाता है कि प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए संदर्भों के बारे में विवरण। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। माइक्रोQR द्वारा समर्थित नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


बारकोड के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQRVersion(MicroQRVersion value) {#setMicroQRVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQRVersion(MicroQRVersion value)
```


MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है MicroQRVersion.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setQrEncodeType(QREncodeType value) {#setQrEncodeType-com.aspose.barcode.generation.QREncodeType-}
```
public final void setQrEncodeType(QREncodeType value)
```


QR / MicroQR चयनकर्ता मोड। मानक QR प्रतीकों के लिए ForceQR चुनें, MicroQR के लिए Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QREncodeType](../../com.aspose.barcode.generation/qrencodetype) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है RectMicroQRVersion.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setStructuredAppend(QrStructuredAppendParameters value) {#setStructuredAppend-com.aspose.barcode.generation.QrStructuredAppendParameters-}
```
public final void setStructuredAppend(QrStructuredAppendParameters value)
```


QR संरचित जोड़ पैरामीटर। संरचित जोड़ मोड MicroQR और RectMicroQR बारकोड द्वारा समर्थित नहीं है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QrStructuredAppendParameters](../../com.aspose.barcode.generation/qrstructuredappendparameters) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR कोड का संस्करण। संस्करण Version1 से Version40 तक। डिफ़ॉल्ट मान है QRVersion.Auto।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [QRVersion](../../com.aspose.barcode.generation/qrversion) |  |

### toString() {#toString--}
```
public String toString()
```


इस [QrParameters](../../com.aspose.barcode.generation/qrparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [QrParameters](../../com.aspose.barcode.generation/qrparameters) को दर्शाती है।
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

