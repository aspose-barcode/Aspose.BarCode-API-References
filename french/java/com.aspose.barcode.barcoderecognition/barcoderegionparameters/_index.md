---
title: "BarCodeRegionParameters"
second_title: "Référence API d'Aspose.BarCode pour Java"
description: "Représente la région des codes-barres reconnus et l'angle du code-barres"
type: docs
weight: 16
url: /fr/java/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Représente la région du code-barres reconnu et l'angle du code-barres

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
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de BarCodeRegionParameters. |
| [getAngle()](#getAngle--) | Obtient l'angle du code-barres (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Obtient le tableau de Point délimitant la région du code-barres |
| [getQuadrangle()](#getQuadrangle--) | Obtient le Quadrangle Aspose.BarCode.BarCodeRecognition délimitant la région du code-barres |
| [getRectangle()](#getRectangle--) | Obtient le Rectangle System.Drawing.Rectangle délimitant la région du code-barres |
| [hashCode()](#hashCode--) | Renvoie le code de hachage pour cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce BarCodeRegionParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de BarCodeRegionParameters.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Une valeur System.Object à comparer à cette instance. |

**Returns:**
booléen -  **true**  si obj a la même valeur que cette instance ; sinon,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Obtient l'angle du code-barres (0-360).

Valeur : L'angle du code-barres (0-360).

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


Obtient le tableau de Point délimitant la région du code-barres

Valeur : Renvoie le tableau de Point délimitant la région du code-barres

**Returns:**
java.awt.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Obtient le Quadrangle Aspose.BarCode.BarCodeRecognition délimitant la région du code-barres

Valeur : Renvoie le Quadrangle Aspose.BarCode.BarCodeRecognition délimitant la région du code-barres

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Obtient le Rectangle System.Drawing.Rectangle délimitant la région du code-barres

Valeur : Renvoie le Rectangle System.Drawing.Rectangle délimitant la région du code-barres

**Returns:**
java.awt.Rectangle
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage pour cette instance.

**Returns:**
int - Un code de hachage entier signé de 32 bits.
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


Renvoie une représentation sous forme de chaîne lisible par l'homme de ce BarCodeRegionParameters.

**Returns:**
java.lang.String - Une chaîne qui représente ce BarCodeRegionParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

