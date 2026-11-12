---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke un ensemble de quatre Points qui représentent une région quadrilatère."
type: docs
weight: 850
url: /fr/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Stocke un ensemble de quatre Points qui représentent une région quadrilatère.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Initialise une nouvelle instance de la structure Quadrangle avec les points décrivant.

| Paramètre | Description |
| --- | --- |
| leftTop | Un Point qui représente le coin supérieur gauche du Quadrangle. |
| rightTop | Un Point qui représente le coin supérieur droit du Quadrangle. |
| rightBottom | Un Point qui représente le coin inférieur droit du Quadrangle. |
| leftBottom | Un Point qui représente le coin inférieur gauche du Quadrangle. |

## Méthodes

| Nom | Description |
| --- | --- |
| [contains(pt)](#contains) | Détermine si le Point spécifié est contenu dans cette structure Quadrangle. |
| [containsPoint(x, y)](#containspoint) | Détermine si le point spécifié est contenu dans cette structure Quadrangle. |
| [containsQuadrangle(quad)](#containsquadrangle) | Détermine si le Quadrangle spécifié est contenu ou intersecte cette structure Quadrangle. |
| [containsRectangle(rect)](#containsrectangle) | Détermine si le Rectangle spécifié est contenu ou intersecte cette structure Quadrangle. |
| [equals(other)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur Quadrangle spécifiée. |
| [getBoundingRectangle()](#getboundingrectangle) | Crée un Rectangle englobant ce Quadrangle |
| [getLeftBottom()](#getleftbottom) | Obtient le Point du coin inférieur gauche de la région QuadrangleValue : Un Point du coin inférieur gauche de la région Quadrangle |
| [getLeftTop()](#getlefttop) | Obtient le Point du coin supérieur gauche de la région QuadrangleValue : Un Point du coin supérieur gauche de la région Quadrangle |
| [getRightBottom()](#getrightbottom) | Obtient le Point du coin inférieur droit de la région QuadrangleValue : Un Point du coin inférieur droit de la région Quadrangle |
| [getRightTop()](#getrighttop) | Obtient le Point du coin supérieur droit de la région QuadrangleValue : Un Point du coin supérieur droit de la région Quadrangle |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isempty) | Teste si tous les Points de ce Quadrangle ont des valeurs zéro.Valeur : Retourne vrai si tous les Points de ce Quadrangle ont |
| [setLeftBottom()](#setleftbottom) | Définit le Point du coin inférieur gauche de la région du Quadrangle.Valeur : Un Point du coin inférieur gauche de la région du Quadrangle |
| [setLeftTop()](#setlefttop) | Définit le Point du coin supérieur gauche de la région du Quadrangle.Valeur : Un Point du coin supérieur gauche de la région du Quadrangle |
| [setRightBottom()](#setrightbottom) | Définit le Point du coin inférieur droit de la région du Quadrangle.Valeur : Un Point du coin inférieur droit de la région du Quadrangle |
| [setRightTop()](#setrighttop) | Définit le Point du coin supérieur droit de la région du Quadrangle.Valeur : Un Point du coin supérieur droit de la région du Quadrangle |
| [toString()](#tostring) | Retourne une représentation sous forme de chaîne lisible par l'homme de ce Quadrangle. |

### contains(pt) {#contains}

Détermine si le Point spécifié est contenu dans cette structure Quadrangle.

| Paramètre | Description |
| --- | --- |
| pt | Le Point à tester. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Détermine si le point spécifié est contenu dans cette structure Quadrangle.

| Paramètre | Description |
| --- | --- |
| x | La coordonnée x du point. |
| y | La coordonnée y du point. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Détermine si le Quadrangle spécifié est contenu ou intersecte cette structure Quadrangle.

| Paramètre | Description |
| --- | --- |
| quad | Le Quadrangle à tester. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Détermine si le Rectangle spécifié est contenu ou intersecte cette structure Quadrangle.

| Paramètre | Description |
| --- | --- |
| rect | Le Rectangle à tester. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur Quadrangle spécifiée.

| Paramètre | Description |
| --- | --- |
| autre | Une valeur de Quadrangle à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Crée un Rectangle englobant ce Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Obtient le Point du coin inférieur gauche de la région QuadrangleValue : Un Point du coin inférieur gauche de la région Quadrangle

### getLeftTop() {#getlefttop}

Obtient le Point du coin supérieur gauche de la région QuadrangleValue : Un Point du coin supérieur gauche de la région Quadrangle

### getRightBottom() {#getrightbottom}

Obtient le Point du coin inférieur droit de la région QuadrangleValue : Un Point du coin inférieur droit de la région Quadrangle

### getRightTop() {#getrighttop}

Obtient le Point du coin supérieur droit de la région QuadrangleValue : Un Point du coin supérieur droit de la région Quadrangle

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Teste si tous les Points de ce Quadrangle ont des valeurs zéro.Valeur : Retourne vrai si tous les Points de ce Quadrangle ont des valeurs zéro ; sinon, faux.

### setLeftBottom() {#setleftbottom}

Définit le Point du coin inférieur gauche de la région du Quadrangle.Valeur : Un Point du coin inférieur gauche de la région du Quadrangle

### setLeftTop() {#setlefttop}

Définit le Point du coin supérieur gauche de la région du Quadrangle.Valeur : Un Point du coin supérieur gauche de la région du Quadrangle

### setRightBottom() {#setrightbottom}

Définit le Point du coin inférieur droit de la région du Quadrangle.Valeur : Un Point du coin inférieur droit de la région du Quadrangle

### setRightTop() {#setrighttop}

Définit le Point du coin supérieur droit de la région du Quadrangle.Valeur : Un Point du coin supérieur droit de la région du Quadrangle

### toString() {#tostring}

Retourne une représentation sous forme de chaîne lisible par l'homme de ce Quadrangle.

**Returns:** A string that represents this Quadrangle.
