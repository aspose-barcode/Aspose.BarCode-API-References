---
title: "ComplexBarcodeGenerator"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "ComplexBarcodeGenerator per codici a barre complessi backend, ad es."
type: docs
weight: 12
url: /it/java/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator per la generazione di immagini di codici a barre complessi backend (ad es. SwissQR).

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Crea un'istanza di ComplexBarcodeGenerator. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [dispose()](#dispose--) | Pulisci eventuali risorse in uso. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Genera l'immagine del codice a barre complesso con le impostazioni correnti. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Parametri di generazione. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
| [save(String filename)](#save-java.lang.String-) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Crea un'istanza di ComplexBarcodeGenerator.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Testo codice complesso |

### dispose() {#dispose--}
```
public void dispose()
```


Pulisci eventuali risorse in uso.

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
### generateBarCodeImage() {#generateBarCodeImage--}
```
public BufferedImage generateBarCodeImage()
```


Genera l'immagine del codice a barre complesso con le impostazioni correnti.

**Returns:**
java.awt.image.BufferedImage - Immagine del codice a barre. Vedi Bitmap.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Parametri di generazione.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
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




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.OutputStream | Flusso di output System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifica il formato file dell'immagine di output. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Percorso in cui salvare. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Percorso in cui salvare. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Specifica il formato file dell'immagine di output. |

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

