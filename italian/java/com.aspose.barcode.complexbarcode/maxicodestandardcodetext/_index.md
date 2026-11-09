---
title: "MaxiCodeStandardCodetext"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6."
type: docs
weight: 29
url: /it/java/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

Classe per la codifica e decodifica del testo del codice MaxiCode per le modalità 4, 5 e 6.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore MaxiCodeStandardCodetext specificato. |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisce il testo del codice. |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMessage()](#getMessage--) | Ottiene il messaggio. |
| [getMode()](#getMode--) | Ottiene la modalità MaxiCode. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza l'istanza dal testo del codice costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Imposta una modalità di codifica MaxiCode. |
| [setMessage(String value)](#setMessage-java.lang.String-) | Imposta il messaggio. |
| [setMode(MaxiCodeMode mode)](#setMode-com.aspose.barcode.generation.MaxiCodeMode-) | Imposta la modalità MaxiCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore MaxiCodeStandardCodetext specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore MaxiCodeStandardCodetext da confrontare con questa istanza. |

**Returns:**
boolean - se obj ha lo stesso valore di questa istanza; altrimenti, **false**.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


Ottiene il tipo di codice a barre.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Costruisce il testo del codice.

**Returns:**
java.lang.String - Testo codificato costruito
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


Ottiene la codifica ECI. Utilizzata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Returns:**
int - codifica ECI.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMessage() {#getMessage--}
```
public String getMessage()
```


Ottiene il messaggio.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public MaxiCodeMode getMode()
```


Ottiene la modalità MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inizializza l'istanza dal testo del codice costruito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Testo codificato costruito. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


Imposta la codifica ECI. Utilizzata quando MaxiCodeEncodeMode è Auto. Valore predefinito: ISO-8859-1

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Codifica ECI. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | una modalità di codifica MaxiCode. |

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


Imposta il messaggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setMode(MaxiCodeMode mode) {#setMode-com.aspose.barcode.generation.MaxiCodeMode-}
```
public void setMode(MaxiCodeMode mode)
```


Imposta la modalità MaxiCode. Il codetext standard può essere usato solo con le modalità 4, 5 e 6.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | [MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) |  |

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

