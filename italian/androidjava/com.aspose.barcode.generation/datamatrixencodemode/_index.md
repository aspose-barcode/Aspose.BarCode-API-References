---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode per Android via Java API Reference
description: La modalità di codifica degli encoder DataMatrix è impostata di default su Auto
type: docs
weight: 83
url: /it/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

Modalità di codifica dell'encoder DataMatrix, predefinita su Auto

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [ANSIX12](#ANSIX12) | Utilizza la codifica ANSI X12. |
| [ASCII](#ASCII) | Codifica un carattere alfanumerico o due caratteri numerici per byte |
| [AUTO](#AUTO) | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. |
| [BASE_256](#BASE-256) | Codifica valori a 8 bit |
| [BINARY](#BINARY) | In modalità Binaria, il CodeText è codificato con la massima compattezza dei dati. |
| [BYTES](#BYTES) | Codifica valori a 8 bit |
| [C40](#C40) | Utilizza la codifica C40. |
| [ECI](#ECI) | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. |
| [EDIFACT](#EDIFACT) | Utilizza la codifica EDIFACT. |
| [EXTENDED](#EXTENDED) | La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica e le codifiche ECI nel codetext. |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | Utilizza la codifica Text. |
## Methods

| Method | Descrizione |
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


Utilizza la codifica ANSI X12.

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


Codifica un carattere alfanumerico o due caratteri numerici per byte

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione.

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


Codifica valori a 8 bit

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione.

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


Codifica valori a 8 bit

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


Utilizza la codifica C40. Codifica caratteri alfanumerici maiuscoli, minuscoli e caratteri speciali.

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre‑2006) potrebbero non supportare questa modalità.

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


Utilizza la codifica EDIFACT. Usa sei bit per carattere, codifica cifre, lettere maiuscole e molti segni di punteggiatura, ma non supporta le lettere minuscole.

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica e le codifiche ECI nel codetext. È consigliabile utilizzare DataMatrixExtCodetextBuilder per la generazione di codetext esteso. Utilizza la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre "\\000026" - identificatore ECI UTF8. Tutti i caratteri Unicode dopo l'identificatore ECI vengono codificati automaticamente nel set di caratteri corretto. Gli schemi di codifica sono impostati nel formato seguente: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text". Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto. Tutti i backslash (\\) devono essere raddoppiati nel testo.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


La modalità ExtendedCodetext consente di cambiare manualmente gli schemi di codifica e le codifiche ECI nel codetext.

È consigliabile utilizzare DataMatrixExtCodetextBuilder per la generazione di codetext esteso.

Utilizza la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione.

Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre "\\000026" - identificatore ECI UTF8

Tutti i caratteri Unicode dopo l'identificatore ECI vengono codificati automaticamente nel set di caratteri corretto.

Gli schemi di codifica sono impostati nel formato seguente: "\\Encodation\_scheme\_name:text\\Encodation\_scheme\_name:text".

Gli schemi di codifica consentiti sono: EDIFACT, ANSIX12, ASCII, C40, Text, Auto.

Tutti i backslash (\\) devono essere raddoppiati nel testo.

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


Utilizza la codifica Text. Codifica caratteri alfanumerici minuscoli, maiuscoli e caratteri speciali.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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

