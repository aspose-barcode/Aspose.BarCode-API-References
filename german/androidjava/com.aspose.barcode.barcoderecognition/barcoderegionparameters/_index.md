---
title: BarCodeRegionParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Stellt den Bereich der erkannten Barcodes und den Barcode-Winkel dar
type: docs
weight: 17
url: /de/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Stellt den Bereich des erkannten Barcodes und den Barcode-Winkel dar

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters-Wert entspricht. |
| [getAngle()](#getAngle--) | Gibt den Winkel des Barcodes zurück (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Liefert das Point-Array, das den Barcode-Bereich begrenzt |
| [getQuadrangle()](#getQuadrangle--) | Liefert das Aspose.BarCode.BarCodeRecognition.Quadrangle, das den Barcode-Bereich begrenzt |
| [getRectangle()](#getRectangle--) | Liefert das System.Drawing.Rectangle, das den Barcode-Bereich begrenzt |
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


Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen BarCodeRegionParameters-Wert entspricht.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Ein System.Object-Wert zum Vergleich mit dieser Instanz. |

**Returns:**
boolean -  **true**  wenn obj denselben Wert wie diese Instanz hat; andernfalls **false**.
### getAngle() {#getAngle--}
```
public double getAngle()
```


Gibt den Winkel des Barcodes zurück (0-360).

Wert: Der Winkel für den Barcode (0-360).

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


Liefert das Point-Array, das den Barcode-Bereich begrenzt

Wert: Liefert das Point-Array, das den Barcode-Bereich begrenzt.

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Liefert das Aspose.BarCode.BarCodeRecognition.Quadrangle, das den Barcode-Bereich begrenzt

Wert: Liefert das Aspose.BarCode.BarCodeRecognition.Quadrangle, das den Barcode-Bereich begrenzt.

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Liefert das System.Drawing.Rectangle, das den Barcode-Bereich begrenzt

Wert: Liefert das System.Drawing.Rectangle, das den Barcode-Bereich begrenzt.

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese Instanz zurück.

**Returns:**
int - Ein 32-Bit vorzeichenbehafteter Ganzzahl-Hashcode.
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
java.lang.String - Eine Zeichenkette, die dieses BarCodeRegionParameters darstellt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

