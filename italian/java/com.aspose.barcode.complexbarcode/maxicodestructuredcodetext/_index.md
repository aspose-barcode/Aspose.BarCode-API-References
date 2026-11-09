---
title: "MaxiCodeStructuredCodetext"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3."
type: docs
weight: 31
url: /it/java/com.aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public abstract class MaxiCodeStructuredCodetext extends MaxiCodeCodetext
```

Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode per le modalità 2 e 3. Questo esempio mostra come decodificare il codetext MaxiCode grezzo in un'istanza di MaxiCodeStructuredCodetext.

```
BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.MAXI_CODE);
  for (BarCodeResult result : reader.readBarCodes())
  {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
      if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
      {
          MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
          System.out.println("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
          System.out.println("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
          System.out.println("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
      }
  }
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MaxiCodeStructuredCodetext()](#MaxiCodeStructuredCodetext--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext). |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisce il testo del codice. |
| [getCountryCode()](#getCountryCode--) | Identifica il codice paese a 3 cifre. |
| [getECIEncoding()](#getECIEncoding--) | Ottiene la codifica ECI. |
| [getEncodeMode()](#getEncodeMode--) | Ottiene una modalità di codifica MaxiCode. |
| [getMode()](#getMode--) | Ottiene la modalità MaxiCode. |
| [getPostalCode()](#getPostalCode--) | Identifica il codice postale. |
| [getSecondMessage()](#getSecondMessage--) | Identifica il secondo messaggio del codice a barre. |
| [getServiceCategory()](#getServiceCategory--) | Identifica la categoria di servizio a 3 cifre. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza l'istanza dal testo del codice costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCountryCode(int value)](#setCountryCode-int-) | Identifica il codice paese a 3 cifre. |
| [setECIEncoding(int value)](#setECIEncoding-int-) | Imposta la codifica ECI. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | Imposta una modalità di codifica MaxiCode. |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) |  |
| [setSecondMessage(MaxiCodeSecondMessage value)](#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-) | Identifica il secondo messaggio del codice a barre. |
| [setServiceCategory(int value)](#setServiceCategory-int-) | Identifica la categoria di servizio a 3 cifre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStructuredCodetext() {#MaxiCodeStructuredCodetext--}
```
public MaxiCodeStructuredCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore specificato [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore [MaxiCodeStructuredCodetext](../../com.aspose.barcode.complexbarcode/maxicodestructuredcodetext) da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
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
### getCountryCode() {#getCountryCode--}
```
public final int getCountryCode()
```


Identifica il codice paese a 3 cifre.

**Returns:**
int
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
### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


Identifica il codice postale. Deve essere di 9 cifre nella modalità 2 o di 6 simboli alfanumerici nella modalità 3.

**Returns:**
java.lang.String
### getSecondMessage() {#getSecondMessage--}
```
public final MaxiCodeSecondMessage getSecondMessage()
```


Identifica il secondo messaggio del codice a barre.

**Returns:**
[MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage)
### getServiceCategory() {#getServiceCategory--}
```
public final int getServiceCategory()
```


Identifica la categoria di servizio a 3 cifre.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
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




### setCountryCode(int value) {#setCountryCode-int-}
```
public final void setCountryCode(int value)
```


Identifica il codice paese a 3 cifre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public abstract void setPostalCode(String value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setSecondMessage(MaxiCodeSecondMessage value) {#setSecondMessage-com.aspose.barcode.complexbarcode.MaxiCodeSecondMessage-}
```
public final void setSecondMessage(MaxiCodeSecondMessage value)
```


Identifica il secondo messaggio del codice a barre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MaxiCodeSecondMessage](../../com.aspose.barcode.complexbarcode/maxicodesecondmessage) |  |

### setServiceCategory(int value) {#setServiceCategory-int-}
```
public final void setServiceCategory(int value)
```


Identifica la categoria di servizio a 3 cifre.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

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

