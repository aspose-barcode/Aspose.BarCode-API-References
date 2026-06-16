---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode per Android via Java API Reference
description: 
type: docs
weight: 49
url: /it/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Generatore di codetext esteso per Han Xin Code per Modalità Estesa di HanXinEncodeMode

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

| Constructor | Descrizione |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Aggiunge frammento di codetext in modalità Auto |
| [addBinary(String text)](#addBinary-java.lang.String-) | Aggiunge frammento di codetext in modalità Binaria |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Aggiunge frammento di codetext in modalità Common Chinese Region One |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Aggiunge frammento di codetext in modalità Common Chinese Region Two |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Aggiunge frammento di codetext in modalità ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Aggiunge frammento di codetext in modalità GB18030 Four Byte |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Aggiunge frammento di codetext in modalità GB18030 Two Byte |
| [addGS1(String text)](#addGS1-java.lang.String-) | Aggiunge frammento di codetext in modalità GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Aggiunge frammento di codetext in modalità Numerica |
| [addText(String text)](#addText-java.lang.String-) | Aggiunge frammento di codetext in modalità Testo |
| [addURI(String text)](#addURI-java.lang.String-) | Aggiunge frammento di codetext in modalità URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Aggiunge frammento di codetext in modalità Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Restituisce il codetext dal generatore di codetext in modalità Estesa |
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


Aggiunge frammento di codetext in modalità Auto

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Aggiunge frammento di codetext in modalità Binaria

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Aggiunge frammento di codetext in modalità Common Chinese Region One

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Aggiunge frammento di codetext in modalità Common Chinese Region Two

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Aggiunge frammento di codetext in modalità ECI

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |
| codifica | int | Codifica ECI in formato intero |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Aggiunge frammento di codetext in modalità GB18030 Four Byte

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Aggiunge frammento di codetext in modalità GB18030 Two Byte

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Aggiunge frammento di codetext in modalità GS1

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Aggiunge frammento di codetext in modalità Numerica

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Aggiunge frammento di codetext in modalità Testo

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Aggiunge frammento di codetext in modalità URI

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Aggiunge frammento di codetext in modalità Unicode

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Stringa di codetext |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
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


Restituisce il codetext dal generatore di codetext in modalità Estesa

**Returns:**
java.lang.String - Codetext in modalità Estesa
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

