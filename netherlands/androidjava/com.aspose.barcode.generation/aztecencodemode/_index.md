---
title: AztecEncodeMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: Coderingsmodus voor Aztec-barcodes.
type: docs
weight: 73
url: /nl/androidjava/com.aspose.barcode.generation/aztecencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecEncodeMode extends Enum<AztecEncodeMode>
```

Coderingsmodus voor Aztec-barcodes.

--------------------

> ```
> String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setECIEncoding(ECIEncodings.UTF_8);
>  generator.save("test.bmp");
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>  //Extended mode
>  //create codetext
>  AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.EXTENDED);
>  generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>  generator.save("test.bmp");
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AUTO](#AUTO) | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BINARY](#BINARY) | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BYTES](#BYTES) | Codeer codetekst als platte bytes. |
| [ECI](#ECI) | In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
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
public static final AztecEncodeMode AUTO
```


In Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.

### BINARY {#BINARY}
```
public static final AztecEncodeMode BINARY
```


In Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid.

### BYTES {#BYTES}
```
public static final AztecEncodeMode BYTES
```


Codeer codetekst als platte bytes. Als er een Unicode‑teken wordt gedetecteerd, wordt het teken gecodeerd als twee bytes, eerst de lagere byte.

### ECI {#ECI}
```
public static final AztecEncodeMode ECI
```


In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (vóór 2006) scanners deze modus mogelijk niet ondersteunen.

### EXTENDED {#EXTENDED}
```
public static final AztecEncodeMode EXTENDED
```


Uitgebreide modus die meerdere ECI‑modi ondersteunt.

Het is beter om AztecExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst.

Gebruik de Display2DText‑eigenschap om zichtbare tekst in te stellen door beheer‑tekens te verwijderen.

ECI‑identificaties worden ingesteld als een enkele slash en een zescijferige identifier "\\000026" - UTF8 ECI‑identifier

Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final AztecEncodeMode EXTENDED_CODETEXT
```


Uitgebreide modus die meerdere ECI‑modi ondersteunt.

Het is beter om AztecExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst.

Gebruik de Display2DText‑eigenschap om zichtbare tekst in te stellen door beheer‑tekens te verwijderen.

ECI‑identificaties worden ingesteld als een enkele slash en een zescijferige identifier "\\000026" - UTF8 ECI‑identifier

Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset.

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
public static AztecEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
### values() {#values--}
```
public static AztecEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecEncodeMode[]
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

