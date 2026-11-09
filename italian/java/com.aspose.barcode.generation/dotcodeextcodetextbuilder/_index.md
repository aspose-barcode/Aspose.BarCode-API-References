---
title: "DotCodeExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: 
type: docs
weight: 33
url: /it/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generatore di codetext esteso per codici a barre 2D DotCode per la modalità ExtendedCodetext di DotCodeEncodeMode

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Aggiunge codetext con Identificatore di Canale Esteso |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | Aggiunge l'identificatore di formato FNC1 agli elementi di codetext esteso |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext esteso |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | Aggiunge il separatore di simboli FNC3 agli elementi di codetext esteso |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Aggiunge codetext semplice agli elementi di codetext esteso |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | Aggiunge la modalità di aggiunta strutturata agli elementi di codetext esteso |
| [clear()](#clear--) | Cancella gli elementi di codetext esteso |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genera codetext esteso dall'elenco di codetext esteso. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


Aggiunge codetext con Identificatore di Canale Esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ECIEncoding | int | Identificatore di Canale Esteso |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso con Identificatore di Canale Esteso |

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


Aggiunge l'identificatore di formato FNC1 agli elementi di codetext esteso

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


Aggiunge l'inizializzazione del lettore FNC3 agli elementi di codetext esteso

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


Aggiunge il separatore di simboli FNC3 agli elementi di codetext esteso

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Aggiunge codetext semplice agli elementi di codetext esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in unicode da aggiungere come elemento di Codetext esteso |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


Aggiunge la modalità di aggiunta strutturata agli elementi di codetext esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| barcodeId | int | ID del codice a barre |
| barcodesCount | int | Conteggio dei codici a barre |

### clear() {#clear--}
```
public void clear()
```


Cancella gli elementi di codetext esteso

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
### getExtendedCodetext() {#getExtendedCodetext--}
```
public String getExtendedCodetext()
```


Genera codetext esteso dall'elenco di codetext esteso.

**Returns:**
java.lang.String - Codetext esteso come stringa
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

