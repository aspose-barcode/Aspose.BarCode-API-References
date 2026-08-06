---
title: AztecEncodeMode
second_title: Aspose.BarCode for Android via Java API-referens
description: Kodningsläge för Aztec-streckkoder.
type: docs
weight: 73
url: /sv/androidjava/com.aspose.barcode.generation/aztecencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecEncodeMode extends Enum<AztecEncodeMode>
```

Kodningsläge för Aztec-streckkoder.

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [AUTO](#AUTO) | I Auto‑läge kodas CodeText med maximal datakomprimering. |
| [BINARY](#BINARY) | I Binärt läge kodas CodeText med maximal datakomprimering. |
| [BYTES](#BYTES) | Koda kodtext som vanliga byte. |
| [ECI](#ECI) | I ECI-läge kodas hela meddelandet om igen i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
## Methods

| Method | Beskrivning |
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


I Auto-läge kodas CodeText med maximal datakomprimering. Unicode-tecken kodas om i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. Om ett tecken hittas som inte stöds av den valda ECI-kodningen kastas ett undantag.

### BINARY {#BINARY}
```
public static final AztecEncodeMode BINARY
```


I Binärt läge kodas CodeText med maximal datakomprimering. Om ett Unicode-tecken hittas kastas ett undantag.

### BYTES {#BYTES}
```
public static final AztecEncodeMode BYTES
```


Koda kodtext som vanliga byte. Om den upptäcker någon Unicode‑tecken, kodas tecknet som två byte, lägre byte först.

### ECI {#ECI}
```
public static final AztecEncodeMode ECI
```


I ECI-läge kodas hela meddelandet om igen i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. Om ett tecken hittas som inte stöds av den valda ECI-kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge.

### EXTENDED {#EXTENDED}
```
public static final AztecEncodeMode EXTENDED
```


Utökat läge som stöder flera ECI‑lägen.

Det är bättre att använda AztecExtCodetextBuilder för generering av utökad kodtext.

Använd egenskapen Display2DText för att ange synlig text genom att ta bort styrtecken.

ECI-identifikatorer anges som ett enkelt snedstreck och sexsiffrig identifierare "\\000026" - UTF8 ECI-identifikator

Alla Unicode-tecken efter ECI-identifikatorn kodas automatiskt till rätt teckenuppsättning.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final AztecEncodeMode EXTENDED_CODETEXT
```


Utökat läge som stöder flera ECI‑lägen.

Det är bättre att använda AztecExtCodetextBuilder för generering av utökad kodtext.

Använd egenskapen Display2DText för att ange synlig text genom att ta bort styrtecken.

ECI-identifikatorer anges som ett enkelt snedstreck och sexsiffrig identifierare "\\000026" - UTF8 ECI-identifikator

Alla Unicode-tecken efter ECI-identifikatorn kodas automatiskt till rätt teckenuppsättning.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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

