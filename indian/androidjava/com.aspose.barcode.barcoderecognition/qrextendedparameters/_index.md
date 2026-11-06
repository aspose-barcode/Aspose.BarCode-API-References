---
title: "QRExtendedParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है"
type: docs
weight: 40
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है

यह उदाहरण दिखाता है कि QR Structured Append डेटा कैसे प्राप्त करें

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
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | पहचाने गए RectMicroQR कोड का संस्करण। |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | QR structured append मोड बारकोड का सूचकांक प्राप्त करता है। |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | QR structured append मोड बारकोड की मात्रा प्राप्त करता है। |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | QR structured append मोड पैरिटी डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) | पहचाने गए QR कोड का संस्करण। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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


QR structured append मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है।

मान: QR structured append मोड बारकोड की मात्रा।

**Returns:**
int - QR structured append मोड बारकोड का सूचकांक।
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


QR structured append मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR structured append मोड बारकोड की मात्रा।

**Returns:**
int - QR structured append मोड बारकोड की मात्रा।
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


QR structured append मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है।

मान: QR structured append मोड बारकोड का सूचकांक।

**Returns:**
int - QR structured append मोड पैरिटी डेटा।
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
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं।

मान: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो  **true**  लौटाता है; अन्यथा,  **false** .

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




### toString() {#toString--}
```
public String toString()
```


इस [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

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

