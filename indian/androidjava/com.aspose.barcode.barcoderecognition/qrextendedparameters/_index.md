---
title: QRExtendedParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Stores a QR Structured Append information of recognized barcode
type: docs
weight: 42
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stores a QR Structured Append information of recognized barcode

यह नमूना दिखाता है कि QR Structured Append डेटा कैसे प्राप्त करें

```
{
```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। |
| [getMicroQRVersion()](#getMicroQRVersion--) | पहचाने गए MicroQR कोड का संस्करण। |
| [getQRErrorLevel()](#getQRErrorLevel--) | पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | QR structured append मोड बारकोड का सूचकांक प्राप्त करता है। |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | QR structured append मोड बारकोड की मात्रा प्राप्त करता है। |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। |
| [getQRVersion()](#getQRVersion--) | पहचाने गए QR कोड का संस्करण। |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | पहचाने गए RectMicroQR कोड का संस्करण। |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR structured append मोड बारकोड का सूचकांक प्राप्त करता है। |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR structured append मोड बारकोड की मात्रा प्राप्त करता है। |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) | पहचाने गए QR कोड का संस्करण। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | एक मान लौटाता है जो दर्शाता है कि पहला [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान दूसरे के बराबर है या नहीं। |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | एक मान लौटाता है जो दर्शाता है कि पहला [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान दूसरे से अलग है या नहीं। |
| [toString()](#toString--) | इस [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH।

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


पहचाने गए MicroQR कोड का संस्करण। M1 से M4 तक।

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। कम से उच्च: LevelL, LevelM, LevelQ, LevelH।

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


QR संरचित एपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड की मात्रा।

**Returns:**
int - QR संरचित एपेंड मोड बारकोड का सूचकांक।
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


QR संरचित एपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड की मात्रा।

**Returns:**
int - QR संरचित एपेंड मोड बारकोड की मात्रा।
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड का सूचकांक।

**Returns:**
int - QR संरचित एपेंड मोड पैरिटी डेटा।
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक।

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


पहचाने गए RectMicroQR कोड का संस्करण। R7x43 से R17x139 तक।

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


QR संरचित एपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड की मात्रा।

**Returns:**
int - QR संरचित एपेंड मोड बारकोड का सूचकांक।
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR संरचित एपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड की मात्रा।

**Returns:**
int - QR संरचित एपेंड मोड बारकोड की मात्रा।
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR संरचित एपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR संरचित एपेंड मोड बारकोड का सूचकांक।

**Returns:**
int - QR संरचित एपेंड मोड पैरिटी डेटा।
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक।

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं

मान: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो **true** लौटाता है; अन्यथा, **false** .

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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


एक मान लौटाता है जो दर्शाता है कि पहला [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान दूसरे के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | पहला तुलना किया गया मान |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | दूसरा तुलना किया गया मान |

**Returns:**
boolean -  **true**  यदि पहला का मान दूसरे के समान है; अन्यथा,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


एक मान लौटाता है जो दर्शाता है कि पहला [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) मान दूसरे से अलग है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | पहला तुलना किया गया मान |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | दूसरा तुलना किया गया मान |

**Returns:**
boolean -  **true**  यदि पहला का मान दूसरे से अलग है; अन्यथा,  **false** .
### toString() {#toString--}
```
public String toString()
```


इस [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) को दर्शाती है।
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

