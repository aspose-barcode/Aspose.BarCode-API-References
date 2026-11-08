---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: 
type: docs
weight: 61
url: /hi/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

2D QR बारकोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर, EncodeMode के ExtendedCodetext मोड के लिए

दृश्यमान टेक्स्ट को सेट करने और प्रबंधन अक्षरों को हटाने के लिए BarcodeGenerator की TwoDDisplayText प्रॉपर्टी का उपयोग करें।

यह उदाहरण दिखाता है कि Extended Mode में FNC1 की पहली स्थिति का उपयोग कैसे करें।

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

यह उदाहरण दिखाता है कि Extended Mode में FNC1 की दूसरी स्थिति का उपयोग कैसे करें।

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

यह उदाहरण दिखाता है कि Extended Mode में मल्टी ECI मोड का उपयोग कैसे करें।

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है। |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | पहली स्थिति में FNC1 सेट करता है। |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\\\\\\u001D') जोड़ता है। |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | दूसरी स्थिति में FNC1 सेट करता है। |
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
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


निर्दिष्ट QR संपीड़न मोड के साथ कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | कोडटेक्स्ट के लिए QR संपीड़न मोड। |
| codetext | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए Unicode में कोडटेक्स्ट। |

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

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


पहली स्थिति में FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो यह प्रतिस्थापित हो जाता है।

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


विस्तारित कोडटेक्स्ट आइटम्स में ग्रुप सेपरेटर (GS - '\\\\\\u001D') जोड़ता है।

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


दूसरी स्थिति में FNC1 सेट करता है। यदि पहले कोई अन्य FNC1 मोड सेट किया गया था, तो यह प्रतिस्थापित हो जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| codetext | java.lang.String | दूसरी स्थिति में FNC1 का मान। मान a-z या A-Z से एकल अक्षर होना चाहिए, या 00 से 99 तक का दो-अंकीय संख्या। |

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

