---
title: DataMatrixExtCodetextBuilder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 33
url: /hi/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

EncodeMode के ExtendedCodetext मोड के लिए 2D DataMatrix बारकोड का विस्तारित कोडटेक्स्ट जेनरेटर।

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
## Constructors

| Constructor | विवरण |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है। |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ कोडटेक्स्ट जोड़ता है। |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [clear()](#clear--) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | पिछले आइटम को "\\000000" द्वारा शील्ड करने की आवश्यकता की जाँच करता है |
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
public void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


परिभाषित एन्कोड मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | एन्कोड मोड मान |
| कोडटेक्स्ट | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| ECIEncoding | int | विस्तारित चैनल पहचानकर्ता |
| कोडटेक्स्ट | java.lang.String | विस्तारित चैनल पहचानकर्ता के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ कोडटेक्स्ट जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| ECIEncoding | int | विस्तारित चैनल पहचानकर्ता |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | एन्कोड मोड मान |
| कोडटेक्स्ट | java.lang.String | परिभाषित एन्कोड मोड के साथ विस्तारित चैनल पहचानकर्ता के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट। |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कोडटेक्स्ट | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

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
| Parameter | Type | विवरण |
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


विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है।

**Returns:**
java.lang.String - स्ट्रिंग के रूप में विस्तारित कोडटेक्स्ट
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


पिछले आइटम को "\\000000" द्वारा शील्ड करने की आवश्यकता की जाँच करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | m\_List में सूचकांक |

**Returns:**
boolean - शील्ड करने की आवश्यकता
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

