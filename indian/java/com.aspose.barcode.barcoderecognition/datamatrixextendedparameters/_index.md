---
title: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है"
type: docs
weight: 29
url: /hi/java/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  DataMatrixExtendedParameters  मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | DataMatrix संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं। |
| [isReaderProgramming()](#isReaderProgramming--) | संकेत देता है कि कोड का उपयोग रीडर को निम्नलिखित डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस DataMatrixExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  DataMatrixExtendedParameters  मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
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


DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड गिनती के बराबर या कम होनी चाहिए। डिफ़ॉल्ट मान -1 है।

मान: DataMatrix संरचित एपेंड मोड बारकोड का ID।

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


DataMatrix संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच का मान होना चाहिए।

मान: DataMatrix संरचित एपेंड मोड बारकोड की गिनती।

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड गिनती के बराबर या कम होनी चाहिए। डिफ़ॉल्ट मान -1 है।

मान: DataMatrix संरचित एपेंड मोड बारकोड का ID।

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


जाँचता है कि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं या नहीं।

Value: यदि सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं तो **true** लौटाता है; अन्यथा, **false**।

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

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


इस DataMatrixExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस DataMatrixExtendedParameters का प्रतिनिधित्व करती है।
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

