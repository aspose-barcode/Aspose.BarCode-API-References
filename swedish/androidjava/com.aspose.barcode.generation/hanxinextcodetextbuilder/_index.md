---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API-referens
description: 
type: docs
weight: 49
url: /sv/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Utökad kodtextgenerator för Han Xin Code för Utökat läge av HanXinEncodeMode

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

| Constructor | Beskrivning |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Lägger till kodtextfragment i Auto-läge |
| [addBinary(String text)](#addBinary-java.lang.String-) | Lägger till kodtextfragment i Binary-läge |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Lägger till kodtextfragment i Common Chinese Region One-läge |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Lägger till kodtextfragment i Common Chinese Region Two-läge |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Lägger till kodtextfragment i ECI-läge |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Lägger till kodtextfragment i GB18030 Four Byte-läge |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Lägger till kodtextfragment i GB18030 Two Byte-läge |
| [addGS1(String text)](#addGS1-java.lang.String-) | Lägger till kodtextfragment i GS1-läge |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Lägger till kodtextfragment i Numeric-läge |
| [addText(String text)](#addText-java.lang.String-) | Lägger till kodtextfragment i Text-läge |
| [addURI(String text)](#addURI-java.lang.String-) | Lägger till kodtextfragment i URI-läge |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Lägger till kodtextfragment i Unicode-läge |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Returnerar kodtext från Extended mode kodtextbyggare |
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


Lägger till kodtextfragment i Auto-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Lägger till kodtextfragment i Binary-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Lägger till kodtextfragment i Common Chinese Region One-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Lägger till kodtextfragment i Common Chinese Region Two-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Lägger till kodtextfragment i ECI-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |
| kodning | int | ECI-kodning i heltalsformat |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Lägger till kodtextfragment i GB18030 Four Byte-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Lägger till kodtextfragment i GB18030 Two Byte-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Lägger till kodtextfragment i GS1-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Lägger till kodtextfragment i Numeric-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Lägger till kodtextfragment i Text-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Lägger till kodtextfragment i URI-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Lägger till kodtextfragment i Unicode-läge

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Codetext sträng |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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


Returnerar kodtext från Extended mode kodtextbyggare

**Returns:**
java.lang.String - Kodtext i Extended mode
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

