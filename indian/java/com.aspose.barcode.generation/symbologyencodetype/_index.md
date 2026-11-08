---
title: "SymbologyEncodeType"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "प्रतीकात्मक एन्कोड प्रकार।"
type: docs
weight: 66
url: /hi/java/com.aspose.barcode.generation/symbologyencodetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
```
public class SymbologyEncodeType extends BaseEncodeType
```

सिम्बोलॉजी एन्कोड प्रकार। इंस्टेंस प्राप्त करने के लिए EncodeTypes देखें।

--------------------

> ```
> Create symbology encode type
>  
>  SymbologyEncodeType symbologyType = EncodeTypes.GS_1_CODE_128
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object other)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BaseEncodeType मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getClassification()](#getClassification--) | इस सिम्बोलॉजी की वर्गीकरण प्राप्त करता है। |
| [getString()](#getString--) | BaseEncodeType का उदाहरण उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| [getString(BaseEncodeType instance)](#getString-com.aspose.barcode.generation.BaseEncodeType-) | BaseEncodeType का उदाहरण उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। |
| [getTypeIndex()](#getTypeIndex--) | एन्कोड प्रकार का सूचकांक प्राप्त करता है |
| [getTypeName()](#getTypeName--) | एन्कोड प्रकार का नाम प्राप्त करता है |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(String stringEncodeType)](#parse-java.lang.String-) | BaseEncodeType के नाम के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [toString()](#toString--) | दिए गए BaseEncodeType का नाम स्ट्रिंग के रूप में लौटाता है। |
| [tryParse(String parsingType, BaseEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---) | BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [tryParse(String parsingType, SymbologyEncodeType[] result)](#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---) | BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट BaseEncodeType मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | java.lang.Object | इस उदाहरण से तुलना करने के लिए एक BaseEncodeType मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassification() {#getClassification--}
```
public BarcodeClassifications getClassification()
```


इस सिम्बोलॉजी की वर्गीकरण प्राप्त करता है।

**Returns:**
[BarcodeClassifications](../../com.aspose.barcode.generation/barcodeclassifications)
### getString() {#getString--}
```
public String getString()
```


BaseEncodeType का उदाहरण उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग प्रारूप है: "Index:0; Name:Codabar"।

**Returns:**
java.lang.String - एन्कोड प्रकार के पूर्ण मान को दर्शाने वाली स्ट्रिंग
### getString(BaseEncodeType instance) {#getString-com.aspose.barcode.generation.BaseEncodeType-}
```
public static String getString(BaseEncodeType instance)
```


BaseEncodeType का उदाहरण उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग प्रारूप है: "Index:-1; Name:None"।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instance | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) | परिवर्तित करने के लिए BaseEncodeType उदाहरण |

**Returns:**
java.lang.String - दिए गए एन्कोड प्रकार के पूर्ण मान को दर्शाने वाली स्ट्रिंग
### getTypeIndex() {#getTypeIndex--}
```
public short getTypeIndex()
```


एन्कोड प्रकार का सूचकांक प्राप्त करता है

**Returns:**
short
### getTypeName() {#getTypeName--}
```
public String getTypeName()
```


एन्कोड प्रकार का नाम प्राप्त करता है

**Returns:**
java.lang.String
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




### parse(String stringEncodeType) {#parse-java.lang.String-}
```
public static BaseEncodeType parse(String stringEncodeType)
```


BaseEncodeType के नाम के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stringEncodeType | java.lang.String | परिवर्तित करने के लिए BaseEncodeType के नाम को शामिल करने वाली स्ट्रिंग। |

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - the instance of , if conversion was successful; otherwise, it returns   .
### toString() {#toString--}
```
public String toString()
```


दिए गए BaseEncodeType का नाम स्ट्रिंग के रूप में लौटाता है।

**Returns:**
java.lang.String - एन्कोड प्रकार के नाम को दर्शाने वाली स्ट्रिंग
### tryParse(String parsingType, BaseEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.BaseEncodeType---}
```
public static boolean tryParse(String parsingType, BaseEncodeType[] result)
```


BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। रिटर्न मान यह दर्शाता है कि परिवर्तन सफल हुआ या विफल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | परिवर्तित करने के लिए "Index:-1; Name:None" के रूप में स्ट्रिंग। |
|  | result | [BaseEncodeType\[\]](../../com.aspose.barcode.generation/baseencodetype) | जब परिवर्तन सफलतापूर्वक पूर्ण हो जाता है, तब वास्तविक SingleEncodeType लौटाता है; |

अन्यथा यह null लौटाता है। |

**Returns:**
boolean -  **true**  यदि s सफलतापूर्वक परिवर्तित हुआ; अन्यथा,  **false** ।
### tryParse(String parsingType, SymbologyEncodeType[] result) {#tryParse-java.lang.String-com.aspose.barcode.generation.SymbologyEncodeType---}
```
public static boolean tryParse(String parsingType, SymbologyEncodeType[] result)
```


BaseEncodeType के स्ट्रिंग प्रतिनिधित्व को उसके उदाहरण में परिवर्तित करता है। रिटर्न मान यह दर्शाता है कि परिवर्तन सफल हुआ या विफल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parsingType | java.lang.String | परिवर्तित करने के लिए "Index:-1; Name:None" के रूप में स्ट्रिंग। |
|  | result | [SymbologyEncodeType\[\]](../../com.aspose.barcode.generation/symbologyencodetype) | जब परिवर्तन सफलतापूर्वक पूर्ण हो जाता है, तब वास्तविक SingleEncodeType लौटाता है; |

अन्यथा यह null लौटाता है। |

**Returns:**
boolean -  **true**  यदि s सफलतापूर्वक परिवर्तित हुआ; अन्यथा,  **false** ।
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

