---
title: "DataMatrixExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: 
type: docs
weight: 32
url: /it/androidjava/com.aspose.barcode.generation/datamatrixextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DataMatrixExtCodetextBuilder extends ExtCodetextBuilder
```

Generatore di codetext esteso per i codici a barre DataMatrix 2D per la modalità ExtendedCodetext di EncodeMode.

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder textBuilder = new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, EncodeMode.BYTES, "World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40, "ABCDE");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DataMatrixExtCodetextBuilder()](#DataMatrixExtCodetextBuilder--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)](#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Aggiunge il codetext con modalità di codifica definita agli elementi di codetext estesi |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Aggiunge codetext con Identificatore di Canale Esteso |
| [addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)](#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-) | Aggiunge il codetext con Identificatore di Canale Esteso con modalità di codifica definita |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | Aggiunge codetext semplice agli elementi di codetext esteso |
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
### DataMatrixExtCodetextBuilder() {#DataMatrixExtCodetextBuilder--}
```
public DataMatrixExtCodetextBuilder()
```


### addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext) {#addCodetextWithEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addCodetextWithEncodeMode(DataMatrixEncodeMode encodeMode, String codetext)
```


Aggiunge il codetext con modalità di codifica definita agli elementi di codetext estesi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Valore della modalità di codifica |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso |

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

### addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext) {#addECICodetextWithEncodeMode-int-com.aspose.barcode.generation.DataMatrixEncodeMode-java.lang.String-}
```
public final void addECICodetextWithEncodeMode(int ECIEncoding, DataMatrixEncodeMode encodeMode, String codetext)
```


Aggiunge il codetext con Identificatore di Canale Esteso con modalità di codifica definita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ECIEncoding | int | Identificatore di Canale Esteso |
| encodeMode | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Valore della modalità di codifica |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso con Identificatore di Canale Esteso e modalità di codifica definita |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


Aggiunge codetext semplice agli elementi di codetext esteso

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| codetext | java.lang.String | Codetext in Unicode da aggiungere come elemento di codetext esteso |

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
java.lang.String - Codetext esteso come stringa.
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
public final void wait(long arg0)
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

