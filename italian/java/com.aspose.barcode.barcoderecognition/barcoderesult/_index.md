---
title: "BarCodeResult"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Memorizza i dati del codice a barre riconosciuti come tipo SingleDecodeType stringa codetext BarCodeRegionParameters regione e altri parametri"
type: docs
weight: 17
url: /it/java/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Memorizza i dati del codice a barre riconosciuto come tipo SingleDecodeType, string codetext, BarCodeRegionParameters region e altri parametri

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Crea una copia della classe BarCodeResult. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone()](#deepClone--) | Crea una copia della classe BarCodeResult. |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore BarCodeResult specificato. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Ottiene i byte del codice codificati |
| [getCodeText()](#getCodeText--) | Ottiene il testo del codice |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Ottiene il testo del codice con codifica. |
| [getCodeType()](#getCodeType--) | Ottiene il tipo di codice a barre |
| [getCodeTypeName()](#getCodeTypeName--) | Ottiene il nome del tipo di codice a barre |
| [getConfidence()](#getConfidence--) | Ottiene il livello di fiducia del riconoscimento del codice a barre riconosciuto |
| [getExtended()](#getExtended--) | Ottiene i parametri estesi del codice a barre riconosciuto |
| [getReadingQuality()](#getReadingQuality--) | Ottiene la qualità di lettura. |
| [getRegion()](#getRegion--) | Ottiene la regione del codice a barre |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeResult. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Crea una copia della classe BarCodeResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Una copia dell'istanza BarCodeResult. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crea una copia della classe BarCodeResult.

**Returns:**
java.lang.Object - Restituisce una copia della classe BarCodeResult.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore BarCodeResult specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore BarCodeResult da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Ottiene i byte del codice codificati

Valore: I byte del codice del codice a barre

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Ottiene il testo del codice

Valore: Il testo del codice del codice a barre

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Ottiene il testo del codice con codifica.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| charset | java.nio.charset.Charset | La codifica per codetext. |

**Returns:**
java.lang.String - Una stringa contenente il testo del codice riconosciuto.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Ottiene il tipo di codice a barre

Valore: Le informazioni sul tipo del codice a barre riconosciuto

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Ottiene il nome del tipo di codice a barre

Valore: Il nome del tipo del codice a barre riconosciuto

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Ottiene il livello di fiducia del riconoscimento del codice a barre riconosciuto

Valore:  BarCodeConfidence.Strong  non presenta falsi o errori di riconoscimento,  BarCodeConfidence.Moderate  potrebbe a volte contenere falsi o testo del codice errato perché questo livello di confidenza per i codici a barre con checksum debole o anche senza,  BarCodeConfidence.None  ha sempre testo del codice errato e potrebbe essere riconoscimenti falsi

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Ottiene i parametri estesi del codice a barre riconosciuto

Valore: I parametri estesi del codice a barre riconosciuto

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Restituisce la qualità di lettura. Funziona per i codici a barre 1D e postali.

Valore: La percentuale di qualità di lettura

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Ottiene la regione del codice a barre

Valore: La regione del codice a barre riconosciuto

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per questa istanza.

**Returns:**
int - Un codice hash intero con segno a 32 bit.
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


Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeResult.

**Returns:**
java.lang.String - Una stringa che rappresenta questo  BarCodeResult .
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

