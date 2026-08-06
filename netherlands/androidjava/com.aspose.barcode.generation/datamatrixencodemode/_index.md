---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode for Android via Java API-referentie
description: DataMatrix-encoders coderingsmodus standaard op Auto
type: docs
weight: 83
url: /nl/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Coderingsmodus van de DataMatrix-encoder, standaard Auto

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ANSIX12](#ANSIX12) | Gebruikt ANSI X12-codering. |
| [ASCII](#ASCII) | Codeert één alfanumeriek of twee numerieke tekens per byte |
| [AUTO](#AUTO) | In de Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BASE_256](#BASE-256) | Codeer 8-bit-waarden |
| [BINARY](#BINARY) | In de Binaire-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. |
| [BYTES](#BYTES) | Codeer 8-bit-waarden |
| [C40](#C40) | Gebruikt C40-codering. |
| [ECI](#ECI) | In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. |
| [EDIFACT](#EDIFACT) | Gebruikt EDIFACT-codering. |
| [EXTENDED](#EXTENDED) | De ExtendedCodetext-modus maakt handmatig schakelen tussen encodatieschema's en ECI-coderingen in codetext mogelijk. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Gebruikt Tekst-codering. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Gebruikt ANSI X12-codering.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Codeert één alfanumeriek of twee numerieke tekens per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


In Auto-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Unicode‑tekens worden opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Codeer 8-bit-waarden

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


In Binary-modus wordt de CodeText gecodeerd met maximale gegevenscompactheid. Als er een Unicode‑teken wordt gevonden, wordt er een uitzondering gegooid.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Codeer 8-bit-waarden

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Gebruikt C40-codering. Codeert hoofdletter alfanumerieke, kleine letters en speciale tekens.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


In ECI-modus wordt het volledige bericht opnieuw gecodeerd in de door ECIEncoding gespecificeerde codering met invoeging van een ECI‑identificatie. Als er een teken wordt gevonden dat niet wordt ondersteund door de geselecteerde ECI‑codering, wordt er een uitzondering gegooid. Houd er rekening mee dat sommige oude (vóór 2006) scanners deze modus mogelijk niet ondersteunen.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers, hoofdlettertekens en veel interpunctietekens, maar ondersteunt geen kleine letters.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext-modus maakt handmatig schakelen tussen encodatieschema's en ECI-coderingen in codetext mogelijk. Het is beter om DataMatrixExtCodetextBuilder te gebruiken voor de generatie van uitgebreide codetext. Gebruik de Display2DText‑eigenschap om zichtbare tekst in te stellen door beheer‑tekens te verwijderen. ECI‑identificaties worden ingesteld als een enkele slash en een zescijferige identifier "\\000026" - UTF8 ECI‑identifier. Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset. Encodatieschema's worden ingesteld in het volgende formaat: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Toegestane encodatieschema's zijn: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Alle backslashes (\\) moeten in de tekst verdubbeld worden.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


De ExtendedCodetext-modus maakt handmatig schakelen tussen encodatieschema's en ECI-coderingen in codetext mogelijk.

Het is beter om DataMatrixExtCodetextBuilder te gebruiken voor de generatie van uitgebreide codetext.

Gebruik de Display2DText‑eigenschap om zichtbare tekst in te stellen door beheer‑tekens te verwijderen.

ECI‑identificaties worden ingesteld als een enkele slash en een zescijferige identifier "\\000026" - UTF8 ECI‑identifier

Alle Unicode‑tekens na de ECI‑identifier worden automatisch gecodeerd naar de juiste tekenset.

Encodatieschema's worden ingesteld in het volgende formaat: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Toegestane encodatieschema's zijn: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Alle backslashes (\\) moeten in de tekst verdubbeld worden.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Gebruikt Tekst-codering. Codeert kleine letters alfanumeriek, hoofdletters en speciale tekens.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

