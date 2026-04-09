---
title: QREncodeMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: Coderingsmodus voor QR-barcode.
type: docs
weight: 102
url: /nl/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Coderingsmodus voor QR-barcode.

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```

--------------------

> ```
> Example how to use FNC1 first position in Extended Mode
>   
>       QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>       textBuilder.addPlainCodetext("000%89%%0");
>       textBuilder.addFNC1GroupSeparator();
>       textBuilder.addPlainCodetext("12345<FNC1>");
>       //generate barcode
>       BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>       generator.setCodeText(textBuilder.getExtended());
>       generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>       generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>       generator.save("d:/test.png");
>  
>       *
>  This sample shows how to use FNC1 second position in Extended Mode.
>  
> 
>     //create codetext
>     QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>     textBuilder.addFNC1SecondPosition("12");
>     textBuilder.addPlainCodetext("TRUE3456");
>     //generate barcode
>     BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>     generator.setCodeText(textBuilder.getExtended());
>     generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>     generator.save("d:/test.png");
>     
> 
>     This sample shows how to use multi ECI mode in Extended Mode.
>     
> 
>    //create codetext
>    QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>    textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>    textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
>    textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
>    textBuilder.addPlainCodetext("t\e\\st");
>    //generate barcode
>    BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>    generator.setCodeText(textBuilder.getExtended());
>    generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>    generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>    generator.save("d:/test.png");
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [AUTO](#AUTO) | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BINARY](#BINARY) | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BYTES](#BYTES) | Codeer codetekst als platte bytes. |
| [ECI](#ECI) | In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. |
| [ECI_ENCODING](#ECI-ENCODING) | Codeer de codetekst met de waarde die is ingesteld in de eigenschap ECIEncoding. |
| [EXTENDED](#EXTENDED) | Uitgebreide kanaalmodus die FNC1 op de eerste positie, FNC1 op de tweede positie en meerdere ECI-modi ondersteunt. Het is beter om QrExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst. Gebruik de eigenschap Display2DText om zichtbare tekst in te stellen door beheerkarakters te verwijderen. Coderingprincipes: Alle symbolen "\\" moeten verdubbeld worden tot "\\\\" in de codetekst. FNC1 op de eerste positie wordt in de codetekst ingesteld als "<FNC1>". FNC1 op de tweede positie wordt in de codetekst ingesteld als "<FNC1(value)>". |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Uitgebreide kanaalmodus die FNC1 op de eerste positie, FNC1 op de tweede positie en meerdere ECI-modi ondersteunt. Het is beter om QrExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst. Gebruik de eigenschap Display2DText om zichtbare tekst in te stellen door beheerkarakters te verwijderen. Coderingprincipes: Alle symbolen "\\" moeten verdubbeld worden tot "\\\\" in de codetekst. FNC1 op de eerste positie wordt in de codetekst ingesteld als "<FNC1>". FNC1 op de tweede positie wordt in de codetekst ingesteld als "<FNC1(value)>". |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | Codeer de codetekst met UTF8-codering met het eerste ByteOfMark-teken. |
| [UTF_8_BOM](#UTF-8-BOM) | Codeer de codetekst met UTF8-codering met het eerste ByteOfMark-teken. |
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
public static final QREncodeMode AUTO
```


In de automatische modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden, indien mogelijk, gecodeerd in kanji‑modus, of ze worden opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificator. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


In Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid.

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


Codeer codetekst als platte bytes. Als er een Unicode‑teken wordt gedetecteerd, wordt het teken gecodeerd als twee bytes, eerst de lagere byte.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


In de ECI‑modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificator. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (voor 2006) scanners deze modus mogelijk niet ondersteunen. Deze modus wordt niet ondersteund door MicroQR‑barcodes.

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


Codeer de codetekst met de waarde die is ingesteld in de eigenschap ECIEncoding. Er kunnen problemen optreden met sommige oude (voor 2006) barcodescanners. Deze modus wordt niet ondersteund door MicroQR‑barcodes.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Uitgebreide kanaalmodus die FNC1 op de eerste positie, FNC1 op de tweede positie en meerdere ECI‑modi ondersteunt. Het is beter om QrExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst. Gebruik de eigenschap Display2DText om zichtbare tekst in te stellen door beheerkarakters te verwijderen. Coderingprincipes: Alle symbolen "\\" moeten verdubbeld worden tot "\\\\" in de codetekst. FNC1 op de eerste positie wordt in de codetekst ingesteld als "<FNC1>". FNC1 op de tweede positie wordt in de codetekst ingesteld als "<FNC1(value)>". De waarde moet een enkel symbool (a‑z, A‑Z) of cijfers van 0 tot 99 zijn. Groepsscheidingsteken voor FNC1‑modi wordt ingesteld als het teken 0x1D '\\\\u001D'. Als u de tekenreeks "<FNC1>" in de barcode wilt invoegen, schrijft u deze als "<\\FNC1>". ECI‑identificatoren worden ingesteld als een enkele slash gevolgd door een zescijferige identifier "\\000026" – UTF8‑ECI‑identifier. Om de huidige ECI‑modus uit te schakelen en terug te gaan naar de standaard JIS8‑null‑modus, wordt de ECI‑identifier "\\000000" ingesteld. Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset. Deze modus wordt niet ondersteund door MicroQR‑barcodes.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


Uitgebreide kanaalmodus die FNC1 op de eerste positie, FNC1 op de tweede positie en meerdere ECI‑modi ondersteunt. Het is beter om QrExtCodetextBuilder te gebruiken voor het genereren van uitgebreide codetekst. Gebruik de eigenschap Display2DText om zichtbare tekst in te stellen door beheerkarakters te verwijderen. Coderingprincipes: Alle symbolen "\\" moeten verdubbeld worden tot "\\\\" in de codetekst. FNC1 op de eerste positie wordt in de codetekst ingesteld als "<FNC1>". FNC1 op de tweede positie wordt in de codetekst ingesteld als "<FNC1(value)>". De waarde moet een enkel symbool (a‑z, A‑Z) of cijfers van 0 tot 99 zijn. Groepsscheidingsteken voor FNC1‑modi wordt ingesteld als het teken 0x1D '\\\\u001D'. Als u de tekenreeks "<FNC1>" in de barcode wilt invoegen, schrijft u deze als "<\\FNC1>". ECI‑identificatoren worden ingesteld als een enkele slash gevolgd door een zescijferige identifier "\\000026" – UTF8‑ECI‑identifier. Om de huidige ECI‑modus uit te schakelen en terug te gaan naar de standaard JIS8‑null‑modus, wordt de ECI‑identifier "\\000000" ingesteld. Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset. Deze modus wordt niet ondersteund door MicroQR‑barcodes.

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


Codeer de codetekst met UTF8‑codering met het eerste ByteOfMark‑teken. Er kunnen problemen optreden met sommige barcodescanners.

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


Codeer de codetekst met UTF8-codering met het eerste ByteOfMark-teken.

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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
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

