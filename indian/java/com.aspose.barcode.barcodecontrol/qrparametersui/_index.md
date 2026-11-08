---
title: "QrParametersUI"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "UI रैपर for com.aspose.barcode.generation.QrParameters क्लास."
type: docs
weight: 17
url: /hi/java/com.aspose.barcode.barcodecontrol/qrparametersui/
---
**Inheritance:**
java.lang.Object
```
public class QrParametersUI
```

UI रैपर for com.aspose.barcode.generation.QrParameters क्लास.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [getClass()](#getClass--) |  |
| [getECIEncoding()](#getECIEncoding--) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [getEncodeGS1SeparatorInByteMode()](#getEncodeGS1SeparatorInByteMode--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि QR और RectMicroQR बारकोड के लिए GS1 विशेष अक्षर बाइट मोड में एन्कोड किए जाने चाहिए या नहीं। |
| [getEncodeMode()](#getEncodeMode--) | BarCode के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। |
| [getErrorLevel()](#getErrorLevel--) | QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। |
| [getMicroQrVersion()](#getMicroQrVersion--) | MicroQR कोड का संस्करण। |
| [getRectMicroQrVersion()](#getRectMicroQrVersion--) | RectMicroQR कोड का संस्करण। |
| [getVersion()](#getVersion--) | QR कोड का संस्करण। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAspectRatio(float value)](#setAspectRatio-float-) | 2D बारकोड मॉड्यूल का ऊँचाई/चौड़ाई अनुपात। |
| [setECIEncoding(int value)](#setECIEncoding-int-) | विस्तारित चैनल इंटरप्रिटेशन पहचानकर्ता। |
| [setEncodeGS1SeparatorInByteMode(boolean value)](#setEncodeGS1SeparatorInByteMode-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि QR और RectMicroQR बारकोड के लिए GS1 विशेष अक्षर बाइट मोड में एन्कोड किए जाने चाहिए या नहीं। |
| [setEncodeMode(QREncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-) | BarCode के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। |
| [setErrorLevel(QRErrorLevel value)](#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-) | QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार स्तर। |
| [setMicroQrVersion(MicroQRVersion value)](#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-) | MicroQR कोड का संस्करण। |
| [setRectMicroQrVersion(RectMicroQRVersion value)](#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-) | RectMicroQR कोड का संस्करण। |
| [setVersion(QRVersion value)](#setVersion-com.aspose.barcode.generation.QRVersion-) | QR कोड का संस्करण। |
| [toString()](#toString--) | इस [QrParameters](../../com.aspose.barcode.generation/qrparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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
public int getECIEncoding()
```


Extended Channel Interpretation Identifiers। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए रेफ़रेंस के विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं है।

**Returns:**
int
### getEncodeGS1SeparatorInByteMode() {#getEncodeGS1SeparatorInByteMode--}
```
public boolean getEncodeGS1SeparatorInByteMode()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि QR और RectMicroQR बारकोड के लिए GS1 विशेष अक्षर बाइट मोड में एन्कोड किए जाने चाहिए या नहीं।

यदि false है, तो QR विनिर्देश के अनुसार GS1 विभाजक अल्फ़ान्यूमेरिक मोड में '%' के रूप में एन्कोड किए जा सकते हैं।

यदि true है, तो GS1 समूह विभाजक बाइट मोड में 0x1D अक्षर के रूप में एन्कोड होते हैं, और '%' अक्षर भी बाइट मोड में डेटा के रूप में संरक्षित करने के लिए एन्कोड होते हैं।

यह विकल्प उन डिकोडरों के साथ संगतता को सुधार सकता है जो बाइट-स्तर GS1 समूह विभाजकों की अपेक्षा करते हैं और '%' डेटा अक्षरों को GS1 विभाजकों के रूप में व्याख्या होने से रोकता है।

**Returns:**
boolean
### getEncodeMode() {#getEncodeMode--}
```
public final QREncodeMode getEncodeMode()
```


BarCode के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto।

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel।

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQrVersion() {#getMicroQrVersion--}
```
public final MicroQRVersion getMicroQrVersion()
```


MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है MicroQRVersion.Auto।

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getRectMicroQrVersion() {#getRectMicroQrVersion--}
```
public final RectMicroQRVersion getRectMicroQrVersion()
```


RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है RectMicroQRVersion.Auto।

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान है QRVersion.Auto।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setECIEncoding(int value) {#setECIEncoding-int-}
```
public void setECIEncoding(int value)
```


Extended Channel Interpretation Identifiers। यह बारकोड रीडर को प्रतीक में डेटा एन्कोड करने के लिए उपयोग किए गए रेफ़रेंस के विवरण बताने के लिए उपयोग किया जाता है। वर्तमान कार्यान्वयन सभी ज्ञात कैरेक्टरसेट एन्कोडिंग्स को शामिल करता है। MicroQR द्वारा समर्थित नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setEncodeGS1SeparatorInByteMode(boolean value) {#setEncodeGS1SeparatorInByteMode-boolean-}
```
public void setEncodeGS1SeparatorInByteMode(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि QR और RectMicroQR बारकोड के लिए GS1 विशेष अक्षर बाइट मोड में एन्कोड किए जाने चाहिए या नहीं।

यदि false है, तो QR विनिर्देश के अनुसार GS1 विभाजक अल्फ़ान्यूमेरिक मोड में '%' के रूप में एन्कोड किए जा सकते हैं।

यदि true है, तो GS1 समूह विभाजक बाइट मोड में 0x1D अक्षर के रूप में एन्कोड होते हैं, और '%' अक्षर भी बाइट मोड में डेटा के रूप में संरक्षित करने के लिए एन्कोड होते हैं।

यह विकल्प उन डिकोडरों के साथ संगतता को सुधार सकता है जो बाइट-स्तर GS1 समूह विभाजकों की अपेक्षा करते हैं और '%' डेटा अक्षरों को GS1 विभाजकों के रूप में व्याख्या होने से रोकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setEncodeMode(QREncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.QREncodeMode-}
```
public final void setEncodeMode(QREncodeMode value)
```


BarCode के एन्कोडिंग मोड का QR सिम्बोलॉजी प्रकार। डिफ़ॉल्ट मान: QREncodeMode.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [QREncodeMode](../../com.aspose.barcode.generation/qrencodemode) |  |

### setErrorLevel(QRErrorLevel value) {#setErrorLevel-com.aspose.barcode.generation.QRErrorLevel-}
```
public final void setErrorLevel(QRErrorLevel value)
```


QR, MicroQR और RectMicroQR बारकोड के लिए Reed-Solomon त्रुटि सुधार का स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH। देखें QRErrorLevel।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel) |  |

### setMicroQrVersion(MicroQRVersion value) {#setMicroQrVersion-com.aspose.barcode.generation.MicroQRVersion-}
```
public final void setMicroQrVersion(MicroQRVersion value)
```


MicroQR कोड का संस्करण। संस्करण M1 से संस्करण M4 तक। डिफ़ॉल्ट मान है MicroQRVersion.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [MicroQRVersion](../../com.aspose.barcode.generation/microqrversion) |  |

### setRectMicroQrVersion(RectMicroQRVersion value) {#setRectMicroQrVersion-com.aspose.barcode.generation.RectMicroQRVersion-}
```
public final void setRectMicroQrVersion(RectMicroQRVersion value)
```


RectMicroQR कोड का संस्करण। संस्करण R7x59 से संस्करण R17x139 तक। डिफ़ॉल्ट मान है RectMicroQRVersion.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion) |  |

### setVersion(QRVersion value) {#setVersion-com.aspose.barcode.generation.QRVersion-}
```
public final void setVersion(QRVersion value)
```


QR कोड का संस्करण। QR कोड के लिए Version1 से Version40 तक और MicroQr के लिए M1 से M4 तक। डिफ़ॉल्ट मान है QRVersion.Auto।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

