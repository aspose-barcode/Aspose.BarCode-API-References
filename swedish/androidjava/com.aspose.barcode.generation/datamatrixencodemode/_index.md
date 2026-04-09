---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode for Android via Java API-referens
description: DataMatrix‑kodare har kodningsläge som standard till Auto
type: docs
weight: 83
url: /sv/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix-kodares kodningsläge, standard är Auto

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ANSIX12](#ANSIX12) | Använder ANSI X12‑kodning. |
| [ASCII](#ASCII) | Kodar en alfanumerisk eller två numeriska tecken per byte |
| [AUTO](#AUTO) | I Auto‑läge kodas CodeText med maximal datakomprimering. |
| [BASE_256](#BASE-256) | Koda 8‑bitsvärden |
| [BINARY](#BINARY) | I Binärt läge kodas CodeText med maximal datakomprimering. |
| [BYTES](#BYTES) | Koda 8‑bitsvärden |
| [C40](#C40) | Använder C40‑kodning. |
| [ECI](#ECI) | I ECI-läge kodas hela meddelandet om igen i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. |
| [EDIFACT](#EDIFACT) | Använder EDIFACT-kodning. |
| [EXTENDED](#EXTENDED) | ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman och ECI-kodningar i kodtexten. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Använder Text-kodning. |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


Använder ANSI X12‑kodning.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Kodar en alfanumerisk eller två numeriska tecken per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


I Auto-läge kodas CodeText med maximal datakomprimering. Unicode-tecken kodas om i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. Om ett tecken hittas som inte stöds av den valda ECI-kodningen kastas ett undantag.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Koda 8‑bitsvärden

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


I Binärt läge kodas CodeText med maximal datakomprimering. Om ett Unicode-tecken hittas kastas ett undantag.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Koda 8‑bitsvärden

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Använder C40-kodning. Kodar versala alfanumeriska tecken, gemena och specialtecken.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


I ECI-läge kodas hela meddelandet om igen i den av ECIEncoding specificerade kodningen med införandet av en ECI-identifikator. Om ett tecken hittas som inte stöds av den valda ECI-kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Använder EDIFACT-kodning. Använder sex bitar per tecken, kodar siffror, versala bokstäver och många skiljetecken, men har ingen stöd för gemena bokstäver.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman och ECI-kodningar i kodtexten. Det är bättre att använda DataMatrixExtCodetextBuilder för generering av utökad kodtext. Använd egenskapen Display2DText för att ange synlig text genom att ta bort styrtecken. ECI-identifikatorer anges som ett enkelt snedstreck och sexsiffrig identifierare "\\000026" - UTF8 ECI-identifikator. Alla Unicode-tecken efter ECI-identifikatorn kodas automatiskt till rätt teckenuppsättning. Kodningsscheman anges i följande format: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Tillåtna kodningsscheman är: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Alla bakåtsnedstreck (\\) måste dubbleras i texten.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


ExtendedCodetext-läget tillåter att manuellt växla kodningsscheman och ECI-kodningar i kodtexten.

Det är bättre att använda DataMatrixExtCodetextBuilder för generering av utökad kodtext.

Använd egenskapen Display2DText för att ange synlig text genom att ta bort styrtecken.

ECI-identifikatorer anges som ett enkelt snedstreck och sexsiffrig identifierare "\\000026" - UTF8 ECI-identifikator

Alla Unicode-tecken efter ECI-identifikatorn kodas automatiskt till rätt teckenuppsättning.

Kodningsscheman anges i följande format: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Tillåtna kodningsscheman är: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Alla bakåtsnedstreck (\\) måste dubbleras i texten.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Använder Text-kodning. Kodar gemena alfanumeriska tecken, versala och specialtecken.

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

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

