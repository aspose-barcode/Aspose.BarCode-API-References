---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Almacena un conjunto de cuatro Points que representan una región de cuadrilátero."
type: docs
weight: 850
url: /es/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Almacena un conjunto de cuatro Points que representan una región de cuadrilátero.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Inicializa una nueva instancia de la estructura Quadrangle con los puntos descriptivos.

| Parámetro | Descripción |
| --- | --- |
| leftTop | Un punto que representa la esquina superior izquierda del Quadrangle. |
| rightTop | Un punto que representa la esquina superior derecha del Quadrangle. |
| rightBottom | Un punto que representa la esquina inferior derecha del Quadrangle. |
| leftBottom | Un punto que representa la esquina inferior izquierda del Quadrangle. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [contains(pt)](#contains) | Determina si el Punto especificado está contenido dentro de esta estructura Quadrangle. |
| [containsPoint(x, y)](#containspoint) | Determina si el punto especificado está contenido dentro de esta estructura Quadrangle. |
| [containsQuadrangle(quad)](#containsquadrangle) | Determina si el Quadrangle especificado está contenido o intersecta esta estructura Quadrangle. |
| [containsRectangle(rect)](#containsrectangle) | Determina si el Rectángulo especificado está contenido o intersecta esta estructura Quadrangle. |
| [equals(other)](#equals) | Devuelve un valor que indica si esta instancia es igual a un valor Quadrangle especificado. |
| [getBoundingRectangle()](#getboundingrectangle) | Crea un Rectángulo que delimita este Quadrangle |
| [getLeftBottom()](#getleftbottom) | Obtiene el punto de la esquina inferior izquierda de la región QuadrangleValor: Un punto de la esquina inferior izquierda de la región Quadrangle |
| [getLeftTop()](#getlefttop) | Obtiene el punto de la esquina superior izquierda de la región QuadrangleValor: Un punto de la esquina superior izquierda de la región Quadrangle |
| [getRightBottom()](#getrightbottom) | Obtiene el punto de la esquina inferior derecha de la región QuadrangleValor: Un punto de la esquina inferior derecha de la región Quadrangle |
| [getRightTop()](#getrighttop) | Obtiene el punto de la esquina superior derecha de la región QuadrangleValor: Un punto de la esquina superior derecha de la región Quadrangle |
| [hashCode()](#hashcode) | Devuelve el código hash de esta instancia. |
| [isEmpty()](#isempty) | Prueba si todos los Points de este Quadrangle tienen valores cero.Valor: Devuelve true si todos los Points de este Quadrangle hav |
| [setLeftBottom()](#setleftbottom) | Establece el Point de la esquina inferior izquierda de la región QuadrangleValor: Un Point de la esquina inferior izquierda de la región Quadrangle |
| [setLeftTop()](#setlefttop) | Establece el Point de la esquina superior izquierda de la región QuadrangleValor: Un Point de la esquina superior izquierda de la región Quadrangle |
| [setRightBottom()](#setrightbottom) | Establece el Point de la esquina inferior derecha de la región QuadrangleValor: Un Point de la esquina inferior derecha de la región Quadrangle |
| [setRightTop()](#setrighttop) | Establece el Point de la esquina superior derecha de la región QuadrangleValor: Un Point de la esquina superior derecha de la región Quadrangle |
| [toString()](#tostring) | Devuelve una representación de cadena legible por humanos de este Quadrangle. |

### contains(pt) {#contains}

Determina si el Punto especificado está contenido dentro de esta estructura Quadrangle.

| Parámetro | Descripción |
| --- | --- |
| pt | El Point a probar. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Determina si el punto especificado está contenido dentro de esta estructura Quadrangle.

| Parámetro | Descripción |
| --- | --- |
| x | La coordenada x del point. |
| y | La coordenada y del point. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Determina si el Quadrangle especificado está contenido o intersecta esta estructura Quadrangle.

| Parámetro | Descripción |
| --- | --- |
| quad | El Quadrangle a probar. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Determina si el Rectángulo especificado está contenido o intersecta esta estructura Quadrangle.

| Parámetro | Descripción |
| --- | --- |
| rect | El Rectangle a probar. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Devuelve un valor que indica si esta instancia es igual a un valor Quadrangle especificado.

| Parámetro | Descripción |
| --- | --- |
| otro | Un valor Quadrangle para comparar con esta instancia. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Crea un Rectángulo que delimita este Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Obtiene el punto de la esquina inferior izquierda de la región QuadrangleValor: Un punto de la esquina inferior izquierda de la región Quadrangle

### getLeftTop() {#getlefttop}

Obtiene el punto de la esquina superior izquierda de la región QuadrangleValor: Un punto de la esquina superior izquierda de la región Quadrangle

### getRightBottom() {#getrightbottom}

Obtiene el punto de la esquina inferior derecha de la región QuadrangleValor: Un punto de la esquina inferior derecha de la región Quadrangle

### getRightTop() {#getrighttop}

Obtiene el punto de la esquina superior derecha de la región QuadrangleValor: Un punto de la esquina superior derecha de la región Quadrangle

### hashCode() {#hashcode}

Devuelve el código hash de esta instancia.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Prueba si todos los Points de este Quadrangle tienen valores cero.Valor: Devuelve true si todos los Points de este Quadrangle tienen valores cero; de lo contrario, false.

### setLeftBottom() {#setleftbottom}

Establece el Point de la esquina inferior izquierda de la región QuadrangleValor: Un Point de la esquina inferior izquierda de la región Quadrangle

### setLeftTop() {#setlefttop}

Establece el Point de la esquina superior izquierda de la región QuadrangleValor: Un Point de la esquina superior izquierda de la región Quadrangle

### setRightBottom() {#setrightbottom}

Establece el Point de la esquina inferior derecha de la región QuadrangleValor: Un Point de la esquina inferior derecha de la región Quadrangle

### setRightTop() {#setrighttop}

Establece el Point de la esquina superior derecha de la región QuadrangleValor: Un Point de la esquina superior derecha de la región Quadrangle

### toString() {#tostring}

Devuelve una representación de cadena legible por humanos de este Quadrangle.

**Returns:** A string that represents this Quadrangle.
