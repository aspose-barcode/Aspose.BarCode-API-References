---
title: "SingleDecodeType"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "एकल डिकोड प्रकार।"
type: docs
weight: 46
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

सिंगल डिकोड टाइप। इंस्टेंस प्राप्त करने के लिए डिकोड टाइप देखें।

--------------------

> ```
> This sample shows how to get instance of single decode type.
>  
>  SingleDecodeType singleType = DecodeType.QR
> ```
## Methods

| Method | विवरण |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट सूची में शामिल है या नहीं। |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | SingleDecodeType के उदाहरण को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित प्रारूप का उपयोग करके: "Index:-1; Name:None"। |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | SingleDecodeType के उदाहरण को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित प्रारूप का उपयोग करके: "Index:-1; Name:None"। |
| [getTypeIndex()](#getTypeIndex--) | डिकोड टाइप का इंडेक्स प्राप्त करता है। |
| [getTypeName()](#getTypeName--) | डिकोड टाइप का नाम प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | SingleDecodeType के नाम की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [toString()](#toString--) | ओवरराइड किया गया मेथड जो SingleDecodeType को नाम स्ट्रिंग के रूप में दर्शाता है। |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट सूची में शामिल है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | एकल और मल्टी डिकोड प्रकारों की सरणी |

**Returns:**
boolean - यदि कोई प्रकार शामिल किया गया हो तो मान true है
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो true; अन्यथा false।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getString() {#getString--}
```
public String getString()
```


SingleDecodeType के उदाहरण को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित प्रारूप का उपयोग करके: "Index:-1; Name:None"।

**Returns:**
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के पूर्ण मान को दर्शाती है
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


SingleDecodeType के उदाहरण को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित प्रारूप का उपयोग करके: "Index:-1; Name:None"।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | कनवर्ट करने के लिए SingleDecodeType इंस्टेंस |

**Returns:**
java.lang.String - एक स्ट्रिंग जो दिए गए एकल डिकोड प्रकार के पूर्ण मान को दर्शाती है
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


डिकोड टाइप का इंडेक्स प्राप्त करता है।

**Returns:**
short - डिकोड प्रकार का सूचकांक
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


डिकोड टाइप का नाम प्राप्त करता है।

**Returns:**
java.lang.String - डिकोड प्रकार का नाम
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseSingleDecodeType(String stringDecodeType) {#parseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType parseSingleDecodeType(String stringDecodeType)
```


SingleDecodeType के नाम की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stringDecodeType | java.lang.String | एक स्ट्रिंग जिसमें कनवर्ट करने के लिए SingleDecodeType का नाम हो। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


ओवरराइड किया गया मेथड जो SingleDecodeType को नाम स्ट्रिंग के रूप में दर्शाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के नाम को दर्शाती है
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

