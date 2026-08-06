---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 49
url: /hi/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Han Xin कोड के विस्तारित मोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर HanXinEncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>  codeTextBuilder.addGB18030TwoByte("\u6f04");
>  codeTextBuilder.addGB18030FourByte("\u3401");
>  codeTextBuilder.addCommonChineseRegionOne("\u5168");
>  codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>  codeTextBuilder.addNumeric("123");
>  codeTextBuilder.addText("qwe");
>  codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>  codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>  codeTextBuilder.addAuto("abc");
>  codeTextBuilder.addBinary("abc");
>  codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
>  codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10");
>  String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10";
>  //generate codetext
>  String str = codeTextBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str);
>  bg.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>  BufferedImage img = bg.generateBarCodeImage();
>  BarCodeReader r = new BarCodeReader(img, DecodeType.HAN_XIN))
>  BarcodeResult[] found = r.readBarCodes();
>  Assert.assertEquals(1, found.length);
>  Assert.assertEquals(expectedStr, found[0].getCodeText());
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | ऑटो मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addBinary(String text)](#addBinary-java.lang.String-) | बाइनरी मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | कॉमन चाइनीज़ रीजन वन मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | कॉमन चाइनीज़ रीजन टू मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | GB18030 फोर बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | GB18030 टु बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addGS1(String text)](#addGS1-java.lang.String-) | GS1 मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | संख्यात्मक मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addText(String text)](#addText-java.lang.String-) | टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addURI(String text)](#addURI-java.lang.String-) | URI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Unicode मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | विस्तारित मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HanXinExtCodetextBuilder() {#HanXinExtCodetextBuilder--}
```
public HanXinExtCodetextBuilder()
```


### addAuto(String text) {#addAuto-java.lang.String-}
```
public void addAuto(String text)
```


ऑटो मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


बाइनरी मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


कॉमन चाइनीज़ रीजन वन मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


कॉमन चाइनीज़ रीजन टू मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |
| एन्कोडिंग | int | इंटीजर फॉर्मेट में ECI एन्कोडिंग |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


GB18030 फोर बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


GB18030 टु बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


GS1 मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


संख्यात्मक मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


URI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Unicode मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| टेक्स्ट | java.lang.String | कोडटेक्स्ट स्ट्रिंग |

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


विस्तारित मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है

**Returns:**
java.lang.String - विस्तारित मोड में कोडटेक्स्ट
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

