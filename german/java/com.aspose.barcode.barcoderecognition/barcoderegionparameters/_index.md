---
title: "BarCodeRegionParameters"
second_title: "Aspose.BarCode für Java API-Referenz"
description: "Stellt den erkannten Barcode‑Bereich und den Barcode‑Winkel dar"
type: docs
weight: 16
url: /de/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Stellt die Region des erkannten Barcodes und den Barcode‑Winkel dar.

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters‑Wert entspricht. |
| [getAngle()](#getAngle--) | Liest den Winkel des Barcodes (0‑360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Liest das Point‑Array, das den Barcode‑Bereich begrenzt |
| [getQuadrangle()](#getQuadrangle--) | Liest das Aspose.BarCode.BarCodeRecognition.Quadrangle, das den Barcode‑Bereich begrenzt |
| [getRectangle()](#getRectangle--) | Liest das System.Drawing.Rectangle, das den Barcode‑Bereich begrenzt |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese Instanz zurück. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeRegionParameters zurück. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters‑Wert entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object‑Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolesch -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Liest den Winkel des Barcodes (0‑360).

Wert: Der Winkel für den Barcode (0‑360).

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


Liest das Point‑Array, das den Barcode‑Bereich begrenzt

Wert: Gibt das Point‑Array zurück, das den Barcode‑Bereich begrenzt

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Liest das Aspose.BarCode.BarCodeRecognition.Quadrangle, das den Barcode‑Bereich begrenzt

Wert: Gibt das Aspose.BarCode.BarCodeRecognition.Quadrangle zurück, das den Barcode‑Bereich begrenzt

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Liest das System.Drawing.Rectangle, das den Barcode‑Bereich begrenzt

Wert: Gibt das System.Drawing.Rectangle zurück, das den Barcode‑Bereich begrenzt

**Returns:**
java.awt.Rectangle
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32‑Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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


Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses BarCodeRegionParameters zurück.

**Returns:**
java.lang.String – Eine Zeichenkette, die dieses BarCodeRegionParameters darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

