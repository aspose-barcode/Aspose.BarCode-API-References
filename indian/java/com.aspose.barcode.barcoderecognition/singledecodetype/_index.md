---
title: "SingleDecodeType"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "एकल डिकोड प्रकार।"
type: docs
weight: 44
url: /hi/java/com.aspose.barcode.barcoderecognition/singledecodetype/
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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट सूची में शामिल है या नहीं। |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) |  |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getString()](#getString--) | SingleDecodeType की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्न प्रारूप का उपयोग करते हुए: "Index:-1; Name:None"। |
| [getString(SingleDecodeType instance)](#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | SingleDecodeType की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्न प्रारूप का उपयोग करते हुए: "Index:-1; Name:None"। |
| [getTypeIndex()](#getTypeIndex--) | डिकोड प्रकार का सूचकांक प्राप्त करता है। |
| [getTypeName()](#getTypeName--) | डिकोड प्रकार का नाम प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseSingleDecodeType(String stringDecodeType)](#parseSingleDecodeType-java.lang.String-) | SingleDecodeType के नाम की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [toString()](#toString--) | ओवरराइड किया गया मेथड जो SingleDecodeType को नाम स्ट्रिंग के रूप में दर्शाता है। |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] types)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट सूची में शामिल है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | एकल और बहु डिकोड प्रकारों की एरे। |

**Returns:**
boolean - मान true है यदि कोई भी प्रकार शामिल किया गया है।
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो True; अन्यथा, false.
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


SingleDecodeType की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्न प्रारूप का उपयोग करते हुए: "Index:-1; Name:None"।

**Returns:**
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के पूर्ण मान को दर्शाती है
### getString(SingleDecodeType instance) {#getString-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public static String getString(SingleDecodeType instance)
```


SingleDecodeType की इंस्टेंस को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है, निम्न प्रारूप का उपयोग करते हुए: "Index:-1; Name:None"।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instance | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | परिवर्तित करने के लिए SingleDecodeType इंस्टेंस |

**Returns:**
java.lang.String - एक स्ट्रिंग जो दिए गए एकल डिकोड प्रकार के पूर्ण मान को दर्शाती है
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


डिकोड प्रकार का सूचकांक प्राप्त करता है।

**Returns:**
short - डिकोड प्रकार का सूचकांक
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


डिकोड प्रकार का नाम प्राप्त करता है।

**Returns:**
java.lang.String - डिकोड प्रकार का नाम
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

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


SingleDecodeType के नाम की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
java.lang.String - एक स्ट्रिंग जो एकल डिकोड प्रकार के नाम को दर्शाती है
### tryParseBaseDecodeType(String parsingType) {#tryParseBaseDecodeType-java.lang.String-}
```
public static BaseDecodeType tryParseBaseDecodeType(String parsingType)
```


एक BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। एक रिटर्न वैल्यू दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें परिवर्तित करने के लिए MultiDecodeType प्रतिनिधित्व शामिल है। |

**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType (\"None\").
### tryParseMultiDecodeType(String parsingType) {#tryParseMultiDecodeType-java.lang.String-}
```
public static MultiDecodeType tryParseMultiDecodeType(String parsingType)
```


एक MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें परिवर्तित करने के लिए MultiDecodeType प्रतिनिधित्व शामिल है। |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - An actual MultiDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या MultiDecodeType (\"None\").
### tryParseSingleDecodeType(String parsingType) {#tryParseSingleDecodeType-java.lang.String-}
```
public static SingleDecodeType tryParseSingleDecodeType(String parsingType)
```


एक SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | एक स्ट्रिंग जिसमें \"EAN8\", \"EAN13\", \"CodaBar\"... के रूप में SingleDecodeType शामिल है, जिसे परिवर्तित किया जाना है। |

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) - An actual SingleDecodeType is returned, when conversion has completed successfully;

अन्यथा यह अनिश्चित प्रकार लौटाता है। या SingleDecodeType (-1, \"None\").
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

