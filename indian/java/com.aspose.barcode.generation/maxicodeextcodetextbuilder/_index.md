---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "MaxiCode बारकोड के लिए ExtendedCodetext मोड में Extended codetext जेनरेटर, MaxiCodeEncodeMode का उपयोग करके। दृश्यमान टेक्स्ट सेट करने के लिए BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करें, जिससे प्रबंधन अक्षर हटाए जा सकें।"
type: docs
weight: 54
url: /hi/java/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

MaxiCode बारकोड के लिए ExtendedCodetext मोड में MaxiCodeEncodeMode के लिए विस्तारित codetext जेनरेटर। BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट सेट करने हेतु प्रबंधित अक्षरों को हटाया जाता है। यह उदाहरण दिखाता है कि Extended Mode में MaxiCodeExtCodetextBuilder का उपयोग कैसे करें।

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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ECIEncoding | int | Extended Channel Identifier |
| codetext | java.lang.String | Extended Channel Identifier के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

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
java.lang.String - विस्तारित Codetext को स्ट्रिंग के रूप में
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

