---
title: "DataMatrixExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 31
url: /hi/java/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

2D DataMatrix बारकोड के लिए ExtendedCodetext मोड के EncodeMode के लिए विस्तारित Codetext जनरेटर।

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | परिभाषित encode मोड के साथ Codetext को विस्तारित Codetext आइटम्स में जोड़ता है। |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | परिभाषित encode मोड के साथ Extended Channel Identifier के साथ Codetext जोड़ता है। |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | विस्तारित कोडटेक्स्ट आइटम्स में साधारण कोडटेक्स्ट जोड़ता है |
| [clear()](#clear--) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | विस्तारित कोडटेक्स्ट सूची से Extended कोडटेक्स्ट उत्पन्न करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


परिभाषित encode मोड के साथ Codetext को विस्तारित Codetext आइटम्स में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode मोड मान |
| codetext | java.lang.String | Unicode में Codetext को विस्तारित Codetext आइटम के रूप में जोड़ने के लिए |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


परिभाषित encode मोड के साथ Extended Channel Identifier के साथ Codetext जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode मोड मान |
| codetext | java.lang.String | Unicode में Codetext को विस्तारित Codetext आइटम के रूप में, Extended Channel Identifier के साथ, परिभाषित encode मोड के साथ जोड़ने के लिए। |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


विस्तारित कोडटेक्स्ट आइटम्स में साधारण कोडटेक्स्ट जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codetext | java.lang.String | Unicode में Codetext को विस्तारित Codetext आइटम के रूप में जोड़ने के लिए |

### clear() {#clear--}
```
public void clear()
```


विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


विस्तारित कोडटेक्स्ट सूची से Extended कोडटेक्स्ट उत्पन्न करता है।

**Returns:**
java.lang.String - विस्तारित Codetext को स्ट्रिंग के रूप में।
### hashCode() {#hashCode--}
```
public native int hashCode()
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

