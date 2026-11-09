---
title: "SwissQRCodetext"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Classe per codificare e decodificare il testo incorporato nel codice SwissQR."
type: docs
weight: 36
url: /it/java/com.aspose.barcode.complexbarcode/swissqrcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class SwissQRCodetext implements IComplexCodetext
```

Classe per codificare e decodificare il testo incorporato nel codice SwissQR.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SwissQRCodetext(SwissQRBill bill)](#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-) | Crea un'istanza di SwissQRCodetext. |
| [SwissQRCodetext()](#SwissQRCodetext--) | Crea un'istanza di SwissQRCodetext. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | Ottiene il tipo di codice a barre. |
| [getBill()](#getBill--) | Dati della fattura SwissQR |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Costruisci il codetext dai dati della fattura SwissQR |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Inizializza la fattura con il codetext costruito. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SwissQRCodetext(SwissQRBill bill) {#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-}
```
public SwissQRCodetext(SwissQRBill bill)
```


Crea un'istanza di SwissQRCodetext.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bill | [SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill) | Dati della fattura SwissQR |

### SwissQRCodetext() {#SwissQRCodetext--}
```
public SwissQRCodetext()
```


Crea un'istanza di SwissQRCodetext.

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
### getBill() {#getBill--}
```
public SwissQRBill getBill()
```


Dati della fattura SwissQR

**Returns:**
[SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill)
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


Costruisci il codetext dai dati della fattura SwissQR

**Returns:**
java.lang.String - Testo codificato costruito
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


Inizializza la fattura con il codetext costruito.

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

