---
title: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "पहचाने गए DotCode बारकोड का विशेष डेटा संग्रहीत करता है"
type: docs
weight: 31
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

पहचाने गए DotCode बारकोड का विशेष डेटा संग्रहीत करता है

यह उदाहरण दिखाता है कि DotCode कच्चे मान कैसे प्राप्त करें।

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [isReaderInitialization()](#isReaderInitialization--) | संकेत देता है कि क्या कोड का उपयोग बारकोड रीडर को प्रारंभिककरण या पुनःप्रोग्रामिंग के लिए निम्न डेटा को निर्देशों के रूप में व्याख्या करने के लिए किया जाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) मान के बराबर है या नहीं।

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
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


DotCode संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड गिनती से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

मान: DotCode संरचित एपेंड मोड बारकोड का ID।

**Returns:**
int - DotCode संरचित एपेंड मोड बारकोड का ID।
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


DotCode संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए।

मान: DotCode संरचित एपेंड मोड बारकोड की गिनती।

**Returns:**
int - DotCode संरचित एपेंड मोड बारकोड की गिनती।
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


संकेत देता है कि क्या कोड का उपयोग बारकोड रीडर को प्रारंभिककरण या पुनःप्रोग्रामिंग के लिए निम्न डेटा को निर्देशों के रूप में व्याख्या करने के लिए किया जाता है। डिफ़ॉल्ट मान false है।

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


इस [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) का प्रतिनिधित्व करती है।
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

