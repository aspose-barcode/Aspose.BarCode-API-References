---
title: "MaxiCodeCodetext"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode."
type: docs
weight: 25
url: /it/java/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode.

Questo esempio mostra come decodificare il codetext MaxiCode grezzo in un'istanza di MaxiCodeCodetext.

```

 BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisce il testo del codice. |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMode()](#getMode--) | Ottiene la modalità MaxiCode. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza l'istanza dal testo del codice costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Imposta una modalità di codifica MaxiCode. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


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
public abstract String getConstructedCodetext()
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
### getMode() {#getMode--}
```
public abstract MaxiCodeMode getMode()
```


Ottiene la modalità MaxiCode.

**Returns:**
[MaxiCodeMode](../../com.aspose.barcode.generation/maxicodemode) - MaxiCode mode
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
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

