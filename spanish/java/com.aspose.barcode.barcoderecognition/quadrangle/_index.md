---
title: "Quadrangle"
second_title: "Referencia de API de Aspose.BarCode para Java"
description: "Almacena un conjunto de cuatro Points que representan una región Quadrangle."
type: docs
weight: 39
url: /es/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Almacena un conjunto de cuatro  Point s que representan una  Quadrangle  región.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Inicializa una nueva instancia de la clase  Quadrangle  con los puntos descriptivos. |
## Campos

| Campo | Descripción |
| --- | --- |
| [EMPTY](#EMPTY) | Representa una clase  Quadrangle  con sus propiedades sin inicializar. |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Determina si el  Quadrangle  especificado está contenido o intersecta esta clase  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Determina si el punto especificado está contenido dentro de esta clase  Quadrangle . |
| [contains(Point pt)](#contains-java.awt.Point-) | Determina si el  Point  especificado está contenido dentro de esta clase  Quadrangle . |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Determina si el  Rectangle  especificado está contenido o intersecta esta clase  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Devuelve un valor que indica si esta instancia es igual a un valor  Quadrangle  especificado. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Crea un  Rectangle  que delimita este  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Obtiene el punto  Point  de la esquina superior izquierda de la región  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Obtiene el punto  Point  de la esquina inferior derecha de la región  Quadrangle |
| [getRightTop()](#getRightTop--) | Obtiene el punto  Point  de la esquina superior derecha de la región  Quadrangle |
| [hashCode()](#hashCode--) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isEmpty--) | Prueba si todos los  Point  de este  Quadrangle  tienen valores cero. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Obtiene el punto  Point  de la esquina superior izquierda de la región  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Obtiene el punto  Point  de la esquina inferior derecha de la región  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Obtiene el punto  Point  de la esquina superior derecha de la región  Quadrangle |
| [toString()](#toString--) | Devuelve una representación de cadena legible por humanos de este  Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Inicializa una nueva instancia de la clase  Quadrangle  con los puntos descriptivos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftTop | java.awt.Point | Un  Point  que representa la esquina superior izquierda del Quadrangle. |
| rightTop | java.awt.Point | Un  Point  que representa la esquina superior derecha del Quadrangle. |
| rightBottom | java.awt.Point | Un  Point  que representa la esquina inferior derecha del Quadrangle. |
| leftBottom | java.awt.Point | Un  Point  que representa la esquina inferior izquierda del Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Representa una clase  Quadrangle  con sus propiedades sin inicializar.

Valor:  Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Determina si el  Quadrangle  especificado está contenido o intersecta esta clase  Quadrangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | El  Quadrangle  a probar. |

**Returns:**
boolean - Devuelve  **true**  si  Quadrangle  está contenido o intersecta esta clase  Quadrangle ; de lo contrario,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Determina si el punto especificado está contenido dentro de esta clase  Quadrangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La coordenada del punto x. |
| y | int | La coordenada del punto y. |

**Returns:**
boolean - Devuelve  **true**  si el punto está contenido dentro de esta clase  Quadrangle ; de lo contrario,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Determina si el  Point  especificado está contenido dentro de esta clase  Quadrangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | java.awt.Point | El  Point  a probar. |

**Returns:**
boolean - Devuelve  **true**  si  Point  está contenido dentro de esta clase  Quadrangle ; de lo contrario,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Determina si el  Rectangle  especificado está contenido o intersecta esta clase  Quadrangle .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | java.awt.Rectangle | El  Rectangle  a probar. |

**Returns:**
boolean - Devuelve  **true**  si  Rectangle  está contenido o intersecta esta clase  Quadrangle ; de lo contrario,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Devuelve un valor que indica si esta instancia es igual a un valor  Quadrangle  especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Un  Quadrangle  valor para comparar con esta instancia. |

**Returns:**
boolean -  **true**  si obj tiene el mismo valor que esta instancia; de lo contrario,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Crea un  Rectangle  que delimita este  Quadrangle

**Returns:**
java.awt.Rectangle - devuelve el Rectangle que delimita este Quadrangle
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

Valor: Un punto de esquina inferior izquierda de la región Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Obtiene el punto  Point  de la esquina superior izquierda de la región  Quadrangle

Valor: Un punto de esquina superior izquierda de la región Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Obtiene el punto  Point  de la esquina inferior derecha de la región  Quadrangle

Valor: Un punto de esquina inferior derecha de la región Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Obtiene el punto  Point  de la esquina superior derecha de la región  Quadrangle

Valor: Un punto de esquina superior derecha de la región Quadrangle

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de esta instancia.

**Returns:**
int - Un código hash entero con signo de 32 bits.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Prueba si todos los  Point  de este  Quadrangle  tienen valores cero.

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




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Obtiene el punto  Point  de la esquina inferior izquierda de la región  Quadrangle

Valor: Un punto de esquina inferior izquierda de la región Quadrangle

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Obtiene el punto  Point  de la esquina superior izquierda de la región  Quadrangle

Valor: Un punto de esquina superior izquierda de la región Quadrangle

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Obtiene el punto  Point  de la esquina inferior derecha de la región  Quadrangle

Valor: Un punto de esquina inferior derecha de la región Quadrangle

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Obtiene el punto  Point  de la esquina superior derecha de la región  Quadrangle

Valor: Un punto de esquina superior derecha de la región Quadrangle

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Devuelve una representación de cadena legible por humanos de este  Quadrangle .

**Returns:**
java.lang.String - Una cadena que representa este Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

