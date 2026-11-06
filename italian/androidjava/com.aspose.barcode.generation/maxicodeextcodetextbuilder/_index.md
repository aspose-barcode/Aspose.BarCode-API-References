---
title: "MaxiCodeExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Generatore di codetext esteso per i codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode. Usa la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione."
type: docs
weight: 54
url: /it/androidjava/com.aspose.barcode.generation/maxicodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class MaxiCodeExtCodetextBuilder extends ExtCodetextBuilder
```

Generatore di codetext esteso per codici a barre MaxiCode per la modalità ExtendedCodetext di MaxiCodeEncodeMode. Utilizzare la proprietà TwoDDisplayText di BarcodeGenerator per impostare il testo visibile rimuovendo i caratteri di gestione. Questo esempio mostra come utilizzare MaxiCodeExtCodetextBuilder in modalità estesa.

```
//create codetext
 MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
 textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
 textBuilder.addPlainCodetext("Plain text");

 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();

 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaxiCodeExtCodetextBuilder()](#MaxiCodeExtCodetextBuilder--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Aggiunge codetext con Identificatore di Canale Esteso |
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
### MaxiCodeExtCodetextBuilder() {#MaxiCodeExtCodetextBuilder--}
```
public MaxiCodeExtCodetextBuilder()
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

