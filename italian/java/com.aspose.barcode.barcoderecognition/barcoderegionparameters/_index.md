---
title: "BarCodeRegionParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Rappresenta la regione dei codici a barre riconosciuti e l'angolo del codice a barre"
type: docs
weight: 16
url: /it/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Rappresenta la regione del codice a barre riconosciuto e l'angolo del codice a barre

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di  BarCodeRegionParameters . |
| [getAngle()](#getAngle--) | Ottiene l'angolo del codice a barre (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Ottiene l'array Point che delimita la regione del codice a barre |
| [getQuadrangle()](#getQuadrangle--) | Ottiene il Quadrangle di Aspose.BarCode.BarCodeRecognition che delimita la regione del codice a barre |
| [getRectangle()](#getRectangle--) | Ottiene il Rectangle di System.Drawing che delimita la regione del codice a barre |
| [hashCode()](#hashCode--) | Restituisce il codice hash per questa istanza. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo  BarCodeRegionParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Restituisce un valore che indica se questa istanza è uguale a un valore specificato di  BarCodeRegionParameters .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Un valore System.Object da confrontare con questa istanza. |

**Returns:**
boolean -  **true**  se obj ha lo stesso valore di questa istanza; altrimenti,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Ottiene l'angolo del codice a barre (0-360).

Valore: L'angolo per il codice a barre (0-360).

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Ottiene l'array Point che delimita la regione del codice a barre

Valore: Restituisce l'array Point che delimita la regione del codice a barre

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Ottiene il Quadrangle di Aspose.BarCode.BarCodeRecognition che delimita la regione del codice a barre

Valore: Restituisce il Quadrangle di Aspose.BarCode.BarCodeRecognition che delimita la regione del codice a barre

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Ottiene il Rectangle di System.Drawing che delimita la regione del codice a barre

Valore: Restituisce il Rectangle di System.Drawing che delimita la regione del codice a barre

**Returns:**
java.awt.Rectangle
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


Restituisce una rappresentazione stringa leggibile dall'uomo di questo  BarCodeRegionParameters .

**Returns:**
java.lang.String - Una stringa che rappresenta questo  BarCodeRegionParameters .
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

