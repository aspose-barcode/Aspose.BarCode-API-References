---
title: "BarCodeConfidence"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Contiene il livello di fiducia del riconoscimento"
type: docs
weight: 46
url: /it/java/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BarCodeConfidence extends Enum<BarCodeConfidence>
```

Contiene il livello di fiducia del riconoscimento

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
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
| [MODERATE](#MODERATE) | Affidabilità del riconoscimento del codice a barre (principalmente codici a barre 1D) con checksum debole o anche senza di esso. |
| [NONE](#NONE) | Affidabilità del riconoscimento del codice a barre dove il testo del codice non è stato riconosciuto correttamente o il codice a barre è stato rilevato come possibile fakeBarCodeExtendedParameters |
| [STRONG](#STRONG) | Affidabilità del riconoscimento confermata con codici BCH come Reed\u2013Solomon. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromValue(int value)](#fromValue-int-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final BarCodeConfidence MODERATE
```


Affidabilità del riconoscimento del codice a barre (principalmente codici a barre 1D) con checksum debole o anche senza di esso. Potrebbe contenere alcune errate interpretazioni del testo del codice o anche riconoscimenti falsi se è bassa.

### NONE {#NONE}
```
public static final BarCodeConfidence NONE
```


Affidabilità del riconoscimento del codice a barre dove il testo del codice non è stato riconosciuto correttamente o il codice a barre è stato rilevato come possibile fakeBarCodeExtendedParameters

### STRONG {#STRONG}
```
public static final BarCodeConfidence STRONG
```


Affidabilità del riconoscimento confermata con codici BCH come Reed\u2013Solomon. Non devono esserci errori nel testo del codice letto o riconoscimenti falsi.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromValue(int value) {#fromValue-int-}
```
public static BarCodeConfidence fromValue(int value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static BarCodeConfidence valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### values() {#values--}
```
public static BarCodeConfidence[] values()
```




**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeConfidence[]
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

