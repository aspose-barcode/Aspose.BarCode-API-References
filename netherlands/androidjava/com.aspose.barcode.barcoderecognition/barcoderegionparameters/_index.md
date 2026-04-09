---
title: BarCodeRegionParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Stelt de regio van de herkende barcodes en de barcode‑hoek voor
type: docs
weight: 17
url: /nl/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Stelt de regio en hoek van de herkende barcode voor

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

| Method | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeRegionParameters‑waarde. |
| [getAngle()](#getAngle--) | Haalt de hoek van de barcode op (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Haalt  de array met punten op die de barcode-regio begrenzen |
| [getQuadrangle()](#getQuadrangle--) | Haalt  Aspose.BarCode.BarCodeRecognition.Quadrangle  die de barcode-regio begrenst |
| [getRectangle()](#getRectangle--) | Haalt  System.Drawing.Rectangle  die de barcode-regio begrenst |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  BarCodeRegionParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven BarCodeRegionParameters‑waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Een System.Object-waarde om te vergelijken met deze instantie. |

**Returns:**
boolean -  **true**  als obj dezelfde waarde heeft als deze instantie; anders,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Haalt de hoek van de barcode op (0-360).

Waarde: De hoek voor de barcode (0-360).

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


Haalt  de array met punten op die de barcode-regio begrenzen

Waarde: Retourneert  de array met punten die de barcode-regio begrenzen

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Haalt  Aspose.BarCode.BarCodeRecognition.Quadrangle  die de barcode-regio begrenst

Waarde: Retourneert  Aspose.BarCode.BarCodeRecognition.Quadrangle  die de barcode-regio begrenst

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Haalt  System.Drawing.Rectangle  die de barcode-regio begrenst

Waarde: Retourneert  System.Drawing.Rectangle  die de barcode-regio begrenst

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze instantie.

**Returns:**
int - Een 32-bits ondertekend geheel getal hashcode.
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


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze  BarCodeRegionParameters .

**Returns:**
java.lang.String - Een tekenreeks die deze  BarCodeRegionParameters  vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

