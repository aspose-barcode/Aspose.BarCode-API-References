---
title: BarCodeConfidence
second_title: Aspose.BarCode per Android via Java API Reference
description: Contiene il livello di fiducia del riconoscimento
type: docs
weight: 13
url: /it/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Contiene il livello di fiducia del riconoscimento

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## Campi

| Campo | Descrizione |
| --- | --- |
| [MODERATE](#MODERATE) | Fiducia di riconoscimento del codice a barre (principalmente codici a barre 1D) con checksum debole o anche senza di esso. |
| [NONE](#NONE) | Fiducia di riconoscimento in cui il testo del codice non è stato riconosciuto correttamente o il codice a barre è stato rilevato come possibile fakeBarCodeExtendedParameters |
| [STRONG](#STRONG) | Fiducia di riconoscimento confermata con codici BCH come Reed\\u2013Solomon. |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


Fiducia di riconoscimento del codice a barre (principalmente codici a barre 1D) con checksum debole o anche senza di esso. Potrebbe contenere alcuni errori di riconoscimento nel testo del codice o addirittura riconoscimenti falsi se è bassa.

### NONE {#NONE}
```
public static final int NONE
```


Fiducia di riconoscimento in cui il testo del codice non è stato riconosciuto correttamente o il codice a barre è stato rilevato come possibile fakeBarCodeExtendedParameters

### STRONG {#STRONG}
```
public static final int STRONG
```


Fiducia di riconoscimento confermata con codici BCH come Reed\\u2013Solomon. Non devono esserci errori nel testo del codice letto o riconoscimenti falsi

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

