---
title: Quadrangle
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: Almacena un conjunto de cuatro Points que representan una región Quadrangle.
type: docs
weight: 43
url: /es/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Almacena un conjunto de cuatro Point que representan una región Quadrangle
## Constructors

| Constructor | Descripción |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Inicializa una nueva instancia de la estructura  Quadrangle  con los puntos descriptivos. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EMPTY](#EMPTY) | Representa una clase  Quadrangle  con sus propiedades sin inicializar. |
## Methods

| Method | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Determina si el  Point  especificado está contenido dentro de esta clase  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Determina si el  Rectangle  especificado está contenido o intersecta esta clase  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determina si el  Quadrangle  especificado está contenido o intersecta esta clase  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Determina si el punto especificado está contenido dentro de esta clase  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor  Quadrangle  especificado. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crea un  Rectangle  que delimita este  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Obtiene la esquina superior izquierda del Point de la región del Quadrangle |
| [getRightBottom()](#getRightBottom--) | Obtiene la esquina inferior derecha del Point de la región del Quadrangle |
| [getRightTop()](#getRightTop--) | Obtiene la esquina superior derecha del Point de la región del Quadrangle |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta instancia. |
| [isEmpty()](#isEmpty--) | Comprueba si todos los Point de este Quadrangle tienen valores cero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Obtiene la esquina superior izquierda del Point de la región del Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Obtiene la esquina inferior derecha del Point de la región del Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Obtiene la esquina superior derecha del Point de la región del Quadrangle |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este Quadrangle. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Inicializa una nueva instancia de la estructura  Quadrangle  con los puntos descriptivos.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| leftTop | android.graphics.Point | Un Point que representa la esquina superior izquierda del Quadrangle. |
| rightTop | android.graphics.Point | Un Point que representa la esquina superior derecha del Quadrangle. |
| rightBottom | android.graphics.Point | Un Point que representa la esquina inferior derecha del Quadrangle. |
| leftBottom | android.graphics.Point | Un Point que representa la esquina inferior izquierda del Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Representa una clase  Quadrangle  con sus propiedades sin inicializar.

Valor: Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


Determina si el  Point  especificado está contenido dentro de esta clase  Quadrangle .

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| pt | android.graphics.Point | El Point a probar. |

**Returns:**
boolean - Devuelve **true** si el Point está contenido dentro de esta clase Quadrangle; de lo contrario, **false**.
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Determina si el  Rectangle  especificado está contenido o intersecta esta clase  Quadrangle .

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| rect | android.graphics.Rect | El Rectangle a probar. |

**Returns:**
boolean - Devuelve **true** si el Rectangle está contenido o intersecta esta clase Quadrangle; de lo contrario, **false**.
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determina si el  Quadrangle  especificado está contenido o intersecta esta clase  Quadrangle .

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | El Quadrangle a probar. |

**Returns:**
boolean - Devuelve **true** si el Quadrangle está contenido o intersecta esta clase Quadrangle; de lo contrario, **false**.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina si el punto especificado está contenido dentro de esta clase  Quadrangle .

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| x | int | La coordenada x del punto. |
| y | int | La coordenada y del punto. |

**Returns:**
boolean - Devuelve **true** si el punto está contenido dentro de esta clase Quadrangle; de lo contrario, **false**.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor  Quadrangle  especificado.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un valor Quadrangle para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Crea un  Rectangle  que delimita este  Quadrangle

**Returns:**
android.graphics.Rect - devuelve el Rectangle que delimita este Quadrangle.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle

Valor: Un punto Point de la esquina inferior izquierda de la región Quadrangle.

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Obtiene la esquina superior izquierda del Point de la región del Quadrangle

Valor: Un punto Point de la esquina superior izquierda de la región Quadrangle.

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Obtiene la esquina inferior derecha del Point de la región del Quadrangle

Valor: Un punto Point de la esquina inferior derecha de la región Quadrangle.

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Obtiene la esquina superior derecha del Point de la región del Quadrangle

Valor: Un punto Point de la esquina superior derecha de la región Quadrangle.

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Comprueba si todos los Point de este Quadrangle tienen valores cero.

Valor: Devuelve **true** si todos los Point de este Quadrangle tienen valores cero; de lo contrario, **false**.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle

Valor: Un punto Point de la esquina inferior izquierda de la región Quadrangle.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Obtiene la esquina superior izquierda del Point de la región del Quadrangle

Valor: Un punto Point de la esquina superior izquierda de la región Quadrangle.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Obtiene la esquina inferior derecha del Point de la región del Quadrangle

Valor: Un punto Point de la esquina inferior derecha de la región Quadrangle.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Obtiene la esquina superior derecha del Point de la región del Quadrangle

Valor: Un punto Point de la esquina superior derecha de la región Quadrangle.

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| valor | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este Quadrangle.

**Returns:**
java.lang.String - Una cadena que representa este Quadrangle.
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

