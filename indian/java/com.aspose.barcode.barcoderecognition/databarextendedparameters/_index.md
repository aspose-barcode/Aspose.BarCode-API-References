---
title: "DataBarExtendedParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है BarCodeReader reader  new BarCodeReaderctest.png DecodeType.DATABAR_OMNI_DIRECTIONAL forBarCodeResult result  reader.readBarCodes    System.out.printlnBarCode Type   result.getCodeTypeName    System.out.printlnBarCode CodeText   result.getCodeText    System.out.printlnQR Structured Append Quantity   result.getExtended.getQR.getQRStructuredAppendModeBarCodesQuantity"
type: docs
weight: 28
url: /hi/java/com.aspose.barcode.barcoderecognition/databarextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public class DataBarExtendedParameters extends BaseExtendedParameters
```

पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataBarExtendedParameters मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [is2DCompositeComponent()](#is2DCompositeComponent--) | DataBar 2D सम्मिलित घटक फ़्लैग प्राप्त करता है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस DataBarExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataBarExtendedParameters मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean - **true** यदि obj का मान इस इंस्टेंस के समान है; अन्यथा, **false**।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### is2DCompositeComponent() {#is2DCompositeComponent--}
```
public boolean is2DCompositeComponent()
```


DataBar 2D सम्मिलित घटक फ़्लैग प्राप्त करता है। डिफ़ॉल्ट मान false है।

**Returns:**
boolean - DataBar 2D सम्मिलित घटक फ़्लैग।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं।

Value: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो **true** लौटाता है; अन्यथा, **false**।

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


इस DataBarExtendedParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस DataBarExtendedParameters का प्रतिनिधित्व करती है।
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

