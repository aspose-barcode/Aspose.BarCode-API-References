---
title: QrExtCodetextBuilder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 2D QR बारकोड के लिए ExtendedCodetext Mode के QrEncodeMode में विस्तारित कोडटेक्स्ट जेनरेटर, BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करके दृश्यमान टेक्स्ट सेट करता है और प्रबंधन अक्षरों को हटाता है।
type: docs
weight: 63
url: /hi/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use FNC1 first position in Extended Mode: QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345<FNC1>"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setQrErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use FNC1 second position in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addFNC1SecondPosition("12"); TextBuilder.addPlainCodetext("TRUE3456"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use multi ECI mode in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); TextBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); TextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); TextBuilder.addPlainCodetext(@"t\\e\\\\st"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp");
## Constructors

| Constructor | विवरण |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है। |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Adds FNC1 in first position to the extended codetext items |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Adds Group Separator (GS - '\\\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Adds FNC1 in second position to the extended codetext items |
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
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
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

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public void addFNC1FirstPosition()
```


Adds FNC1 in first position to the extended codetext items

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public void addFNC1GroupSeparator()
```


Adds Group Separator (GS - '\\\\u001D') to the extended codetext items

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public void addFNC1SecondPosition(String codetext)
```


Adds FNC1 in second position to the extended codetext items

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कोडटेक्स्ट | java.lang.String | दूसरी स्थिति में FNC1 का मान |

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

