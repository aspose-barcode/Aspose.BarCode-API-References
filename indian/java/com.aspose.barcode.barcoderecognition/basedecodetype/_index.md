---
title: "BaseDecodeType"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "MultiDecodeType और SingleDecodeType के लिए बेस क्लास।"
type: docs
weight: 22
url: /hi/java/com.aspose.barcode.barcoderecognition/basedecodetype/
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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [containsAny(BaseDecodeType[] types)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | निर्धारित करता है कि क्या दिए गए किसी भी डिकोड प्रकार को शामिल किया गया है |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [equals(Object other)](#equals-java.lang.Object-) | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### containsAny(BaseDecodeType[] types) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public abstract boolean containsAny(BaseDecodeType[] types)
```


निर्धारित करता है कि क्या दिए गए किसी भी डिकोड प्रकार को शामिल किया गया है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| types | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | सत्यापित करने के लिए प्रकार। |

**Returns:**
boolean - यदि कोई प्रकार शामिल किया गया है तो मान true है।
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो True; अन्यथा, false.
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो True; अन्यथा, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक java.lang.Object मान। |

**Returns:**
boolean - यदि obj का मान इस इंस्टेंस के समान है तो True; अन्यथा, false.
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

