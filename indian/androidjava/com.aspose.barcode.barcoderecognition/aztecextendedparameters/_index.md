---
title: "AztecExtendedParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है।"
type: docs
weight: 12
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/aztecextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class AztecExtendedParameters extends BaseExtendedParameters
```

Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है।

--------------------

> ```
> This sample shows how to get Aztec raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345");
>  generator.save("test.png");
> 
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.AZTEC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText());
>      System.out.println("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
>      System.out.println("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
>      System.out.println("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
>      System.out.println("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
>  }
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट AztecExtendedParameters मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | Aztec संरचित एपेंड मोड बारकोड की आईडी प्राप्त करता है। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | Aztec संरचित एपेंड मोड बारकोड की संख्या प्राप्त करता है। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | Aztec संरचित एपेंड मोड का फ़ाइल आईडी प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | परीक्षण करता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [isReaderInitialization()](#isReaderInitialization--) | संकेत देता है कि क्या कोड का उपयोग बारकोड रीडर को प्रारंभिककरण या पुनःप्रोग्रामिंग के लिए निम्न डेटा को निर्देशों के रूप में व्याख्या करने के लिए किया जाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस AztecExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट AztecExtendedParameters मान के बराबर है या नहीं।

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
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


Aztec संरचित एपेंड मोड बारकोड की आईडी प्राप्त करता है। आईडी 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान 0 है।

मान: Aztec संरचित एपेंड मोड का बारकोड आईडी।

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


Aztec संरचित एपेंड मोड बारकोड की संख्या प्राप्त करता है। डिफ़ॉल्ट मान 0 है। संख्या 1 से 26 के बीच होनी चाहिए।

मान: Aztec संरचित एपेंड मोड की बारकोड संख्या।

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public String getStructuredAppendFileId()
```


Aztec संरचित एपेंड मोड का फ़ाइल आईडी प्राप्त करता है। डिफ़ॉल्ट मान खाली स्ट्रिंग है।

मान: Aztec संरचित एपेंड मोड का फ़ाइल आईडी।

**Returns:**
java.lang.String
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
public boolean isReaderInitialization()
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


इस AztecExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस AztecExtendedParameters का प्रतिनिधित्व करती है।
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

