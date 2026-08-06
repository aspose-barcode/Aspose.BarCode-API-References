---
title: HanXinEncodeMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: Coderingsmodus voor Han Xin Code.
type: docs
weight: 89
url: /nl/androidjava/com.aspose.barcode.generation/hanxinencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum HanXinEncodeMode extends Enum<HanXinEncodeMode>
```

Han Xin Code-coderingsmodus. Het wordt aanbevolen om Auto te gebruiken met ASCII / Chinese tekens of Unicode voor Unicode‑tekens.

--------------------

> ```
> // Auto mode
>   String codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.save("test.bmp");
> 
> 
>  // Binary mode
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN)
>  generator.setCodeText(encodedArr);
>  generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>   // ECI mode
>   String codetext = "\u0391\u0392\u0393\u0394\u0395";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.ECI);
>   generator.getParameters().getBarcode().getHanXin().setHanXinECIEncoding(ECIEncodings.ISO_8859_7);
>   generator.save("test.bmp");
> 
>   // URI mode
>   String codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HAN_XIN, codetext);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.URI);
>   generator.save("test.bmp");
> 
> 
>   // Extended mode
>   String str = "\\gb180302b:\u6f04\\gb180304b:\u3401\\region1:\u5168\\region2:\u8785\\numeric:123\\text:qwe\\\\unicode:\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l" +
>       "\\000009:\u0391\u0392\u0393\u0394\u0395\\auto:abc\\binary:abc\\\\uri:backslashes_should_be_doubled\\\\000555:test";
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> 
>   // Using HanXinExtCodetextBuilder for Extended mode (same codetext as in previous example)
>   //create codetext
>   HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>   codeTextBuilder.addGB18030TwoByte("\u6f04");
>   codeTextBuilder.addGB18030FourByte("\u3401");
>   codeTextBuilder.addCommonChineseRegionOne("\u5168");
>   codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>   codeTextBuilder.addNumeric("123");
>   codeTextBuilder.addText("qwe");
>   codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>   codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>   codeTextBuilder.addAuto("abc");
>   codeTextBuilder.addBinary("abc");
>   codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
> 
>   String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test";
> 
>   //generate codetext
>   String str = codeTextBuilder.getExtendedCodetext();
> 
>   //generate
>   BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.HanXin, str);
>   generator.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>   generator.save("test.bmp");
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AUTO](#AUTO) | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BINARY](#BINARY) | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [ECI](#ECI) | In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. |
| [EXTENDED](#EXTENDED) | Uitgebreide modus staat combinaties van interne modi toe: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. |
| [UNICODE](#UNICODE) | Unicode‑modus biedt een manier om elke tekstgegevensreferentie naar UTF‑8‑codering/tekenset in Han Xin Code weer te geven. |
| [URI](#URI) | URI‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI)-referentie volgens RFC 3986 zijn. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final HanXinEncodeMode AUTO
```


In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden gecodeerd met GB18030‑codering volgens de HanXin-barcode‑specificatie.

### BINARY {#BINARY}
```
public static final HanXinEncodeMode BINARY
```


In Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid.

### ECI {#ECI}
```
public static final HanXinEncodeMode ECI
```


In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (vóór 2006) scanners deze modus mogelijk niet ondersteunen.

### EXTENDED {#EXTENDED}
```
public static final HanXinEncodeMode EXTENDED
```


Uitgebreide modus staat combinaties van interne modi toe: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One, Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte. Codetext kan handmatig worden opgebouwd met prefixes en dubbele backslashes, bijv.: @"\\auto:abc\\000009:\\u0391\\u0392\\u0393\\u0394\\u0395\\auto:ab\\\\c" of met de HanXinExtCodetextBuilder. Als de codetext een ECI-fragment bevat, mogen daarna alleen de volgende modi in die codetext voorkomen na het ECI‑fragment: Auto, Binary, Text, Numeric, URI, ECI.

### UNICODE {#UNICODE}
```
public static final HanXinEncodeMode UNICODE
```


Unicode‑modus biedt een manier om elke tekstgegevensreferentie naar UTF‑8‑codering/tekenset in Han Xin Code weer te geven.

### URI {#URI}
```
public static final HanXinEncodeMode URI
```


URI‑modus geeft aan dat de gegevens die in Han Xin Code worden weergegeven een Uniform Resource Identifier (URI)-referentie volgens RFC 3986 zijn.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static HanXinEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[HanXinEncodeMode](../../com.aspose.barcode.generation/hanxinencodemode)
### values() {#values--}
```
public static HanXinEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.HanXinEncodeMode[]
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

