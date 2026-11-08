---
title: "MultiDecodeType"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "संयोजन डिकोड प्रकार।"
type: docs
weight: 34
url: /hi/java/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

संयोजन डिकोड प्रकार।

यह उदाहरण दिखाता है कि कैसे संयुक्त MultiDecode प्रकार बनाएँ जो SingleDecodeType और MultiDecode प्रकारों को संयोजित करते हैं।

```

```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास की नई इंस्टेंस को प्रारंभ करता है। |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | MultiDecodeType में एक और [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) जोड़ता है। |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | जाँचें कि यह बारकोड प्रकारों से सभी प्रकारों को शामिल करता है या नहीं। |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | क्या यह किसी भी प्रकार को शामिल करता है |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं। |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकारों का संग्रह केवल निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान को ही शामिल करता है या नहीं। |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं। |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) को MultiDecodeType से बाहर करता है और नया MultiDecodeType इंस्टेंस लौटाता है। |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | एकल प्रकारों की सूची को दर्शाता है। |
| [getSingleTypesCount()](#getSingleTypesCount--) | एकल प्रकारों की संख्या लौटाता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | MultiDecodeType को स्ट्रिंग के रूप में दर्शाने वाला ओवरराइड किया गया मेथड। |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसकी इंस्टेंस में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | एकल डिकोड प्रकारों का एरे |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास की नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | बहु और एकल डिकोड प्रकारों का एरे |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


MultiDecodeType में एक और [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | सूची में जोड़ने के लिए एकल DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


जाँचें कि यह बारकोड प्रकारों से सभी प्रकारों को शामिल करता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | इनपुट एकल या बहु बारकोड प्रकार |

**Returns:**
boolean - मान true है यदि सभी प्रकार शामिल किए गए हैं
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


क्या यह किसी भी प्रकार को शामिल करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार |

**Returns:**
boolean - मान true है यदि कोई भी प्रकार शामिल किया गया है।
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | इस इंस्टेंस की तुलना करने के लिए एक [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकारों का संग्रह केवल निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान को ही शामिल करता है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | इस डिकोड प्रकारों के संग्रह की तुलना करने के लिए एक [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान। |

**Returns:**
boolean - यदि यह संग्रह केवल निर्दिष्ट डिकोड प्रकार को ही शामिल करता है तो **true**, अन्यथा **false**।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) को MultiDecodeType से बाहर करता है और नया MultiDecodeType इंस्टेंस लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | बाहर करने के लिए एकल DecodeType। |

**Returns:**
[MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) - New MultiDecodeType instance with excluded SingleDecodeType.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSingleTypes() {#getSingleTypes--}
```
public final List<SingleDecodeType> getSingleTypes()
```


एकल प्रकारों की सूची को दर्शाता है।

**Returns:**
java.util.List<com.aspose.barcode.barcoderecognition.SingleDecodeType> - एकल प्रकारों की सूची
### getSingleTypesCount() {#getSingleTypesCount--}
```
public final int getSingleTypesCount()
```


एकल प्रकारों की संख्या लौटाता है।

**Returns:**
int
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




### toString() {#toString--}
```
public String toString()
```


MultiDecodeType को स्ट्रिंग के रूप में दर्शाने वाला ओवरराइड किया गया मेथड।

**Returns:**
java.lang.String - एक स्ट्रिंग जो MultiDecodeType इंस्टेंस को \"singleDecodeType1, singleDecodeType2, ...\" के रूप में दर्शाती है।

 **"AllSupportedTypes"**  returns when all types are included.
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

