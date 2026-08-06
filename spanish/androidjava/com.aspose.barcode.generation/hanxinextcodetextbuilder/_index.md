---
title: HanXinExtCodetextBuilder
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: 
type: docs
weight: 49
url: /es/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Generador de codetexto extendido para Han Xin Code en modo extendido de HanXinEncodeMode

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

| Constructor | Descripción |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Agrega fragmento de codetexto en modo automático |
| [addBinary(String text)](#addBinary-java.lang.String-) | Agrega fragmento de codetexto en modo binario |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Agrega fragmento de codetexto en modo Región China Común Uno |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Agrega fragmento de codetexto en modo Región China Común Dos |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Agrega fragmento de codetexto en modo ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Agrega fragmento de codetexto en modo GB18030 de cuatro bytes |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Agrega fragmento de codetexto en modo GB18030 de dos bytes |
| [addGS1(String text)](#addGS1-java.lang.String-) | Agrega fragmento de codetexto en modo GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Agrega fragmento de codetexto en modo numérico |
| [addText(String text)](#addText-java.lang.String-) | Agrega fragmento de codetexto en modo texto |
| [addURI(String text)](#addURI-java.lang.String-) | Agrega fragmento de codetexto en modo URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Agrega fragmento de codetexto en modo Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Devuelve el codetexto del generador de codetexto en modo extendido |
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


Agrega fragmento de codetexto en modo automático

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Agrega fragmento de codetexto en modo binario

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Agrega fragmento de codetexto en modo Región China Común Uno

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Agrega fragmento de codetexto en modo Región China Común Dos

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Agrega fragmento de codetexto en modo ECI

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |
| codificación | int | Codificación ECI en formato entero |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Agrega fragmento de codetexto en modo GB18030 de cuatro bytes

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Agrega fragmento de codetexto en modo GB18030 de dos bytes

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Agrega fragmento de codetexto en modo GS1

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Agrega fragmento de codetexto en modo numérico

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Agrega fragmento de codetexto en modo texto

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Agrega fragmento de codetexto en modo URI

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Agrega fragmento de codetexto en modo Unicode

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| text | java.lang.String | Cadena de codetexto |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
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


Devuelve el codetexto del generador de codetexto en modo extendido

**Returns:**
java.lang.String - Codetexto en modo extendido
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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

