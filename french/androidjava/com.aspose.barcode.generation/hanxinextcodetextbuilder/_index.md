---
title: HanXinExtCodetextBuilder
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: 
type: docs
weight: 49
url: /fr/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Générateur de texte de code étendu pour le code Han Xin en mode étendu de HanXinEncodeMode

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Ajoute un fragment de texte de code en mode Auto |
| [addBinary(String text)](#addBinary-java.lang.String-) | Ajoute un fragment de texte de code en mode Binaire |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Ajoute un fragment de texte de code en mode Région chinoise commune Un |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Ajoute un fragment de texte de code en mode Région chinoise commune Deux |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Ajoute un fragment de texte de code en mode ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Ajoute un fragment de texte de code en mode GB18030 quatre octets |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Ajoute un fragment de texte de code en mode GB18030 deux octets |
| [addGS1(String text)](#addGS1-java.lang.String-) | Ajoute un fragment de texte de code en mode GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Ajoute un fragment de texte de code en mode Numérique |
| [addText(String text)](#addText-java.lang.String-) | Ajoute un fragment de texte de code en mode Texte |
| [addURI(String text)](#addURI-java.lang.String-) | Ajoute un fragment de texte de code en mode URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Ajoute un fragment de texte de code en mode Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Renvoie le texte de code depuis le générateur de texte de code en mode Étendu |
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


Ajoute un fragment de texte de code en mode Auto

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Ajoute un fragment de texte de code en mode Binaire

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Ajoute un fragment de texte de code en mode Région chinoise commune Un

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Ajoute un fragment de texte de code en mode Région chinoise commune Deux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Ajoute un fragment de texte de code en mode ECI

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |
| encodage | int | Encodage ECI au format entier |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Ajoute un fragment de texte de code en mode GB18030 quatre octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Ajoute un fragment de texte de code en mode GB18030 deux octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Ajoute un fragment de texte de code en mode GS1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Ajoute un fragment de texte de code en mode Numérique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Ajoute un fragment de texte de code en mode Texte

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Ajoute un fragment de texte de code en mode URI

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Ajoute un fragment de texte de code en mode Unicode

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texte | java.lang.String | Chaîne de texte de code |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Renvoie le texte de code depuis le générateur de texte de code en mode Étendu

**Returns:**
java.lang.String - Texte de code en mode Étendu
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

