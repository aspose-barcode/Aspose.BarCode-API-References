---
title: "BaseDecodeType"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "MultiDecodeType और SingleDecodeType के लिए बेस क्लास।"
type: docs
weight: 22
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/basedecodetype/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDecodeType
```

MultiDecodeType और SingleDecodeType के लिए बेस क्लास।

--------------------

> ```
> This sample shows how to use BaseDecodeType with SingleDecodeType and MultiDecodeType
>  
>  BaseDecodeType decodeOne = DecodeType.CODE_128;
>  BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.CODE_128, DecodeType.CODE_39_STANDARD, DecodeType.CODE_39_FULL_ASCII);
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | निर्धारित करता है कि दिए गए डिकोड प्रकारों में से कोई भी शामिल है या नहीं |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [equals(Object other)](#equals-java.lang.Object-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


निर्धारित करता है कि दिए गए डिकोड प्रकारों में से कोई भी शामिल है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | सत्यापित करने के प्रकार। |

**Returns:**
boolean - यदि कोई प्रकार शामिल किया गया हो तो मान true है।
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो true; अन्यथा false।
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो true; अन्यथा false।
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| अन्य | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो true; अन्यथा false।
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




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है, ठोस प्रकार निर्धारित करने के बाद। एक रिटर्न मान दर्शाता है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें कनवर्ट करने के लिए MultiDecodeType का प्रतिनिधित्व हो। |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType ("None").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है। एक रिटर्न मान दर्शाता है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें कनवर्ट करने के लिए MultiDecodeType का प्रतिनिधित्व हो। |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType ("None").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में बदलता है। एक रिटर्न मान दर्शाता है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें "EAN8", "EAN13", "CodaBar"... जैसे स्वरूप में SingleDecodeType हो, जिसे कनवर्ट किया जाना है। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या SingleDecodeType (-1, "None").
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

