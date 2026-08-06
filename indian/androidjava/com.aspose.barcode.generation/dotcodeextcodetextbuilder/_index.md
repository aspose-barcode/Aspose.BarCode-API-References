---
title: DotCodeExtCodetextBuilder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 35
url: /hi/androidjava/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

2D DotCode बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर, DotCodeEncodeMode के ExtendedCodetext मोड के लिए।

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
>  {
>      generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  	   generator.save("test.bmp");
>  }
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है। |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है। |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है। |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | विस्तारित कोडटेक्स्ट आइटम्स में FNC3 सिंबल सेपरेटर जोड़ता है। |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | विस्तारित कोडटेक्स्ट आइटम्स में स्ट्रक्चर्ड अपेंड मोड जोड़ता है। |
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
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public void addFNC1FormatIdentifier()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC1 फ़ॉर्मेट पहचानकर्ता जोड़ता है।

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public void addFNC3ReaderInitialization()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC3 रीडर इनिशियलाइज़ेशन जोड़ता है।

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public void addFNC3SymbolSeparator()
```


विस्तारित कोडटेक्स्ट आइटम्स में FNC3 सिंबल सेपरेटर जोड़ता है।

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कोडटेक्स्ट | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


विस्तारित कोडटेक्स्ट आइटम्स में स्ट्रक्चर्ड अपेंड मोड जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| barcodeId | int | बारकोड की आईडी |
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

