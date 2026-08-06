---
title: BarCodeRegionParameters
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Representa la región de los códigos de barras reconocidos y el ángulo del código de barras
type: docs
weight: 17
url: /es/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Representa la región del código de barras reconocido y el ángulo del código de barras

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

| Method | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeRegionParameters. |
| [getAngle()](#getAngle--) | Obtiene el ángulo del código de barras (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Obtiene la matriz de Point que delimita la región del código de barras |
| [getQuadrangle()](#getQuadrangle--) | Obtiene el Aspose.BarCode.BarCodeRecognition.Quadrangle que delimita la región del código de barras |
| [getRectangle()](#getRectangle--) | Obtiene el System.Drawing.Rectangle que delimita la región del código de barras |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este BarCodeRegionParameters |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor especificado de BarCodeRegionParameters.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor System.Object para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Obtiene el ángulo del código de barras (0-360).

Valor: El ángulo para el código de barras (0-360).

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


Obtiene la matriz de Point que delimita la región del código de barras

Valor: Devuelve la matriz de Point que delimita la región del código de barras

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Obtiene el Aspose.BarCode.BarCodeRecognition.Quadrangle que delimita la región del código de barras

Valor: Devuelve el Aspose.BarCode.BarCodeRecognition.Quadrangle que delimita la región del código de barras

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Obtiene el System.Drawing.Rectangle que delimita la región del código de barras

Valor: Devuelve el System.Drawing.Rectangle que delimita la región del código de barras

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
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


Devuelve una representación de cadena legible por humanos de este BarCodeRegionParameters

**Returns:**
java.lang.String - Una cadena que representa este BarCodeRegionParameters
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

