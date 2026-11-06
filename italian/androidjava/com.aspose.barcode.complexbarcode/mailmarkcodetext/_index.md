---
title: "MailmarkCodetext"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
description: "Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati."
type: docs
weight: 24
url: /it/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

Classe per la codifica e la decodifica del testo incorporato nel codice Royal Mailmark a 4 stati.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | Inizializza una nuova istanza della classe  MailmarkCodetext . |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisci il codetext dai dati Mailmark. |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | Il PC e il DP devono rispettare un formato PAF. |
| [getFormat()](#getFormat--) | "0" \\u2013 Null o Test "1" \\u2013 Letter "2" \\u2013 Large Letter |
| [getItemID()](#getItemID--) | Il valore massimo è 99999999. |
| [getSupplychainID()](#getSupplychainID--) | I valori massimi sono 99 per il Barcode C e 999999 per il Barcode L. |
| [getVersionID()](#getVersionID--) | Attualmente "1" \\u2013 Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza i dati Mailmark dal codetext costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | Il PC e il DP devono rispettare un formato PAF. |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 Null o Test "1" \\u2013 Letter "2" \\u2013 Large Letter |
| [setItemID(int value)](#setItemID-int-) | Il valore massimo è 99999999. |
| [setSupplychainID(int value)](#setSupplychainID-int-) | I valori massimi sono 99 per il Barcode C e 999999 per il Barcode L. |
| [setVersionID(int value)](#setVersionID-int-) | Attualmente "1" \\u2013 Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


Inizializza una nuova istanza della classe  MailmarkCodetext .

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
public BaseEncodeType getBarcodeType()
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
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Costruisci il codetext dai dati Mailmark.

**Returns:**
java.lang.String - Codetext costruito
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota le 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna.

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 Null o Test "1" \\u2013 Letter "2" \\u2013 Large Letter

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


Il valore massimo è 99999999.

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


I valori massimi sono 99 per il Barcode C e 999999 per il Barcode L.

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


Attualmente "1" \\u2013 Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


Inizializza i dati Mailmark dal codetext costruito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| constructedCodetext | java.lang.String | Codetext costruito. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota le 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 Null o Test "1" \\u2013 Letter "2" \\u2013 Large Letter

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


Il valore massimo è 99999999.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


I valori massimi sono 99 per il Barcode C e 999999 per il Barcode L.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


Attualmente "1" \\u2013 Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro)

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

