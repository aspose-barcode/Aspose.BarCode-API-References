---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode för Java API-referens"
description: "Representerar det igenkända streckkodsområdet och streckkodsvinkeln"
type: docs
weight: 16
url: /sv/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Representerar den erkända streckkodens region och streckkodsvinkel

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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returnerar ett värde som indikerar om denna instans är lika med ett angivet BarCodeRegionParameters‑värde. |
| [getAngle()](#getAngle--) | Hämtar vinkeln på streckkoden (0‑360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Hämtar Point‑array som avgränsar streckkodsområdet |
| [getQuadrangle()](#getQuadrangle--) | Hämtar Aspose.BarCode.BarCodeRecognition.Quadrangle som avgränsar streckkodsområdet |
| [getRectangle()](#getRectangle--) | Hämtar System.Drawing.Rectangle som avgränsar streckkodsområdet |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för detta objekt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en människoläsbar strängrepresentation av detta BarCodeRegionParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returnerar ett värde som indikerar om denna instans är lika med ett angivet BarCodeRegionParameters‑värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett System.Object‑värde att jämföra med detta objekt. |

**Returns:**
boolesk -  **true**  om obj har samma värde som detta objekt; annars,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Hämtar vinkeln på streckkoden (0‑360).

Värde: Vinkeln för streckkoden (0‑360).

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


Hämtar Point‑array som avgränsar streckkodsområdet

Värde: Returnerar Point‑array som avgränsar streckkodsområdet

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Hämtar Aspose.BarCode.BarCodeRecognition.Quadrangle som avgränsar streckkodsområdet

Värde: Returnerar Aspose.BarCode.BarCodeRecognition.Quadrangle som avgränsar streckkodsområdet

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Hämtar System.Drawing.Rectangle som avgränsar streckkodsområdet

Värde: Returnerar System.Drawing.Rectangle som avgränsar streckkodsområdet

**Returns:**
java.awt.Rectangle
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för detta objekt.

**Returns:**
int - En 32‑bitars signerad heltals‑hashkod.
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


Returnerar en människoläsbar strängrepresentation av detta BarCodeRegionParameters.

**Returns:**
java.lang.String - En sträng som representerar detta BarCodeRegionParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

