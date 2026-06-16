---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode für Android via Java API-Referenz
description: 
type: docs
weight: 49
url: /de/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Erweiterter Codetext-Generator für Han Xin Code für den erweiterten Modus von HanXinEncodeMode

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

| Constructor | Beschreibung |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Fügt Codetext-Fragment im Auto‑Modus hinzu |
| [addBinary(String text)](#addBinary-java.lang.String-) | Fügt Codetext-Fragment im Binär‑Modus hinzu |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Eins hinzu |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Zwei hinzu |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Fügt Codetext-Fragment im ECI‑Modus hinzu |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Fügt Codetext-Fragment im GB18030‑Vier‑Byte‑Modus hinzu |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Fügt Codetext-Fragment im GB18030‑Zwei‑Byte‑Modus hinzu |
| [addGS1(String text)](#addGS1-java.lang.String-) | Fügt Codetext-Fragment im GS1‑Modus hinzu |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Fügt Codetext-Fragment im Numerischen Modus hinzu |
| [addText(String text)](#addText-java.lang.String-) | Fügt Codetext-Fragment im Text‑Modus hinzu |
| [addURI(String text)](#addURI-java.lang.String-) | Fügt Codetext-Fragment im URI‑Modus hinzu |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Fügt Codetext-Fragment im Unicode‑Modus hinzu |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Gibt den Codetext vom Codetext‑Builder des erweiterten Modus zurück |
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


Fügt Codetext-Fragment im Auto‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Fügt Codetext-Fragment im Binär‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Eins hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Zwei hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Fügt Codetext-Fragment im ECI‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |
| Kodierung | int | ECI‑Kodierung im Ganzzahlformat |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Fügt Codetext-Fragment im GB18030‑Vier‑Byte‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Fügt Codetext-Fragment im GB18030‑Zwei‑Byte‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Fügt Codetext-Fragment im GS1‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Fügt Codetext-Fragment im Numerischen Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Fügt Codetext-Fragment im Text‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Fügt Codetext-Fragment im URI‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Fügt Codetext-Fragment im Unicode‑Modus hinzu

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Codetext‑Zeichenkette |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
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


Gibt den Codetext vom Codetext‑Builder des erweiterten Modus zurück

**Returns:**
java.lang.String – Codetext im erweiterten Modus
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

