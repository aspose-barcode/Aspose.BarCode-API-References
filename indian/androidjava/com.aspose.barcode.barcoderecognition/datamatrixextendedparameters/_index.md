---
title: DataMatrixExtendedParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Stores special data of DataMatrix recognized barcode
type: docs
weight: 31
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

Stores special data of DataMatrix recognized barcode

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
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming)_);
>  }
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataMatrixExtendedParameters मान के बराबर है या नहीं |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrix संरचित अपेंड मोड बारकोड का आईडी प्राप्त करता है |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | DataMatrix संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | DataMatrix संरचित अपेंड मोड बारकोड का आईडी प्राप्त करता है |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [isReaderProgramming()](#isReaderProgramming--) | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | पहले DataMatrixExtendedParameters मान के दूसरे के बराबर होने को दर्शाने वाला मान लौटाता है। |
| [op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-) | पहले DataMatrixExtendedParameters मान के दूसरे से अलग होने को दर्शाने वाला मान लौटाता है। |
| [toString()](#toString--) | इस DataMatrixExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट DataMatrixExtendedParameters मान के बराबर है या नहीं

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


DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड गिनती से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

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


DataMatrix संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड गिनती से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है।

मान: DataMatrix संरचित एपेंड मोड बारकोड का ID।

**Returns:**
int
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
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है।

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




### op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Equality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


पहले DataMatrixExtendedParameters मान के दूसरे के बराबर होने को दर्शाने वाला मान लौटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | पहला तुलना किया गया मान |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | दूसरा तुलना किया गया मान |

**Returns:**
boolean -  **true**  यदि पहला का मान दूसरे के समान है; अन्यथा,  **false** .
### op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-com.aspose.barcode.barcoderecognition.DataMatrixExtendedParameters-}
```
public static boolean op_Inequality(DataMatrixExtendedParameters first, DataMatrixExtendedParameters second)
```


पहले DataMatrixExtendedParameters मान के दूसरे से अलग होने को दर्शाने वाला मान लौटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| first | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | पहला तुलना किया गया मान |
| second | [DataMatrixExtendedParameters](../../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | दूसरा तुलना किया गया मान |

**Returns:**
boolean -  **true**  यदि पहला का मान दूसरे से अलग है; अन्यथा,  **false** .
### toString() {#toString--}
```
public String toString()
```


इस DataMatrixExtendedParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस DataMatrixExtendedParameters को दर्शाती है।
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

