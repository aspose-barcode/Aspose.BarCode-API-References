---
title: "MultiDecodeType"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "संयुक्त डिकोड प्रकार।"
type: docs
weight: 35
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/multidecodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
```
public class MultiDecodeType extends BaseDecodeType
```

संयुक्त डिकोड प्रकार।

यह नमूना दिखाता है कि कैसे संयुक्त MultiDecode प्रकार बनाएँ जो SingleDecodeType और MultiDecode प्रकारों को मिलाते हैं।

```

```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MultiDecodeType(SingleDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-) | नए उदाहरण को प्रारंभ करता है [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास का। |
| [MultiDecodeType(BaseDecodeType[] barcodeTypes)](#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | नए उदाहरण को प्रारंभ करता है [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास का। |
## Methods

| Method | विवरण |
| --- | --- |
| [add(SingleDecodeType singleType)](#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | MultiDecodeType में एक और [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) जोड़ता है। |
| [containsAll(BaseDecodeType[] barcodeTypes)](#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | जाँचें कि क्या यह सभी बारकोड प्रकारों को शामिल करता है। |
| [containsAny(BaseDecodeType[] decodeTypes)](#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-) | क्या यह किसी प्रकार को शामिल करता है। |
| [equals(MultiDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं। |
| [equals(SingleDecodeType other)](#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकार संग्रह केवल निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान को ही शामिल करता है या नहीं। |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं। |
| [exclude(SingleDecodeType singleType)](#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-) | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) को MultiDecodeType से बाहर करता है और नया MultiDecodeType उदाहरण लौटाता है। |
| [getClass()](#getClass--) |  |
| [getSingleTypes()](#getSingleTypes--) | एकल प्रकारों की सूची का प्रतिनिधित्व करता है। |
| [getSingleTypesCount()](#getSingleTypesCount--) | एकल प्रकारों की संख्या लौटाता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | MultiDecodeType को स्ट्रिंग के रूप में दर्शाने वाली ओवरराइडेड मेथड। |
| [tryParseBaseDecodeType(String parsingType)](#tryParseBaseDecodeType-java.lang.String-) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। |
| [tryParseMultiDecodeType(String parsingType)](#tryParseMultiDecodeType-java.lang.String-) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [tryParseSingleDecodeType(String parsingType)](#tryParseSingleDecodeType-java.lang.String-) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiDecodeType(SingleDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.SingleDecodeType...-}
```
public MultiDecodeType(SingleDecodeType[] barcodeTypes)
```


नए उदाहरण को प्रारंभ करता है [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [SingleDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/singledecodetype) | एकल डिकोड प्रकारों की एरे |

### MultiDecodeType(BaseDecodeType[] barcodeTypes) {#MultiDecodeType-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public MultiDecodeType(BaseDecodeType[] barcodeTypes)
```


नए उदाहरण को प्रारंभ करता है [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) क्लास का।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | बहु और एकल डिकोड प्रकारों की एरे |

### add(SingleDecodeType singleType) {#add-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final void add(SingleDecodeType singleType)
```


MultiDecodeType में एक और [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | सूची में जोड़ने के लिए एक Single DecodeType |

### containsAll(BaseDecodeType[] barcodeTypes) {#containsAll-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public final boolean containsAll(BaseDecodeType[] barcodeTypes)
```


जाँचें कि क्या यह सभी बारकोड प्रकारों को शामिल करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | एकल या बहु बारकोड प्रकारों को इनपुट करें |

**Returns:**
boolean - मान true है यदि सभी प्रकार शामिल किए गए हैं।
### containsAny(BaseDecodeType[] decodeTypes) {#containsAny-com.aspose.barcode.barcoderecognition.BaseDecodeType...-}
```
public boolean containsAny(BaseDecodeType[] decodeTypes)
```


क्या यह किसी प्रकार को शामिल करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| decodeTypes | [BaseDecodeType\[\]](../../com.aspose.barcode.barcoderecognition/basedecodetype) | डिकोड प्रकार |

**Returns:**
boolean - यदि कोई प्रकार शामिल किया गया हो तो मान true है
### equals(MultiDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.MultiDecodeType-}
```
public boolean equals(MultiDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) | इस उदाहरण से तुलना करने के लिए एक [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### equals(SingleDecodeType other) {#equals-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public boolean equals(SingleDecodeType other)
```


एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकार संग्रह केवल निर्दिष्ट [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान को ही शामिल करता है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| other | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | इस डिकोड प्रकार संग्रह से तुलना करने के लिए एक [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) मान। |

**Returns:**
boolean -  **true**  यदि यह संग्रह केवल निर्दिष्ट डिकोड प्रकार को ही शामिल करता है; अन्यथा,  **false** ।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट [MultiDecodeType](../../com.aspose.barcode.barcoderecognition/multidecodetype) मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक System.Object मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### exclude(SingleDecodeType singleType) {#exclude-com.aspose.barcode.barcoderecognition.SingleDecodeType-}
```
public final MultiDecodeType exclude(SingleDecodeType singleType)
```


[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) को MultiDecodeType से बाहर करता है और नया MultiDecodeType उदाहरण लौटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| singleType | [SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype) | एक Single DecodeType जिसे बाहर किया जाना है। |

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


एकल प्रकारों की सूची का प्रतिनिधित्व करता है।

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




### toString() {#toString--}
```
public String toString()
```


MultiDecodeType को स्ट्रिंग के रूप में दर्शाने वाली ओवरराइडेड मेथड।

**Returns:**
java.lang.String - एक स्ट्रिंग जो MultiDecodeType इंस्टेंस को "singleDecodeType1, singleDecodeType2, ..." के रूप में दर्शाती है

 **"AllSupportedTypes"**  returns when all types are included.
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

