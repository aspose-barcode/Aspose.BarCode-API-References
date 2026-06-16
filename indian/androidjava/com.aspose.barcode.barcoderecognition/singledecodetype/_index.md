---
title: SingleDecodeType
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Single decode type.
type: docs
weight: 48
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/singledecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public final class SingleDecodeType extends BaseDecodeType
```

एकल डिकोड प्रकार। उदाहरण प्राप्त करने के लिए डिकोड प्रकार देखें।

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
| [getString()](#getString--) | SingleDecodeType के उदाहरण को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित स्वरूप का उपयोग करते हुए: "Index:-1; Name:None"। |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | SingleDecodeType के उदाहरण को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित स्वरूप का उपयोग करते हुए: "Index:-1; Name:None"। |
| [getTypeIndex()](#getTypeIndex--) | डिकोड प्रकार का सूचकांक प्राप्त करता है |
| [getTypeName()](#getTypeName--) | डिकोड प्रकार का नाम प्राप्त करता है |
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
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | एकल और बहु डिकोड प्रकारों की एरे |

**Returns:**
boolean - यदि कोई प्रकार शामिल है तो मान true होता है
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| अन्य | com.aspose.barcode.barcoderecognition.MultiDecodeType |  |

**Returns:**
boolean
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

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
boolean - यदि obj का मान इस उदाहरण के समान है तो true; अन्यथा false।
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


SingleDecodeType के उदाहरण को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित स्वरूप का उपयोग करते हुए: "Index:-1; Name:None"।

**Returns:**
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के पूर्ण मान का प्रतिनिधित्व करती है
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


SingleDecodeType के उदाहरण को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्नलिखित स्वरूप का उपयोग करते हुए: "Index:-1; Name:None"।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | परिवर्तित करने के लिए SingleDecodeType उदाहरण |

**Returns:**
java.lang.String - एक स्ट्रिंग जो दिए गए एकल डिकोड प्रकार के पूर्ण मान का प्रतिनिधित्व करती है
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


डिकोड प्रकार का सूचकांक प्राप्त करता है

**Returns:**
short - डिकोड प्रकार का सूचकांक
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


डिकोड प्रकार का नाम प्राप्त करता है

**Returns:**
java.lang.String - डिकोड प्रकार का नाम
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
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
| stringDecodeType | java.lang.String | एक स्ट्रिंग जिसमें परिवर्तित करने के लिए SingleDecodeType का नाम शामिल है। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - the instance of , if conversion was successful; otherwise, it returns \{@link \}.
### toString() {#toString--}
```
public String toString()
```


ओवरराइड किया गया मेथड जो SingleDecodeType को नाम स्ट्रिंग के रूप में दर्शाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के नाम का प्रतिनिधित्व करती है
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें MultiDecodeType प्रतिनिधित्व है जिसे परिवर्तित किया जाना है। |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें MultiDecodeType प्रतिनिधित्व है जिसे परिवर्तित किया जाना है। |

**Returns:**
com.aspose.barcode.barcoderecognition.MultiDecodeType - जब रूपांतरण सफलतापूर्वक पूरा हो जाता है, तो वास्तविक MultiDecodeType लौटाया जाता है;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें \"EAN8\" या \"EAN13\" या \"CodaBar\"... के रूप में SingleDecodeType होता है, जिसे परिवर्तित किया जाना है। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या SingleDecodeType (-1, \"None\").
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

