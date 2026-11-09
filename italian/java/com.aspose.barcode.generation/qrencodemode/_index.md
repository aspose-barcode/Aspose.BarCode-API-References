---
title: "QREncodeMode"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Modalità di codifica per i codici a barre QR."
type: docs
weight: 100
url: /it/java/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

Modalità di codifica per i codici QR. Questi esempi mostrano come codificare e salvare un codice QR con formati di dati estesi.

```
{@code
 //This sample shows how to use ECI encoding and save a BarCode image.
 
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText("12345TEXT");
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
 generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
 generator.save("test.png");
 
 //This sample shows how to use FNC1 first position in Extended Mode.
 Extended Channel mode which supports FNC1 first position, FNC1 second position and multi ECI modes.
 It is better to use QrExtCodetextBuilder for extended codetext generation.
 Use Display2DText property to set visible text by removing managing characters.
 Encoding Principles:
 All symbols "\" must be doubled "\\" in the codetext.
 FNC1 in first position is set in codetext as "<FNC1>".
 FNC1 in second position is set in codetext as "<FNC1(value)>". The value must be a single character from a-z or A-Z, or a two-digit number from 00 to 99.
 Group Separator for FNC1 modes is set as 0x1D character ''.
 If you need to insert "<FNC1>" string into barcode write it as "<\FNC1>".
 ECI identifiers are set as single slash and six digits identifier, for example "\000026" for UTF8 ECI identifier.
 The default ECI mode is ISO/IEC 8859-1 ECI identifier "\000003". It does not need to be encoded at the beginning of the codetext.
 To switch from another ECI mode to the default ECI mode, use "\000003".
 All unicode characters after ECI identifier are automatically encoded into correct character codeset.
 QR compaction mode selectors are set as single slash and mode name: "\auto", "\num", "\alnum", "\byte", "\kanji".
 "\auto" sets automatic compaction mode, "\num" sets Numeric mode, "\alnum" sets AlphaNumeric mode, "\byte" sets Bytes mode, and "\kanji" sets Kanji mode.
 The default compaction mode is "\auto".
 Compaction mode selectors define the encoding mode for the following data until the next compaction mode selector or ECI identifier is found.
 If the data cannot be encoded in the selected compaction mode, an ArgumentException is thrown.
 This mode is not supported by MicroQR barcodes.
 
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");
 
 //This sample shows how to use FNC1 second position in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.GetExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.Extended);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.png");
 
 //This sample shows how to use multi ECI mode in Extended Mode.
 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
 textBuilder.addPlainCodetext"t\e\\st");
 textBuilder.addAlphaNumericCodetext("ASPOSE2001");
 textBuilder.addNumericCodetext(@"20012026");
 //generate barcode
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.setCodeText(textBuilder.getExtendedCodetext();
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text";
 generator.save("test.png");
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [AUTO](#AUTO) | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. |
| [BINARY](#BINARY) | In modalità Binaria, il CodeText è codificato con la massima compattezza dei dati. |
| [ECI](#ECI) | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. |
| [EXTENDED](#EXTENDED) | Modalità Canale Esteso che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. |
## Metodi

| Metodo | Descrizione |
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
### AUTO {#AUTO}
```
public static final QREncodeMode AUTO
```


In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. I caratteri Unicode vengono codificati in modalità kanji se possibile, oppure vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione.

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. Se viene trovato un carattere Unicode, viene generata un'eccezione.

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI. Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene sollevata un'eccezione. Si prega di notare che alcuni scanner vecchi (pre‑2006) potrebbero non supportare questa modalità. Questa modalità non è supportata dai codici MicroQR.

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


Modalità Canale Esteso che supporta la prima posizione FNC1, la seconda posizione FNC1 e modalità ECI multiple. È consigliabile utilizzare QrExtCodetextBuilder per la generazione di codetext esteso. Utilizzare la proprietà Display2DText per impostare il testo visibile rimuovendo i caratteri di gestione. Principi di codifica: tutti i simboli "\\" devono essere raddoppiati "\\\\" nel codetext. FNC1 nella prima posizione si imposta nel codetext come "<FNC1>". FNC1 nella seconda posizione si imposta nel codetext come "<FNC1(value)>": il valore deve essere un singolo carattere da a‑z o A‑Z, o un numero a due cifre da 00 a 99. Il separatore di gruppo per le modalità FNC1 è impostato come carattere 0x1D '\\u001d'. Se è necessario inserire la stringa "<FNC1>" nel codice a barre, scriverla come "<\\FNC1>". Gli identificatori ECI sono impostati come barra singola e identificatore a sei cifre, ad esempio "\\000026" per l'identificatore ECI UTF8. La modalità ECI predefinita è l'identificatore ECI ISO/IEC 8859-1 "\\000003". Non è necessario codificarla all'inizio del codetext. Per passare da un'altra modalità ECI a quella predefinita, usare "\\000003". Tutti i caratteri Unicode dopo l'identificatore ECI vengono codificati automaticamente nel set di caratteri corretto. I selettori di modalità di compattazione QR sono impostati come barra singola e nome della modalità: "\\auto", "\\num", "\\alnum", "\\byte", "\\kanji". "\\auto" imposta la modalità di compattazione automatica, "\\num" imposta la modalità Numerica, "\\alnum" imposta la modalità Alfanumerica, "\\byte" imposta la modalità Byte e "\\kanji" imposta la modalità Kanji. La modalità di compattazione predefinita è "\\auto". I selettori di modalità di compattazione definiscono la modalità di codifica per i dati seguenti fino a quando non viene trovato il prossimo selettore di modalità di compattazione o un identificatore ECI. Se i dati non possono essere codificati nella modalità di compattazione selezionata, viene sollevata un'ArgumentException. Questa modalità non è supportata dai codici MicroQR.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static QREncodeMode fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
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
| Parametro | Tipo | Descrizione |
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
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

