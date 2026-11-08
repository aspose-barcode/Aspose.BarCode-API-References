---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 33
url: /hi/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

2D DotCode बारकोड के लिए ExtendedCodetext Mode के DotCodeEncodeMode में Extended codetext जेनरेटर

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 सिंबल सेपरेटर जोड़ता है |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | विस्तारित कोडटेक्स्ट आइटम्स में साधारण कोडटेक्स्ट जोड़ता है |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | विस्तारित कोडटेक्स्ट आइटम्स में स्ट्रक्चर्ड अपेंड मोड जोड़ता है |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC3 सिंबल सेपरेटर जोड़ता है

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


विस्तारित कोडटेक्स्ट आइटम्स में साधारण कोडटेक्स्ट जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codetext | java.lang.String | Unicode में Codetext को विस्तारित Codetext आइटम के रूप में जोड़ने के लिए |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


विस्तारित कोडटेक्स्ट आइटम्स में स्ट्रक्चर्ड अपेंड मोड जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| barcodeId | int | बारकोड का ID |
| barcodesCount | int | बारकोड की संख्या |

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

