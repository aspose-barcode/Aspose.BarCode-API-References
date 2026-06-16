---
title: QREncodeMode
second_title: Aspose.BarCode per Android via Java API Reference
description: Modalità di codifica per i codici a barre QR.
type: docs
weight: 102
url: /it/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Modalità di codifica per i codici a barre QR.

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
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. |
| [BINARY](#BINARY) | In modalità Binaria, il CodeText è codificato con la massima compattezza dei dati. |
| [BYTES](#BYTES) | Codifica il testo del codice come byte semplici. |
| [ECI](#ECI) | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. |
| [ECI_ENCODING](#ECI-ENCODING) | Codifica il testo del codice con il valore impostato nella proprietà ECIEncoding. |
| [EXTENDED](#EXTENDED) | Modalità Extended Channel che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. È consigliabile utilizzare QrExtCodetextBuilder per la generazione estesa del codetext. Utilizzare la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Principi di codifica: tutti i simboli "\\" devono essere raddoppiati "\\\\" nel codetext. FNC1 nella prima posizione è impostato nel codetext come "<FNC1>". FNC1 nella seconda posizione è impostato nel codetext come "<FNC1(value)>". |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | Modalità Extended Channel che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. È consigliabile utilizzare QrExtCodetextBuilder per la generazione estesa del codetext. Utilizzare la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Principi di codifica: tutti i simboli "\\" devono essere raddoppiati "\\\\" nel codetext. FNC1 nella prima posizione è impostato nel codetext come "<FNC1>". FNC1 nella seconda posizione è impostato nel codetext come "<FNC1(value)>". |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | Codifica il codetext con codifica UTF8 con il primo carattere ByteOfMark. |
| [UTF_8_BOM](#UTF-8-BOM) | Codifica il codetext con codifica UTF8 con il primo carattere ByteOfMark. |
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
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode sono codificati in modalità kanji se possibile, oppure vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene sollevata un'eccezione.

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


Codifica il testo del codice come byte semplici. Se rileva un carattere Unicode, il carattere verrà codificato in due byte, con il byte meno significativo per primo.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. Questa modalità non è supportata dai codici a barre MicroQR.

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


Codifica il codetext con il valore impostato nella proprietà ECIEncoding. Potrebbero verificarsi problemi con alcuni scanner di codici a barre vecchi (pre 2006). Questa modalità non è supportata dai codici a barre MicroQR.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Modalità Extended Channel che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. È consigliabile utilizzare QrExtCodetextBuilder per la generazione estesa del codetext. Utilizzare la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Principi di codifica: tutti i simboli "\\" devono essere raddoppiati "\\\\" nel codetext. FNC1 nella prima posizione è impostato nel codetext come "<FNC1>". FNC1 nella seconda posizione è impostato nel codetext come "<FNC1(value)>". Il valore deve essere simboli singoli (a-z, A-Z) o cifre da 0 a 99. Il separatore di gruppo per le modalità FNC1 è impostato come carattere 0x1D '\\\\u001D'. Se è necessario inserire la stringa "<FNC1>" nel codice a barre, scriverla come "<\\FNC1>". Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre "\\000026" - identificatore ECI UTF8. Per disabilitare la modalità ECI corrente e convertire alla modalità predefinita JIS8, viene impostato l'identificatore ECI zero mode "\\000000". Tutti i caratteri Unicode dopo l'identificatore ECI sono automaticamente codificati nel set di caratteri corretto. Questa modalità non è supportata dai codici a barre MicroQR.

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


Modalità Extended Channel che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. È consigliabile utilizzare QrExtCodetextBuilder per la generazione estesa del codetext. Utilizzare la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Principi di codifica: tutti i simboli "\\" devono essere raddoppiati "\\\\" nel codetext. FNC1 nella prima posizione è impostato nel codetext come "<FNC1>". FNC1 nella seconda posizione è impostato nel codetext come "<FNC1(value)>". Il valore deve essere simboli singoli (a-z, A-Z) o cifre da 0 a 99. Il separatore di gruppo per le modalità FNC1 è impostato come carattere 0x1D '\\\\u001D'. Se è necessario inserire la stringa "<FNC1>" nel codice a barre, scriverla come "<\\FNC1>". Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre "\\000026" - identificatore ECI UTF8. Per disabilitare la modalità ECI corrente e convertire alla modalità predefinita JIS8, viene impostato l'identificatore ECI zero mode "\\000000". Tutti i caratteri Unicode dopo l'identificatore ECI sono automaticamente codificati nel set di caratteri corretto. Questa modalità non è supportata dai codici a barre MicroQR.

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


Codifica il codetext con codifica UTF8 con il primo carattere ByteOfMark. Potrebbero verificarsi problemi con alcuni scanner di codici a barre.

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


Codifica il codetext con codifica UTF8 con il primo carattere ByteOfMark.

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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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

