---
title: "DataMatrixEncodeMode"
second_title: "Aspose.BarCode för Java API-referens"
description: "DataMatrix‑kodares kodningsläge är som standard Auto"
type: docs
weight: 81
url: /sv/java/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix‑kodarens kodningsläge, standard är Auto.

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
| [ASCII](#ASCII) | Kodar ett alfanumeriskt eller två numeriska tecken per byte |
| [AUTO](#AUTO) | I Auto‑läge kodas CodeText med maximal datakomprimering. |
| [BASE_256](#BASE-256) | Koda 8‑bitsvärden |
| [BINARY](#BINARY) | I Binärt läge kodas CodeText med maximal datakomprimering. |
| [C40](#C40) | Använder C40‑kodning. |
| [ECI](#ECI) | I ECI‑läge kodas hela meddelandet om igen med den angivna ECIEncoding‑kodningen och en ECI‑identifierare infogas. |
| [EDIFACT](#EDIFACT) | Använder EDIFACT‑kodning. |
| [EXTENDED](#EXTENDED) | ExtendedCodetext‑läge möjliggör manuell växling av kodningsscheman och ECI‑kodningar i kodtext. |
| [TEXT](#TEXT) | Använder Text‑kodning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
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


Kodar ett alfanumeriskt eller två numeriska tecken per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


I Auto‑läge kodas CodeText med maximal datakomprimering. Unicode‑tecken kodas om med den angivna ECIEncoding‑kodningen och en ECI‑identifierare infogas. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Koda 8‑bitsvärden

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


I Binärt läge kodas CodeText med maximal datakomprimering. Om ett Unicode‑tecken hittas kastas ett undantag.

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Använder C40‑kodning. Kodar versala alfanumeriska tecken, gemena och specialtecken.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


I ECI‑läge kodas hela meddelandet om igen med den angivna ECIEncoding‑kodningen och en ECI‑identifierare infogas. Om ett tecken hittas som inte stöds av den valda ECI‑kodningen kastas ett undantag. Observera att vissa äldre (före 2006) skannrar kanske inte stödjer detta läge.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Använder EDIFACT‑kodning. Använder sex bitar per tecken, kodar siffror, versala bokstäver och många skiljetecken, men har ingen stöd för gemena bokstäver.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext‑läge möjliggör manuell växling av kodningsscheman och ECI‑kodningar i kodtext. Det är bättre att använda DataMatrixExtCodetextBuilder för generering av utökad kodtext. Använd egenskapen Display2DText för att ange synlig text och ta bort styrtecken. ECI‑identifierare anges som ett enkelt snedstreck och en sexsiffrig identifierare "\\000026" – UTF8 ECI‑identifierare. Alla Unicode‑tecken efter ECI‑identifieraren kodas automatiskt till rätt teckenuppsättning. Kodningsscheman anges i följande format: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Tillåtna kodningsscheman är: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Alla bakåtsnedstreck (\\) måste dubbleras i texten.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Använder Text‑kodning. Kodar gemena alfanumeriska tecken, versala och specialtecken.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static DataMatrixEncodeMode fromValue(int value)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
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
| Parameter | Typ | Beskrivning |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

