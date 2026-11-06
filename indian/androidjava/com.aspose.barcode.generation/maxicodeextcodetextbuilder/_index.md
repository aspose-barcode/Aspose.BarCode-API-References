---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "ExtendedCodetext मोड में MaxiCode बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर, MaxiCodeEncodeMode का उपयोग करके, BarcodeGenerator की TwoDDisplayText प्रॉपर्टी से दृश्यमान टेक्स्ट सेट करने हेतु, प्रबंधन अक्षरों को हटाते हुए।"
type: docs
weight: 54
url: /hi/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

MaxiCode बारकोड के लिए ExtendedCodetext मोड में MaxiCodeEncodeMode के लिए विस्तारित कोडटेक्स्ट जेनरेटर। दृश्यमान टेक्स्ट सेट करने और प्रबंधन अक्षरों को हटाने के लिए BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करें। यह उदाहरण दिखाता है कि Extended मोड में MaxiCodeExtCodetextBuilder का उपयोग कैसे करें।

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [clear()](#clear--) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | विस्तारित कोडटेक्स्ट सूची से विस्तारित कोडटेक्स्ट उत्पन्न करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| ECIEncoding | int | विस्तारित चैनल पहचानकर्ता |
| codetext | java.lang.String | विस्तारित चैनल पहचानकर्ता के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


साधारण कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| codetext | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

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

